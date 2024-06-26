# Occupations in Data Analysis
- Data analysts and scientists,
- AI and machine learning (ML) specialists,
- Big Data specialists,
- Digital marketing and strategy specialists,
- Process automation specialists,
- Business development professionals,
- Digital transformation specialists,
- Information security analyst,
- Software and applications developers,	
- Internet of Things (IoT) specialists,

# Basics of Data
## Chapter 1: Data Analyst
### Module Focus
- Understand the role of a Data Analyst Is and the scope of it,
- Compare and Contrast different Data Types,
- Compare and Contrast common data structures and file formats,
- Learner Assumptions.

Along with this, it will be important to know as well what is the:
- Process of Data Analytics,
- Techniques of Data Analytics, and
- The role of Data Governances.

### What is Data Analytics
The main goal of Data Analytics is to transform raw data into actionable insights that guide decision making processes within an organization.

Key Responsibilities:
- Data Collection and Preparation:
- - This refers to data which has been retrieved through various means, like databases, external sources, etc, along with the various steps to clean the data to ensure accuracy, non-ambigous data, etc.

- Data Analysis:
- - This refers to the various methods and tools used in order to interpret data, such as machine learning, statistical methods, etc, which would allow the user to identify patterns and trends within the data.

- Data Visualization and Storytelling:
- - This refers to using a platform to visually display data through means of, for instance, graphcs, charts, etc, which allows for ease of explanation and articulation of the data to stakeholders.

- Decision Support:
- - This refers to providing educated recommendations for various business decisions, predicting future trends, potential implications of business decisions, etc, based on both prior experience, along with the gathered findings from analysing the data

- Collabortation and Comms
- - This refers to the Data Analyst working with the various departments within a business, such as Marketing, Finance, etc, to gain further insights into their data, along with being able to properly articulate the data to the non-technical stakeholders.

- Continous Learning Adaptation
- - This refers to continously monitoring various trends, tools and technologies to identify more efficient and effective ways in ordr to analyse data for the business.

#### Youtube Link: https://youtu.be/yZvFH7B6gKI

### Analytics Proccess
While a Data Analyst would generally sequentially follow the Analytics Process, which refers to the Data Analyst:
- Obtaining Data,
- Clenaing and Manipulating the Data,
- Analyising the Data,
- Creating Visual Represenations of said data, and
- Reporting and Communicating the results of the data,
The process is more iterative, since it can be frequently revisited whilst the tean is working with a Data Set.

### Analytics Techniques
The three types of Analytics Includes:
- Descriptive Analytics
- Predictive Analytics
- Prescriptive Analytics

# Note ---> Do more research on these 3 topics

### Machine Learning, AI and Deep Learning
#### AI
AI Includes any type of technique where an individual attempts to get a Computer System to imitate Human Behavior, thus meaning that it is possible to prompt the computer to imitate the intelligence of a human which would allow it to output a particular result, however currently it is unable to function at the level of complex reasoning which a normal human mind contains.

#### Machine Learning
Machine learning makes use of Algorithms in order to analyse datasets in order to help you make informed business decisions about the future, such as Recommending the next movie that a customer might wish to watch based on their past activity and the preferences of similar customers. It is a subset of AI

#### Deep Learning
Deep Learning is a subset of Machine Learning, since it uses complex techniques, which is called Neural Networks, in order to discover and find data in a particular way. It is more used for image, video and sound analyis.


## Data Governance
Data Governance Programs refers to when a business maintains and pursues a high level of quality regarding their data, along with the ability for the business control said data.

## Analytics Tools
Analytics Tools primarily focus on assisting and automating various tasks of a Data Analyst to reduce ambigous data, promote more efficient and healthy workflows, etc. Some of these tools includes Spreadsheet Tools like Microsoft Excel, Google Sheets, RStudio which makes use of the R Programming Language, etc.



