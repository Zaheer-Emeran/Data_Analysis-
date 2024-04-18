# Data Analytics and Reporting
## Chapter 6: Data Analytics Tools
### Spreadsheets
Spreadsheets are productivity software packages that allow users to create documents that organize any type of data into rows and columns. Users may place any data they like in the spreadsheet and then quickly and easily perform mathematical calculations, such as finding the sum of the values in a row or searching out the minimum, maximum, mean, and median values in a dataset. Spreadsheets lack any of the constraints of a relational database.

### Programming Languages
In many cases, business analysts and data scientists need a way to be able to load, manipulate, and analyze data outside of the constraints of software written by another organization. 

#### Languages
- R
The R programming language is extremely popular among data analysts because it is focused on creating analytics applications.

- Python
Python is arguably the most popular programming language in use today. Python is about the same age as R, but the major difference between Python and R is that Python is a general-purpose programming language.
This means that it is capable of creating software to meet just about any need you might imagine. You can do everything from code a video game to perform a complex data analysis in Python. With that flexibility, however, comes some complexity. While R is quite popular because of its ease of use, writing software in Python requires some more expertise.

- Structured Query Language (SQL)
language of databases. Any time a developer, administrator, or end user interacts with a database, that interaction happens through the use of a SQL command. SQL is divided into two major sublanguages:

- The Data Definition Language (DDL) is used mainly by developers and administrators. It's used to define the structure of the database itself. It doesn't work with the data inside a database, but it sets the ground rules for the database to function.

- The Data Manipulation Language (DML) is the subset of SQL commands that are used to work with the data inside of a database. They do not change the database structure, but they add, remove, and change the data inside a database.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/cfba03ef-c775-4d3a-889b-e7a08a160512)

### Statistics Packages
These software packages go beyond the simple statistical analyses that are possible in spreadsheets and provide access to advanced statistical environments that are accessible through a graphical user interface and/or a built-in scripting language.

- Stata
- IBM SPSS
- MiniTab

### Machine Learning
- IBM SPSS Modeler
- RapidMiner


### Analytics Suites
- IBM Cognos
It uses a web-based platform to offer analysts within an organization access to their data and is backed by IBM's Watson artificial intelligence capability. The major components of Cognos include the following:
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/c09182a6-095c-4208-bd3c-f5ab3e8f0ba1)


- Microsoft Power BI
Power BI is Microsoft's analytics suite built on the company's popular SQL Server database platform. Power BI is popular among organizations that make widespread use of other Microsoft software because of its easy integration with those packages and cost-effective bundling within an organization's Microsoft enterprise license agreement.
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/097245b7-ff47-472f-a264-8def90111a19)


- Microstrategy

MicroStrategy is an analytics suite that is less well-known than similar tools from IBM and Microsoft, but it does have a well-established user base. MicroStrategy offers many of the same tools as its counterparts, making it easy for users to build dashboards and reports and apply machine learning techniques to their business data.

- Domo
Domo is a software-as-a-service (SaaS) analytics platform that allows businesses to ingest their data and apply a variety of analytic and modeling capabilities. It is not a very widely used tool, but knowledge of it is included in the objectives for the Data+ exam.

- Datorama
Salesforce Datorama is an analytics tool that focuses on a specific component of an organization's business: sales and marketing. It's not a general-purpose analytics tool but is instead focused on applying machine learning, visualization, and other analytics techniques to the sales and marketing process.

- AWS Quicksight
- AWS QuickSight is a dashboarding tool available as part of the Amazon Web Services cloud offering. This tool's power comes from the fact that it is available on a pay-as-you-go basis and its integration with the powerful data storage, data warehousing, machine learning, and artificial intelligence capabilities offered by the Amazon cloud.

- Tableau
Tableau is arguably the most popular data visualization tool available in the market today. The focus of this tool is on the easy ingestion of data from a wide variety of sources and powerful visualization capabilities that allow analysts and business leaders to quickly identify trends in their data and drill down into specific details.


- Qlik
Qlik is another popular SaaS analytics platform, offering access to cloud-based analytics capabilities. The major products offered by Qlik include the following:
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/17db3dc7-33f9-4329-8130-dd6c1305d483)

- BusinessObjects
BusinessObjects is an enterprise reporting tool from SAP that is designed to provide a comprehensive reporting and analytics environment for organizations. One of the strengths of this suite is the ability to integrate BusinessObjects reports with other applications, allowing organizations to integrate analytics into other portions of their workflow.


## Chapter 7: Data Visualization with Reports and Dashboards
### Understanding the Business Requirements
- A report is a static electronic or physical document that reflects information at a given point in time.
- a dashboard is an interactive visualization that encourages people to explore data dynamically.
- The most important thing to define when developing a report or dashboard is answering the question, “Who is the audience?”
- Once you clearly understand the audience and their needs, you can turn your attention to identifying the data sources that will satisfy the requirements of your audience.
- As you identify data sources, you'll need to consider how old the data can be while satisfying the needs of your audience.
- Once you identify who needs what data and when they need it, you can focus on how people access the report. If people access the report digitally, one way to solve the distribution challenge is with a pull approach. With a pull approach, you publish a report to a known location, like a web page, and let people know the frequency and timing of when the report updates. With this approach, people can go to the website when they want to use the report.
- With a push approach, the report is automatically sent to the appropriate people as it becomes available.
-  With a blended approach, you store the report centrally and let people know when the report has been updated and is ready for use. With the blended approach, you inform people that the report is available while maintaining central control of the report itself.


