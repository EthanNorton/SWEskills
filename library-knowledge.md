# Essential Libraries and Tools for Machine Learning Engineering

 

## CuDF and Nvidia Learning Applications

### CuDF
CuDF is a GPU DataFrame library that allows for efficient data manipulation on large datasets using GPU acceleration.

### Goals
- Master the CuDF API and operations to handle large datasets efficiently.
- Leverage GPU acceleration to improve data processing performance.

### Nvidia Learning Applications

#### NIMS
NVIDIA Infrastructure Management Service (NIMS) helps manage, monitor, and optimize GPU resources.

#### Distributed/Parallel Computing
Understanding distributed and parallel computing frameworks is crucial for scaling machine learning tasks across multiple GPUs and nodes.

#### cuDNN
The NVIDIA CUDA Deep Neural Network library (cuDNN) provides GPU-accelerated functionalities for deep neural networks.

- **Learning Objectives**
  - Deep dive into cuDNN, its functionalities, and its integration with other libraries like cuBLAS and TensorRT.
  - **References**:
    - [Interpretable ML-enhanced CNN Performance Analysis of cuBLAS, cuDNN, and TensorRT](https://www.researchgate.net/profile/Jurn-Gyu-Park/publication/370220863_Interpretable_ML_enhanced_CNN_Performance_Analysis_of_cuBLAS_cuDNN_and_TensorRT/links/64467877d749e4340e34b7c1/Interpretable-ML-enhanced-CNN-Performance-Analysis-of-cuBLAS-cuDNN-and-TensorRT.pdf)
    - [Performance Analysis of cuBLAS, cuDNN, and TensorRT](https://www.mdpi.com/2079-9292/11/19/3205)

## Understanding Tensors

### Definition
Tensors are multidimensional arrays that serve as the fundamental data structures in machine learning.

### Goals and Projects Applications
- **Build a Neural Network for Predicting Energy Levels**
  - Develop a neural network model using tensor operations to predict energy levels.
- **Understanding One-Hot Encoding**
  - Master one-hot encoding techniques for categorical data representation.
- **Gradient Descent Optimizer**
  - Implement and understand the gradient descent optimization process for training neural networks.

## Utilizing and Applying Keras Library

### Keras
Keras is a high-level neural networks API that runs on top of TensorFlow, CNTK, or Theano.

![image](https://github.com/EthanNorton/SWEskills/assets/86625413/672ef6cd-1cfd-4625-821e-0684ad097fef)

### Goals
- **Model Building**
  - Build, compile, and train neural network models using Keras.
- **Hyperparameter Tuning**
  - Optimize model performance through hyperparameter tuning.
- **Model Evaluation**
  - Evaluate model performance and make predictions using Keras functions.
- **Advanced Features**
  - Explore and utilize advanced Keras features such as custom layers, callbacks, and the functional API.
    
### Data Flow Graph
![image](https://github.com/EthanNorton/SWEskills/assets/86625413/59f61592-3736-44c5-814e-106862205cdd)

## Additional Relevant Libraries

### Data Processing

#### Pandas
Pandas is a powerful library for data analysis and manipulation in Python.

### My Goals
- Use Pandas for efficient data cleaning, transformation, and analysis.
- Leverage DataFrame and Series objects for handling structured data.

#### Dask
Dask is a parallel computing library that extends Python capabilities to handle larger-than-memory datasets.

### Goals
- Handle large datasets with Dask that do not fit into memory.
- Utilize Dask's parallel computing capabilities to speed up data processing.

### Machine Learning

#### Scikit-Learn
Scikit-Learn provides simple and efficient tools for data mining and data analysis.

### Goals
- Apply Scikit-Learn for standard machine learning tasks such as classification, regression, clustering, and dimensionality reduction.
- Utilize pipelines and model selection tools to streamline the machine learning workflow.

#### XGBoost
XGBoost is an optimized distributed gradient

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

### Key Concepts:
- **Data Modeling:** Understanding relational database schema design, normalization, and data warehousing concepts.
- **ETL Process:** Knowing how to design, implement, and manage ETL workflows, ensuring data quality and integrity.
- **AWS Fundamentals:** Familiarity with core AWS services like S3, EC2, and IAM, as well as data-specific services like Redshift and Glue.

