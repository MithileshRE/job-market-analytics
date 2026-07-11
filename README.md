# job-market-analytics
Real-time job market analytics pipeline on Microsoft Fabric
# Job Market Analytics Pipeline
Real-time job market analytics on Microsoft Fabric.

## Project Overview
- 50 job postings analyzed
- 47 companies indexed
- $127K average salary
- 7 job categories

## Architecture
## What's Inside

### Notebooks (Spark/PySpark)
- `01_load_raw_data.py` - Load CSV into OneLake
- `02_transform_staging.py` - ETL transformation with SQL CTEs
- `03_build_warehouse.py` - Build star schema warehouse

### Data
- `sample_job_postings.csv` - 50 job records with salary, skills, companies

### Dashboard
- `market_overview.png` - Power BI dashboard screenshot

## Tech Stack
- Microsoft Fabric (OneLake, Spark, Warehouse)
- Power BI (Dashboard)
- PySpark & SQL (Transformation)

## Key Insights
- Business Intelligence: 28% of jobs
- EDI & Integration: 18% of jobs
- Top Skills: SQL, Python, Power BI, Spark, Azure
- Salary Range: $70K - $220K

## How to Use
1. Download the Spark notebooks
2. Upload to your Fabric workspace
3. Run notebooks in order (01 → 02 → 03)
4. Connect Power BI to the warehouse
5. Build your dashboard

---

**Built on Microsoft Fabric | 2026**
