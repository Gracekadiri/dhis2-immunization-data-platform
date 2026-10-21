# DHIS2 Immunization Data Platform

## Executive Summary
An end-to-end data platform designed to extract, transform, and visualize public health immunization and stockout metrics from DHIS2 data sources.

## Architecture & Technology Stack
- **Ingestion & Pipeline:** Python & DHIS2 API
- **Orchestration:** Apache Airflow
- **Data Warehouse:** Google BigQuery
- **Transformation & Data Quality:** dbt (data build tool)
- **Visualization & Analytics:** Power BI

## Repository Structure
- `docs/` - System architecture, data dictionaries, and setup guides
- `src/` - Ingestion scripts for DHIS2 API
- `dags/` - Airflow DAGs for scheduled pipeline execution
- `dbt/` - Data transformations and quality testing models
- `dashboards/` - Power BI templates and reporting specifications

## Setup & Getting Started
*Instructions for setting up the environment and running the pipeline locally will be added as components are built.*