### Understanding Report Design Elements
Whenever you give people a tool, it should be approachable and easy to use. When creating a report or a dashboard, you can use existing design principles as guideposts. These design principles, known as the “five Cs” of creating visualizations, will help ensure that your reports and dashboards communicate clearly and efficiently. 
- Control
- Correctness
- Clarity
- Consistency
- Concentration

Along with these topics, there are a few visual topics which go furhter in depth:
- Report Cover Page
- Executive Sumamry
- Design Elements
- Color Schemes
- Layouts
- Fonts
- Graphics (Graphs)
- Corporate Reporting Standards
- Documentation Elements
- Version Number
- Reference Data Sources
- Frequently Asked Questions
- Appendix

### Understanding Dashboard Development Methods
#### Consumer Types
For instance: C-level Executives
-  Ensure you spend sufficient time identifying the key performance indicators (KPIs) crucial to senior leaders. A KPI is a metric that leadership agrees is crucial to achieving the organization's business objectives. As you identify what leaders want to see, you can locate where to get the relevant data.
-  You may be developing dashboards for people external to your organization. Your organization may enter into a service level agreement (SLA) that describes the level of service an external vendor or partner can expect. Violating an SLA can result in financial and reputational damages.

#### Data Source Considerations
Static data is data that refreshes at some regular interval. A typical design pattern is for operational databases to update a data warehouse every night. 

Continuous data, also known as live data, typically comes directly from an operational database that people use to perform their daily duties. The operational database provides a live data feed to the dashboard.

![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/faeb7383-7ac7-4585-bd38-8941601884fc)

#### Data Type Considerations
When creating a dashboard, you use qualitative data to create dimensions. A dimension is an attribute that you use to divide your data into categories or segments. To make sure you are representing the source data categories entirely, map the field definitions from the source data to your visualization tool. 

A measure is a numeric, quantitative value that a dashboard user is curious about. 

#### Development Process
- After you identify the data sources that will power your dashboard, you must turn your attention to developing the dashboard itself.
- Use wireframes and mock-ups to help build and refine the dashboard's design.
- A wireframe is a blueprint for an application that defines the basic design and functions of a dashboard.
- Similarly, a wireframe defines the basic structure, functionality, and content of a dashboard.
- A mock-up extends a wireframe by providing details about the visual elements of the dashboard, including fonts, colors, logos, graphics, and page styles.
- Incorporating wireframes, mock-ups, and a data story plan helps design an optimal web interface.

#### Delivery Considerations
- Accounting for how you will refresh data is one of the many things to consider. As you document their requirements and develop mock-ups, you need to determine whether people can subscribe to changes
-  If subscription capability is a requirement, you need to have a system where people can opt-in to receive a notification when the underlying data changes.
-   crucial detail you need to identify as part of the development process is how interactive the dashboard needs to be.
-   The level of interactivity needs to accommodate requirements from the data story plan.

#### Operational Considerations
- Once you have final approval, you proceed with developing the dashboard. Similar to the design stage, make sure you include frequent opportunities to gather feedback. Once dashboard development is complete, test it thoroughly to verify its functionality.
- As you build a dashboard, make sure you clearly define the access permissions. Access permissions define the data that a given person can access. When defining access permissions, do so in terms of roles instead of people.

### Expoloring Visualization Types
- Line Chart
- Pie Chart
- Bar Chart
- Stacked Chart
- Scatter Chart
- Bubble Chart
- Histogram
- Maps (Geographic, Heat and Tree Maps)
- Waterfall
- Infographic
- Word Cloud
![image](https://github.com/Zaheer-Emeran/Data_Analysis-/assets/162816701/2d3d6a9c-62a5-4809-b76a-a95296108f80)

### Comparing Report Types
#### Static and Dynamic
- Static reports pull data from various data sources to reflect data at a specific point in time.
- Dynamic reports give people real-time access to information.

#### Ad Hoc
Ad hoc reports, or one-time reports, use existing data to meet a unique need at a specific point in time.

#### Self-Service (On-Demand)
Self-service reports, or on-demand reports, allow individuals to answer questions that are unique to them at a time of their choosing.

#### Recurring Reports
Recurring reports provide summary information on a regularly scheduled basis. Typically, recurring reports get delivered to their audience immediately after creation.

For example, a company's sales leader will want monthly, quarterly, and annual sales numbers available regularly.
#### Tactical and Research

There are numerous types of recurring operational reports that organizations use to monitor organizational health and performance.

Compliance reports detail how your organization meets its compliance obligations. 

Some of these reports include:
- Financial Compliance Reporting
- Safety Compliance Reporting
- Risk Compliance Reports
  
### Tactical and Research
Tactical reports provide information to inform an organization's short-term decisions. Tactical information helps organizations accomplish initiatives like constructing a building, opening a manufacturing plant, or shipping products from one location to another.

- A research report helps an organization make strategic decisions.
- To achieve strategic objectives, an organization executes multiple tactical initiatives.
- Where a tactical report informs a decision with a finite scope and duration, research reports inform the development of an overarching strategy.
- Since the decision implications are broad, strategic reports take more time to create than tactical reports. 
- Strategic reports often combine internal data about an organization's operational performance and risks with data about external forces.


# Data Governance
## Chapter 8: Definition of Data Governance
### Subheading 1
Content

### Subheading 2
Content

### Subheading 3
Content



## Sumamry: Definition of Data Governance
### Subheading 1
Content

## Exam Prep

## Review Questions
