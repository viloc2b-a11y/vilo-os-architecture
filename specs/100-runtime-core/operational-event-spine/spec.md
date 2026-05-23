\# Operational Event Spine



Status: Draft



\---



\# Objective



Define the immutable operational event architecture that serves as the single source of truth for runtime execution, governance, compliance, operational intelligence, and financial intelligence across Vilo OS.



The Operational Event Spine is the nervous system of the platform.



\---



\# Core Principle



Everything important becomes an immutable operational event.



The system computes reality from events.



\---



\# Event Philosophy



Operational truth derives from:

\- observed execution

\- emitted events

\- immutable lineage



NOT from mutable status fields alone.



\---



\# Event Chain



User Action

→ Runtime Execution

→ Event Emission

→ Immutable Storage

→ State Computation

→ Governance Signals

→ Financial Signals

→ Operational Intelligence



\---



\# Event Requirements



Every operationally meaningful action must emit an event.



Events must be:

\- immutable

\- timestamped

\- attributable

\- traceable

\- queryable

\- explainable

\- replayable



\---



\# Core Event Categories



\## Study Events



Examples:

\- study\_created

\- study\_published

\- protocol\_amended

\- study\_closed



\---



\## Subject Events



Examples:

\- subject\_created

\- subject\_screened

\- subject\_randomized

\- subject\_withdrawn



\---



\## Visit Events



Examples:

\- visit\_scheduled

\- visit\_started

\- visit\_locked

\- visit\_signed

\- visit\_closed



\---



\## Procedure Events



Examples:

\- procedure\_started

\- procedure\_completed

\- procedure\_skipped

\- procedure\_failed



\---



\## Source Events



Examples:

\- source\_created

\- source\_updated

\- source\_signed

\- source\_corrected

\- addendum\_created



\---



\## Safety Events



Examples:

\- ae\_created

\- sae\_triggered

\- safety\_escalated

\- safety\_resolved



\---



\## Governance Events



Examples:

\- deviation\_created

\- capa\_created

\- query\_opened

\- monitoring\_finding\_created



\---



\## Financial Events



Examples:

\- billable\_expected

\- billable\_earned

\- billable\_missed

\- invoice\_generated

\- payment\_received



\---



\# Event Structure



Each event must include:



\- event\_id

\- event\_type

\- entity\_type

\- entity\_id

\- study\_id

\- site\_id

\- subject\_id (if applicable)

\- visit\_id (if applicable)

\- procedure\_id (if applicable)

\- actor\_id

\- actor\_role

\- timestamp

\- event\_payload

\- lineage\_reference

\- source\_reference

\- previous\_event\_reference



\---



\# Immutable Rules



Events must NEVER:

\- be overwritten

\- be deleted

\- lose attribution

\- lose timestamps

\- lose lineage



Corrections must generate new events.



\---



\# State Computation



Runtime state must be computed from:

\- ordered events

\- runtime aggregation

\- lineage reconstruction



NOT from isolated mutable flags.



\---



\# Replayability



The system must support:

\- full runtime reconstruction

\- longitudinal reconstruction

\- audit replay

\- protocol replay

\- deviation replay

\- source reconstruction



\---



\# Governance Integration



The event spine powers:

\- audit lineage

\- protocol compliance

\- inspection readiness

\- monitoring intelligence

\- CAPA intelligence

\- deviation intelligence



\---



\# Financial Integration



The event spine powers:

\- earned revenue computation

\- leakage detection

\- amendment impact

\- coordinator burden valuation

\- invoice reconciliation



\---



\# AI Integration



AI systems must consume:

\- event-derived truth

\- runtime lineage

\- explainable operational history



AI must NEVER infer operational state from incomplete snapshots alone.



\---



\# UX Integration



Coordinator UX should consume:

\- computed operational state

\- active blockers

\- unresolved dependencies

\- workflow progression

\- longitudinal continuity



without exposing raw event complexity.



\---



\# Technical Foundation



Recommended architecture:



\- PostgreSQL append-only event table

\- immutable event IDs

\- event indexing

\- temporal querying

\- lineage graph support

\- replay-safe ordering



\---



\# Explicit Non-Goals



The event spine is NOT:

\- a logging system

\- analytics-only infrastructure

\- debugging telemetry

\- sponsor reporting infrastructure



It is operational truth infrastructure.



\---



\# Final Rule



If operational truth cannot be reconstructed completely from the event spine, the architecture is invalid.