## Chapter 2: Understanding Data
### Exploring Data Types
- A data element is an **attribute** about a **person**, **place**, or **thing** containing **data** within a **range of values**.
- Data elements also describe characteristics of activities, including orders, transactions, and events.
- A data type limits the values a data element can have. This could be, for instance, Pet Name, Animal Type, and Breed Name.

### Tablular Data
Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic. Each column represents a uniquely named field within a table, also called a variable, about a single characteristic. 

### Structured Data Types
Structured data is tabular in nature and organized into rows and columns. Structured data is what typically comes to mind when looking at a spreadsheet. With clearly defined column headings, spreadsheets are easy to work with and understand. In a spreadsheet, cells are where columns and rows intersect.

Alphanumeric is the most widely used data type for storing character-based data. As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters. The alphanumeric data type is ideal for storing product stock-keeping units (SKUs).

There are times when it is necessary to impose even stricter limits on character-related data to exclude numbers. Excluding numbers can be achieved using the text data type. Closely related to the alphanumeric data type, it is even more stringent. It is helpful to think of text as a subset of alphanumeric, only allowing the storage of alphabetic characters. It improves the overall data quality.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/e0bdd6ab-c382-4fb3-afdc-bf034b53374b)

All of the data types shown in Table 2.2 support alphanumeric data. Where they differ is in how much data they can handle. Before defining a column as alphanumeric, you need to determine how long your longest-possible text value will be.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/662cb82a-23ae-4e54-a55e-a3a67cd13c54)

- Numeric: Numbers Exclusively
- Whole Numbers: Integers
- Rational Numbers: Includes Decimal Points

### Strong and Weak Typing
- Data types define values placed in columns. Strong typing is when technology rigidly enforces data types.
- Weak typing loosely enforces data types. Spreadsheets use weak typing to help make it easier for people to accomplish their work.

### Untructured Data Types
Unstructured data is any type of data that does not fit neatly into the tabular model. 
Instances:
- Binary
> Binary data types are one of the most common data types for storing unstructured data. It supports any type of digital file you may have, from Microsoft Excel spreadsheets to digital photographs.

- Audio
> The impact of capturing, storing, and analyzing audio data has led to the development of avalanche detection systems. These systems listen for and detect the acoustic characteristics of an avalanche. <br>
> Audio can be stored in its raw form, which consumes the most storage space. Alternatively, it can be encoded with a compression algorithm to reduce the amount of space required. <br>
> Regardless of if it is in raw or compressed form, storing audio requires a data type designed to handle raw binary data.

- Images
>  it is easy for a human to identify the contents of the photograph. However, it is a binary file to a computer, ultimately stored as a series of ones and zeros.
>  Applying artificial intelligence algorithms for image processing over a set of digital photos allows people to look for the objects they contain.

### Categories of Data
- Quantitative vs Qualitative
> Quantitative Data refers to Numerical data, such as Age, Height and Weight
> Qualitative Data refers to Descriptive Data, such text describing characteristics of a Data Set

- Discrete vs Continuous Data
> A helpful way to think about discrete data is that it represents measurements that can't be subdivided.
> You may intuitively think of discrete data as using whole numbers, but that doesn't have to be the case.
> Can also be thought about when finding things to count.
> For example, if a fundraising organization sells chickens in half-chicken increments, you can buy 1.5 chickens. However, you can't buy .25 chickens.

> Continuous Data can best be described as data which consistently changes, and also commonly makes use of decimal numbers. For instance, Height, Weightm etc.
> Qualitative Data Is descrete.
> Quantitative data can be either Discrete or Continuous.

- Categorical Data
> Text data with a known, finite number of categories is categorical.
> When considering an individual data element, it is possible to determine whether or not it is categorical.

- Dimensional Data
> Dimensional modeling is an approach to arranging data to facilitate analysis.
> Dimensional modeling organizes data into fact tables and dimension tables.
> Fact tables store measurement data that is of interest to a business.
> Dimensional data contains groupings of individual attributes about a given subject.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/a8e76c71-169e-451d-9f66-37363e8c4ea5)


