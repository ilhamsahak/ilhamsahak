# Mohd Ilham Ishak

Senior Data Engineer based in Malaysia.

I design and build scalable data pipelines, orchestration workflows, and analytics systems. My work focuses on managing the full data lifecycle, from ingestion to transformation, orchestration, and reporting, with strong emphasis on reliability, automation, and maintainability.

---

# What I Do

* Design and maintain cloud-based data warehouse architectures using BigQuery
* Build scalable ELT pipelines using SQL and Python
* Implement workflow orchestration using Apache Airflow
* Automate batch processing and reporting pipelines
* Develop internal APIs and utilities using FastAPI
* Build operational dashboards and reporting systems
* Support forecasting and performance analytics workflows
* Improve pipeline reliability through validation and monitoring strategies

---

# Tech Stack

## Data Engineering

* SQL
* Python
* Google BigQuery
* Google Cloud Platform (GCP)
* Apache Airflow
* FastAPI
* Docker
* Git and GitHub

## Data Modeling

* Medallion Architecture (Bronze, Silver, Gold)
* Star Schema Design
* Incremental Processing
* Partitioning and Clustering Optimization

## Analytics and BI

* Power BI
* Looker Studio
* DAX
* KPI Development
* Time Series Analysis

---

# Current Focus

* Workflow orchestration architecture using Apache Airflow
* CI/CD pipelines for data workflow deployment
* BigQuery performance and cost optimization
* Data pipeline reliability and failure recovery strategies
* Standardizing deployment and environment workflows
* Event-driven and dependency-aware pipeline execution

---

# Selected Work

## Data Warehouse Architecture

Designed and implemented centralized warehouse structures using layered modeling:

* Raw ingestion layer (Landing or Bronze)
* Transformation layer (Silver)
* Reporting and analytics layer (Gold)

Key outcomes:

* Improved data consistency across reporting pipelines
* Reduced redundant transformation logic
* Simplified data lineage tracking

---

## Automated Ingestion Pipelines

Built automated ingestion workflows integrating:

* POS transactional data
* External platform data
* Batch file ingestion workflows

Key outcomes:

* Eliminated manual data loading processes
* Standardized ingestion across multiple data sources
* Reduced operational delays in reporting cycles

---

## Workflow Orchestration with Airflow

Designed orchestration pipelines to manage batch dependencies and execution workflows.

Key capabilities:

* Controlled execution order across dependent workflows
* Managed pipeline retries and failure handling
* Implemented scheduled and event-triggered workflows

---

## Parallel Completion Marker Architecture

Talend to Airflow to BigQuery

Designed a marker-based orchestration pattern to synchronize multiple upstream jobs before executing downstream processing.

Architecture overview:

* Multiple Talend jobs run independently
* Each job sends completion markers to Airflow
* Airflow accumulates job states
* Downstream processing executes only after all jobs complete
* Marker state is cleared after successful execution

Key outcomes:

* Prevented premature downstream execution
* Eliminated race conditions between parallel jobs
* Improved reliability of batch orchestration workflows

---

## Reporting Automation

Developed automated reporting pipelines supporting operational and business teams.

Key outcomes:

* Reduced manual reporting time by more than 90 percent
* Standardized recurring reporting workflows
* Improved reporting accuracy and consistency

---

## Forecasting and Performance Analysis

Built forecasting workflows used for operational planning and performance monitoring.

Key capabilities:

* Time-based forecasting models
* Performance trend analysis
* KPI-driven decision support

---

# Architecture Patterns Used

* Medallion Data Architecture
* Event-based Workflow Triggering
* Parallel Completion Barrier Pattern
* Batch Dependency Orchestration
* Idempotent Pipeline Design

---

# About

I focus on building structured, reliable, and maintainable data systems that support real operational workflows.

My approach prioritizes:

* Clarity in pipeline design
* Reliability in execution
* Observability in production
* Maintainability over complexity

---

# Contact

Email: [ilhamishakaman@gmail.com](mailto:ilhamishakaman@gmail.com)
Location: Malaysia
