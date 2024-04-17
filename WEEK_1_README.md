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

### Subheading 3
Content


## Chapter 4: Data Quality
### Subheading 1
Content

### Subheading 2
Content

### Subheading 3
Content


## Chapter 5: Data Analysis and Statics
### Subheading 1
Content

### Subheading 2
Content

### Subheading 3
Content



