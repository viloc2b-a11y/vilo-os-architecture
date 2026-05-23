\# Regulatory Workspace Engine



Status: Draft



\---



\# Objective



Define the regulatory workspace architecture responsible for study startup readiness, essential document tracking, delegation logs, training evidence, regulatory package completion, expiration tracking, and inspection-ready regulatory lineage.



\---



\# Core Principle



Regulatory is not a file cabinet.



Regulatory readiness is a continuously computed operational state.



\---



\# Responsibilities



The engine must support:



\- essential document tracking

\- regulatory package readiness

\- delegation of authority

\- training evidence

\- credential/license tracking

\- document expiration tracking

\- IRB document tracking

\- site activation readiness

\- amendment regulatory impact

\- inspection-ready regulatory lineage



\---



\# Core Entities



\- Regulatory Document

\- Essential Document

\- Document Version

\- Delegation Log

\- Training Record

\- Credential

\- License

\- IRB Approval

\- Site Activation Checklist

\- Regulatory Gap

\- Regulatory Readiness Signal



\---



\# Readiness Computation



The system must compute readiness from:



\- required essential documents

\- missing documents

\- expired documents

\- pending signatures

\- missing training

\- missing delegation

\- unresolved regulatory gaps

\- amendment requirements



\---



\# Delegation of Authority



The engine must support:



\- role assignment

\- responsibility delegation

\- PI oversight

\- start/end dates

\- protocol-specific delegation

\- training linkage

\- signature lineage



\---



\# Training Linkage



Training must link to:



\- protocol version

\- amendment version

\- role

\- delegated responsibility

\- activation readiness

\- inspection evidence



\---



\# Expiration Tracking



The system must track expiration for:



\- licenses

\- CVs

\- GCP training

\- medical licenses

\- lab certifications

\- IRB approvals

\- other time-sensitive documents



\---



\# Operational Event Integration



The engine emits events such as:



\- regulatory\_document\_uploaded

\- document\_expired

\- training\_completed

\- delegation\_assigned

\- regulatory\_gap\_created

\- site\_ready\_for\_activation



\---



\# UX Requirements



Users must see:



\- what is missing

\- what is expired

\- what blocks activation

\- who needs training

\- what needs PI signature

\- what changed due to amendment



\---



\# MVP Scope



MVP must support:



\- regulatory document tracking

\- document status

\- expiration alerts

\- delegation log

\- training records

\- activation readiness checklist

\- immutable regulatory events



\---



\# Deferred Scope



Deferred:



\- enterprise eTMF replacement

\- external IRB integration

\- credentialing marketplace

\- automated document classification AI



\---



\# Explicit Non-Goals



The engine is NOT:



\- static document storage

\- generic compliance folder

\- disconnected startup tracker

\- sponsor startup portal



\---



\# Final Rule



If site readiness must be manually calculated outside the system, the regulatory architecture has failed.

