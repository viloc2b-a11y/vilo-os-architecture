\# Recruitment and Patient Navigation Runtime Engine



Status: Draft



\---



\# Objective



Define the runtime architecture for recruitment, prescreening, referral intake, patient navigation, enrollment conversion, longitudinal engagement, and operational recruitment intelligence.



\---



\# Core Principle



Recruitment is not marketing.



Recruitment is operational patient orchestration.



\---



\# Responsibilities



The engine must support:



\- lead intake

\- referral intake

\- prescreening workflows

\- eligibility triage

\- outreach tracking

\- navigation workflows

\- enrollment conversion tracking

\- diversity/access workflows

\- no-show reduction

\- longitudinal engagement

\- recruitment operational analytics



\---



\# Core Entities



\- Recruitment Lead

\- Referral

\- Prescreening Record

\- Outreach Attempt

\- Navigation Task

\- Eligibility Signal

\- Enrollment Conversion

\- Recruitment Source

\- Contact Preference

\- Recruitment Workflow

\- Engagement Event



\---



\# Recruitment Runtime Chain



Lead

→ Prescreening

→ Eligibility Triage

→ Outreach

→ Navigation

→ Screening Visit

→ Enrollment

→ Longitudinal Follow-Up



\---



\# Prescreening Workflows



The system must support:



\- protocol-specific prescreening

\- inclusion/exclusion triage

\- multilingual workflows

\- referral-based intake

\- source attribution

\- prescreening documentation

\- prescreening status progression



\---



\# Navigation Workflows



The system must support:



\- appointment coordination

\- transportation coordination

\- reminder workflows

\- document collection guidance

\- bilingual navigation

\- missed appointment recovery

\- unresolved navigation tasks



\---



\# Diversity and Access Support



The engine must support:



\- multilingual communication

\- underserved population workflows

\- referral partnerships

\- access barrier tracking

\- navigation burden tracking

\- community referral source analysis



\---



\# Longitudinal Engagement



The system must support:



\- follow-up reminders

\- unresolved outreach

\- retention workflows

\- re-engagement workflows

\- longitudinal communication history



\---



\# Recruitment Intelligence



The engine must compute:



\- referral conversion rates

\- outreach effectiveness

\- screen fail patterns

\- navigation burden

\- no-show risk

\- enrollment bottlenecks

\- diversity access signals



\---



\# Operational Event Integration



The engine emits events such as:



\- lead\_created

\- prescreening\_completed

\- outreach\_attempted

\- appointment\_confirmed

\- no\_show\_detected

\- screening\_completed

\- subject\_enrolled

\- retention\_risk\_detected



\---



\# Financial Integration



The engine must support:



\- recruitment cost signals

\- navigation burden signals

\- enrollment conversion value

\- referral ROI

\- recruitment leakage analysis



\---



\# UX Requirements



Recruitment staff must see:



\- who needs outreach

\- who is eligible

\- who is pending navigation

\- who missed appointments

\- who is at retention risk

\- where recruitment bottlenecks exist



\---



\# MVP Scope



MVP must support:



\- lead intake

\- prescreening workflows

\- outreach tracking

\- navigation task tracking

\- enrollment conversion tracking

\- multilingual placeholders

\- immutable recruitment events



\---



\# Deferred Scope



Deferred:



\- patient mobile app

\- automated omnichannel campaigns

\- advanced predictive enrollment AI

\- external CRM replacement

\- ad platform integrations



\---



\# Explicit Non-Goals



The engine is NOT:



\- generic CRM

\- marketing automation platform

\- ad management platform

\- disconnected call center software



\---



\# Final Rule



If recruitment workflows become disconnected from operational study execution, the architecture has failed.

