# Glossary

Definition of terms used in the context of the DINA collection management system and its related data model.
May contains links to related [DarwinCore terms](http://tdwg.github.io/dwc/terms/) (although we are not making committment to using DwC terms or any assertions about using DwC terms in exactly the same way).

## catalogNumber

Identifier representing [Catalogued Object](#catalogued-object) that is almost always user-generated, up to discretion of collection manager (eg CNC 1234567). Ideally, numeric portion of a catalogNumber should maintain local nuniqueness (unique within the collection). catalogNumber is a [DarwinCore Term](https://dwc.tdwg.org/terms/#dwc:catalogNumber).

## Catalogued Object

The catalogued object contains data and identifiers related to the accessioning of a single specimen. Includes identification/determination support.
Same as DarwinCore [Preserved Specimen](https://dwc.tdwg.org/terms/#preservedspecimen).

## Collecting Event

Data associated with the collecting of the specimen(s) at a given time and place.

## Material Sample

Represent what was collected in a [Collecting Event](#collecting-event). Could be one or a group of specimen, see DarwinCore [definition](https://dwc.tdwg.org/terms/#materialsample).

## occurrenceID 

Identifier representing the [Catalogued Object](#catalogued-object) that is almost always machine-generated (eg b3405026-3e96-53bb-a713-59bc48a90e3e as a UUID v5 with a namespace) or auto-incremented number from the internal database. ocurrenceID is a [DarwinCore Term](https://dwc.tdwg.org/terms/#dwc:occurrenceID).

## Preparation

Process used to move from [Material Sample](#material-sample) to [Catalogued Object](#catalogued-object).
