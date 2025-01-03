# Migrate from Single Server to Postgresql SQL Server Lab

### Overall Estimated Duration: 90 Minutes

## Overview

This lab focuses on migrating a PostgreSQL database from a Single Server to a Flexible Server using the latest migration tool. The migration leverages the benefits of Flexible Server, including enhanced performance, high availability, cost optimization, and greater control over server configurations. By transitioning to Flexible Server, the lab demonstrates how to modernize database infrastructure effectively while ensuring minimal downtime and improved scalability for PostgreSQL workloads.

## Objective

The objective of the PostgreSQL Migration lab is to equip participants with the skills to seamlessly migrate databases from a Single Server to a Flexible Server, by the end of this lab you will be able to:

- **Migrating the database from a Single PostgreSQL server to Flexible PostgreSQL Server using an offline method:** The objective is to enable the seamless migration of a PostgreSQL database from a Single Server to a Flexible Server using the latest migration tool, focusing on modernization and optimization.

## Prerequisites

Participants should have:

- **Basic PostgreSQL Knowledge:** Familiarity with PostgreSQL database management and operations.

- **Azure Platform Understanding:** Basic knowledge of Azure services, including Azure Database for PostgreSQL.

## Architechture

This architecture illustrates the migration of a PostgreSQL database from a Single Server to a Flexible Server using the Single to Flexible Migration Service. The process can be executed via the Azure Portal or CLI. The source Single Server is migrated to the target Flexible Server, leveraging enhanced scalability, performance, and advanced configuration options provided by the Flexible Server architecture.

## Architechture Diagram

![](./Images/lab2archv2.png)

## Explanation of Components

- **PostgreSQL Single Server:** The source database configuration, offering a simplified and managed PostgreSQL experience with basic customization options.

- **PostgreSQL Flexible Server:** The target database configuration, designed for enhanced performance, scalability, and control with advanced configuration capabilities.

- **Single to Flexible Migration Service**: The tool used to facilitate seamless migration, supporting the Azure Portal for efficient database transition.

## Getting Started with Lab

1. Once the environment is provisioned, a virtual machine and lab guide will be loaded in your browser. Use this virtual machine throughout the workshop to perform the lab.

    ![](Images/new-gt-1.png)

1. To get the lab environment details, you can select the **Environment Details** tab. Additionally, the credentials will also be emailed to your email address provided at registration.

    ![](Images/new-gt-2.png)
    
1. You can also open the Lab Guide in a separate full window by selecting the **Split Window** icon at the bottom right corner.

    ![](Images/new-gt-3.png) 
     
## Log in to Azure Portal and verify the pre-deployed resources

In this task you will be Signing in to Azure Portal.

1. Open Azure Portal from the desktop by double-clicking on it.
    
   ![](Images/azure%20portal.png)
   
2. On the **Sign into Microsoft Azure** tab, you will see the login screen, enter the following username, and then click on **Next**.

   * Email/Username: <inject key="AzureAdUserEmail"></inject>

   ![](https://raw.githubusercontent.com/CloudLabsAI-Azure/AVW-SAP-on-Azure/main/media/M2-Ex1-portalsignin-1.png)

3. Now enter the following password and click on **Sign in**. 

   * Password: <inject key="AzureAdUserPassword"></inject>

   ![](https://raw.githubusercontent.com/CloudLabsAI-Azure/AVW-SAP-on-Azure/refs/heads/main/media/M2-Ex1-portalsignin-2.png)

4. If you see the pop-up **Action Required**, click **Ask Later**.

   ![](Images/action.png)

5. If you see the pop-up **Stay Signed in?**, click on **No**.

   ![](https://raw.githubusercontent.com/CloudLabsAI-Azure/AVW-SAP-on-Azure/main/media/M2-Ex1-portalsignin-3.png)

6. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

7. If a **Welcome to Microsoft Azure** popup window appears, click **Cancel** to skip the tour.

8. Now you can see the Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

   ![](https://raw.githubusercontent.com/CloudLabsAI-Azure/AVW-SAP-on-Azure/refs/heads/main/media/M2-Ex1-rg.png)
 
9. We have pre-deployed all the required resources already and you will be using them throughout the lab.

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: cloudlabs-support@spektrasystems.com

- Live Chat Support: https://cloudlabs.ai/labs-support
   
Now, click on Next from the lower right corner to move to the next page.

### Happy Learning!!


 
