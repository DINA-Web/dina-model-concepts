Component Description: Determinations
=======================

## Specific scope of the component
The collection information package need to cope with determinations (considered as labels, names or titles) assigned to physical entity. 

### Definition
A determination is an annotation event that was executed by an agent who (or that) assigned a label (usually a taxonomic name) to a physical entity.

## What does the component do? (envisioned feature set)

This component stores the application of names (usually taxonomic names) to physical entities as a running list of temporally-constrained entries each with one or more agents credited with the action.
It holds the history of all determinations for the physical entities in order to preserve the applied names or titles of these entities independent from the latest state of knowledge or any other implicit assumptions or interpretation. Changes in taxonomic research that are applied to the physical entities are considered to be new determinations.
Changes in nomenclature without changes in taxonomic concepts are considered new records in the determination component, but referenced to existing determinations and are assigned the type "nomenclatural update").
For a comprehensive snapshot of the derivation process evidence to the source of the namestring is stored as well.


### Has links to
* Agents
  * Person
  * Algorithm
* Physical Entity
  * Files & multimedia
  * Bibliographic items
  * Images of catalog entries
  * Photographs of labels
* PreparationProcess?


### Potential fields
* Namestring (label or title): drawn from a big bucket of flat names as aid for data entry, but no cross-reference to a taxonomic concept
* Determination date
* Type of determination (e.g. (automated) nomenclatural update, taxonomic revision)
* Reference to linked determination
* Evidence
* Taxonomic status
* Determiner(s) (verbatim agent string)
* Verified by (refers to a prior determination)
* Date verified (refers to a prior determination)
* Identification qualifier (eg cf., aff., stet!)
* preferred status (only one determination be preferred to be displayed as "main" label or title in the UI)


## What does the component __not__ do? (excluded features to avoid misperception / confusion)
It does not consist of hard, relational links to a source classification, nor does it contain any hierarchical information, nor are scientific names parsed and stored as component parts. 
Rather, the relationship is akin to the behaviour of a gazetteer such that the determination does not change with advances in taxonomic research or if an alternate classification is used. 
It is a snapshot that contains nothing but a bare (taxonomic) name that the determiner used. 
In other words, alteration of names in taxonomic hierarchies does not alter the content or spirit of any determination. 
It also does not attempt to reconcile a determination against other concepts, nor does it attempt to resolve it to currently accepted use.


## Relevant issues


## Lead of development team


## Link to component specs repo
