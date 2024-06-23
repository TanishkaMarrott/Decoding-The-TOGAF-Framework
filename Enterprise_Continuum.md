# Enterprise Continuum

--> Core concept within TOGAF 

In simple words :-  "A categorisation Framework for artifacts & solutions"
On the basis of :- Varying levels of abstraction / specialisation
  
**Key Elements**

--> Architecture Continuum - Collection of Architectural Building Blocks. They're re-usable across projects

--> Solutions Continuum - Collection of the "actual implementations of the functionality that's been represented by the ABBs". These are the Solution Building Blocks (SBBS)

</br>

> Intangible (ABBs) --> Something tangible (SBBs)

</br>

> Architectural continuum represents a gradation / continuous refinement of architectural elements from generic to organisation-specific elements. While, the Solutions Continuum help us understand the advancement of implementations from generic solutions to specific implementations.

Layers:- Will remain identical for both of them

1 --> Foundational :-  More like a Universal Scaffolding --> basic, fundamental building blocks that form a base for more specific structures --> DBMS, OS, netwroking services

2 --> Common Systems:- Building blocks that're reusable across multiple systems/ organisations --> Could be some common security frameworks, or shared middleware services

3 --> Industry-specific:- Address concerns of a specific industry like HCLS, BFSI

4 --> Organisation-specific:- Custom-built applications, proprietary Business processes

 
## Tools and Techniques to manage the Enterpise Continuum Plus an in-depth analysis into the Architecture Repository

I'd like to talk a bit about about the tools and techniques that we could use for the purpose of categorisation, storage and retrieval of assets that're a part of the Enterprise Continuum

-  Architecture repository :- Key component of the EC. Serves as a storage and management system for all our artifacts.
  
  > It's more like a structured environment for storing and managing these architectural assets

  - Key Components:- 
      - Meta-model,
      - Governance Log,
      - Standards Information Base,
      - Reference Library and
      - Capability Assesment repository

    (We'd be discussing more about this subsequently.)

 - We'd require some Architecture modelling tools too, that could be used for creating architectural models and diagrams. These could then be stored in the Architectural Repository, example) Archimate, IBM Rational System Architect
   
- Tracking versions, managing changes to the architectural artifacts too are essential. That's where Configuration Management Tools like Jira, and Azure DevOps come into the scene. 

  > We need to ensure that updates are *consistently* applied throughout the repository

- Some Content Management System (CMS) like SharePoint, that would enable easy access to docouments and collaboration amongst the stakeholders.
- Plus, a colloboration tool like Slack/ Confluence, for facilitating a smoother, quicker communication/ collaboration among the architecture teams,

  ### Techniques:-