### Common Data Structures
Analysts need to be able to perform their roles as efficiently as possible. It is common to use multiple tools to analyze data. Improved integration and interoperability between tools make it easier for analysts to be productive. As a result, several concepts have become standardized.

#### Structured Data
Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows. <br>
However, structured data does not translate directly to data quality. Data Quality refers to Data which is unambigous, properly correct, etc.<br>
It is a best practice to specify a key that uniquely identifies all values for a given row.


#### Semi-Structured Data
Semi-structured data is data that has structure and that is not tabular. Email is a well-known example of semi-structured data. Every email message has structural components, including recipient, sender, subject, date, and time. However, the body of an email is unstructured text, while attachments could be anything type of file.

#### Unstructured Data
Unstructured data is qualitative, describing the characteristics of an event or an object. Images, phrases, audio or video recordings, and descriptive text are all examples of unstructured data. There is very little that is common about different kinds of unstructured data.

A Forbes study shows that over 90 percent of businesses need to manage and derive value from unstructured data.

Machine data is a common source of unstructured data. Machine data has various sources, including Internet of Things devices, smartphones, tablets, personal computers, and servers. 

As machines operate, they create digital footprints of their activity. This data is unstructured and can identify machine-to-machine interaction.

A wide variety of technologies has emerged to facilitate the storage of unstructured data. Operationally, these technologies are similar to how a key in a tabular dataset identifies its associated values. With unstructured data, the key is a unique identifier, whereas the value is the unstructured data itself.


### Common File Formats
#### Text Files
- Consist of plain text and are limited in scope to alphanumeric data.
- Commonly referred to as a flat file,
- Is widly adopted since they can be opened without requiring a specific software and can be opened using various Operating Systems.
- A unique character known as a delimiter facilitates transmitting structured data via a text file.
- The delimiter is the character that separates individual fields. A delimiter can be any character. This can include characters like commans, tabs, etc.
- When a file is comma-delimited, it is known as a comma-separated values (CSV) file.
- Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.
- CSV can either be structured, semi-structured or unstructured.


#### Fixed-Width Files
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/13f183a9-9340-4709-9d5e-05cddefa5e82)


#### JavaScript Object Notation (JSON)
- It is Designed to add structure to a text file without incurring significant overhead.
- It is Easily readable by people and easily parsed by modern programming languages like Python,R, etc.
- Think of Dictionaries in Python

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/a0599dc9-49ff-40d0-8a73-59ff3913c2c3)

#### Extensible Markup Language (XML)
- Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file.
- Incurs more overhead because it makes extensive use of tags.
-  Tags describe a data element and enclose each value for each data element. While these tags help readability, they add a significant amount of overhead.
-  Compared with the JSON in Figure 2.29, XML results in a file roughly double in size.
-  In small Files its insignificant, but more profound when dealing with Gigabytes and TB.

#### HypterText Markup Language (HTML)
- HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser.
- It is the foundation for how people interact with the World Wide Web.



## Chapter 3: Databases and Data Acquisition
Chapter Outcome:
- Data Concepts and Environments
- Identify basic concepts of data schemas and dimensions
- Understanding the domain of Data Mining
- Explain data acquisition concepts
- Explain common techniques for data manipulation and query optimization

# Note: 
- Add fact and dimensional tables.
- Describe the characteristics of OLTP and OLAP systems.
- Describe approaches for handling dimensionality.
- Understand integration and how to populate a data warehouse.
- Differentiate between data collection methods.
- Describe how to manipulate data and optimize queries. 

### Exploring Databases
One of the oldest and most mature databases is the relational database. Relational databases excel at storing and processing structured data. 
The power of the relational model is that it also allows us to describe how entities connect or relate, to each other.


