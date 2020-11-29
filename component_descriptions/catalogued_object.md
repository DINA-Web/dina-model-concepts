Component Description: Catalogued Object
=======================

## Specific scope of the component

Objects are being catalogued in the context of a specific purpose and catalogue numbers are being assigned in order to reference and count the objects. The catalogued objects are usually being referenced for transanctions, inventories and to make them discoverable for research and exhibitions. 

## What does the component do? (envisioned feature set)

### Definition
Catalogued objects are [physical entities](physical_entity.md) or composites of many physical entities with associated catalogue numbers in a collection catalogue or inventory.
They are results of one or many [preparation process(es)](preparation_process.md) and may be composed of one or many parts, that are not necessarily from the same organism (e.g. herbarium sheet with leaves, flower and seeds; assembled skeleton; insect drawer).
So, a catalogued object can be considered an aggregation layer of one or many physical entities with an identifier (catalogue number).

### Features
* traditional reference and quantification of objects in a collection in countable units
* assignment of catalogue numbers and multiple (legacy) numbers.
* description of the status and conditions of the objects
* scientific reference
* voucher specimen

### Has links to:
* physical entities it is composed of
* preparation event it originated from
* storage
* transactions
	* accessions
	* loans
	* movements
	* digitization requests
* conservation status & history
* conditions
* rights (to access, by whom)
* valuation
* multimedia

### Potential fields
* catalogued object ID aka catalogue number
* other IDs (collection barcode, legacy IDs…)
* title
* description
* physical dimensions
* is voucher (boolean)
* (plus links to other components)


## What does the component __not__ do?
* it is not the authoriative center for determination and collecting event


## Link to component specs repo