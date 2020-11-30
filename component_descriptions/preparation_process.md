Component Description: Preparation Process
=======================

## Specific scope of the component
Collection information packages need to cope with preparations for supporting daily work of collection staff handling the collection objects.

## What does the component do? (envisioned feature set)
* Document the preparation event(s), preparation type(s), preservation methods(s) of physical entity and/or catalogued object
* Document the relation between the states

### Definition

Preparation processes are deliberate changes of the state of physical entities for a certain purpose. The most relevant purposes are: preservation, research, display/exhibition.
A preparation method could be constructive (e.g. mounting a skeleton), destructive (e.g. taking tissue samples) and without influence to the physical entity (e.g. cast from a bone).
A preparation process is a mandatory component for catalogued objects and is optional for physical entities. When a physical entity becomes a catalogued object it always undergoes a preparation.

#### Example: DNA sampling
* DNA sampling is a preparation process
* A DNA sample is a physical entity as a result of a preparation process "DNA sampling"
* The DNA sample could be consumed after analyses or could be accessioned in a biobank. In the latter case the phyiscal entity "DNA sample" would become a catalogued object.

### Has links to
* Files and multimedia
  * Document protocols (preparation methods) 
* Agents: taxidermist, collection staff, etc. who conducted 
* Physical entity
* Physical storage location(s)
* Catalogued objects
* Loans and transactions
* Acquisitions
* Controlled vocabularies


### Potential fields
* Date/time of the event (must be continious)
  * date/time ranges and partial date/time with uncertainty (e.g. 2020-02/2020-03)
* purpose for preparation
* method / protocol [metadata and link to document/resource/literature]
  * reference to standardized methods / best practice
  * description
* preparation process type [controlled vocab, might be also hierarchical: constructive, destructive, uninfluential, cleaning, sonserving]
* resulting preparation type [controlled vocab: sheet, vial, pin, cast, plate, filter paper... ]
* Conservation status [controlled vocab]
* Type substrate [controlled vocab: 70% ethanol, silica, buffer “X”, oil…]

* Agents
  * various roles, but mainly person who did the action of preparation
  * ordering of the agents in a given activity must be preserved
  * same agent could have multiple roles in a given preparation event
* Conditions during the preparation event 

## What does the component __not__ do? (excluded features to avoid misperception / confusion)
* the links to taxonomy are no links to determination, but taxonomy because preparation methods can be specific to taxonomic groups
* You cannot have a catalogued object without a preparation

## Relevant issues
* https://github.com/DINA-Web/dina-model-concepts/issues/38
* https://github.com/DINA-Web/dina-model-concepts/issues/36
* https://github.com/DINA-Web/dina-model-concepts/issues/35
* https://github.com/DINA-Web/dina-model-concepts/issues/34
* https://github.com/DINA-Web/dina-model-concepts/issues/31
* https://github.com/DINA-Web/dina-model-concepts/issues/29
* https://github.com/DINA-Web/dina-model-concepts/issues/26


## Lead of development team


## Link to component specs repo
