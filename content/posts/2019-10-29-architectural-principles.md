+++ 
date = 2019-10-20T10:00:00Z
title = "Architectural principles"
description = ""
slug = "" 
tags = []
categories = []
externalLink = ""
author = "Dr Mark Wardle"
status = "Approved"
+++

Today we held the October 2019 meeting of the Welsh Technical Standards Board. In our work plan, we had recognised the need to define some broad architectural principles which should apply to work within health and care in Wales. Ann Wrightson, head of information architecture at Aneurin Bevan Health Board, led this work and presented it at our September meeting, and today, we approved it.

This is envisaged as a living document that will be updated over time to adapt and flex to our changing requirements. Let us know what you think. It builds on the foundational work we have already agreed:

* [Adoption of the GDS standards](/posts/2018-06-19-wtsb)
* [Adoption of the Welsh Government digital service standard](/posts/2018-06-19-wtsb)
* [Publication of our design principles](/posts/2018-12-01-wtsb)


---

# Introduction

## Scope and Purpose
This version is a draft in development of a WTSB Reference Architecture, prepared for peer review and input from colleagues. 

The purpose of the WTSB Reference Architecture is to provide a common architectural baseline that applies throughout the work of the WTSB, as a document adopted by the WTSB then cited rather than replicated in subsequent work. 

## Background

Initial work on a WTSB Reference Architecture was undertaken in response to positive impressions of similar work in Australia and NHS Scotland. This version is offered for peer review and input from colleagues in the context of the Digital Architecture Review. 

## Overview

The content of the WTSB Reference Architecture is envisaged as:

* eHealth&Care Architecture Principles (complete in draft in this version)
* High level Target Architecture
* Catalogue of roles and responsibilities
* Architecture Building Blocks
* Standardized patterns for other roles
* Appendices incorporating principles adopted by WTSB from UK and Welsh Government 


## Acknowledgements
As well as drawing on previous work in NHS Wales including the NHS Wales Digital Architecture Review (2019) , this work has drawn on (and in parts follows closely): 

