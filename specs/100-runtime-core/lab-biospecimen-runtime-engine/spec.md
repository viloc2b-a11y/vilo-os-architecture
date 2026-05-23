\# Lab and Biospecimen Runtime Engine



Status: Draft



\---



\# Objective



Define the runtime architecture for lab procedures, biospecimen collection, processing, tracking, chain of custody, result review, abnormal result workflows, central/local lab coordination, and specimen-derived financial traceability.



\---



\# Core Principle



Lab and biospecimen workflows are operational runtime events, not isolated lab logs.



\---



\# Responsibilities



The engine must support:



\- lab procedure execution

\- biospecimen collection tracking

\- specimen processing

\- chain of custody

\- central lab shipments

\- local lab result handling

\- abnormal result workflows

\- repeat collection workflows

\- missed specimen detection

\- lab-linked source documentation

\- specimen-linked financial traceability



\---



\# Core Entities



\- Lab Procedure

\- Biospecimen

\- Specimen Collection

\- Specimen Processing

\- Chain of Custody Event

\- Lab Result

\- Abnormal Result

\- Lab Shipment

\- Lab Requisition

\- Repeat Collection

\- Specimen Deviation



\---



\# Runtime Workflow



Protocol Requirement

→ Visit Procedure

→ Specimen Collection

→ Processing

→ Chain of Custody

→ Shipment / Local Result

→ Result Review

→ Abnormal Workflow

→ Source Evidence

→ Financial Signal



\---



\# Chain of Custody



The system must capture:



\- collector

\- collection time

\- specimen type

\- tube/container type

\- processing time

\- storage condition

\- transfer event

\- shipment event

\- receiving confirmation

\- deviation reason if applicable



\---



\# Result Review



The engine must support:



\- result receipt

\- normal/abnormal flag

\- PI/Sub-I review

\- clinically significant determination

\- AE linkage

\- repeat lab workflow

\- safety escalation trigger

\- source documentation linkage



\---



\# Abnormal Result Logic



The system must support:



\- threshold-triggered workflows

\- protocol-specific abnormality rules

\- repeat collection requirements

\- safety escalation

\- visit blocking

\- unresolved result carry-forward



\---



\# Biospecimen Financial Traceability



The system must generate signals for:



\- collected specimens

\- missed specimens

\- repeat collections

\- processing work

\- shipment work

\- central lab coordination

\- pass-through costs

\- additional protocol-required burden



\---



\# Operational Event Integration



The engine emits events such as:



\- specimen\_collected

\- specimen\_processed

\- chain\_of\_custody\_transferred

\- lab\_result\_received

\- abnormal\_result\_flagged

\- pi\_review\_completed

\- repeat\_collection\_required

\- specimen\_deviation\_created



\---



\# Governance Integration



The engine supports:



\- specimen lineage

\- protocol compliance

\- deviation tracking

\- audit reconstruction

\- inspection-ready specimen history



\---



\# UX Requirements



The coordinator/lab user must see:



\- what specimens are required

\- what is collected

\- what is missing

\- what must be processed

\- what must be shipped

\- what results need review

\- what abnormal results require action



\---



\# MVP Scope



MVP must support:



\- lab procedure execution

\- specimen collection status

\- chain of custody events

\- result review status

\- abnormal result workflow

\- specimen deviation events

\- financial signal placeholder



\---



\# Deferred Scope



Deferred:



\- full LIMS replacement

\- instrument integration

\- automated HL7/FHIR feeds

\- courier API integration

\- advanced specimen inventory system



\---



\# Explicit Non-Goals



The engine is NOT:



\- standalone LIMS

\- generic inventory system

\- disconnected specimen tracker

\- central lab portal replacement



\---



\# Final Rule



If specimen lineage cannot be reconstructed from collection to result review, the lab runtime architecture has failed.