#### ERD Instance
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/fdf388e5-959c-4d46-819c-8f4be38d3db7)
The entity relationship diagram (ERD) is a visual artifact of the data modeling process. It shows the connection between related entities. 
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/4029d938-7603-47dc-86c2-4fe76120ee64)
Cardinality refers to the relationship between two entities, showing how many instances of one entity relate to instances in another entity. You specify cardinality in an ERD with various line endings. The first component of the terminator indicates whether the relationship between two entities is optional or required. The second component indicates whether an entity instance in the first table is associated with a single entity instance in the related table or if an association can exist with multiple entity instances. 

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/3a02893b-df5b-4709-80f1-1f36fdc2aede)
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/36e18577-0028-439f-8742-9f675314e378)
A binary relationship connects two entities, as seen in Figure 3.2. A ternary relationship connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price. <br>
Database designers would continue to add entities and relationships to the diagram until it meets all of the business needs of a business.<br>
ERDs are particularly useful when formulating how to retrieve information from the database that is spread across multiple tables because the diagrams allow you to visualize the connections between entities.<br>

### Relational Database
Relational databases are software, or pieces of software, that let you make an operational system out of an ERD. <br>
When creating a database table, the ordering of columns does not matter because you can specify the column order when retrieving data from a table.
<br> When an attribute becomes a column, you assign it a data type.
<br> Completing all of this work results in a diagram known as a schema.
<br> You can think of a schema as an ERD with the additional details needed to create a database.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/e95380aa-4301-4829-891e-5ffa3bbd2b44)

An associative table is both a table and a relationship. An associative table lets you identify the relationship between a specific animal and a particular person with a minimum amount of data duplication. 

A primary key is one or more attributes that uniquely identify a specific row in a table. It is best to use a synthetic primary key, which is simply an attribute whose only purpose is to contain unique values for each row in the table. 
Note that within a given table, the actual sequencing of the rows does not matter.

 A foreign key is one or more columns in one table that points to corresponding columns in a related table. Frequently, a foreign key references another table's primary key.


![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/5e70c11b-de88-4c57-a93b-85a4142e72d4)

Your query needs to perform a database join to retrieve the data to substitute in the email reminder. A join uses data values from one table to retrieve associated data in another table, typically using a foreign key.

#### Platforms / Database Types:
MySQL, MariaDB, and PostgreSQL. Amazon Web Services (AWS) developed Aurora, PostgreSQL. Aurora 

#### Non-Relational Databases:
- Key-Value
A key-value database is one of the simplest ways of storing data. Data is stored as a collection of keys and their corresponding values. A key must be globally unique across the entire database. The use of keys differs from a relational database, where a given key identifies an individual row in a specific table.
<br> A key can be a sequence of numbers, alphanumeric strings, or some other combination of values.
<br> It also can scale to accommodate many simultaneous requests without impacting performance. 
<br> One reason for choosing a key-value database is when you have lots of data and can search by a key's value
- Document
  JSON files
  ![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/9f8731e1-3023-46dd-9346-1fb75171ca00)


- Column-Family
Get brief description and instance of this

- Graph
Get brief description and instance of this

### Databases Use Cases
#### Online Transactional Processing (OLTP)
They handle daily online transactions
<br>While the number of transactions a system handles on a given day can be very high, individual transactions process small amounts of data.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/b86ef78e-2906-4895-927f-5a4cd8ffb2ff)


### Normalization
First normal form (1NF) is when every row in a table is unique and every column contains a unique value.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/a9965f92-2992-4c1a-a74c-2ed758636c93)

Second normal form (2NF) starts where 1NF leaves off. In addition to each row being unique, 2NF applies an additional rule stating that all nonprimary key values must depend on the entire primary key.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/dcac0c41-4518-4463-8ab9-e38dd8ef694f)

Third normal form (3NF) builds upon 2NF by adding a rule stating all columns must depend on only the primary key.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/94532dfa-b776-4362-a936-d99260f0652e)

While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different. OLTP databases need to balance transactional read and write performance, resulting in a highly normalized design. Typically, OLTP databases are in 3NF.


**The greater the number of joins, the more complex the query.**
**The more complex the query, the longer it takes to retrieve results.**

#### Online Analytical Processing (OLAP)
OLAP systems focus on the ability of organizations to analyze data.

