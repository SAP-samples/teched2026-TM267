# TM267 - Transform your configuration of SAP S/4HANA Cloud with agentic AI

## Description

This repository contains the material for the SAP TechEd 2026 session TM267 - Transform your configuration of SAP S/4HANA Cloud with agentic AI

## Overview

This session introduces attendees to Business Configuration Assistant & Agents which guide project teams through their solution implementation.
## Business Configuration Assistant \& Agents

The **Business Configuration Agents \& Assistant** guide project teams through their solution implementation. 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/50744f29-df34-4299-8867-a00d45fb755a" />


The **Business Configuration Assistant** is the single entry point — it understands your migration context and automatically routes requests to the right specialist agent. It orchestrates the 3 domain specific agents below which are not visible for the user.

|Agent|Role|
|-|-|
|**Business Configuration Scoping Agent**|Generates, validates, and refines Business Scope Proposals| 
|**Business Configuration Organizational Structure Agent**|Generates, validates, and refines Organizational Structure Proposals|
|**Business Configuration Process Adaptation Agent**|Analyzes legacy system configuration against best practices of the target solution and provides corresponding recomendations|

> \*\*Human-in-the-Loop by design:\*\* The agents always propose — you always decide. No scope is confirmed, no org fix is applied, and no configuration is changed without your explicit approval.

</br>

Familiarize yourself with SAP Central Business Configuration. 

SAP Central Business Configuration acts as the backbone for your implementation and provides the apps for scoping, organizational structure setup and configuration.

Each implementation in SAP Central Business Configuration is covered in an own workspace. Additional context (e.g. legacy system data) can be assigned to each Workspace and acts as a Basis for the agents.

Note: Unlike in a real implementation we prepared individual workspaces for the exercises to avoid unneccessary waiting time for longer background processes. You will be guided to select the correct workspace as part of the task.    

When agents will be generally available (GA) there will be Joule as entry point to the agentic transformation but in this exercise, it is not available. 



## Exercises

- [Exercise 1 - Explore Migrated Scope](exercises/ex0)
- [Exercise 2 - Review your migrated Organizational Structure ](exercises/ex1/)
- [Exercise 3 - Analyze Configuration Deltas](exercises/ex2/)

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (20xx-)20xx SAP SE or an SAP affiliate company and <your-project> contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/SAP/<your-project>).
