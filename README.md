# MICROSOFT ANALYTICS USE CASE

| __IN-HOUSE TECHNOLOGY STACK FOR THE USE CASE:-__ |
| --------- |
| Hadoop Cluster with 200 Nodes. |
| Oracle. |
| SQL Server. |
| PostgresSQL. |
| Tableau. |
| Alteryx. |
| Talend. |
| Informatica. |
| PowerBI. |
| Python and R. |


| __GOAL OF CONTOSO:-__ |
| --------- |
| Strategic Plan to move to Cloud. |
| Interest in findings on the ability of Azure or a Multi-Cloud Solution to host all their tools. |
| Primary Requirement - Hadoop Cluster to Azure. |
| What is the Hadoop Equivalent Azure Service?  |
| How to Migrate Data? |
| Possibility to Operate in Hybrid Infrastructure? |
| Develop a Phase Plan. 1st Phase - Migrate Hadoop Cluster to Azure, 2nd Phase - Migrate rest of the Spoke Applications. |
| Data Ops Team is Linux and Open-Source Oriented. |


| __WHAT IS MISSING FROM REQUIREMENT GATHERING:-__ |
| --------- |
| Purpose of Each Data Technologies in Spoke. |
| Workflow of all Data Technologies in On-Premises. |
| Volume of Data and Growth % Per Month/Quater/Bi-Yearly or Yearly. |
| Timelines. |
| Problem Statement. |
| Motivation to Move to Azure. |


| __NOTE:-__ |
| --------- |
| Legacy System is not a relevant motivation. With New Hardware Infrastructure, Version upgrades of Data Technologies, and Enhancement of Applications can eradicate Legacy System callouts. |
| Legacy Systems can be classified into 4 Broad Categories:- 1) Obsolete Hardware 2) Obsolete Application Software Version 3) Obsolete Database Version 4) Obsolete Application Codebase. |
| All the above points can be addressed On-Premise, without the actual need to move to the Cloud. |


| __EQUIVALENT AZURE SERVICES IN COMPARISON TO IN-HOUSE TECHNOLOGY STACK FOR THE USE CASE:-__ |
| --------- |

| __HADOOP CLUSTER:-__ |
| --------- |
| [Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-overview) |