Instead of having data distributed across multiple tables, denormalization results in wider tables than those found in an OLTP database. It is more efficient for analytical queries to read large amounts of data for a single table instead of incurring the cost of joining multiple tables together.

databases that power OLAP systems have a denormalized design


#### Schema Concepts (Large Data Storage Types Zaheer)
The design of a database schema depends on the purpose it serves. 

Transactional systems require highly normalized databases, whereas a denormalized design is more appropriate for analytical systems.
Transactional data may come from systems that power the human resources, sales, etc

A data warehouse is a database that aggregates data from many transactional systems for analytical purposes. A data warehouse facilitates analytics across the entire company.

A data mart is a subset of a data warehouse. Data warehouses serve the entire organization, whereas data marts focus on the needs of a particular department within the organization. 

A data lake stores raw data in its native format instead of conforming to a relational database structure. Using a data lake is more complex than a data warehouse or data mart, as it requires additional knowledge about the raw data to make it analytically useful.

For data warehouses and data marts, several design patterns exist for modeling data. It is crucial to realize that the structure of a database schema impacts analytical efficiency, particularly as the volume of data grows. 

. Life-cycle considerations include where data comes from, how frequently it changes, and how long it needs to persist.

(Database, Data Warehouse, Data Lake: https://youtu.be/-bSkREem8dM )

##### Star Schema
The star schema design to facilitate analytical processing gets its name from what the schema looks like when looking at its entity relationship diagram.  Star schemas are denormalized to improve read performance over large datasets. At the centre of the star is a fact table

 the dimension tables connect directly to the fact table.

Data marts frequently use a star-schema approach cause Data marts are comparatively less complicated, because they represent a single data subject area
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/a320c7d3-6061-4545-830c-084773576d51)

##### Snowflakse Schema
Another design pattern for data warehousing is the snowflake schema. As its name implies, the schema diagram looks like a snowflake. Snowflake and star schemas are conceptually similar in that they both have a central fact table surrounded by dimensions. Where the approaches differ is in the handling of dimensions. With a snowflake schema, you may need more than one join to get the data you are looking for.

With a snowflake, dimensions have subcategories, which gives the snowflake design its shape. A snowflake schema is less denormalized than the star schema. a snowflake schema requires less storage space than a star schema.

Data warehouses often use snowflake schemas,

### Dimensionality 
Dimensionality refers to the number of attributes a table has. The greater the number of attributes, the higher the dimensionality. One dimension you will frequently encounter is time. For example, to understand historical profitability, you need to keep track of pricing at the product level over time. One way to accomplish this is to add a start and end date to each product's price.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/18323f2f-372f-4150-ac68-300c00297793)

### Handling Dimensionality
There are multiple ways to design dimensions, like the start and end date approach. 

Another method extends the snowflake approach to modelling dimensions. You have a product dimension for the current price and a product history table for maintaining price history. One advantage of this approach is that it is easy to retrieve the current price while maintaining access to historical information.

Another approach is to use an indicator flag for the current price. . The indicator flag method keeps all pricing data in a single place. It also simplifies the query structure to get the current price. Instead of doing date math, you look for the price where the Current flag equals “Y.”

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/7c97cfec-5ea3-4a99-a87b-f597625bab2d)

### Data Acquisition Concepts
To perform analytics, you need data. Data can come from internal systems you operate, or you can obtain it from third-party sources.

#### Integration
Data from transactional systems flow into data warehouses and data marts for analysis.

One approach is known as extract, transform, and load (ETL).
- Extract: The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible.
- Transform: goal is to reformat the data from its transactional structure to the data warehouse's analytical design.
- Load: load phase is to ensure data gets into the analytical system as quickly as possible.

Extract, load, and transform (ELT) is a variant of ETL. With ELT, data is extracted from a source database and loaded directly into the data warehouse. Once the extract and load phases are complete, the transformation phase gets underway. One key difference between ETL and ELT is the technical component performing the transformation. With ETL, the data transformation takes place external to a relational database, using a programming language like Python. ELT uses SQL and the power of a relational database to reformat the data.

