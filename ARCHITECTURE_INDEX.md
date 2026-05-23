\# Vilo OS Architecture Index



Status: Active  

Repository: vilo-os-architecture  

Purpose: Single navigation map for Vilo OS architecture, specs, runtime models, governance, and implementation handoff.



\---



\# Product Definition



Vilo OS is an execution-native clinical research operating system for research sites.



It is designed to reduce coordinator cognitive load, orchestrate protocol execution, generate governance lineage, and derive financial intelligence from runtime execution.



\---



\# Core Principle



The coordinator should not carry protocol complexity cognitively.



The system orchestrates execution.



\---



\# Architecture Layers



\## 1. Execution Runtime Core



Location:



\- specs/100-runtime-core/



Includes:



\- Visit Runtime Engine

\- Operational Event Spine

\- Subject Lifecycle and Timeline Engine

\- Lab and Biospecimen Runtime Engine



\---



\## 2. Protocol Intelligence



Location:



\- specs/200-protocol-intelligence/



Includes:



\- Protocol Graph Engine

\- Study Builder and Runtime Publication Engine

\- Amendment Impact and Training Engine



\---



\## 3. eSource Runtime



Location:



\- specs/300-esource-runtime/



Includes:



\- eSource Runtime Engine



\---



\## 4. Safety Orchestration



Location:



\- specs/400-safety-orchestration/



Includes:



\- Safety Orchestration Engine



\---



\## 5. Financial Runtime



Location:



\- specs/500-financial-runtime/



Includes:



\- Financial Runtime Intelligence Engine



\---



\## 6. Governance Fabric



Location:



\- specs/600-governance-fabric/



Includes:



\- Governance Fabric Engine

\- Document and TMF Intelligence Layer

\- Operational Intelligence and Signal Engine

\- RBAC and Blinding Engine

\- Query and Monitoring Finding Engine

\- Regulatory Workspace Engine



\---



\## 7. Experience Layer



Location:



\- specs/700-experience-layer/



Includes:



\- Coordinator Workspace Experience Layer

\- Recruitment and Patient Navigation Runtime Engine

\- Site Operations Command Center



\---



\## 8. Enterprise Roadmap



Location:



\- specs/800-enterprise-roadmap/



Includes:



\- MVP Boundary and Enterprise Roadmap



\---



\# Build Order



1\. Operational Event Spine

2\. Visit Runtime Engine

3\. Subject Lifecycle Timeline

4\. Protocol Graph Engine

5\. Study Builder / Runtime Publication

6\. eSource Runtime

7\. Safety Orchestration

8\. Governance Fabric

9\. Financial Runtime Intelligence

10\. Coordinator Workspace

11\. Operational Intelligence Signals

12\. Enterprise Roadmap



\---



\# Non-Goals



Vilo OS is NOT:



\- generic CTMS

\- sponsor-first software

\- CRO workflow platform

\- dashboard-first product

\- AI wrapper

\- generic form builder

\- static document repository

\- ERP

\- LIMS replacement

\- eTMF replacement



\---



\# Agent Rules



All agents must follow:



1\. Specs before implementation.

2\. Runtime before dashboards.

3\. Coordinator-first before sponsor visibility.

4\. Event-derived state before mutable status.

5\. Postgres-first before microservices.

6\. Human-governed AI only.

7\. No feature should increase coordinator cognitive load.



\---



\# Implementation Repo



Product implementation lives separately:



```text

C:\\DEV\\vilo-os

