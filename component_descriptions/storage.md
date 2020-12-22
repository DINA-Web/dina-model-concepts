# Functional Component: storage

## Specific scope of the module
Collection items have storage locations. Representations of storage locations are necessary for collection management, in particular for all processing requiring information on the storage location of a given object and processes changing the location of an object, temporarily or permanently.

## What does the module do? (envisioned feature set)
Realize the creating / reading / update / deleting of records for:
- storage locations of collection objects
- values of properties of storage locations, e.g.,
  - Type of storage location (e.g. room, cabinet, shelf, tray …)
  - storage conditions of storage location (temperature, humidity, light, safety features, object classes stored, containment levels (e.g., pathogens, living collections)
  - inspection status, schedule
  - identifiers and references to the unit e.g. RFID tags, PIDs, “vernacular” names
  - administrative details: phone numbers, people permitted, emergency contacts
- relations between storage locations, hierarchical
- links to object states as far as they are contingent on storage conditions

Realize the referencing of storage locations for
- representing object location
- representing changes in object location / full history of changes

## What does the module not do? (excluded features to avoid misperception / confusion)
- parasite / host relations are not treated as storage locations
- no virtual storage locations (in terms of files etc.)

## Lead of development team
MfN

## Link to module specs repo
- media / files e.g., images, maps / GIS
- movements, transactions
