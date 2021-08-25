Functional Component: Entity Relations
=======================

## Specific scope of the component

Physical entities and/or derived entities might have relations amongst each other in different ways. Some relations can be created automatically, because samples have been collected in the same expedition, with the same method, are stored in the same room, are derived from the same parent entity, have been shipped for a loan in the box etc. But although these relations can be created automatically, there needs to be a place to store and lookup additional information on the kind of relation. For digitization purposes a lot of relations might need to be registered retrospectively and thus manually. Additionally, biological interactions and conditions can be documented as relations as well (e.g. "parasite-host" relations or "growth medium").
Relations are not only informative to the users for better discovery, but they are also essential for tracking the objects history, provernance, past and recent biological interactions. These relations can be described by free text and other specific metadata (ideally controlled vocabulary) that is connected to the entities by their unique references in the system across different versions in the history of the objects.

## What does the component do? (envisioned feature set)

* store the metadata of relations between entities
   * reference to entity, event, agent, collection etc.
   * type of relation (e.g. "derived from", "grows on", "removed from", "arisen from", "cultivated on", "hybrid of", "shared event", "taxonomically related", etc.)
* facilitate automatic relationships and manual entry (can be triggered by or treated like annotations)
   * simple user interface for looking up entities and adding relationship metadata
   * for discovery: grouped search results by relationship across organisational units (e.g. sub-collections)
* optional: visual representation (e.g. a graph) of relationships amongst objects.

### Has links to
* agents
* physical entities (which might be catalogued objects, but also living specimens)
* storage
* file store (e.g. images, stored loan forms, permit documents)
* annotations
* taxonomy as metadata 

### Potential fields
* relation type (controlled vocab) 
* description of relationship
* entity A 
* entity type A (e.g. physical entity, event, storage, organizational unit, etc.)
* entity B
* entity type B (e.g. physical entity, event, storage, organizational unit, etc.)
* direction of relation (A -> B, bidirectional, B -> A)
* references to files (e.g. images of biological interaction)
* created by (link to agent)
* created at (date)

## What does the component __not__ do? (excluded features to avoid misperception / confusion)
* create new entities
* allow ingesting annotations (only reacting on annotations)
* especially relevant for living collections: This component is not supposed to store continuous status changes or observations about the relationship of entities within the same relation type (means: new relationships should be created only if the relation type changes).

## Lead of development team


## Link to component specs repo
