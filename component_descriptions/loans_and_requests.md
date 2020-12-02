Functional Component: Loans and requests  (transactions?)
=======================

## Specific scope of the component

Collections get requests for loans, visits and digitization. The metadata of these requests are generally used for organizing and processing the requests, but they are also used as performance indicators (number of loans per year) and for measuring the demand for digitization as an indicator for priotization in (mass) digitization processes.

## What does the component do? (envisioned feature set)

* store the metadata of requests
   * Who, when, what, how?
* initiate the a potential change of the objects' availability
* help communicate between requester and collection staff
* document the decisions and interactions
* track the purpose of request / use case (e.g. exhibition, taxonomic reserach)
* create documents and labels for shipping
* create agreements (loan forms)
* link objects with related data that result from a transaction (e.g. research data, transcripts, publications)

### Has links to
* agents
* catalogued objects
* storage
* file store (e.g. images, stored loan forms, permit documents (e.g. relevant for ABS))
* annotations

### Potential fields
* requested at
* requested by
* status of request (e.g. new, processed, on hold, sent out, returned, re-accessioned ...)
* deadline for return
* type of request [loan, digitization, visit, other]
* purpose / description
* (Links to linked components):

## What does the component __not__ do? (excluded features to avoid misperception / confusion)
* discovery mechanisms to search the collection
* allow ingesting annotations or data
* store the emails / communication history (?)

## Lead of development team
* MfN

## Link to component specs repo