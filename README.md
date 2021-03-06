# big-data-provenance-ontology
A big data provenance ontology that defines the types and relations used to express the data transformation process in the big data system. Researchers can select partial elements of the ontology or further extend it in specific scenarios.

In the ontology, we define four top class: Entity, Activity, Agent and Influence.

Entity refers to digital object, which includes data, job, task and network object. Data includes file data, indexed data, streaming data and message in the big data scenario. Job and task are used to express the provenance information of big data processing whose typical feature is distributed and parallel processing. Network object includes network resource, bookmark, cookie, etc. In this ontology, network object is mainly used to represent the source of network stream.

An activity is something that occurs over a period of time and acts upon or with entities. According to entity types, we define the provenance representation of activities related to data, jobs and tasks. Job and task related activities include job submission, task assignment and task execution. Data related activities include data collection, data organization and data usage. Data organization includes data storage, access, distribution, and deletion related activities. Data usage includes data preparation, analysis and visualization. The entire life cycle of data can be covered by these activities.

An agent is something that bears some form of responsibility for an activity occurring, for the existence of an entity, or for the activities of other agents. The agent includes a single user, group (such as company, community) and software agent. According to the role of agent, it can be divided into data producer, data consumer, data collector, job submitter, job master, task worker and job submitter.

Influence represent the provenance relationships among entities, activities and agents. Taking the three types of nodes as influencer, the influence can be divided into three types.



