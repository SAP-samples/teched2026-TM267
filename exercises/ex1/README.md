**Exercise 2** — Review the migrated Organization Strcture

## Abstract

The **Business Configuration Organizational Structure Agent** helps you build an enterprise organizational structure proposal based on your migration content from the staging area and SAP Best Practices. It answers org-related questions and validates selections against the SAP reference org model as well as the selected scope.

The agent is invoked automatically by the Business Configuration Assistant when the user intent is organizational structure-related. You do not call it directly.

> **Important:**
> The Organizational Structure Agent will never confirm org on your behalf. After reviewing the proposal, you must confirm it manually in the *Organizational Structure* app. Joule always provides a direct navigation link.

Note: For demo purpose an organizational structure proposal is already pre-loaded to the workspace: **TM267-xx_Migration_Org**

In the Transformation Cockpit, you can: 

- Review issues and their severity level 

- Review issues per org unit (e.g. missing city, name too long) 

- Navigate directly from the Transformation Cockpit to the Org app to fix the issues

- Track status — mark issues as *In Progress* or *Resolved* via status buttons 

Note: Resolved issues do not disappear from the list automatically — they must be manually marked as *Resolved* to reflect the correct status.


1. Open [SAP Central Business Configuration](https://my37555731.trn01.cbc.eu.one.cloud.sap/).
2. Logon with the provided credentials.
3. Go to *Settings*.
4. Choose *Switch Workspace* in the upper right corner.
5. Switch to the workspace *TM267-xx_Migration_Org*.
>Note:  Use the *Switch Workspace* button, in the *Action* column.  
6. Open the define your organizational Structure app and review the created org structure.
>Note:  The org strcture was already created during migration and the units are not yet confirmed so you can still modify them.  
7. Go to the Transformation Cockpit and review organizational Structure related tasks.
8. Aim to resolve organizational structure issue.
>Example:
>Add missing city for 1020 plant or correct name length for 1010 plant.
>
>Note:  In case units are missing basic information in your legacy system, during migration those units will not be created. You will need to create them manually.
>>For example, in case of missing country information, the units are not present in the system so you need to create the units which did not have country information from scratch. 
9. Review the results in the Org App and in the Transformation Cockpit.
>Note: Once the issue is resolved in the Organizational Structure app, you can set the status of the issue in Transformation Cockpit to resolved. 


## Summary

You've now used the Transformation Cockpit to resolve the issues detected during the org migration. 

Continue to - [Exercise 3](../ex2/README.md)