ELT has an advantage in the speed with which data moves from the operational to the analytical database. 

#### ETL Vendors
Whether you choose ETL or ELT for loading your data warehouse, you don't have to write transformations by hand. Many products support both ETL and ELT. 

An initial load occurs the first time data is put into a data warehouse. After that initial load, each additional load is a delta load, also known as an incremental load. A delta load only moves changes between systems.

The initial load happens right before the data warehouse becomes available for use. 
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/c1c8465f-1bc5-43a9-bfe4-cc763ade50ff)

The frequency with which delta loads happen depends on business requirements. Depending on how fresh the data needs to be, delta loads can happen at any interval. Hourly, daily, and weekly refreshes are typical.

#### Data Collection Methods
- Application Programming Interfaces (APIs)
- Web Services
- Web Scraping
- Human-In-The-Loop
- Surveys
- Survey Tools
- Observation
- Sampling

### Working with Data
Determining an appropriate database structure, identifying data sources, and loading a database takes a considerable amount of effort. To turn a database design into an operational database ready to accept data, you use the Data Definition Language (DDL) components of SQL. DDL lets you create, modify, and delete tables and other associated database objects.

To generate insights, a productive analyst must be comfortable using the Data Manipulation Language (DML) capabilities of SQL to insert, modify, and retrieve information from databases. While DDL manages the structure of a database, DML manages the data in the database.

#### Data Manipulation - For possible actions
- Create New Data
- Read Existing Data
- Update Exisiting Data
- Delete Existing Data

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/4a5c6470-af3a-4db3-8536-ba818d79fb1c)

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/3157607c-7c64-45b3-96a9-537cadc1e963)

The keywords in SQL are case-insensitive.

#### Filtering
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/e317be03-6d4e-4721-bb77-dffd8c0d95fd)

#### Filtering and Logical Operators
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/da09496f-8223-4986-aa93-f492a7455396)

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/35ac2cca-62cb-4a97-a3c9-39618a8e1343)

#### Sorting
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/b29f2b38-b438-47e5-8f71-3006ae0ac7c6)

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/8cc1dbae-971d-4207-9ab3-45b2a920bb25)

#### Logical Functions
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/056283d8-3909-4e4d-b0e9-226131279eea)

IFF is just one example of a logical function. When using logical functions, you need to balance their convenience with the knowledge that you are replacing data from the database with the function's coded values.

#### Aggregate Functions
Summarized data helps answer questions that executives have, and aggregate functions are an easy way to summarize data. Aggregate functions summarize a query's data and return a single value. 
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/00772c3e-c8a4-444e-a891-c0e023885a0c)

#### System Functions
Each database platform offers functions that expose data about the database itself. One of the most frequently used system functions returns the current date. The current date is a component of transactional records and enables time-based analysis in the future. The current date is also necessary for a system that uses an effective date approach.

#### Query Optimization
- Parametrization
- Indexing
- Data Subsets and Temporary Tables
- Execution Plam
  


## Chapter 4: Data Quality
#Note: Figure out what the actual fluff is the difference between the adding parts in this chap

## Topics to gather info on
- Aggregation
- Transposition
- Normalization
- Min-Max Normalization
- Parsing/String Manipulation

### Duplicate Data
Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system.
<br> Humans are primarily responsible for creating duplicate data.  The best way to resolve duplicate data is to prevent its creation in the first place.
<br> Having multiple data sources for the same data elements is also a source of duplicate data.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/4b1a7c2a-cf6e-4228-8d56-cb6b7951c46f)
To resolve duplicate data issues, the company has a duplicate resolution process. 

### Redundant Data
While duplicate data typically comes from accidental data entry, redundant data happens when the same data elements exist in multiple places within a system. Frequently, data redundancy is a function of integrating multiple systems.
<br> When integrating multiple data sources, dealing with redundant data is a persistent challenge.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/0939dd0a-84b9-43bc-b55d-70cafa4d00aa)

