# DINA Information Packages and Modules Description

Approach for breaking down the DINA work and architecture from content-driven high-level concepts (Information Packages) to lower-level functionality-oriented (but still high-level) modules.

* __Information Packages__ make up the information model. Information Packages should be logically standalone, thus independent from other Information Packages.  
  * It addresses the question _Which information lives where?_ 
  * The Information Packages are not expected to change too much over time.

* For each Information Package one to many __Modules__ are described. Although a module description should already already focus on  functionality, the technical implementaion should play only a minor role. Rather the module description should be high-level and focussed on the accomplishment of use cases and workflows. 
  * It addresses the question _Which functionality needs to be considered per module?_
  * It should be possible to develop a data model from the module descriptions. 
  * The module descriptions should be versioned (different MVPs) and are expected to be modified for each MVP.

* Each module description links to a desicated __specification repository__ in which the backlog for the implementation will be documented (e.g. API endpoints, software stack, data schema etc.)
  * It addresses the question _How to implement the desired functionality?_


The above-mentioned three levels should not be mixed.

<hr/>

# Existing Information Packages

* [collection objects](informations_packages/collection_objects.md)


