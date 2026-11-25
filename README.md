# Olist E-Commerce Data Engineering Project | Microsoft Fabric

## Project Overview

This project focuses on building an end-to-end data engineering and analytics solution using the Olist Brazilian E-Commerce dataset.

The project uses Microsoft Fabric to organise raw e-commerce data, implement the Medallion Architecture (Bronze, Silver, and Gold), perform SQL-based data processing, and develop an interactive Power BI report for business insights.

## Technologies Used

- Microsoft Fabric
- Fabric Lakehouse
- Fabric Data Warehouse
- SQL
- Microsoft Fabric Data Pipeline
- Power BI
- Semantic Model
- Medallion Architecture

## Architecture

The project follows the Medallion Architecture with three layers:

### 1. Bronze Layer
- Stores the raw Olist e-commerce datasets.
- Uses a Microsoft Fabric Lakehouse (`lh_bronze`).
- Maintains the initial raw data for further processing.

### 2. Silver Layer
- Organises processed data within the Fabric Warehouse.
- Uses SQL-based data processing and transformations.
- Structures data for further analytical use.

### 3. Gold Layer
- Contains the final organised data tables.
- Prepares data for business reporting and analysis.
- Serves as the analytical layer for Power BI.

## Microsoft Fabric Components

| Component | Purpose |
|---|---|
| `lh_bronze` | Raw data storage using Lakehouse |
| `wh_olist` | Data warehouse |
| `PI_olist_load` | Data pipeline |
| `olist_model` | Power BI semantic model |
| `olist_report` | Power BI report |

## SQL Implementation

SQL was used for warehouse operations and data processing.

The project includes saved SQL queries covering the implementation of the Bronze, Silver, and Gold schemas and related warehouse operations.

Screenshots of the SQL implementations are available in the repository.

## Data Source

Dataset: Olist Brazilian E-Commerce Public Dataset.

The project uses nine raw dataset files containing e-commerce information.

Dataset source: [Olist E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Power BI Reporting

An interactive Power BI report was developed using the Fabric semantic model to present e-commerce data insights through visualisations and report pages.

## Project Workflow

1. Raw dataset ingestion into Microsoft Fabric Lakehouse.
2. Organisation of raw data in the Bronze layer.
3. SQL-based processing and transformation.
4. Organisation of data into Silver and Gold layers.
5. Use of Microsoft Fabric Warehouse and Pipeline.
6. Creation of a semantic model.
7. Development of a Power BI report.

## Repository Structure

```text
Olist-Ecommerce-Fabric/
│
├── README.md
│
└── screenshots/
    ├── SQL_Queries/
    ├── Warehouse/
    ├── Pipeline/
    └── PowerBI/
```

## Key Learnings

- Working with Microsoft Fabric Lakehouse and Warehouse.
- Understanding and implementing Medallion Architecture.
- SQL-based data processing and warehouse organisation.
- Understanding data pipelines and data flow.
- Connecting analytical data models with Power BI.
- Building an end-to-end data engineering workflow.

---

**Project Type:** Data Engineering & Analytics  
**Platform:** Microsoft Fabric  
**Focus:** SQL | Data Warehousing | Medallion Architecture | Power BI
