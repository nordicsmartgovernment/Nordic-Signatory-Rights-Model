# Nordic-Signatory-Rights-Model

Information about signatory rights is mainly registered in two different ways in various nations' business registers.

General provisions about signatory rights are registered either as free-text string or as textual code values, that specify terms for who can representent a legal entity. This is often only available in the national language.
If signature rights have been assigned to named persons, these are registered with role types indicating that they have signature rights on the legal entity they represent.
A legal entity with multiple signatory rights can be registered with both variants. There are also examples of signatory rights consisting of both text and roles.

Unstructured information and different registration methods create challenges when information about signatory rights is to be exchanged and interpreted across national borders and systems.

This document proposes a generic approach for how to exchange signatory rights as structured and machine-readable rules within the EU. The Signatory rights model has been developed by the Nordic Smart Government and Business program and is a subset of the Nordic Smart Government data model. The signatory right descriptions (instances of the model) can be used to validate that certain agents (persons or other legal entities) have the authority to take legally binding decisions on behalf of some legal entity.

The Signatory rights class is defined as criterion for one or more mandates that gives power to an agent to represent a legal entity. A legal entity can be registered with one or more instances of Signatory rights.

Signatory rights can consist of one or more signatory rules. Each rule describes in a structured machine-readable way the conditions for a mandate to be valid by setting requirements for the number of agents (Person or Legal entity) and the position(s) (Post) they must hold in a legal entity. An agent can hold one or many positions in a legal entity and can acquire signatory rights through multiple signatory rules.

The Signatory rights model is based on the Core Criterion and Core Evidence Vocabulary defining Signatory rights and Signatory rule as subclasses of respectively Criterion and Constraint. The model is also related to Core Vocabulary of Powers and Mandates, which could be used to further define the type of the mandate. However, the Signatory rights model focuses on defining machine readable rules for determining if an Agent or group of Agents have signatory power.