| __ORACLE:-__ |
| --------- |
| [Oracle Database in Azure VM](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/oracle/oracle-database-quick-create) |
| __Platform:-__ Infrastructure-As-A-Service (IaaS)|
| Oracle databases can be run on Azure Infrastructure using __Oracle Database on Oracle Linux Images__ available in the Azure Marketplace. Below are the Editions:- |
| __Oracle Database 12.2, and 18.3 Enterprise Edition__ |
| __Oracle Database 12.2, and 18.3 Standard Edition__ |
| __Oracle Database 19.3__ |
| __Optionally configure with multiple attached disks and improve database performance by installing Oracle Automated Storage Management (ASM).__ |
| __********************************************************************************************************************************************__ |
| [OCI and Azure](https://www.oracle.com/cloud/azure/oracle-database-for-azure/) |
| __Platform:-__ Multicloud (Oracle Cloud Infrastructure - OCI) and Microsoft Azure|
| Oracle Database Service for Microsoft Azure is an Oracle-managed service for Azure customers to easily provision, access, and operate enterprise-grade Oracle Database services in Oracle Cloud Infrastructure (OCI) with a familiar Azure-like experience. |
| The service establishes low-latency connectivity between Microsoft Azure and OCI, deploys Oracle Database on OCI, and provides metrics on Azure. |
| There are no charges for Oracle Interconnect for Microsoft Azure ports or data ingress/egress over the Interconnect.  |
| You will be billed normally for the consumption of Oracle Database services. |
| __********************************************************************************************************************************************__ |


| __SQL SERVER:-__ |
| --------- |
| [Azure SQL Managed Instance](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview?view=azuresql) |
| __Platform:-__ Platform-As-A-Service (PaaS) |
| Azure SQL Managed Instance is Microsoft's intelligent, scalable, cloud database service. It allows you to use the full power of SQL Server without any hassle of setting up the infrastructure. This includes Machine Learning Services which contains Microsoft R and Python packages for high-performance predictive analytics and machine learning. |


| __POSTGRESSQL:-__ |
| --------- |
| [Azure Database for Postgresql](https://docs.microsoft.com/en-us/azure/postgresql/) |
| __Platform:-__ Platform-As-A-Service (PaaS) |
| Azure Database for PostgreSQL is a relational database service in the Microsoft cloud based on the PostgreSQL open source relational database. |


| __TABLEAU:-__ |
| --------- |
| [Tableau in Azure](https://www.tableau.com/learn/whitepapers/next-generation-cloud-bi-tableau-server-hosted-microsoft-azure) |
| [Tableau Server on Azure - Quickstart](https://www.tableau.com/about/blog/2019/8/introducing-tableau-server-linux-azure-quickstart) |


| __ALTERYX:-__ |
| --------- |
| __Alteryx__ is used for Analytics and Specializes in __Data Preparation__ |
| The Key Difference Between __ALTERYX__ and __TABLEAU__ is that the Latter specializes in __Data Visualization__ |
| __Notes:-__ |
| __Platform:-__ Infrastructure-As-A-Service (IaaS)|
| [Alteryx Server on Azure](http://downloads.alteryx.com/Documentation/Alteryx%20Server%20on%20Azure.pdf) |
| [Alteryx Server on Azure](https://community.alteryx.com/t5/Alteryx-Server-Knowledge-Base/Alteryx-Server-on-Azure/ta-p/24395) |
| __Platform:-__ Software-As-A-Service (SaaS)|
| [Azure Marketplace: Alteryx APA(Analytic Process Automation) Platform](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/alteryx.alteryx-analytics-platform?tab=Overview) |


| __TALEND:-__ |
| --------- |
| __Talend__ is an open-source data integration platform. It provides various software and services for __Data Integration__, __Data Management__, __Enterprise Application Integration__, __Data Quality__, __Cloud Storage__ and __Big Data__. |
| [Mordernize Cloud Platform for Big Data Analytics With Talend and Microsoft Azure](https://www.talend.com/resources/talend-microsoft-azure-together/) |
| __Notes:-__ |
| __Platform:-__ Integration Platform-As-A-Service (iPaaS)|
| [Azure Marketplace: Talend Remote Engine for Microsoft Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/talend.talendremoteengine?tab=Overview) |
| __Connectivity:__ By pairing a Talend Remote Engine created from Talend Cloud with a Talend Remote Engine for Azure, you can execute tasks and plans easily with minimal configuration steps. [Talend Remote Engine for Microsoft Azure](https://help.talend.com/r/en-US/Cloud/remote-engine-azure-user-guide/talend-remote-engine-for-microsoft-azure) |


| __INFORMATICA:-__ |
| --------- |
| __Informatica Intelligent Cloud Services (IICS)__ is a Cloud-Based Data Integration Platform that provides a variety of features such as business data integration, application integration, and API management between cloud and local applications. |
| [Informatica Intelligent Cloud Services](https://www.informatica.com/content/dam/informatica-com/en/collateral/solution-brief/informatica-intelligent-cloud-services-for-microsoft-azure_3999en.pdf) |
| __Notes:-__ |
| __Platform:-__ Integration Platform-As-A-Service (iPaaS)|
| [Azure Marketplace - Informatica](https://azuremarketplace.microsoft.com/en-au/marketplace/apps/informatica.annualiics?tab=Overview) |
| __Connectivity:__ Secure Agents enables secure communication across the firewall between your organization and Informatica Intelligent Cloud Services(IICS). [Informatica Intelligent Cloud Services (IICS) IP addresses to be allowed in the Organization firewall](https://knowledge.informatica.com/s/article/524982?language=en_US&pageversion=19456) |
| [Minimum requirements and Best Practices when installing Informatica Cloud Secure Agent](https://knowledge.informatica.com/s/article/526096?language=en_US) |
| [Secure Agent Installation Guide - Linux](https://github.com/jbrazda/Informatica/blob/master/Guides/InformaticaCloud/ic_sa_installation.md) |


| __POWERBI:-__ |
| --------- |
| To Prepare and Deliver Reports. | 
| __Platform:-__ Software-As-A-Service (SaaS)|


| __PYTHON AND R LANGUAGE IN AZURE:-__ |
| --------- |
| [Data Science Virtual Machine](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide#data-science-virtual-machine) |
| __Platform:-__ Infrastructure-As-A-Service (IaaS)|
| The __Data Science Virtual Machine (DSVM)__ is a customized VM image on Microsoft's Azure cloud platform built specifically for doing data science. It has many popular data science tools, including Microsoft R Open, RStudio Desktop, and RStudio Server. The DSVM can be provisioned with either Windows or Linux as the operating system.  |
| __********************************************************************************************************************************************__ |
| [ML Services on HDInsight](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide#ml-services-on-hdinsight) |
| __Platform:-__ Platform-As-A-Service (PaaS)|
| Microsoft ML Services provide Data Scientists and R programmers with on-demand access to scalable, distributed methods of analytics on HDInsight. This solution provides the latest capabilities for R-based analytics on datasets of virtually any size, loaded to either Azure Blob or Data Lake storage.|
| __********************************************************************************************************************************************__ |
| [Azure Machine Learning](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide#azure-machine-learning) |
| __Platform:-__ Platform-As-A-Service (PaaS)|
| Azure Machine Learning is a cloud service for accelerating and managing the machine learning project lifecycle. Machine learning professionals, data scientists, and engineers can use it in their day-to-day workflows: Train and deploy models, and manage MLOps. |
| __********************************************************************************************************************************************__ |
| [Azure SQL Managed Instance](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/r-developers-guide#azure-sql-managed-instance) |
| __Platform:-__ Platform-As-A-Service (PaaS)|
| Azure SQL Managed Instance is Microsoft's intelligent, scalable, cloud database service. It allows you to use the full power of SQL Server without any hassle of setting up the infrastructure. This includes Machine Learning Services which contains Microsoft R and Python packages for high-performance predictive analytics and machine learning. |
| __********************************************************************************************************************************************__ |


| __BILL OF MATERIAL (BOM):-__ |
| --------- |

| __AZURE SERVICES__ | __PURPOSE__ | __PLATFORM__ |
| --------- | --------- | --------- |
| __Resource Group__ | Placeholder for all Azure Resources. | - |
| __Azure Key Vault__ | To Store Credentials. | __PaaS__ |
| __Log Analytics__ | To Store and Query Logs, Monitoring and Incident Management. | __PaaS__ |
| __Storage Account__ | To Backup Data + Store and Archive Logs | __PaaS__ |
| __Virtual Network, Subnet, DDos, Peering, Network Security Group(NSG), Route Table, Global DNS and Private DNS__ | Setting Up Network Infrastructure | __PaaS__ |
| __HDInsight__ | Hadoop Cluster (__LINUX__). | __PaaS__ |
| __Oracle__ | Oracle Database (If IaaS, then __LINUX__ VMs).| __IaaS__ or __Multicloud: OCI and Azure__ |
| __Azure SQL Managed Instance__ | Managed SQL. | __PaaS__ |
| __Azure Database for PostgreSQL__ | Managed PostgreSQL. | __PaaS__ |
| __Tableau__ | - | __PaaS__ |
| __Alteryx__ | Used for Data Preparation (If IaaS, then __LINUX__ VMs).| __IaaS__(Alteryx Server on Azure) or __SaaS__(Alteryx APA - Analytic Process Automation) Platform |
| __Talend__ | Remote Engine on Virtual Machine (__LINUX__) peering Between Talend Cloud and Azure Remote Engine. | __IaaS__ |
| __Informatica__ | Secure Agents on Virtual Machines (__LINUX__) COmmunicating to IICS. | __IaaS__ |
| __PowerBI__ | Prepare and Deliver Reports. | __SaaS__ |


| __OPTIONAL AZURE SERVICES UNDER BILL OF MATERIAL (BOM):-__ |
| --------- |

| __AZURE SERVICES__ | __PURPOSE__ | __PLATFORM__ |
| --------- | --------- | --------- |
| __Data Science VM__ | Customized VM for Data Science (Python and R) - __LINUX.__ | __IaaS__ |
| __ML Services on HDInsight__ | Cloud Service for creating and managing machine learning solutions. | __PaaS__ |
| __Azure Machine Learning__ | Cloud Service for day-to-day workflow used by Data Scientists - MLOps.  | __PaaS__ |


| __CALLING OUT EXCEPTIONS:-__ |
| --------- |
| Customer should have Robust Network Infrastructure - Azure __HUB AND SPOKE__. Building Hub and Spoke is __OUT OF SCOPE.__ | 
| Customer should have Resilient Bandwidth connecting Azure and In-House Datacentre. Setting up this connectivity is __OUT OF SCOPE.__ |


| __SECURITY AND VULNERABILITY MANAGEMENT OF AZURE SQL MANAGED INSTANCE AND POSTGRESQL:-__ | 
| --------- |
| Setting up Private Endpoint. | 
| Configure Required Firewall Rules. | 
| Setting up Azure Active Directory Admin (It can be an AAD User or AAD Group). |
| Configuring Required Role Based Access Control(RBAC). |
| Setting up Audit and Vulnerability Assessment and Populating the Report in Storage Account With Email Notification.


| __PROPOSED APPROACH:-__ |
| --------- |
| POC - Functional Test |
| Non-Prod - Functional and Performance Test |
| Prod - Functional and Performance Test |
| Cutover (On-Prem) and Golive (Cloud) |


| __PROPOSED GUIDELINES FOR MIGRATION:-__ |
| --------- |
| POC (Proof-of-Concept) based on the above requirement gathering. |
| Focus on Functional Testing rather than Performance Testing during POC Phase. |
| Primary task to evaluate - HDInsight (Hadoop Cluster). |
| This will then be followed by Each Spoke Data Technology Equivalent Azure Service mentioned in BOM. |
| Approach will be One Azure Service at a time as there might be issues related to Setup and Connectivity which needs to be addressed. If Any Data Technologies are tightly coupled, we then take the Approach of Setting the Services Together in Azure by calling out an Exception. |
| When POC of all Recommended Azure Services is complete, we move to Next Phase - Non-Prod Environment. The Setup should be seamless as we have all our learnings in POC. |
| Performance Testing will be done in the Non-Prod Environment. |
| Based on the success criteria defined for Performance Testing in Non-Prod, an equivalent like-to-like Production environment will be deployed. |
| Non-Prod and Prod will have a like-to-like configuration with the sole purpose that if there is any issue in production, it can be reproduced in UAT. |


| __CUSTOMER REQUIREMENTS/NEEDS__ | __IF REQUREMENTS HAS BEEN MET:-__ | __JUSTIFICATIONS__ 
| --------- | --------- | --------- |
| Strategic Plan to Move to Cloud. | Yes | This is explained in Section __PROPOSED APPROACH__ and __PROPOSED GUIDELINES FOR MIGRATION.__ |
| Interest in findings on the ability of Azure or a Multi-Cloud Solution to Host all their tools. | Yes | With Oracle, Informatica and Alteryx, there is a possibility of Multi-Cloud. |
| Primary Requirement - Hadoop Cluster to Azure. | Yes | HDInsight - Hadoop Cluster will be the Primary Azure Service to be Evaluated During POC. This is also mentioned in the __PROPOSED GUIDELINES FOR MIGRATION.__ |
| What is the Hadoop Equivalent Azure Service? | Yes | HDInsight (Cluster Type = Hadoop) |
| Possibility to Operate in Hybrid Infrastructure? | Yes | Considering the Pre-Requisites. |
| Develop a Phase Plan. 1st Phase - Migrate Hadoop Cluster to Azure, 2nd Phase - Migrate Rest Spoke Applications. | Yes | Addressed in __PROPOSED GUIDELINES FOR MIGRATION.__ |
| Data Ops Team is Linux and Open-Source Oriented. | Yes | All Chosen Platform is Linux. |
