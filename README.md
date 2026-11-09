<h1 align="center">Usama Zia</h1> <p align="center"><b>Senior Analytics Engineer</b> · I build data pipelines that run themselves, for fintech payments</p> <p align="center"> <img src="https://img.shields.io/badge/Lahore,_PK-UTC+5-1f2937?style=flat-square" alt="Lahore, Pakistan, UTC+5"/> <img src="https://img.shields.io/badge/Open_to-Remote_·_Relocation-15803d?style=flat-square" alt="Open to remote and relocation"/> <a href="https://www.linkedin.com/in/YOUR-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a><!-- TODO --> <a href="mailto:usama.zia72@gmail.com"><img src="https://img.shields.io/badge/Email-usama.zia72@gmail.com-b91c1c?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a> </p>
sql
-- whoami.sql
select
    'Usama Zia'                              as name,
    'Senior Analytics Engineer'              as role,
    'Card issuing & payments (fintech)'      as domain,
    7                                        as years_in_fintech,
    array['SQL', 'Python', 'Airflow', 'dbt', 'Tableau'] as core_stack,
    array['remote', 'relocation']            as open_to
from engineers
where automates_the_repeatable
  and ships_to_production
  and explains_it_to_the_business;
Impact
Result	How
100+ hrs / month saved	Automated weekly and monthly reporting end to end with SQL, Python, Tableau Prep and Tableau
~4x faster pipelines	Rebuilt 5 Tableau Prep workflows as Airflow DAGs
40% faster turnaround	Reports reach business teams sooner
60% less manual work	Contact Center Analytics platform joining 4 source systems
50+ enterprise clients	Monthly Business Review rebuilt on one shared data source, with clearer executive KPIs
HA + DR Airflow	Led the highly available Airflow setup; designed reusable, production-ready DAG patterns

<sub>Production code belongs to my employer and stays private. The projects below rebuild the same patterns on public data.</sub>

How I build
Python · SQL
SQL · dbt
orchestrates
guards
Source systemstransactions · contact center· ops
Greenplum70+ instances
Star-schema martstested · documented
Tableau dashboardsKPIs · fraud · declines
Airflow (HA + DR)
Data quality checks
Stack
Layer	Tools
Ingest & orchestrate	Python (Pandas) · Apache Airflow · Tableau Prep
Store	Greenplum · PostgreSQL · MySQL · Informix
Model & transform	SQL · dbt · Star schema · Data quality checks
Serve	Tableau · Power BI · Power Query
Run & collaborate	Git · Bitbucket · Jira · Dynatrace · Nagios · Xymon · Agile · ITIL
Adding now	Snowflake · advanced dbt · Docker · GitHub Actions
Projects
Project	What it does	Stack
Card Payments Decline & Fraud Analytics <!-- TODO -->	Pipeline on synthetic card transactions: approval rates, decline reasons by merchant and country, fraud trends. CI on every pull request.	Python · dlt · Snowflake · dbt · Airflow · Tableau
dbt Production Patterns <!-- TODO -->	Layered models, custom macros, incremental models, snapshots, tests on every model	dbt · DuckDB · Snowflake
Build log
console
$ dbt build --select +usama_zia
1 of 5 OK   fintech_production_experience ........... [7 yrs]
2 of 5 OK   incident_leadership_10_plus_analysts .... [99% SLA]
3 of 5 RUN  dbt_analytics_engineering_cert .......... [target Dec 2026]
4 of 5 RUN  snowpro_core_cof_c03 .................... [target Jan 2027]
5 of 5 RUN  payments_fraud_analytics_platform ....... [target Mar 2027]
Experience

Senior Analytics Engineer · i2c Inc. · 2024 – present<br/> Pipelines, data models and executive reporting for a global payments platform. Mentored 5 analysts through probation.

Incident Team Lead · i2c Inc. · 2019 – 2023<br/> Led 10+ analysts; kept SLA adherence at 99% and uptime at 99.9%. Root cause analysis under ITIL.

BS Information Technology · PUCIT, Lahore · 2019

<p align="center">Hiring for analytics or data engineering? <a href="mailto:usama.zia72@gmail.com">Let's talk.</a></p>
