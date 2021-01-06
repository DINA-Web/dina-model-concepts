Functional Component: Transactions and Requests
=======================

## Specific scope of the component

Collections get requests for transactions like loans, gifts and exchanges, but also internal movements, as well as requests for visits and digitization. The metadata of these requests are generally used for organizing and processing the requests, but they are also used as performance indicators (number of loans per year) and for measuring the demand for digitization as an indicator for priotization in (mass) digitization processes.

## What does the component do? (envisioned feature set)

* store the metadata of requests and transactions
   * Who, when, what, how?
* track the purpose of request / use case (e.g. exhibition, taxonomic reserach)
* hold the generic protocols for transactions
   * e.g. if transaction type == "loan" follow the steps in loan policy
   * e.g. if tranactions type == "donation" follow the accession guidelines and ABS regulations
* facilitate internal processing for transactions
   * help communicate between requester and collection staff
   * initiate a potential change of the objects' availability
* central documention of decisions and interactions based on the communication and processes (e.g. summary of email communication)
   * negotiations (who decided what and when based on which protocol and regulation)
   * eventual difference between original request and actual transaction
* provide content for documents and paper work (e.g. loan forms, loan agreements, labels for shipping etc)
* facilitate the aggregation of links to other information that are related to the transaction or request
   * object related data that result from a transaction (e.g. research data, determinations, transcripts, publications, annotations)
   * link to processes related to a transaction (e.g. preparation)
   * state changes before and after the transaction (e.g. for tracking damages)
   * link to regulations, permits & related other documents 

### Has links to
* agents
* physical entities (which might be catalogued objects)
* storage
* file store (e.g. images, stored loan forms, permit documents (e.g. relevant for ABS))
* annotations
* taxonomy as metadata 

### Potential fields
* requested at (date)
* requested by (link to agent)
* type of request [loan, gift, exchange, digitization, visit, other]
* transaction type
* status of request (e.g. new, processed, on hold, rejected, sent out, returned, re-accessioned ...)
* purpose / description
  * history of (summarized) communication  (e.g. as copied and pasted from emails, phone calls etc)
* count of entities in transaction
* deadline (date) for return or follow-up processes
* returned at (date)
* issued by (link to (potentially several) agents)
* notes on state after return
* (Links to linked other components)

## What does the component __not__ do? (excluded features to avoid misperception / confusion)
* discovery mechanisms to search the collection
  * although the instead the original query is being stored with the related metadata 
* allow ingesting annotations or data
* store the emails / communication history

## Lead of development team
* MfN

## Link to component specs repo
