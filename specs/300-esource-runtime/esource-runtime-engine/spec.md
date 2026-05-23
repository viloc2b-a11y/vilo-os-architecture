\# eSource Runtime Engine



Status: Draft



\---



\# Objective



Define the dynamic eSource runtime that allows protocol-aware source capture, section-based forms, signatures, corrections, addenda, lineage, and procedure-linked documentation.



\---



\# Core Principle



eSource is not a static form.

eSource is protocol-linked execution evidence.



\---



\# Responsibilities



The eSource Runtime Engine must support:



\- dynamic source sections

\- procedure-linked source capture

\- visit-linked source packages

\- coordinator signatures

\- PI/Sub-I signatures

\- corrections

\- addenda

\- audit lineage

\- section add/remove

\- partial and complete sections

\- multiple input modalities



\---



\# Source Structure



A source package contains:



\- visit context

\- subject context

\- protocol version

\- procedure-linked sections

\- general clinical sections

\- safety sections

\- signature blocks

\- audit lineage



\---



\# Dynamic Sections



The system must allow:



\- adding sections

\- removing sections

\- reordering sections

\- marking sections not done

\- linking sections to procedures

\- linking sections to visits

\- linking sections to safety events



\---



\# Input Modalities



Supported input types:



\- text

\- number

\- date

\- time

\- dropdown

\- multi-select

\- checkbox

\- yes/no

\- calculated field

\- vital signs group

\- medication table

\- medical history table

\- AE table

\- lab value table

\- file attachment

\- signature



\---



\# Vital Signs Example



Vital signs must support structured fields such as:



\- weight

\- height

\- BMI

\- temperature

\- blood pressure

\- pulse

\- respiratory rate

\- heart rate

\- oxygen saturation



BMI should be calculated when height and weight are available.



\---



\# Signatures



The engine must support:



\- coordinator signature

\- PI signature

\- Sub-I signature

\- timestamped signatures

\- role attribution

\- locked signed source

\- post-signature addenda



\---



\# Correction Model



Corrections must:



\- preserve original value

\- capture corrected value

\- capture reason

\- capture actor

\- capture timestamp

\- emit immutable event

\- preserve audit trail



\---



\# Addendum Model



Addenda must:



\- reference signed source

\- include reason

\- include author

\- include timestamp

\- preserve original signed state



\---



\# Protocol Linkage



Each source section may link to:



\- protocol version

\- visit definition

\- visit instance

\- procedure definition

\- procedure execution

\- safety event

\- operational event



\---



\# Governance Integration



The eSource runtime must generate:



\- source lineage

\- correction events

\- signature events

\- monitoring evidence

\- deviation support evidence

\- audit artifacts



\---



\# Financial Integration



Procedure-linked source completion may trigger:



\- billable earned

\- billable pending

\- billable blocked

\- missed revenue signal



\---



\# MVP Scope



MVP must support:



\- section-based dynamic source

\- visit source packages

\- procedure-linked sections

\- structured fields

\- signatures

\- corrections

\- addenda

\- immutable event emission



\---



\# Explicit Non-Goals



The eSource engine is NOT:



\- generic no-code form builder

\- sponsor EDC replacement

\- uncontrolled document editor

\- PDF-only documentation tool



\---



\# Final Rule



If eSource capture does not produce executable operational evidence, it does not belong in Vilo OS.

