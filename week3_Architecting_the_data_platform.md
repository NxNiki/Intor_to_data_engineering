# Data Platforms, Data Stores, and Security

The architecture of a data platform can be seen as a set of layers, or functional components, each one performing a set of specific tasks. These layers include:

- Data Ingestion or Data Collection Layer, responsible for bringing data from source systems into the data platform.

- Data Storage and Integration Layer, responsible for storing and merging extracted data.

- Data Processing Layer, responsible for validating, transforming, and applying business rules to data.

- Analysis and User Interface Layer, responsible for delivering processed data to data consumers.

Data Pipeline Layer, responsible for implementing and maintaining a continuously flowing data pipeline.

A well-designed data repository is essential for building a system that is scalable and capable of performing during high workloads. 

The choice or design of a data store is influenced by the type and volume of data that needs to be stored, the intended use of data, and storage considerations. 
The privacy, security, and governance needs of your organization also influence this choice.

The CIA, or Confidentiality, Integrity, and Availability triad are three key components of an effective strategy for information security. 
The CIA triad is applicable to all facets of security, be it infrastructure, network, application, or data security.


# Data collection and data wrangling:

Data Wrangling/Data munging
- Data Exploration
- Transformation
- Validation
- Making data available for credible and meaningful analysis

Data Normalization:
- Cleaning unused data
- Reducing redundancy
- reducing inconsistency

Denormalization: 
Combining data from multiple tables into a single table for faster querying of data for reports and analysis

Cleaning:
- Detecting issues and errors
- validation against rules and constraints
- profiling data to inspect source data
- visualization (outliers)

Depending on where the data must be sourced from, several methods and tools are available for gathering data. 
These include query languages for extracting data from databases, APIs, Web Scraping, Data Streams, RSS Feeds, and Data Exchanges. 

Once the data you need has been gathered and imported, your next step is to make it analytics-ready. This is where the process of Data Wrangling, or Data Munging, comes in. 

Data Wrangling involves a whole range of transformations and cleansing activities performed on the data. Transformation of raw data includes the tasks you undertake to: 

- Structurally manipulate and combine data using Joins and Unions. 

- Normalize data, that is, clean the database of unused and redundant data.

- Denormalize data, that is, combine data from multiple tables into a single table so that it can be queried faster.

Cleansing activities include: 

- Profiling data to uncover anomalies and quality issues.

- Visualizing data using statistical methods in order to spot outliers. 

- Fixing issues such as missing values, duplicate data, irrelevant data, inconsistent formats, syntax errors, and outliers. 

A variety of software and tools are available for the data-wrangling process. Some of the popularly used ones include Excel Power Query, 
Spreadsheets, OpenRefine, Google DataPrep, Watson Studio Refinery, Trifacta Wrangler, Python, and R, each with their own set of features, strengths, limitations, and applications.
