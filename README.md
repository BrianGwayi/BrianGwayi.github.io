# Data Pipeline Orchestration in Airflow
![airflowbanner](assets/imgs/afbanner.png)
Apache Airflow® is an open-source platform for developing, scheduling, and monitoring batch-oriented workflows. Airflow’s extensible Python framework enables you to build workflows connecting with virtually any technology. A web interface helps manage the state of your workflows. Airflow is deployable in many ways, varying from a single process on your laptop to a distributed setup to support even the biggest workflows.  
## Code Snippet
```
default_args={‘Owner’ : ‘gwayi’}
@dag(
dag_id=”jobs_listing”, # unique identifier
default_args=default_args, # default arguments
schedule=@daily, # how often the dag runs
start_date=datetime(2024, 7, 20), # start date for the dag
catchup=False, # run/not run missed intervals
tags=['Team A'], # to categorize and filter dags in UI
)
```
## Airflow UI
![airflowbanner](assets/imgs/graph.png)

## Projects
[job_lisitng pipeline](https://github.com/BrianGwayi/Simple_Airflow_Pipeline)  
[adventure_works](https://github.com/BrianGwayi/Apache-Airflow)

# Reporting - Dashboard Development
## Microsoft Power BI
This simple revenue report tracks revenue targets. Keeping a close eye on previous month revenue also help identify growth opportunities, resource allocation and ultimately lead the business to long term success.  

## Landing Page

![PBIDesktop_OlUKNlaaPm](https://github.com/BrianGwayi/Coffee-Shop-Revenue-PowerBI/assets/115585139/33c60224-0e7f-453c-9233-c07c251fdc48)

## Detailed Page

![PBIDesktop_tu1YirWecQ](https://github.com/BrianGwayi/Coffee-Shop-Revenue-PowerBI/assets/115585139/07a7cbd9-4957-44e3-bc11-f35243ed4fa9)

### Tech Stack
- Databases:Oracle 9I/10g, DB2, PostgreSQL, MySQL, SQL Server
- Reporting:Power BI,Tableau, Looker
- Orchestration and Integration: Kafka, Airflow,Talend
- Languages: Python, Unix Shell Script, SQL and PL/SQL

# Data Specialist
### Education
Business Information Technology, Bsc

### Work Experience
Data Lead @ Afriama  
Business Intelligence Analyst @ Absa Bank   
Officer Credit Operation @ Co-operative Bank  
Data Entry Freelancer @ Jumia Food 
