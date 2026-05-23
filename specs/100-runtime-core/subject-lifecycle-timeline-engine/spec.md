\# Subject Lifecycle and Longitudinal Timeline Engine



Status: Draft



\---



\# Objective



Define the subject lifecycle architecture responsible for managing screening, enrollment, randomization, visit progression, safety continuity, medical history, concomitant medications, deviations, source completion, and financial traceability across the full study journey.



\---



\# Core Principle



A subject is not a record.



A subject is a longitudinal operational runtime.



\---



\# Responsibilities



The engine must support:



\- subject creation

\- screening lifecycle

\- eligibility status

\- enrollment state

\- randomization state

\- visit progression

\- longitudinal safety continuity

\- medical history

\- concomitant medications

\- deviations

\- source completeness

\- financial traceability

\- subject timeline reconstruction



\---



\# Subject Lifecycle States



Core states:



\- Pre-Screened

\- Screening

\- Screen Failed

\- Eligible

\- Enrolled

\- Randomized

\- In Treatment

\- In Follow-Up

\- Completed

\- Withdrawn

\- Lost to Follow-Up



\---



\# Longitudinal Timeline



The timeline must display:



\- screening events

\- eligibility decisions

\- randomization events

\- visits

\- procedures

\- AE/SAE events

\- con med updates

\- medical history updates

\- deviations

\- source signatures

\- queries

\- monitoring findings

\- financial signals



\---



\# Runtime Integration



Subject state derives from:



\- operational events

\- visit runtime

\- procedure execution

\- protocol graph

\- safety workflows

\- source completion

\- governance signals

\- financial signals



\---



\# Screening and Eligibility



The engine must support:



\- inclusion criteria tracking

\- exclusion criteria tracking

\- screening checklist

\- screening failures

\- eligibility confirmation

\- PI review/signature requirement

\- protocol version linkage



\---



\# Randomization



The engine must support:



\- randomization readiness

\- randomization confirmation

\- blinding-aware handling

\- role-based visibility

\- randomization lineage

\- event emission



\---



\# Safety Continuity



The subject timeline must preserve:



\- unresolved AEs

\- unresolved SAEs

\- safety holds

\- overdue follow-up

\- safety-related visit blockers

\- longitudinal safety burden



\---



\# Medical History and ConMeds



The engine must support:



\- longitudinal medical history

\- concomitant medication tracking

\- indication linkage

\- start/stop dates

\- relationship to AE or condition

\- visit review history



\---



\# Financial Traceability



The subject runtime must show:



\- earned revenue by visit/procedure

\- missed billables

\- unscheduled burden

\- safety-related burden

\- unresolved financial gaps



\---



\# UX Requirements



The coordinator must be able to answer:



\- Where is this subject in the study?

\- What is pending?

\- What is blocking progress?

\- What changed since last visit?

\- What safety items carry forward?

\- What documentation is missing?

\- What revenue has been earned or missed?



\---



\# MVP Scope



MVP must support:



\- subject lifecycle states

\- subject timeline

\- visit progression

\- safety carry-forward visibility

\- medical history and con meds linkage

\- source completion status

\- basic financial traceability



\---



\# Deferred Scope



Deferred:



\- patient portal

\- sponsor-facing subject analytics

\- advanced automated eligibility extraction

\- autonomous subject risk scoring



\---



\# Explicit Non-Goals



The engine is NOT:



\- static demographics page

\- EDC subject record clone

\- isolated subject table

\- sponsor report view



\---



\# Final Rule



If a coordinator cannot understand a subject’s operational status within one screen, the subject architecture has failed.

