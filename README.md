# Compliance

This repo contains useful Compliance Operator information, tools and techniques - but defintions first.

Compliance in an IT security context means several things. In a broad sense, Compliance (or security) covers physical, administrative and technical requirements (legal and contractual) with the implementation of security best practices and standards on any program / project with their respective IT systems. RedHat's OpenShift Compliance Operator can be used to manage these security settings.

*This is a work in progress.*

# `TL;DR` Squishy terms
* **Compliance:** Legal and/or contractual requirements to secure or present how a program or project has implemented security best practices and standards. (In some odd locations, implementing security standards is different from "compliance" ¯\\_ (ツ)_/¯ )
* **Operator:** An Operator is a Kubernetes plug-in component or application that manages and controls the state of Kubernetes resources.
* **Upstream:** This term is best understood (to me) as the development version of a product. In a small example, Fedora is the upstream source for RHEL. The hard part is connecting **ALL** the upstream projects with the respective downstream products. 
* **Security**
    * **Physical:** The fences, walls, doors, locks and badges required to touch a system.
    * **Administrative:** The paperwork, manual procedures, HR policies and other written instructions - AKA the bureaucracy. 
    * **Technical:**
        * Implementers: The team that monitor the system, operations (sysops) and sysadmins, and apply their respective security settings.
        * Researchers: The brain-boys (or girls) that develop the security fixes.
* **Policy**
    * The administrative aspect, which is some insane multi-dimensional Venn diagram of overlapping "jurisdictions", should-do's, must-do's, can't-dos... 
    * The technical aspect, which also applies a specific set of higher level "rules" implemented in some "enterprise" level software application based on system architecture.

# The Requirements

## General Principles
