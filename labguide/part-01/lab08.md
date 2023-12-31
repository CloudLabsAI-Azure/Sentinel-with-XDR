## Part:1 Lab 08 - Ingest Logs from Microsoft Entra ID

## Lab scenario
Set up log ingestion from Microsoft Entra ID (Azure Active Directory) into a SIEM (Security Information and Event Management) solution for security monitoring and analysis.

## Lab objectives (Duration: 45 minutes)
In this lab, you will complete the following tasks:
- Task 1: Ingesting logs from Microsoft Entra ID to Sentinel

## Architecture Diagram

   ![](../media/lab08.png)

### Task 1: Ingesting logs from Microsoft Entra ID to Sentinel 

In this task, you will explore the Microsoft Sentinel .

1. In the Search bar of the Azure portal, type *Sentinel*, then select **Microsoft Sentinel**.

     ![Picture 1](../media/image_7.png)

2. Select your Microsoft Sentinel Workspace.

3. Select the **Data Connectors**.

4. Search for and select the **Azure Active Directory** (Microsoft Entra ID) connector. Select the AD connector.

   ![Picture 1](../media/Sentinel_Azure_ad_Connector_install.png)

5. Click on **Install**.

6. you will be able to see the incidents generated by Microsoft Entra ID based on Analytics rule setup in the **incidents** tab

   ![Picture 1](../media/Sentinel_course_incidents_3.png)

## Review
In this lab we have completed Ingesting logs from Microsoft Entra ID to Sentinel.
