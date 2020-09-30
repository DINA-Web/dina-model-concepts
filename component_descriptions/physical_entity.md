Component Description: Physical Entity
=======================

## Specific scope of the component

Previously called Material Samples.

## What does the component do? (envisioned feature set)

### Definition

A physical result of a sampling event.

In natural history collections,
the material sample is typically collected, and either preserved or destructively processed. (from Darwin Core)

### Has links to
* Collection Event(s): a physical entity come from 1 or multiple collecting event
* Catalogued Object(s): many to many, a catalogued object may consist of several physical entities (with own identities) and physical entity may comprise several collection objects
* Files and Multimedia
* Preparations
* DNA Sampling & Sequencing (Need to look at this use cases)
* Loans and Transactions
* Physical storage location(s)

### Potential fields
* Import Permit Tracking (CFIA for AAFC)
* Field number or Other IDs of all sorts
* Substrate type, air/water/soil
* Potentially a History of State of the object - frozen/ dead/ in water/etc… (Link to preparation and protocol)
* Amount? weight/ countable unit (3 parts of something) ( Talk to Falko for more)
* Contaminated? Or another better term for this.
* Date status changed
  * State = destroyed
* Protocols to capture something from the collection event.
* Stores the preparation details specific for a Material Sample
  * example?
* Stores the provenance of subsampling events
  * Example: living material that is periodically sampled, each subsequent sample needs to have at minimum a link to a parent sample

## What does the component __not__ do? (excluded features to avoid misperception / confusion)


## Lead of development team


## Link to component specs repo
