\# Safety Orchestration Engine



Status: Draft



\---



\# Objective



Define the runtime safety orchestration system responsible for adverse events, serious adverse events, safety escalation, longitudinal monitoring, conditional workflows, unresolved safety state tracking, and protocol-driven clinical safety execution.



\---



\# Core Principle



Safety is not a disconnected reporting workflow.



Safety is a continuously orchestrated longitudinal runtime state.



\---



\# Responsibilities



The Safety Orchestration Engine must support:



\- AE workflows

\- SAE workflows

\- longitudinal safety tracking

\- unresolved safety carry-forward

\- conditional safety escalation

\- protocol-driven monitoring

\- lab-triggered workflows

\- repeated safety assessments

\- protocol-specific safety logic

\- safety-linked operational guidance



\---



\# Core Safety Entities



\- Adverse Event

\- Serious Adverse Event

\- Safety Signal

\- Safety Escalation

\- Safety Assessment

\- Safety Workflow

\- Safety Resolution

\- Safety Hold

\- Safety Dependency



\---



\# Safety Runtime Model



Safety state must persist across:



\- visits

\- procedures

\- amendments

\- longitudinal subject history

\- unresolved assessments



Safety is never isolated to a single visit.



\---



\# AE Runtime



The system must support:



\- AE creation

\- AE severity grading

\- seriousness classification

\- relationship assessment

\- outcome tracking

\- ongoing AE state

\- resolution tracking

\- visit linkage

\- procedure linkage



\---



\# SAE Runtime



The system must support:



\- SAE escalation

\- sponsor notification tracking

\- reporting timelines

\- unresolved SAE carry-forward

\- documentation completeness

\- regulatory traceability



\---



\# Conditional Safety Logic



The engine must support:



\- lab-triggered workflows

\- repeated assessments

\- protocol safety dependencies

\- medication-triggered monitoring

\- threshold-triggered escalation

\- protocol-specific escalation trees



Examples:

\- HIT monitoring

\- adrenal monitoring

\- repeated liver function monitoring

\- ECG escalation logic

\- pregnancy escalation workflows



\---



\# Safety Holds



Safety conditions may:



\- block visits

\- block procedures

\- require escalation

\- require PI review

\- require additional source

\- require sponsor notification



The coordinator should never manually infer safety blocking state.



\---



\# Longitudinal Safety Intelligence



The engine must continuously compute:



\- unresolved safety items

\- overdue follow-up

\- repeated abnormal findings

\- cumulative safety burden

\- protocol risk signals

\- escalation urgency



\---



\# Governance Integration



Safety orchestration must generate:



\- audit lineage

\- reporting evidence

\- escalation evidence

\- monitoring evidence

\- protocol compliance signals

\- inspection readiness evidence



\---



\# Operational Event Integration



Safety workflows emit immutable events such as:



\- ae\_created

\- sae\_triggered

\- safety\_hold\_placed

\- escalation\_required

\- followup\_overdue

\- safety\_resolved



\---



\# Financial Integration



Safety workflows may generate:



\- unscheduled visits

\- additional procedures

\- coordinator burden

\- sponsor billables

\- reimbursement triggers



\---



\# UX Requirements



The coordinator experience must provide:



\- unresolved safety visibility

\- escalation guidance

\- longitudinal safety continuity

\- protocol-aware safety guidance

\- actionable next steps



NOT disconnected AE tables.



\---



\# MVP Scope



MVP must support:



\- AE workflows

\- SAE workflows

\- unresolved safety tracking

\- safety-linked visit blocking

\- longitudinal safety continuity

\- immutable safety events



\---



\# Explicit Non-Goals



The engine is NOT:



\- a static AE log

\- a sponsor reporting portal

\- a disconnected pharmacovigilance system

\- a generic ticketing system



\---



\# Final Rule



If unresolved safety state can be forgotten between visits, the architecture has failed.

