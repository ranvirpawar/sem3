## 1. Data Warehouse Fundamentals

### 1.1 Introduction to Data Warehouse, OLTP Systems
- **Data Warehouse**: Centralized repository for storing large volumes of structured data for analytical purposes.
- **OLTP Systems**: Operational systems for day-to-day transactions.

**Differences between OLTP Systems and Data Warehouse**:
- OLTP: Real-time transactions; Data Warehouse: Historical and aggregated data for analysis.
- OLTP: Optimized for insert, update, delete; Data Warehouse: Optimized for read-heavy, analytical queries.

### 1.2 Characteristics of Data Warehouse; Functionality of Data Warehouse
- **Characteristics of Data Warehouse**:
  - Subject Oriented
  - Integrated
  - Time-variant
  - Non-volatile
- **Functionality of Data Warehouse**:
  - Data Consolidation
  - Data Cleaning
  - Data Transformation
  - Data Loading
  - Data Refreshing

### 1.3 Advantages and Applications of Data Warehouse; Top-Down and Bottom-Up Development Methodology
- **Advantages**:
  - Improved Data Quality
  - Enhanced Business Intelligence
  - Historical Analysis
  - Decision Support
- **Applications**:
  - Market Basket Analysis
  - Customer Segmentation
  - Forecasting
  - Trend Analysis
- **Development Methodologies**:
  - Top-Down
  - Bottom-Up

### 1.4 Tools for Data Warehouse Development
- ETL Tools (Talend, Informatica)
- Reporting Tools (Tableau, Power BI)
- Database Systems (Oracle, SQL Server)

## 2. Data Warehouse Architecture

### 2.1 Introductions, Components of Data Warehouse Architecture
- **Data Warehouse Architecture**: Overall design and structure of the system.
- **Components**:
  - Data Sources
  - ETL Process
  - Data Warehouse Database
  - OLAP Cube or Data Marts
  - Front-end Reporting Tools

### 2.2 Technical Architectures; Federated Data Warehouse Architecture; Tool selection
- **Technical Architectures**:
  - Single-tier
  - Two-tier
  - Three-tier
- **Federated Data Warehouse Architecture**: Combines multiple data warehouses or data marts.
- **Tool Selection**: Based on factors like scalability, compatibility, cost, and vendor support.

### 2.3 Dimensional Modeling: E-R Modeling VS Dimensional Modeling
- **Dimensional Modeling**: Organizing data for easy retrieval and analysis.
- **E-R Modeling**: Designing databases based on entity relationships.

### 2.4 Data Warehouse Schemas
- Star Schema
- Snowflake Schema
- Fact Constellation Schema

### 2.5 Introduction to Metadata : Categorizing Metadata
- **Metadata**: Data about the data.
- **Categories of Metadata**:
  - Technical Metadata
  - Business Metadata

### 2.6 Metadata management in practice; Metadata requirements gathering, Metadata classification, Metadata collection strategies, Tools for Metadata Management
- **Metadata Management**: Organizing, controlling, and maintaining metadata.
- **Steps**:
  - Requirements Gathering
  - Classification
  - Collection Strategies
  - Tools for Metadata Management

## 3. Data Preprocessing and ETL

### 3.1 Data Pre-processing: Data Cleaning tasks
- **Data Preprocessing**: Preparing raw data for analysis.
- **Data Cleaning Tasks**:
  - Handling Missing Values
  - Removing Duplicates
  - Data Transformation

### 3.2 Data Integration and Data Reduction
- **Data Integration**: Combining data from different sources.
- **Data Reduction**: Reducing volume while producing same results.

### 3.3 Discretization and Concept Hierarchy Generation
- **Discretization**: Converting continuous attributes into categorical ones.
- **Concept Hierarchy Generation**: Creating hierarchies for attributes.

### 3.4 Data Transformation; Basic Tasks in Transformation, Major Data Transformation Types
- **Data Transformation**: Converting data for analysis.
- **Basic Tasks**:
  - Aggregation
  - Normalization
  - Attribute Construction
- **Transformation Types**:
  - Smoothing
  - Aggregation
  - Generalization

### 3.5 Introduction to ETL (Extract, Transform and Load)
- **ETL**: Process to collect, transform, and load data into a data warehouse.

### 3.6 ETL requirements and steps: Data Extraction; Extraction Methods, Logical Extraction Methods, Physical Extraction Methods
- **ETL Requirements**:
  - Data Sources Identification
  - Data Extraction Criteria
  - Data Transformation Rules
  - Data Loading Rules
- **Extraction Methods**:
  - Full Extraction
  - Incremental Extraction
- **Logical Extraction Methods**:
  - Key-based Extraction
  - Time-based Extraction
- **Physical Extraction Methods**:
  - Batch Extraction
  - Real-time Extraction

### 3.7 Data loading; Data Loading Techniques, ETL Tools
- **Data Loading**: Loading transformed data into the data warehouse.
- **Loading Techniques**:
  - Bulk Loading
  - Incremental Loading
- **ETL Tools**: Software for Extracting, Transforming, and Loading data.

