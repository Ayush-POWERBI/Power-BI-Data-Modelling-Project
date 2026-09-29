# Power BI Data Modeling Project

## 📌 Project Overview

This project focuses on designing and implementing a structured Data Model in Power BI from complex and messy source data.

The data was analyzed, cleaned, transformed, and structured according to the requirements of the analysis. Power Query was used for data transformation, while Power BI Data Modeling and DAX were used to build a scalable and analysis-ready model.

The main objective was to convert raw and inconsistent data into a clean, structured model suitable for business reporting and analysis.

## 🎯 Project Objectives

- Analyze and understand the source data
- Identify Fact and Dimension tables
- Clean and transform messy data
- Resolve data quality issues according to requirements
- Build relationships between tables
- Design a structured Star Schema
- Create DAX measures for analysis
- Organize the model for scalable reporting
- Prepare the data model for Power BI dashboards

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Fact & Dimension Tables
- Data Cleaning
- Data Transformation

## 🧩 Data Model

### Dimension Tables

- Dim_Customers
- Dim_Products
- Dim_Campaign
- Dim_Dates
- Dim_Geo
- Dim_Junk

### Fact Tables

- Fact_Sales
- Fact_Order_Process
- Fact_Inventory
- Fact_Campaign_Spend
- Fact_Promotion_Coverage
- Fact_Sales_Target

### Supporting Tables

- _Measures
- Security

The model was designed to establish meaningful relationships between business entities while maintaining a clear separation between transactional data and descriptive attributes.

## 🔄 Data Transformation

The source data contained several inconsistencies and required significant transformation before it could be used effectively.

Power Query was used to:

- Clean inconsistent data
- Handle missing and blank values
- Resolve data quality issues
- Correct data types
- Remove unnecessary data
- Transform raw datasets
- Structure Fact and Dimension tables
- Create required fields
- Prepare clean, analysis-ready data

## 🏗️ Data Modeling

The transformed datasets were organized into a structured analytical model using a Star Schema approach.

Fact tables contain transactional and measurable information, while Dimension tables provide descriptive information used for filtering and analysis.

Relationships were created between relevant Fact and Dimension tables using appropriate business keys.

This improves:

- Data organization
- Filtering
- DAX calculations
- Report performance
- Maintainability
- Scalability

## 📊 DAX & Measures

DAX measures were created to support analytical and reporting requirements.

A dedicated _Measures table was created to keep measures organized and make the model easier to maintain.

The model supports analysis of:

- Sales performance
- Inventory
- Campaign performance
- Promotion coverage
- Target vs Actual performance
- Customer analysis
- Product analysis

## 🔐 Security

A dedicated Security table was included to support security-related requirements and provide a foundation for implementing Row-Level Security (RLS).

## 🔍 Key Challenges

### Messy Source Data

The source data required extensive cleaning and transformation before it could be used for analysis.

### Fact & Dimension Identification

Different datasets were analyzed to determine which tables represented measurable business events and which represented descriptive entities.

### Relationship Design

Relationships between multiple Fact and Dimension tables were structured to support accurate filtering and analysis.

### Data Preparation

The raw data was transformed according to the requirements of the analysis instead of directly loading the source data into Power BI.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Power BI Data Modeling
- Fact and Dimension table design
- Star Schema
- Table relationships
- Power Query transformations
- Data cleaning
- DAX measures
- Handling messy real-world data
- Building scalable analytical models

## 🚀 Project Outcome

The final result is a structured and analysis-ready Power BI data model created from messy source data.

The complete workflow was:

Raw Data → Data Cleaning → Data Transformation → Fact & Dimension Design → Relationships → DAX Measures → Analytical Data Model

The model can be used as a foundation for developing interactive Power BI dashboards and performing business-focused analysis.

## 👨‍💻 Skills Demonstrated

Power BI | Power Query | DAX | Data Modeling | Star Schema | Data Cleaning | Data Transformation | Fact & Dimension Modeling | Business Intelligence
