\# Role-Based Access Control and Blinding Engine



Status: Draft



\---



\# Objective



Define the access control and blinding architecture responsible for secure operational visibility, role-based permissions, blinded study protection, audit attribution, and runtime-safe information exposure across Vilo OS.



\---



\# Core Principle



Access is operationally contextual.



Visibility must derive from runtime responsibility and protocol constraints.



\---



\# Responsibilities



The RBAC and Blinding Engine must support:



\- role-based permissions

\- study-level permissions

\- site-level permissions

\- subject-level restrictions

\- blinded study handling

\- monitor review access

\- source protection

\- PI/Sub-I separation

\- audit attribution

\- operational explainability



\---



\# Core Roles



Examples:



\- Organization Owner

\- Site Director

\- Principal Investigator

\- Sub-Investigator

\- Research Coordinator

\- Regulatory Coordinator

\- Finance Coordinator

\- Monitor / CRA

\- Sponsor Viewer

\- Lab User

\- Pharmacist

\- QA Reviewer



\---



\# Permission Model



Permissions must support:



\- entity-level access

\- study-level access

\- subject-level access

\- procedure-level access

\- source-level access

\- signature-level access

\- financial visibility

\- governance visibility



\---



\# Blinding Principles



The system must support:



\- blinded studies

\- partially blinded workflows

\- unblinded pharmacy workflows

\- blinded coordinator workflows

\- monitor-safe views

\- sponsor-safe views



\---



\# Runtime Blinding



Blinding must apply dynamically to:



\- treatment allocation

\- investigational product visibility

\- randomization data

\- unblinded procedures

\- pharmacy workflows

\- source visibility

\- exported documents



\---



\# Audit Attribution



Every action must preserve:



\- actor identity

\- role at execution time

\- timestamp

\- organizational context

\- blinded/unblinded state



\---



\# CRA / Monitor Access



Monitor workflows must support:



\- read-only source review

\- blinded-safe review

\- query creation

\- monitoring findings

\- source lineage review

\- audit reconstruction



Without exposing restricted operational data.



\---



\# Financial Visibility



The engine must support:



\- restricted financial access

\- role-aware revenue visibility

\- sponsor-isolated financials

\- coordinator workload visibility

\- invoice-level restrictions



\---



\# Governance Integration



RBAC integrates with:



\- audit lineage

\- signature attribution

\- CAPA workflows

\- monitoring findings

\- deviation workflows

\- inspection reconstruction



\---



\# UX Requirements



Users should only see:



\- operationally relevant actions

\- allowed workflows

\- role-appropriate visibility

\- permitted financial data

\- permitted source sections



without manually filtering information.



\---



\# Security Principles



The architecture must support:



\- least privilege access

\- immutable auditability

\- secure lineage

\- runtime-safe data exposure

\- role inheritance controls

\- permission explainability



\---



\# MVP Scope



MVP must support:



\- organization roles

\- study-level permissions

\- blinded vs unblinded handling

\- CRA review mode

\- role-based source visibility

\- immutable attribution



\---



\# Deferred Scope



Deferred:



\- enterprise IAM federation

\- SSO provider orchestration

\- external sponsor identity federation

\- advanced attribute-based policy engines



\---



\# Explicit Non-Goals



The engine is NOT:



\- generic admin panel permissions

\- static role table only

\- sponsor-wide identity system

\- disconnected security middleware



\---



\# Final Rule



If blinded information can leak through runtime workflows or exports, the architecture has failed.