There are several options for resolving redundant data. One approach synchronizes changes to shared data elements between the Accounting and Sales systems. However, technical or political realities can make synchronizing source systems unfeasible.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/f616d135-99b1-4021-ac26-43f88008de7d)
Another root cause of data redundancy is an inappropriate database design

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/0b873bf7-b079-4e44-92e3-5abb68368533)
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/ee5f119f-ce0c-40cd-95c7-2944b98f5d9b)
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/7dfc081f-e69b-4b18-92c6-892ab43fc9fb)
The best way to resolve a data redundancy issue is by restructuring the tables.

### Missing Values
<br> Missing values / null values occur when you expect an attribute to contain data but nothing is there. 
<br> A null value is the absence of a value. A null is not a space, blank, or other character.
<br> There are situations when allowing nulls makes sense. Suppose you are storing data about people and have a column for Middle Initial. Since not everyone has a middle initial, the Middle Initial column should be optional. 

However, if you read a CSV file using the Python or R programming language, the null value for January 4th poses a problem. Trying to calculate the average, which was successful in SQL, results in an error in Python and R as the equivalent functions in those languages do not handle null values.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/0782c8af-6336-435f-bdf4-84eae1ef6921)

### Invalid Data
Invalid data are values outside the valid range for a given attribute. 

<br> An invalid value violates a business rule instead of having an incorrect data type
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/4cff3269-d645-4f69-8c4d-5a1ee3206705)
Text data is more complex. One thing that leads to invalid character data is an absence of referential integrity within a database.
<br> Text data is more complex. One thing that leads to invalid character data is an absence of referential integrity within a database. I
<br> If two tables have a relationship but no foreign keys, the conditions for invalid character data exist.

### Nonparamettric Data
Nonparametric data is data collected from categorical variables, Sometimes the categories indicate differentiation, and sometimes they have a rank order associated with them. . In this latter case, the rank order of the values is of significance, not the individual values themselves.

### Data Outliers
With outliers, you need to understand why they exist and whether they are valid in the context of your analysis. You know what outliers are Z.

### Specification Mismatch
A specification describes the target value for a component. A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values.

### Data Type Validation
Data type validation ensures that values in a dataset have a consistent data type.

## Data Manipulation Techniques
### Recording Data
Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis. Recoding groups data into multiple categories, creating a categorical variable.

categorical variable is either nominal or ordinal. 
- Nominal variables are any variable with two or more categories where there is no natural order of the categories, like hair color or eye color.
- Ordinal variables are categories with an inherent rank. For example, T-shirt size is an example of an ordinal variable, as sizes come in small, medium, large, and extra-large. 


### Derived Variables
A derived variable is a new variable resulting from a calculation on an existing variable.However, derived variables don't have to be categorical.
For instance, calculating age from when the person was born.

### Data Merge
A data merge uses a common variable to combine multiple datasets with different structures into a single dataset. Merging data improves data quality by adding new variables to your existing data. ETL processes commonly append data while transforming data for use in analytical environments.

Consider the systems that support a university. When a person applies, the university stores data, including admissions essays, high school transcripts, letters of recommendation, and standardized test scores. Upon becoming a student, a person generates academic data, including course enrollment and grades. Some students have work-study jobs, which create payroll data, including hours worked and hourly rate.

Merging tables and columns together into another table
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/631453c9-decd-4ffe-9654-720c6c83c9c3)


### Data Blending
Data blending combines multiple sources of data into a single dataset at the reporting layer. While data blending is conceptually similar to the extract, transform, and load process in Chapter 3, there is a crucial difference. Recall that ETL processes operate on a schedule, copying data from source systems into analytics environments. Business requirements drive the scheduling, such as near real-time, hourly, daily, weekly, monthly, or annually. Typically, an organization's IT department designs, builds, operates, and maintains ETL processes.

