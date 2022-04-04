# About models in DINA

The main goal in DINA is creating resources, APIs and software, for collection data management. Models are a core ingredient for the application development for specifying what kind of information is represented. 

Models in DINA serve different processes

The main domain model provides a framework to represent collection object history, including history of objects the collection object is derived from
DINA assumes a distinctly process / state / event based perspective (e.g., the collection of an object is seen as a collecting process) on collection object history
the model itself is abstract and is synthetic (i.e. it disregards how software modules as tools to create or update corresponding representations segment its conceptual space)
It’s basically an entity-relationship (ER) model.

The main model is complemented by models of curatorial processes that change a collection object (physically) or update knowledge about it
examples: preserving, subsampling, determining, relocating processes
these are the process-parts of the collection object history
participants (persons, corporate bodies with roles), material entities at the start and the end of the process
These models inform the design of user interfaces and software components in general that are used to document curatorial processes and update the representation of the collection object history in the process. Therefore, they are important for the DINA collection management system.

# Segmenting the model space for application development: Information Packages, Functional Component Descriptions and Module Descriptions

Approach for breaking down the DINA work and architecture from content-driven high-level concepts (Information Packages) to lower-level functionality-oriented components.

![Three levels of the DINA modelling process](./Modelling-Levels.PNG)

* __[Information Packages](information_packages/)__ make up the information model. Information Packages should be logically standalone, thus independent from other Information Packages.  
  * It addresses the question _Which information lives where?_ 
  * The Information Packages are not expected to change too much over time.

* For each Information Package one to many __[Functional Components](component_descriptions/)__ are described. Although a component description should already focus on functionality, the technical implementaion should play only a minor role. Rather the component description should be high-level and focussed on the accomplishment of use cases and workflows. 
  * It addresses the question _Which functionality needs to be considered per component?_
  
* From the functional component descriptions __module descriptions__ can be derived. 
  * It should be possible to develop a data model from the module descriptions. 
  * The module descriptions should be versioned (different MVPs) and are expected to be modified for each MVP.
  * Each module description links to a dedicated __specification repository__ in which the backlog for the implementation will be documented (e.g. API endpoints, software stack, data schema etc.)
  * It addresses the question _How to implement the desired informationa and functionality?_


The above-mentioned three levels should not be mixed.

<hr/>

# Existing Information Packages

* [collection objects](information_packages/collection_objects.md)


