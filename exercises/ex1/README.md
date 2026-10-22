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

- Track status — mark issues as *In Progress* and then *Resolved* via status buttons 

Note: Resolved issues do not disappear from the list automatically — they must be manually marked as *Resolved* to reflect the correct status.


1. Open [SAP Central Business Configuration](https://my37555731.trn01.cbc.eu.one.cloud.sap/).
2. Logon with the provided credentials.
3. Go to *Settings*.
4. Choose *Switch Workspace* in the upper right corner.
5. Switch to the workspace *TM267-xx_Migration_Org*.
>Note:  Use the *Switch Workspace* button, in the *Action* column.
>
<img width="1032" height="498" alt="Screenshot 2026-10-21 at 4 28 15 PM" src="https://github.com/user-attachments/assets/b77ac111-c5f2-479d-b56e-600577e96fc3" />
 
6. Open the *Organizational Strcuture* app and review the created org structure.
>Note:  The org strcture was already created during migration and the units are not yet confirmed so you can still modify them.  
7. Go to the Transformation Cockpit and review organizational structure related issues.
8. Aim to resolve organizational structure issue in the next steps.
>Example:
>Add missing city for 1020 plant or correct name length for 1010 plant.
>Note:  In case units are missing basic information in your legacy system, during migration those units will not be created. You will need to create them manually.
>>For example, in case of missing country information, the units are not present in the system so you need to create the units which did not have country information from scratch.
9. Navigate to the *Organizational Structure* app, search 1020 , select the plant and add the missing city in the right side panel.
>><img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a5556a0f-6be3-4d8e-b27b-cca07be74589" />

10. Now search for 1010 plant, select it and enter a name which is shorter than 30 characters
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/03f311cb-4fa2-4e35-b629-08d2e8ec30ee" />

12. Mark the resolved issues as resolved in the Transformation Cockpit.
>Note: Once the issue is resolved in the Organizational Structure app, you can set the status of the issue in Transformation Cockpit to *in progress* and then to *resolved*. 


## Summary

You've now used the Transformation Cockpit to resolve the issues detected during the org migration. 

Continue to - [Exercise 3](../ex2/README.md)

