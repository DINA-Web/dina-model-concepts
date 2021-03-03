Component Description: Collecting Event
=======================

## Specific scope of the component
Physical entities in natural science collections are collected at some place at a certain point in time. Independent of the fact whether this information is known, this must have happened.


## What does the component do? (envisioned feature set)

### Definition
A collecting event is a documented activity whose purpose is to gather samples that may later acquire scientific value that is executed by an agent at a place and time that they described.
Collecting event is a mandatory component and is always present. It could be empty when the details are unknown.
An action that occurs at some location during some time. (from Darwin Core)

This component should distinguish between verbatim and derived collecting event information although both kinds of information might be diplayed in user interfaces in parallel.
Verbatim information may not have any documentation whatsoever (eg personal communication, specimens collected pre 1700’s, etc.) and may remain blank in perpetuity. However, there may be assertions made based on evidence found elsewhere they will reside in fields that record these interpretations about place and time.


### Has links to
* Files and multimedia
  * Document protocols (includes fieldnotes?) 
  * Image of the site
  * Collecting permit
* Agents
  * various roles depending on the nature of the participation 
  * this includes the interpreted names of (historic people)
  * ordering of the agents in a given activity must be preserved
  * same agent could have multiple roles in a given collecting event
* Physical entity
* Acquisitions ?
* Controlled vocabularies
  * Habitat classifications
  * Country names, water bodies etc
  * Gazetteers
* sites
  * descriptions of regions, landscapes, habitat
  * ecological parameters
* Collecting Event (a parent or associated collecting event)
  * Used when there is discontinuous events in time or space

### Potential fields
* Verbatim values (as written on the labels or any value before interpretation:  names, dates, locality)
* Interpretations of the places derived from the verbatim data
  * Type of interpretation e.g. from georeferencing activities 
  * Evidence for interpretation / assertion => reference to the source
  * Preferred flag
  * Date/time of the event (must be continuous)
    * date/time ranges and partial date/time with uncertainty (e.g. 2020-02/2020-03)
  * Location of the event (must be continious)
    * location of the locality specified according to some geodetic reference system, e.g. as latitude/longitude, UTM, decimal degrees, georeferenced polygons, transects, in each case with error estimates
    * process of the determination of the location of the locality - should be represented in terms of the type of procedure performed for the and the agent responsible for the determination
    * altitude specified according to some altitude reference system (can also be negative, i.e. depth for aquatic sites or caves)
    * different geometric figures (points, lines (transect), polygons (2d and 3D))
  * link to agents
* Conditions during the collecting event / at the collection site (e.g. weather conditions)
* Quantify sampling effort, sample size & unit
* metadata on linked or aggregated collecting events (e.g. that belong to the same expedition or time series)


## What does the component __not__ do? (excluded features to avoid misperception / confusion)
* full management of hierarchical geographic information, administrative areas etc.
  * although this might information that is linked to as controlled (external) vocabulary, it is not part of the collecting events in a narrow sense
* this component does not accommodate the unique management of collector names (see verbatim information vs. link to agents module) 

## Lead of development team


## Link to component specs repo
