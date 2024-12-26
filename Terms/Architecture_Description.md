# Architecture description

>[!IMPORTANT]
> **[Systems](System.md)** have **[Architectures](Architecture.md)**. An **Architecture Description** is used to express an **[Architecture](Architecture.md)** of a **[System of Interest](System_of_Interest.md)**.

An **Architecture description** (AD) is a work product that expresses an **[Architecture](Architecture.md)** for a **[System ofInterrest](System_of_Interest.md)**. **[Stakeholders](Stakeholder.md)** use **Architecture Descriptions** to understand, analyze and compare ([System](System.md)) **[Architectures](Architecture.md)**. An **AD** take the form of document(s), model(s), simulation(s) or other forms.
An **architecture description** results form the execution of architecting activities within the life cycle of the **[System of Interest](System_of_Interest.md)**.

AD can document essential aspects of a [system](System.md) :

- Inteded use and environment
- Principles, assumptions and constraints on structure and behavior
- Points of flexibility or limitations of the [system](System.md)
- Architecture decisions, their **[rationales](Rationale.md)** and **impacts**.

Possibles uses of architecture descriptions :

- Analyse and evaluate existing [system](System.md) performance :
  - planning, scheduling and budgeting activites
  - training and policy about the [system](System.md)
  - [System](System.md) interaction processes
  - [System](System.md) maintenance activities
- Review, analysis, and evaluation of the [system](System.md) acress its life cycle
  - Analyse and evaluate alternative implementations of an [architecture](Architecture.md)
  - [System](System.md) design activities
  - [System](System.md) manufacturing activities

> [!WARNING] Requirements
>
>An **AD** shall :
>
>- Identify the **[System of Interest](System_of_Interest.md)**.
>- Identify the system **[Stakeholders](Stakeholder.md)** having **[Concerns](Concern.md)** considered fundamental to the **[Architecture](Architecture.md)** of the **[System of Interest](System_of_Interest.md)**.
>- Identify the **[Concerns](Concern.md)** considered fundamental to the **[Architecture](Architecture.md)** of the **[System of Interest](System_of_Interest.md)**.
>- Associate each identified **[concern](Concern.md)** with the identified **[stakeholders](Stakeholder.md)** having that **[concern](Concern.md)**.

## Architecture description Context

![Architecture Description Context](../Resources/Architecture_Description_Context.png)

**Architectural Descriptions** should address relevant **[stakeholder](Architecture_Description.md)** **[concerns](Concern.md)** about the **[system of interest](System_of_Interest.md)**.

## Architecture description Content

![Architecture description content](../Resources/Architecture_Descriptio_Content.png)

**Architecture Descriptions** are comprised of **[Architecture Views](Architecture_View.md)** of **[AD elements](Architecture_Description_Element.md)**. (Any item in a AD is considered an [AD Element](Architecture_Description_Element.md)) [Stakeholder](Stakeholder.md) [concerns](Concern.md) are addressed when an **AD** exposes **[AD Elements](Architecture_Description_Element.md)** an **[Architecture Views](Architecture_View.md)** that satisfies the conventions established by an **[Architecture Viewpoint](Architecture_Viewpoint.md)**.
