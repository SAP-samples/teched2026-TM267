# Business Configuration Assistant \& Agents

The **Business Configuration Agents \& Assistants** guide project teams through their solution implementation.

The **Business Configuration Assistant** is the single entry point — it understands your migration context and automatically routes requests to the right specialist agent.

|Agent|Role|
|-|-|
|**Business Configuration Scoping Agent**|Generates, validates, and refines Business Scope Proposals|
|**Business Configuration Organizational Structure Agent**|Generates, validates, and refines Organizational Structure Proposals|
|**Business Configuration Process Adaptation Agent**|Analyzes legacy system configuration against best practices of the target solution and provides corresponding recomendations|

> \*\*Human-in-the-Loop by design:\*\* The agents always propose — you always decide. No scope is confirmed, no org fix is applied, and no configuration is changed without your explicit approval.

</br>

Familiarize yourself with SAP Central Business Configuration and Joule the central tooling for the Business Configuration Assistant. 

SAP Central Business Configuration acts as the backbone for your implementation and provides the apps for scoping, organizational structure setup and configuration.

Each implementation in SAP Central Business Configuration is covered in an own workspace. Additional context (e.g. legacy system data) can be assigned to each Workspace and acts as a Basis for the agents.

Note: Unlike in a real implementation we prepared individual workspaces for the exercises to avoid unneccessary waiting time for longer Background processes. You will be guided to select the correct Workspace as part of the task.    

Joule is the Engagement layer to interact with the Business Configuration Assistant and herewith provides the entry point to the agentic Transformation.

**Exercise 1 - Explore Scoping issues detected during migration**

### Abstract

The Transformation Cockpit allows a central overview across all relevant deviations between the legacy system and the target solution. 

The **Business Configuration Scoping Agent** hereby helps you build accurate scope proposals based on your migration content from the staging area and SAP Best Practices. It answers scope-related questions, validates selections against country policies and licensing entitlements, and generates deviation reports on demand.

The agent is invoked automatically by the Business Configuration Assistant when the user intent is scoping-related. You do not call it directly.

> \*\*Important:\*\*
> The Scoping Agent will never confirm scope on your behalf. After reviewing the proposal, you must confirm it manually in the \*Define Scope\* app. Joule always provides a direct navigation link.

Note: A first scope proposal is already pre-loaded to the selected workspace

In the Transformation Cockpit you can:
- Review issues including their severity level 

- View all scoping scenarios from the legacy/staging system 

- Inspect each scenario's details and issues 

- Download the scenario list — usable to create a support case 

Note: Only issues related to license-dependent scenarios and scenarios not covered by Best Practice content are displayed. 



1. Open [SAP Central Businsess Configuration](https://my37555731.trn01.cbc.eu.one.cloud.sap/) in a new browser tab. 
Log on with the provided user credentials. 
>Note: 
Workspaces are pre-created. You have already been assigned as a team member to the workspace **TM267-xx_Migration_Scoping** related to this exercise so that you can directly start the exercise.

2. Open the *Transformation Cockpit* and review the issues detected during migration.
>Note: 
Identify the scenarios which need to be added via a ticket and the scenarios which cannot be added at all, since they are not part of the best practices. Issue list can also be downloaded for your documentation. 
>Example:
BH1 - was pricing relevant, was not added to scope and can only be added via a support case.

3. TBD


## Summary

You have used the Transformation Cockpit to analyze scoping issues detected during migration. 

Now, you can continue to - [Exercise 2](../ex1/README.md)
