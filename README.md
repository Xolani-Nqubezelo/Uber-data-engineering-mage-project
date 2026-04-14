# Building Data Pipelines for Modern Data Engineering | End to End Data Engineering Project (Medallion Architecture)
uber data engineering pipeline using mage AI and BigQuery




# Tools and Technologies
We’ll explore how to set up an end-to-end data engineering project using a suite of Azure services, integrating dbt for efficient data transformations. Here’s a detailed breakdown of each component and its role in our project:

Cloud Provider — Azure: Azure will be our foundational cloud platform, providing a robust and scalable environment for all our data operations. Azure’s wide array of services and tools offers a cohesive ecosystem, ensuring seamless integration and management of our data pipeline components.

Database — Azure SQL: We will utilize Azure SQL, the cloud-based version of Microsoft SQL Server, as our primary database system. This choice brings the reliability and familiarity of SQL Server into a flexible, cloud-native environment. For demonstration purposes, we’ll employ the AdventureWorks LT sample database, which provides a rich dataset for various transformation scenarios.

Azure Data Lake: As a central repository for our large-scale data storage and analytics, Azure Data Lake will play a crucial role. It offers a secure, scalable, and cost-effective storage solution, capable of handling massive volumes of structured and unstructured data. This will be instrumental in storing raw data, intermediate results, and final outputs in various formats.

Azure Key Vault: Security and confidentiality are paramount in data engineering projects. Azure Key Vault will be used to securely store and manage sensitive information such as keys, secrets, and certificates. This ensures that our data pipeline maintains high security standards, protecting access to databases, data lakes, and other critical resources.

Azure Databricks: For powerful data processing and analytics, we’ll leverage Azure Databricks. This Apache Spark-based analytics service provides an optimized environment for big data processing and machine learning. It’s instrumental for handling complex data transformation and analysis tasks, offering both performance and ease of use.

Azure Data Factory: As our primary data integration tool, Azure Data Factory will orchestrate and automate the movement and transformation of data. It’s a key component for building data pipelines, allowing us to efficiently manage data flows between various Azure services and external data sources.

dbt (Data Build Tool): dbt will be a key player in our data transformation strategy. It allows for the creation and management of data transformation workflows using familiar SQL syntax. dbt fits seamlessly into our architecture, particularly in the transformation phase, where it can be used to model data, run tests, and generate documentation. This makes it easier for teams, especially those proficient in SQL, to contribute to the data transformation process, ensuring that business logic is consistently applied and documented. Integrating dbt with Azure SQL and Azure Data Lake enhances our ability to manage and transform data efficiently, while maintaining clarity and consistency across the entire pipeline.

# Setting up the stage on Azure Cloud
Getting started with Azure is pretty easy, as they offer free 12 months access to over 55+ services. You can get started by creating a free account. Once that is created, you only need to sign in with your credentials and you will have access to the landing page.

# Setting up the resource groups
Setting up resource groups in Azure is a fundamental step in organizing and managing your Azure resources efficiently. A resource group in Azure is a container that holds related resources for an Azure solution. Once logged in, find the “Resource groups” option in the navigation pane on the left-hand side or list of services. If it’s not visible, use the search bar at the top to search for “Resource groups”, fill in the required details and once the deployment is complete, you can navigate to the resource group and start adding resources like Azure SQL databases, Azure Data Lake storage accounts, etc.
<img width="1902" height="878" alt="image" src="https://github.com/user-attachments/assets/62085022-1ffc-41e5-b4b4-2b835db6ad9e" />

