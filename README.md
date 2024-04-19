# Data-Analytics-Week-2
The analytics process.
Data is acquired, it is then cleaned and manipulated. Analysed thoroughly then visualisation is implemented. Reports are done based on data analysed.

Descriptive analytics is like taking a snapshot of what's happening in your data right now. It's the first step in data analysis, where you try to understand and summarize the main characteristics of your data. Imagine you have a bunch of numbers representing sales from different stores over the past year. Descriptive analytics would help you answer questions like: What was the average sales per store? What was the total sales? What was the highest and lowest sales recorded? It's all about organizing, summarizing, and presenting your data in a way that's easy to understand, so you can get a clear picture of what's going on without digging too deep into complex analysis techniques.

Predictive analytics is like looking into a crystal ball to forecast what might happen in the future based on patterns and trends in your data. Let's say you have data on past sales,
 customer demographics, and advertising spending. Predictive analytics would use this information to make educated guesses about future sales, customer behavior, or advertising effectiveness. It's like using the past to predict what's likely to happen next. This can be super helpful for businesses because it allows them to anticipate trends, make smarter decisions, and even plan ahead more effectively.

Prescriptive analytics is like having a wise advisor who not only tells you what's likely to happen in the future but also suggests the best actions to take. It goes beyond just predicting outcomes; it recommends specific steps to achieve desired results. Imagine you run a delivery service and want to minimize delivery times. Prescriptive analytics would not only forecast traffic patterns but also suggest the most efficient routes for your drivers to take. It's all about using data to not only understand what might happen but also to guide you on what you should do about it. This can help businesses make more informed decisions and optimize their strategies for better outcomes.

Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic. Each column represents a uniquely named field within a table, also called a variable, about a single characteristic.

Unstructured data is any type of data that does not fit neatly into the tabular model. 
Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses eg. Binary

Quantitative data consists of numeric values. Data elements whose values come from counting or measuring are quantitative.
Qualitative data consists of frequent text values. Data elements whose values describe characteristics, traits, and attitudes are all qualitative.
    
Structured data fits well into CSV files, a popular format for exchanging data via flat files.
A complex data structure, you need capabilities beyond what a flat-file provides. Formatting the data as JSON or XML is a viable alternative.
Relational Databases:

Organize data into tables with rows and columns.
Use structured query language (SQL) for data manipulation and retrieval.
Ensure data integrity through ACID (Atomicity, Consistency, Isolation, Durability) properties.
Relationships between data entities are defined through keys.
Schema is predefined and typically follows a fixed structure.
Suitable for applications with well-defined data models and relationships, such as transactional systems.
Non-relational Databases (NoSQL):

Data is stored in various formats, such as key-value pairs, documents, graphs, or wide-column stores.
Lack a fixed schema, providing flexibility to handle unstructured or semi-structured data.
Designed for scalability and high performance, especially in distributed environments.
Support for eventual consistency rather than strong consistency.
Can handle large volumes of data with ease, making them suitable for big data applications.
Ideal for scenarios where data models may evolve rapidly or where high scalability and flexibility are required, such as web applications, real-time analytics, and IoT (Internet of Things) platforms.

Database Use Cases
The database's structure needs to match its intended purpose. Business requirements impact the design of individual tables and how they are interconnected. Transactional and reporting systems need different implementation approaches to serve the people who use them efficiently. Databases tend to support two major categories of data processing: Online Transactional Processing (OLTP) and Online Analytical Processing (OLAP).
Online Transactional Processing
OLTP systems handle the transactions we encounter every day. Example transactions include booking a flight reservation, ordering something online, or executing a stock trade. While the number of transactions a system handles on a given day can be very high, individual transactions process small amounts of data. OLTP systems balance the ability to write and read data efficiently.
Normalization.
Normalization is a process for structuring a database in a way that minimizes duplication of data.

Entity Relationship Diagram - is a visual artifact of the data modeling process. It shows the the connection between the related entities.
A unary relationship - is when an entity has a connection with itself.
A binary relationship connects two entities.
A ternary relationship connects three entities.

Schema Concepts
A data warehouse is a database that aggregates data from many transactional systems for analytical purposes.
A data mart is a subset of a data warehouse. Data warehouses serve the entire organization, whereas data marts focus on the needs of a particular department within the organization.
A data lake stores raw data in its native format instead of conforming to a relational database structure. Using a data lake is more complex than a data warehouse or data mart, as it requires additional knowledge about the raw data to make it analytically useful.

Dimensionality

Dimensionality refers to the number of attributes a table has. The greater the number of attributes, the higher the dimensionality.
There are multiple ways to design dimensions. Table 3.5 illustrates the start and end date approach.

Extract:  In the first phase, you extract data from the source system and place it in a staging area. The goal of the extract phase is to move data from a relational database into a flat file as quickly as possible.
Transform:  The second phase transforms the data. The goal is to reformat the data from its transactional structure to the data warehouse's analytical design.
Load:  The purpose of the load phase is to ensure data gets into the analytical system as quickly as possible.

