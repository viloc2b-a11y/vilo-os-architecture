\# Query and Monitoring Finding Engine



Status: Draft



\---



\# Objective



Define the architecture for query management, CRA monitoring findings, source review issues, coordinator response workflows, finding resolution, escalation, and query burden intelligence.



\---



\# Core Principle



Queries and findings are not isolated comments.



They are operational burden, governance signals, and evidence of workflow friction.



\---



\# Responsibilities



The engine must support:



\- query creation

\- query assignment

\- query response

\- query resolution

\- CRA monitoring findings

\- source-linked findings

\- procedure-linked findings

\- deviation-linked findings

\- CAPA escalation

\- query burden analysis

\- monitoring risk signals



\---



\# Core Entities



\- Query

\- Query Response

\- Monitoring Finding

\- Finding Resolution

\- Finding Severity

\- Finding Category

\- Query Burden Signal

\- Escalation

\- CAPA Link



\---



\# Query Lifecycle



Core states:



\- Open

\- Assigned

\- Responded

\- Reopened

\- Resolved

\- Escalated

\- Closed



\---



\# Monitoring Finding Lifecycle



Core states:



\- Draft

\- Open

\- Under Review

\- Action Required

\- Resolved

\- CAPA Required

\- Closed



\---



\# Linkage Requirements



Queries and findings may link to:



\- study

\- subject

\- visit

\- procedure

\- source section

\- source field

\- deviation

\- CAPA

\- safety event

\- operational event

\- financial signal



\---



\# Operational Event Integration



The engine emits events such as:



\- query\_opened

\- query\_assigned

\- query\_responded

\- query\_resolved

\- finding\_created

\- finding\_escalated

\- capa\_required

\- finding\_closed



\---



\# Coordinator Burden Intelligence



The system must compute:



\- query volume

\- query aging

\- repeated query themes

\- coordinator query burden

\- monitor finding density

\- source friction patterns

\- protocol complexity contribution



\---



\# Governance Integration



Queries and findings contribute to:



\- inspection readiness

\- deviation risk

\- CAPA need

\- monitoring risk

\- protocol complexity scoring

\- workflow friction analytics



\---



\# Financial Integration



The system must detect:



\- uncompensated query burden

\- monitor-driven rework burden

\- protocol complexity negotiation evidence

\- amendment-related query burden



\---



\# UX Requirements



Coordinator/CRA UX must support:



\- source-context query display

\- direct response workflow

\- clear ownership

\- aging visibility

\- escalation visibility

\- resolution evidence



\---



\# MVP Scope



MVP must support:



\- query lifecycle

\- monitoring findings

\- source-linked query context

\- assignment and response

\- resolution tracking

\- immutable query events

\- basic query burden metrics



\---



\# Deferred Scope



Deferred:



\- sponsor-wide query analytics portal

\- EDC query sync

\- automated query auto-response

\- advanced AI finding classification



\---



\# Explicit Non-Goals



The engine is NOT:



\- generic comments

\- simple notes

\- disconnected ticketing

\- sponsor reporting module



\---



\# Final Rule



If query burden cannot be measured and traced to runtime cause, the architecture is incomplete.

