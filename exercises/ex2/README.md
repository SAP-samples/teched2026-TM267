**Exercise 3 — Analyze Configuration Deltas**


**Abstract**


The **Business Configuration Process Adaptation Agent** analyzes the customer's ECC configuration records against S/4HANA Cloud Public Edition best practices and generates structured, prioritized delta reports. It classifies the discrepancies, assesses the business impact, and recommends a resolution path — reducing weeks of manual spreadsheet analysis to an automated, intelligent assessment.

The Configuration Comparisson app allows a detailed assesment of the configuration deltas by record and attribute.

> \*\*Note:\*\*
> The agent analyzes and recommends — it does not apply configuration changes automatically. Configuration adjustments are executed manually in the relevant configuration activity (SSCUI) after reviewing the agent's recommendations. 

</br>
In the Transformation Cockpit, you can: 

 - Review issues and their severity level 

- Compare legacy configuration vs. Best Practice content side by side in *Configuration Compare*

- Track issue status (same status management as org) 

- View related SSCUIs connected to each configuration object 

Note: No live S/4HANA system connection established — direct navigation into a configuration activity is not possible. 


1. Open [SAP Central Business Configuration](https://my37555731.trn01.cbc.eu.one.cloud.sap/).
2. Logon with the provided credentials.
3. Go to *Settings*.
4. Choose *Switch Workspace* in the upper right corner.
5. Switch to the workspace *TM267-xx_Migration_Configuration**.
>Note:  
Use the *Switch Workspace* button, in the *Action* column.  
6. Go to the Transformation Cockpit and review configuration related tasks.
>Note:
Check the following configuration settings for differences (copy and paste the texts below into the search help of the system): 

- Billing: Document Types: Multiple data inconsistencies detected 

- BP Roles: Multiple data inconsistencies detected 

- Transaction-Dependent Defaults: Invoice Verification: Multiple data inconsistencies detected 

- Cost Center Types: Field conflicts and extra records in target 

- Customers: Incoterms: Texts: Multiple data inconsistencies detected
  
7. Select a configuration issue and navigate to the *Comparison App*.
8. Review the deviations between ECC data and reference content.
9. Identify the related configuration activities (SSCUIs) for which the selected issue occured.

**Summary**
You've now used the Transformation Cockpit to resolve the issues detected during the configuration migration.



   
