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


1. Open SAP Central Business Configuration in a new browser tab.
2. System    [https://my37555731.trn01.cbc.eu.one.cloud.sap](https://my37555731.trn01.cbc.eu.one.cloud.sap/ ) . 
Log on with the provided user credentials.
(example TM267-*xx* - where *xx* is your assigned number)
Common password: Teched2026
3. Select Workspace **TM267-xx_Migration_Scoping**  (xx- being your assigned number)
4. Open Joule in a separate browser tab
5. Initiate context in Joule with following prompt:
**XYZ**

## Summary

Now that you have familiarized with the Assistant and Agents
continue to - [Exercise 1 - Define your Scope(../ex1/README.md)
