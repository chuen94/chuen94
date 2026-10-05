# Yi-Chuen (Alice) Wang
**Data Analyst · Manufacturing Analytics · M.S. Analytics, Georgia Tech**

I turn operational sensor and process data into reliable, decision-ready insights.
My background sits at the intersection of manufacturing operations and modern data
analytics: five years in a high-volume industrial R&D environment, where I taught
myself the modern data stack and built self-directed pipelines and dashboards on
real production data.

---

## What I Do
- **Analysis & Reporting** — SQL-driven analysis and dashboards for manufacturing and process monitoring
- **ELT Pipelines** — ingestion, transformation, and quality validation with dbt on Snowflake and DuckDB
- **Near-Real-Time Monitoring** — micro-batch pipelines feeding auto-refreshing Grafana dashboards
- **Statistical Methods** — time-series anomaly detection and process monitoring for manufacturing data

---

## Featured Projects

### [Factory Telemetry Pipeline](https://github.com/chuen94/manufacturing_pipeline)
Manufacturing analytics pipeline on synthetic data. DuckDB + dbt models (incremental fact, SCD2, tests) feed a Grafana dashboard, and a material-substitution analysis tests whether a swap really changes scrap, downtime or yield. CI runs dbt build on every push.

**Stack:** Python · DuckDB · dbt Core · Grafana · GitHub Actions

### [SECOM — High-Dimensional Sensor Pipeline](https://github.com/chuen94/SECOM)
ELT pipeline on Snowflake + dbt for the UCI SECOM semiconductor dataset
(~1,500 records × 590+ sensor variables). Jinja macro-based dynamic SQL, medallion
architecture, data quality contracts, and automated CI/CD. Orchestrated with Dagster.
**Stack:** Python · Snowflake · dbt Core · Dagster · GitHub Actions

### [TEP](https://github.com/chuen94/TEP) · [DAMADISC](https://github.com/chuen94/DAMADISC)
Time-series anomaly-detection research on the Tennessee Eastman Process simulation and
industrial sensor data — prestudy conducted ahead of an industry-mentored collaboration
with Enrisk (collaboration work product not public).

---

## Tech Stack
| Category | Tools |
|---|---|
| **Analysis & Reporting** | SQL, dashboards, statistical methods |
| **Data Transformation** | dbt (Core/Cloud), SQL, Jinja |
| **Warehouses** | Snowflake, DuckDB, MySQL |
| **Languages** | Python (Pandas, NumPy, statsmodels), SQL |
| **Orchestration** | Dagster, GitHub Actions (CI/CD) |
| **Visualization** | Tableau, Power BI, Grafana |

---

## Background
M.S. Analytics, Georgia Tech (2026) · M.S. Inorganic Chemistry (intercalation research), Oregon State

Five years in a high-volume manufacturing R&D environment. Alongside my core
responsibilities, I built self-directed data work — including a proof-of-concept ELT
pipeline connecting production MySQL through dbt transformation layers to Grafana
monitoring, and a Tableau dashboard for production quality-defect analysis.

Location: La Habra, CA &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/yi-chuen-wang/)
