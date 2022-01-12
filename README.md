# AWS-Data-Analytics
## Four Types of data Analysis
- ### Descriptive Analysis
  - Descriptive analysis answers the “what happened” by summarizing past data, usually in the form of dashboards.
- ### Diagnostic Analysis
  - After asking the main question of “what happened”, the next step is to dive deeper and ask why did it happen? This is where diagnostic analysis comes in.
    Diagnostic analysis takes the insights found from descriptive analytics and drills down to find the causes of those outcome Example - Marketing company drilling down to   determine which marketing activities increased trials.
- ### Predictive Analysis
  - Predictive analysis attempts to answer the question “what is likely to happen”. This type of analytics utilizes previous data to make predictions about future outcomes. This analysis relies on statistical modeling, which requires added technology and manpower to forecast
    examples - Risk Assessment, Sales Forecasting
 - ### Prescriptive Analysis
   - The final type of data analysis is the most sought after, combining the insight from all previous analyses to determine the course of action to take in a current problem or decision. Artificial Intelligence (AI) is a perfect example of prescriptive analytics. AI systems consume a large amount of data to continuously learn and use this information to make informed decisions.
# Advantages of Amazon AWS Databases
- Highly Scalable: You can scale your database as your application grows without any downtime.
- Fully Managed: Everything, from maintenance to hardware upgrades, is managed by AWS.
- Enterprise Class: world-class infrastructure.
- Distributed: Now that your application and database exist on separate machines, your application becomes highly fault-tolerant.
- Since everything is managed by AWS, you don’t need a Database Maintenance team in your organization.you don’t need a Database Maintenance team in your organization.

Summarizing, AWS Database Services are highly scalable, fully managed services provided by AWS for the Internet-scale applications on a pay-as-you-go model. They offer various databases like relational databases, non-relational databases, etc

## Types of AWS Database Services
AWS provides a wide range of fully managed, purpose-built and both relational and non-relational database services specially designed to handle any kind of application requirements. 

### Relational Database: 
In relational databases, the data is usually stored in a tabular format. Relational databases particularly use structured query language (SQL) to run queries to perform operations such as insertion, updating, deletion, and more. AWS provides following relational database services.
- Amazon RDS
  - RDS is used to set up, operate, and scale a relational database in the cloud. t’s compatible with six popular database engines – Amazon Aurora, MySQL, MariaDB, PostgreSQL, Oracle and Microsoft SQL Server
  - 
- Amazon Redshift
   - Amazon Redshift is also a managed database service and a relational database. Because of its vast storage potential and differing functionality, Redshift is sometimes referred to as a data warehouse. Redshift is an OLAP database, standing for ‘online analytical processing’. This means it’s especially suited to processing analytical queries involving more complex calculations. running its own engine adapted from PostgreSQL.
- Amazon Aurora

### Key–Value Database: (NoSQL)
The key–value database is a type of NoSQL database where the method of having a value attached to a key is used to store data. Meaning that the data is composed of two elements, keys and values.

Amazon DynamoDB

### In-memory Database: 
This type of database is primarily based on the main memory for computer data storage. Basically, an in-memory database keeps the whole data in the RAM. Meaning that each time you access the data, you only access the main memory and not any disk. And the reason that the main memory is faster than any disk is why in-memory databases are so popular.

Amazon ElastiCache
