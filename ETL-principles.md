### Focus on Python for Data Engineering

#### Extract, Transform, Load (ETL) in Python:

##### Data Extraction:
- **Pandas:** Read data from CSV, Excel, SQL databases, and more.
- **SQLAlchemy:** Connect and extract data from relational databases.
- **Requests/BeautifulSoup:** Extract data from web APIs or scrape websites.

##### Data Transformation:
- **Pandas:** Clean, manipulate, and transform data.
- **NumPy:** Perform numerical operations on data.
- **PySpark:** Process large datasets using Spark's Python API (useful for big data).

##### Data Loading:
- **Pandas/SQLAlchemy:** Write data back to relational databases.
- **Boto3:** Interact with AWS services to load data into S3, Redshift, etc.

### Tools and Libraries for Data Engineering:

#### Data Extraction:
- **Pandas, Reading and Filtering Data:**
  - `pd.read_csv()`
  - `pd.read_sql()`
- **SQLAlchemy:**
  - `create_engine()`
  - `engine.execute()`
  - https://www.theseus.fi/bitstream/handle/10024/851088/neittamo_joona.pdf?sequence=5 **article to fill this gap**

- **Requests, API learning:**
  - `requests.get()`
  - `response.json()`

#### Data Transformation:
- **Pandas, Preprocessing and cleaning:**
  - `df.groupby()`
  - `df.merge()`
  - `df.apply()`
- **NumPy, various statistics analysis:**
  - `np.array()`
  - `np.mean()`
  - `np.sum()`
- **PySpark:**
  - `spark.read()`
  - `df.withColumn()`
  - `df.filter()`
  - https://norma.ncirl.ie/6486/1/sumitkumarsahoo.pdf **article to fill this gap**

#### Data Loading:
- **Pandas, exporting for reports, plugging  back into Excel:**
  - `df.to_csv()`
  - `df.to_sql()`
- **SQLAlchemy:**
  - `Table.insert()`
  - `engine.execute()`
- **Boto3:**
  - `s3_client.upload_file()`
  - `redshift.execute()`
  - https://journal.uob.edu.bh/bitstream/handle/123456789/4983/IJCDS160103_1570908738.pdf?sequence=3 **article to fill this gap**

# Deeper learning and growth areas to focus on.
 
### Key Concepts:
- **Data Modeling:** Understanding relational database schema design, normalization, and data warehousing concepts.
- **ETL Process:** Knowing how to design, implement, and manage ETL workflows, ensuring data quality and integrity.
- **AWS Fundamentals:** Familiarity with core AWS services like S3, EC2, and IAM, as well as data-specific services like Redshift and Glue.

### ETL Process:

#### Data Extraction:
- **Pandas:** [Documentation](https://pandas.pydata.org/docs/): Pandas is a powerful library for data manipulation and analysis in Python. It provides data structures and functions to efficiently handle structured data, making it an essential tool for data extraction tasks.
- **SQLAlchemy:** [Tutorial](https://docs.sqlalchemy.org/en/14/tutorial/): SQLAlchemy is a SQL toolkit and Object-Relational Mapping (ORM) library for Python. It allows you to interact with relational databases using Python objects, providing a high-level abstraction for database operations.
- **Requests/BeautifulSoup:** [Requests Documentation](https://docs.python-requests.org/en/master/), [Beautiful Soup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): Requests is a simple yet powerful HTTP library for Python, used for making HTTP requests to web servers. BeautifulSoup is a Python library for parsing HTML and XML documents, making it useful for web scraping tasks.

#### Data Transformation:
- **Pandas:** [Documentation](https://pandas.pydata.org/docs/): Pandas provides a wide range of functions for data transformation, including data cleaning, manipulation, and aggregation. Its intuitive syntax and powerful functionality make it the go-to choice for data manipulation tasks in Python.
- **NumPy:** [Documentation](https://numpy.org/doc/stable/): NumPy is a fundamental package for scientific computing with Python. It provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently.
- **PySpark:** [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/index.html): PySpark is the Python API for Apache Spark, a fast and general-purpose cluster computing system. PySpark allows you to process large datasets in parallel, making it suitable for big data processing tasks.

#### Data Loading:
- **Pandas/SQLAlchemy:** [Pandas Documentation](https://pandas.pydata.org/docs/), [SQLAlchemy Documentation](https://docs.sqlalchemy.org/en/14/): Pandas provides convenient functions for writing data to various formats, including CSV files and SQL databases. SQLAlchemy complements Pandas by providing a powerful ORM framework for interacting with relational databases in Python.
- **Boto3:** [Boto3 Documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html): Boto3 is the Amazon Web Services (AWS) SDK for Python. It allows you to interact with AWS services programmatically, making it suitable for loading data into AWS services such as S3 (Simple Storage Service) and Redshift.

#### Additional Resources and Tools for Growth:
- **Apache Spark:** [Apache Spark Documentation](https://spark.apache.org/docs/latest/): Apache Spark is a fast and general-purpose cluster computing system. It provides high-level APIs in Java, Scala, Python, and R, making it suitable for a wide range of data processing tasks, including ETL.
- **Apache Kafka:** [Apache Kafka Documentation](https://kafka.apache.org/documentation/): Apache Kafka is a distributed streaming platform that is commonly used for building real-time data pipelines. It allows you to publish and subscribe to streams of records in a fault-tolerant and scalable manner.
- **Informatica, ODI, SSIS, Datastage:** These are popular ETL tools used in the industry for data integration and transformation. Exploring these tools can provide insights into different approaches to ETL and broaden your skill set in data engineering.