* the [eHealth Architecture Principles published by NHS Scotland (2009)](https://www.ehealth.scot/wp-content/uploads/documents/standard-architecture-principles1.pdf)
* the [eHealth Architecture Principles and Interoperability Framework published by the National eHealth Transition Authority of Australia (NeHTA) (2012)](https://www.digitalhealth.gov.au/implementation-resources/ehealth-foundations/ehealth-architecture-principles)
* the [Abstract of a Cookbook for Regional Interoperability in the Yorkshire & Humber Local Health and Care Records Exemplar (2018)](https://yhcr.org/wp-content/uploads/2019/05/YHCR-Interoperability-Cookbook-Abstract-v1.5.docx).


# eHealth&Care Architecture Principles

Architecture principles are general rules and guidelines that inform and support designing, developing and implementing IT resources and assets and their configuration into digital solutions.

*Notes:*

‘Healthcare’ is used throughout as a compact expression denoting the scope of WTSB work across health and social care in Wales.  ‘eHealth&Care’ is used similarly to denote the corresponding scope of information systems with their connectivity and platforms.

Each principle is expressed as title, description, rationale and implications (similar to TOGAF)

* *title*: the essence of the principle; 
* *description*: a succinct and unambiguous definition of the fundamental principle; 
* *rationale*: the business and clinical benefits of adhering to the principle; 
* *implications*: an outline of the key tasks, resources and potential costs associated with following the principle;
* *supporting resources* are also cited where relevant.

Implications and supporting resources in particular will require filling out as work proceeds on required standards and governance

*Method note*: The NHS Scotland principles have been used as a framework, & adapted to WTSB context including the NHS Wales Digital Architecture review. Other sources were used as resources in this process.

## 1. Adhering to the eHealth&Care Architecture Principles 

### Description 

NHS Wales Health Boards and Trusts, their partner organisations in delivering healthcare, and suppliers of healthcare systems and services used in Wales, all adhere to the eHealth&Care Architecture Principles. 

### Rationale 

Adherence to the eHealth&Care Architecture Principles enables incremental and sustainable establishment of an improved architecture that has the security, reliability, flexibility and cost effectiveness necessary to achieve the benefits described in [A Healthier Wales: our plan for health and social care (2018)](https://gov.wales/sites/default/files/publications/2019-04/in-brief-a-healthier-wales-our-plan-for-health-and-social-care.pdf).

### Implications 
An open digital architecture is equally about changing the interactions between the providers and consumers of systems and data. Achieving this requires alignment of operating model, governance, responsibilities and oversight, with clarity, simplicity and transparency throughout.

Solution owners and technical, planning, commercial and policy leads work together to ensure that new solutions comply with the Principles and existing solutions become increasingly compliant through managed change. 

### Supporting resources 


## 2. Solutions are based on the eHealth&Care Reference Architecture 

### Description 

The eHealth&Care Reference Architecture guides the design and delivery of all eHealth&Care solutions.  Aligning with the Reference Architecture is the easy option.

### Rationale 

Undertaking design and delivery of eHealth&Care solutions guided by the eHealth&Care Reference Architecture allows us to make principled, sound decisions without revisiting the fundamentals of what we are trying to achieve.  By basing decisions on previously agreed Architecture Principles and Solution Architecture Patterns (such as defined system roles and responsibilities supported by standards) instead of working from first principles, we can make difficult decisions about architecture and solutions consistently, easier and faster.  Within and across the organisations in scope, a common Reference Architecture provides a set of widely understood decision making principles and a powerful technique to build a cohesive architecture of joined up information systems.

### Implications 

A highly modular approach is key, with well defined roles, responsibilities and interfaces. It means that individual components can be stress-tested and monitored for performance independent of the whole, and enables Health Boards to integrate existing functionality into workflows.
New programme and project solution architectures, nationally and in Health Boards, are explicitly aligned with the Reference Architecture. A degree of pragmatism with respect to existing investments is expected, however alignment is a high priority design goal and divergence must be justified and mitigated. This approach is strongly supported (technically and commercially) so that it is actually the easy option.

Assets are designed for reuse across programmes and projects: this applies to specification, architecture and design assets, as well as software assets (tested modules) and code that is open for less formal reuse. Responsibilities for maintenance and support need to be clear and equitable.
Existing solutions and programme and project architectures converge into alignment with the Reference Architecture, through managed change with increased alignment a consistent and high priority design goal.

### Supporting resources 

* The core eHealth&Care Reference Architecture document (this document and successors)
* Supportive contracts and contract management with vendors supplying systems & services.
* Steady development of further resources forming a comprehensive managed library of documentation and other resources (eg testing instances for standard services, code libraries)
* Networks of collaboration


## 3. The architecture supports Welsh healthcare organisational structures 

### Description 

eHealth&Care digital solutions support the organisational structure of healthcare in Wales, and enable innovation and legitimate variation in response to local clinical and business priorities.  

### Rationale 

Healthcare organisations across Wales have their own priorities and delivery plans as well as joint programmes/projects with partner organisations, collaborative work, and shared aims. The actual eHealth&Care architecture – the digital architecture as implemented – therefore needs to be supportive and enabling in this context.  

### Implications 

* Solution architecture design gives high priority to organisational structures, staff capability and capacity, and the specific goals and boundaries of eHealth&Care initiatives – whilst solution component and interface design gives high priority to reusing existing assets and services, designing for reuse, and use of standards. 

* This is hard, and a particular challenge for achieving a coherent reference architecture and ubiquitous use of standards across a large and complex estate of information systems. It is much easier – and very counterproductive – for conformance to become a simple absolute design value and an end in itself, a ‘dead hand’. The next principle – Agility – provides for systematic mitigation of this issue.

### Supporting resources 

## 4. Agile architecture and solutions 

### Description 

eHealth&Care digital solutions across Wales have a high proportion of reused and reusable components and services, and provide good support for innovation and business change because it is easy to do new things in much the same way as existing things. 

### Rationale 

Architecture and design that expects and enables future change reduces the cost and risk of implementing new solutions. 

The ability to scale, extend, upgrade and reconfigure a solution architecture means that the solution can support changing business and clinical priorities in a cost-effective manner, and also support innovation. Agile architectures have a high proportion of reusable components and services, and provide an environment (eg platform services, codes of connection, and interoperability standards) where it is easy to do new things in much the same way as existing things.  (Agility in architecture is not the same as ‘Agile’ development, though the two work well together.)

### Implications 

* The eHealth&Care Reference Architecture, programme and project solution architectures, architecture components and interface standards are designed for agility (for architecture components and interface standards this is a higher bar than ‘reuse’). This involves a discipline of simplicity, separation of concerns and loose coupling.

* Loose coupling describes connectivity between systems where no ‘insider knowledge’ is needed to interoperate effectively.  For example, an interaction that requires both endpoints to ‘know’ a required sequence of states in a workflow is less loosely coupled than an interaction that communicates state explicitly.

* Governance and oversight must give high priority to design for agility. 

### Supporting resources 
 

## 5. Complying with standards 

### Description 

eHealth&Care solutions, architecture components and interfaces throughout healthcare in Wales ‘play by the rules’ i.e. use standards formally published and adopted for Wales where applicable, with a strong presumption in favour of open standards generally.  

### Rationale 
Complying with standards and, in particular, open standards, helps to maximise return on investment and minimise costs. 

Lack of standards or use of proprietary standards (such as interface specifications developed by suppliers) increases the risk of excessive integration complexity and costs. 

Open standards, developed with rigorous community governance and selected and implemented with care, simplify the integration of solutions, make it easier to replace components with equivalents from another source, and so help reduce whole lifetime costs and risks of a solution deployed within a managed architecture.

### Supporting resources 

* A library of specific standards for Wales, guidance on using other open standards, and implementation support, that is kept up to date and fit for purpose.
* Processes and resources to adopt, adapt or develop new standards as required.
* Governance processes and practical support to make compliance the easy option. 

## 6. Use and adapt pre-existing national and local assets 

### Description 

Architecture components from the existing Health Informatics architecture in NHS Wales should be used, gaining benefits from existing investment; converge existing components into alignment with the Reference Architecture through managed change. 

### Rationale 

The existing Health Informatics architecture in NHS Wales provides a range of useful and reusable services as well as representing considerable investment. Progressive managed change will converge National systems and services into an open platform; Health Boards will benefit from tracking these developments and integrating national services into their workflows.  Aligning local assets with the Reference Architecture provides a sound basis for collaborative innovation, and promotes a more open and competitive market for healthcare IT systems and services in Wales.

### Implications 

* Existing components with sustainable value will converge into alignment with the Reference Architecture, through managed change with increased alignment a consistent and high priority design goal.
* The capabilities of existing national and local applications are considered when designing solutions to meet new business and clinical requirements; managed change with increased alignment will form part of realizing such solutions until alignment is fully achieved.

### Supporting resources 

* eHealth&Care Reference Architecture
* Standards such as interface specifications and codes of connection 

## 7. Information is governed 

### Description 

eHealth&Care solutions adhere to NHS Wales’ standards for Information Governance. 
(Specific considerations for accessibility and security are detailed in separate principles below.)

### Rationale 
Patients entrust NHS Wales and partner organisations with personal information in the expectation that it will be stored securely and accessed when required for legitimate purposes. Robust information governance is key to enabling solutions to reach their full potential. Legislation and policy applies.

### Implications 
* Information governance is a core perspective in architecture design.
* Information governance professionals are core stakeholders in developing solution concepts and detailed architectures. 

### Supporting resources 

* Advice and guidance from Information Governance professionals, both national and local
Guidance documentation provided locally and nationally

## 8. Information is accessible 

### Description 

Information held in or managed by eHealth&Care solutions is made available to authorised individuals and for processing by authorised applications, through any authorised channel and at any place and time where healthcare is delivered. 

### Rationale 
Safe, efficient and effective decision making, either clinical, administrative, or managerial, is directly dependent on the availability and accessibility of information, and therefore systems storing or managing information make that information readily available to authorised (identified, authenticated) individuals and applications. This includes facilitating the sharing of health information with patients, carers and service users. 

### Implications 
* eHealth&Care solutions enable access to stored information and also enable appropriate controls on access
* Within appropriate governance and without further hindrance:

  - Clinical information held in one system can be brought out of that system into a different system (such as but not limited to the CDR) without loss of meaning or ability to analyse the data
  - Operational and management data held in one system can be brought out of that system into a different system (such as a BI facility) without loss of meaning or ability to analyse the data
  - eHealth&Care architecture and solutions enable near-real-time access to operational and management data, irrespective of how the data is collected and stored
  - eHealth&Care architecture and solutions enable near-real-time access to clinical data, irrespective of how the data is collected and stored
  - eHealth&Care architecture and solutions support the sharing of information with the Welsh Government, local authorities, & other organisations

### Supporting resources 

## 9. Information represented as data requires metadata

### Description 

When information is represented as data in eHealth&Care solutions, a data value requires metadata such as a unit of measure, the meaning of the value, provenance (where created, when and by whom) and context (created for what purpose and/or what business context). This is especially important for patient and service user information.

### Rationale 
Safe, efficient and effective decision making is directly dependent on the ability of the decision maker to have confidence in, and where necessary to appraise the relevance and accuracy of, the information used in making the decision.

Recording clinical information intrinsically involves recording much more than bare data values.
For example, a numeric data value (e.g. the number 8.3) only makes sense as clinical information in the context of a unit of measure (e.g. kg), the meaning of the value (e.g. body weight), provenance and context (e.g. as part of a standard set of observations recorded by a qualified practitioner in some community baby clinic on such a date).  

When recording on paper much of this is implicit or readily visible (eg a particular kind of form is used; ‘Weight‘ and ‘kg’ are preprinted on the form used in the clinic; the whole form is dated and signed by the practitioner who completed it).  

The data value ‘8.3’ cannot be reused safely and meaningfully without also recording and reusing the metadata (unit of measure, meaning, provenance and context).

Without careful analysis and incorporation of metadata, digital recording of clinical information is at risk of losing data attributes and contextual information that are essential for safe and veridical reuse of the information. (For clarity, this is in addition to other patient safety related data management essentials such as associating patient information with the right patient.)

### Implications 
* eHealth&Care solutions ensure that information represented as data includes or is robustly associated with requisite metadata.
* In particular, this applies to situations where clinical information held in one system is brought out of that system into a different system (such as but not limited to the CDR). 
* eHealth&Care solution design and implementation decisions that have the effect of reusing or transferring data with loss of context are scrutinised from a clinical informatics perspective.
* This scrutiny is embedded as routine in clinical safety assurance of eHealth&Care solutions.
* Where relevant, caveats are applied to transferred datasets, to ensure their limitations are known and respected.

### Supporting resources 

## 10. Information is secure 

### Description 
Information held in eHealth&Care architecture and solutions is secured against unauthorised access, modification or loss. A common methodology is applied, based on risk.

### Rationale 
Security against unauthorised access, modification or loss is a regulatory requirement for patient information and other information held in confidence, and good practice for other information assets. A common methodology and a risk based approach enable cost effective measures across the eHealth&Care architecture, with security measures aligned with architecture principles and implemented solution architectures.

### Implications 

* eHealth&Care solution architectures and implementations follow a common approach to information security risks within their risk management protocol, comply with national and local policy, adopt best practice to mitigate identified risks, and obtain expert advice as required. 

### Supporting resources 

## 11. Common vocabulary and data definitions 

### Description 
Data is defined consistently across eHealth&Care solutions. Various reference data is managed locally and nationally as appropriate and made available as services to all solutions that need it. Data definitions are available to system users, and to designers and developers, for reference. Data definitions are developed and sustained collaboratively as shared architecture assets.

### Rationale 
Common vocabulary and data definitions are required to ensure that data collected in different systems is comparable for reuse and analysis. This includes clinical point of care information as well as information required for operational management and for clinical purposes other than direct patient care, for example healthcare planning, public health, clinical audit, research and clinical governance. 

A common understanding of concepts embodied in terminologies and data definitions is key to interoperability. Terminologies and data definitions capture the meaning and structure of shared information and thus must be shared and accepted in the community where they are used.

### Implications 

* eHealth&Care solution architectures make use of national and local data standards to ensure that the end to end integrity of clinical meaning and operational relevance is maintained. 
* All operational services must identify the terminology and/or data definitions associated with the information provided or received through the service, and make this information available appropriately for use both at design time for solutions using the services, and (concisely and as appropriate) within the data during operation.
* Standardised terminologies and data definitions are adopted and developed with open, consultative community process and published for use by any eHealth&Care solution, using standard identification schemes. 

### Supporting resources 

## 12. Applications are easy to use and safe in use 

### Description 
An application (or a set of applications used together) is easy to use and to learn to use, providing fluent support of users’ work. Aspects of usability relevant to patient safety are subject to formal clinical safety assurance.

Consistent presentation of applications and information to end-users is ideal, though subject to trade-off with principle 13](#13-ehealth-care-solution-components-come-from-various-sources).

### Rationale 

Applications that are easy to use and to learn to use and provide a fluent user experience enable users to be more self-sufficient, reduce user errors, improve efficiency, foster a positive attitude to eHealth&Care solutions, and reduce the need for formal training. 

### Implications 

* When designing solutions, due consideration is given to measures such as single sign-on, sharing patient context across applications, and using a portal to combine different information sources and functionality into a fluent user experience (see [principle 14](#14-open-platform-underpinned-by-technical-and-information-standards) for technical implications).
* Buy-or-build decisions (see [principle 13](#13-ehealth-care-solution-components-come-from-various-sources)) pay due regard to usability of 3rd party applications and their ability to contribute to an integrated user experience.
* Clinical safety assurance including hazard analysis of user experience is an ongoing requirement for sustaining clinical solutions.

## 13. eHealth&Care solution components come from various sources

### Description 

The eHealth&Care architecture principles apply equally to solutions and architecture components from any source.  There is a presumption in favour of making best use of services and Architectural Building Blocks provided in the Open NHS Wales Platform, and in favour of continuing to derive benefit from previous investments by adapting existing systems and services to use emerging standards. Within this context, there is no architectural presumption for or against deciding to buy a commercial product, develop in-house, or use an open source solution. 

### Rationale

Developing shared assets as an Open NHS Wales Platform (see [principle 14](#14-open-platform-underpinned-by-technical-and-information-standards)) is an architecture strategy and pattern supported and enabled by the eHealth&Care Reference Architecture. 

Buy-or-build and similar trade-offs for specific solutions are often dependent on matters specific to a programme or project, and so not properly the subject of an architecture principle for the whole of eHealth&Care.  Stakeholders are expected to make economically rational decisions taking into account whole-of-life costs of new capability, potential for widening the user base through the open platform, and total cost of ownership.

### Implications 
Programmes and projects will make their own decisions on how to acquire new architecture components, while also being responsible for ensuring that their solution architectures as a whole are aligned with the eHealth&Care Reference Architecture and applicable standards.  

### Supporting resources 

## 14. Open platform underpinned by technical and information standards

### Description 
Digital channels, system and applications, whether national or local, “play by the rules” i.e. work within a common framework of technical and information standards.  Strongly controlled national platforms maintain and protect the “single version of the truth” and provide a robust and resilient means of access for authorised health and social care professionals wherever they are in the system. 

### Rationale 
Pervasive national and local use of standards enables freedom of choice, provides opportunities to innovate and allows digital applications to evolve and respond to a dynamic and changing health and social care landscape.

### Implications 
* Collaborative approach with effective governance, to support and ensure an open platform approach with pervasive use of standards.
* Effective process and supporting human and digital resources for adoption, adaptation, development and dissemination of technical and information standards. 

### Supporting resources 

## 15. Solutions and services are designed to meet their level of clinical and business criticality

### Description 
The level of criticality and required availability for each solution and service is known and kept under review, with risk based management through their active life. 

### Rationale 
Many eHealth&Care solutions are required to be highly available to support critical clinical and operational processes. 

### Implications 
* Solutions are designed with due regard to the criticality of the clinical and/or operational services that they support. 
* Components are designed with known (and documented) characteristics regarding reuse in highly available and resilient services.
* Core services are designed and sustained to achieve and maintain high availability as their capacity and load increases, and as technology develops.
* Business continuity and disaster recovery are given due weight in solution architecture and application design.

### Supporting resources 

## 16. Comply with legislative and policy requirements 

### Description 

eHealth&Care solutions comply with applicable legislation and policies in all organisations within which they operate, and enable their users to comply with applicable professional standards and codes of practice. 

### Rationale 
eHealth&Care operates in a complex legislative and policy environment including regulations and codes of practice that determine how individuals' health & care information must be handled. 

In addition to meeting their legal obligations, healthcare providers must comply with professional standards and ethical codes in areas such as protecting the confidentiality of individuals’ health information, retention of health records, and ensuring the security of health information systems. 

The development, implementation and use of eHealth&Care solutions must support compliance with applicable legislation, professional standards and ethical codes. 

### Implications 
* Applicable legislative, policy and professional practice requirements are explicitly identified for all eHealth solutions and infrastructure, and are reviewed regularly to reflect changes in legislation and policy. 
* For sustainability, policy requirements should be expressed in terms of obligations, permissions, prohibitions, outcomes and performance requirements, rather than prescribing implementation mechanisms.  

### Supporting resources 




 