Data Acquisition Methods
1. An application programming interface (API) is a structured method for computer systems to exchange information.
2. Web Services - A web service is an API you can call via Hypertext Transfer Protocol (HTTP), the language of the World Wide Web.
3. Web Scraping - one of the data you want may not be available internally as an API or publicly via a web service. However, data may exist on a website. If data exists in a structured format, you can retrieve it programmatically. Programmatic retrieval of data from a website is known as web scraping.
4. Human-In-The-Loop - Basically understanding the data from humans and how they feel about the services you provide to them.
5. Surveys - One way to collect data directly from your customers is by conducting a survey.
6. Survey Tools - Instead of designing a custom application to collect survey data, several survey products let you design complex surveys without worrying about building a database. Qualtrics is a powerful tool for developing and administering surveys.
7. Observation - is the act of collecting primary source data, from either people or machines. Observational data can be qualitative or quantitative.
8. Sampling - Suppose you want to analyse one day's worth of data. In that case, the 800 billion records represent the total population, or the number of events, available. Since manipulating 800 billion records is unwieldy, you might collect a sample, or subset, of the overall population.

Data Manipulation
The acronym CRUD (Create, Read, Update, Delete) is a handy way to remember these four operations.
Create - ##INSERT-Creates new data in an existing table

Read - ##SELECT-Retrieves data from an existing table

Update - ##UPDATE-Changes existing data in an existing table

Delete - ##DELETE-Removes existing data from an existing table

Duplicate Data
Duplicate data occurs when data representing the same transaction is accidentally duplicated within a system.
**Data Analytics Tools**
 
**Spreadsheets**
- The spreadsheet is the most widely used tool in the world of analytics.
- It is hard to imagine anyone who does not use spreadsheets as part of their work because they provide an intuitive way to organize our data into rows and columns.
- Spreadsheet software is installed on pretty much every computer in the modern work environment, and web-based spreadsheets are freely available to anyone.
 
 
**Microsoft Excel**
- Microsoft Excel is the most commonly used desktop spreadsheet application.
- It is available as a component of the widely deployed Microsoft Office productivity suite and most modern knowledge workers have access to it.
- Excel then allows users to perform calculations and visualizations on their data
 
 
**Programming Languages**
 
**R**
- The R programming language is extremely popular among data analysts because it is focused on creating analytics applications
 
**Python**
- Python is arguably the most popular programming language in use today. Python is about the same age as R, but the major difference between Python and R is that Python is a general-purpose programming language
 
**Structured Query Language (SQL)**
- The Structured Query Language (SQL) is the language of databases. Any time a developer, administrator, or end user interacts with a database, that interaction happens through the use of a SQL command
 
SQL is divided into two major sublanguages:
 
- **The Data Definition Language (DDL)** is used mainly by developers and administrators. It's used to define the structure of the database itself. It doesn't work with the data inside a database, but it sets the ground rules for the database to function.
- **The Data Manipulation Language (DML)** is the subset of SQL commands that are used to work with the data inside of a database. They do not change the database structure, but they add, remove, and change the data inside a database.
 
 
There are three DDL commands that you should know:
 
- The **CREATE** command is used to create a new table within your database or a new database on your server.
- The **ALTER** command is used to change the structure of a table that you've already created. If you want to modify your database or table, the ALTER command lets you make those modifications.
- The **DROP** command deletes an entire table or database from your server. It's definitely a command that you'll want to use with caution!
 
 
There are also four DML commands that you should know:
 
- The **SELECT** command is used to retrieve information from a database. It is the most commonly used command in SQL as it is used to pose queries to the database and retrieve the data that you're interested in working with.
- The **INSERT** command is used to add new records to a database table. If you are adding a new employee, customer order, or marketing activity, the INSERT command allows you to add one or more rows to your database.
- The **UPDATE** command is used to modify rows in the database. If you need to change something that is already stored in your database, the UPDATE command will do that.
- The **DELETE** command is used to delete rows from a database table. Don't confuse this command with the DROP command. The DROP command deletes an entire database table, whereas the DELETE command just deletes certain rows from the table.
 
 
 
**Microsoft Power BI**
- Power BI is Microsoft's analytics suite built on the company's popular SQL Server database platform.
- Power BI is popular among organizations that make widespread use of other Microsoft software because of its easy integration with those packages and cost-effective bundling within an organization's Microsoft enterprise license agreement
 
 
The major components of Power BI include the following:
 
- **Power BI Desktop** is a Windows application for data analysts, allowing them to interact with data and publish reports for others.
- The **Power BI** service is Microsoft's software-as-a-service (SaaS) offering that hosts Power BI capabilities in the cloud for customers to access.
- **Mobile apps** for Power BI provide users of iOS, Android, and Windows devices with access to Power BI capabilities.
- **Power BI Report Builder** allows developers to create paginated reports that are designed for printing, email, and other distribution methods.
- **Power BI Report Server** offers organizations the ability to host their own Power BI environment on internal servers for stakeholders to access.
 
 
**AWS QuickSight**
- AWS QuickSight is a dashboarding tool available as part of the Amazon Web Services cloud offering
- This tool's power comes from the fact that it is available on a pay-as-you-go basis and its integration with the powerful data storage, data warehousing, machine learning, and artificial intelligence capabilities offered by the Amazon cloud.
 
 
**Tableau**
- Tableau is arguably the most popular data visualization tool available in the market today.
- The focus of this tool is on the easy ingestion of data from a wide variety of sources and powerful visualization capabilities that allow analysts and business leaders to quickly identify trends in their data and drill down into specific details.
 
 
**Qlik**
- Qlik is another popular SaaS analytics platform, offering access to cloud-based analytics capabilities.
 
 
The major products offered by Qlik include the following:
 
- **QlikView** is the company's original analytics platform that focuses on providing rapid insights.
- **Qlik Sense** is a more advanced platform providing more sophisticated analytics capabilities
