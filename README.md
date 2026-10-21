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
- `docs/` System architecture, data dictionaries, and setup guides
- `src/` Ingestion scripts for DHIS2 API
- `dags/` Airflow DAGs for scheduled pipeline execution
- `dbt/` Data transformations and quality testing models
- `dashboards/` Power BI templates and reporting specifications

## Setup & Getting Started

1. **Clone the repository** (or open your local project folder):
   ```powershell
   cd C:\Projects\dhis2-immunization-data-platform

```

2. **Create and activate the virtual environment:**
```powershell
py -3 -m venv .venv

```


*(Note: If PowerShell blocks script execution, run: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process`)*
```powershell
.venv\Scripts\Activate

```


3. **Install the dependencies:**
```powershell
pip install -r requirements.txt

```



```

```