Data blending differs from ETL in that it allows an analyst to combine datasets in an ad hoc manner without saving the blended dataset in a relational database. Instead of the blended dataset persisting over time, it exists only at the reporting layer, not in the source databases.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/62f7f2f6-4ef5-445a-bd1b-ee5bcb762ca3)
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/687cc4a0-0e8d-492b-9161-a1234f542426)

### Concatenation
Concatenation is the merging of separate variables into a single variable. 

Concatenation is a highly effective technique when dealing with a source system that stores components of a single variable in multiple columns. The need for concatenation frequently occurs when dealing with date and time data. 
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/ea58ec1e-bbb5-4d25-a49d-783d877c4e5d)

### Data Append
A data append combines multiple data sources with the same structure, resulting in a new dataset containing all the rows from the original datasets. 
When appending data, you save the result as a new dataset for ongoing analysis.

### Imputation
Imputation is a technique for dealing with missing values by replacing them with substitutes. When merging multiple data sources, you may end up with a dataset with many nulls in a given column. If you are collecting sensor data, it is possible to have missing values due to collection or transmission issues.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/afc36cda-0aeb-4011-8e7a-119ec1c225b7)

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/248276e0-24d2-4410-a3a6-62f6611031a3)

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/bd9ce437-0929-4846-abb0-365d0cc99581)

### Reduction
When dealing with big data, it is frequently unfeasible and inefficient to manipulate the entire dataset during analysis. Reduction is the process of shrinking an extensive dataset without negatively impacting its analytical value. There are a variety of reduction techniques from which you can choose. Selecting a method depends on the type of data you have and what you are trying to analyze. Dimensionality reduction and numerosity reduction are two techniques for data reduction.

### Dimensionality Reduction
One reduction technique is dimensionality reduction, which removes attributes from a dataset. Removing attributes reduces the dataset's overall size. 

### Numerosity Reduction
Another technique is numerosity reduction, which reduces the overall volume of data.
<br> One way to reduce the volume of quantitative data is by creating a histogram.
![Uploading image.png…]()




### Managing Data Quality
#### Circumstances for Quality Checking
- Data Acquisition
- Data Transformation and Conversion
- Data Manipulation
- Final Product Preparation

### Automated Validation
Many data sources feed analytics environments. While some of these data sources are other computer systems, others depend directly on people. Whenever people interact with systems, it's possible to introduce data-related errors. Whether source data is machine- or human-generated, one way to prevent data entry mistakes from adversely impacting data quality is to automate data validation checks.

### Data Quality Dimensions
- Data Accuracy
- Data Completeness
- Data Consistency
- Data Timeliness
- Data Uniqueness
- Data Validity

### Methods to Validate Quality
#### Reasonable Expectations
One approach is to determine whether or not the data in your analytics environment meets your reasonable expectations.
It is worth spending time reflecting on what measures are reasonable for your environment. After defining how you want to measure your expectations, automate the reasonable expectation check by creating exception reports as part of your ETL processes.


#### Data Profiling
Another approach to improving quality is to profile your data. Data profiling uses statistical measures to check for data discrepancies, including values that are missing, that occur either infrequently or too frequently, or that should be eliminated. Profiling can also identify irregular patterns within your data.

Uses statistical methods to check for discrepencies in data.


#### Data Audits
Another method to keep in mind is auditing your data. Data audits look at your data and help you understand whether or not you have the data you need to operate your business. Data audits use data profiling techniques and can help identify data integrity and security issues.


#### Sampling
Another method for validating data quality is by examining a sample of your data. Sampling is a statistical technique in which you use a subset of your data to inform conclusions about your overall data.

#### Cross-Validation
Analysts frequently use existing data to generate predictive models using a variety of statistical methods. Cross-validation is a statistical technique that evaluates how well predictive models perform. Cross-validation works by dividing data into two subsets. The first subset is the training set, and the second is the testing, or validation, set.












## Chapter 5: Data Analysis and Statics
### Subheading 1
Content

### Subheading 2
Content

### Subheading 3
Content



