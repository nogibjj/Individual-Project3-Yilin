[![CI](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml)
## Individual Project #3: Databricks ETL (Extract Transform Load) Pipeline
- Introduction:
This project is to build a data pipeline using Databricks. The pipeline will extract data from a CSV file, transform the data using Spark, and load the data into a Delta Lake table. The pipeline will be scheduled to run once a day.

## Jupyter Notebook
- [Notebook for Databricks pipeline](https://github.com/nogibjj/Individual-Project3-Yilin/blob/main/Explore%20hive_metastore.default.salaries.ipynb)

## Steps
### Import Data into Delta Lake
> Upload the CSV file from Kaggle to Databricks
![](Results/ImportData.png)

> Check the table in warehouse
![](Results/warehouse.png)

> Query the raw data
![](Results/raw_data.png)
### Prepare the raw data

![](Results/prepared_data.png)

### Query the transformed data

> Which artists released the most songs each year?

![](Results/sql_query1.png)

> Find songs for your DJ list

![](Results/sql_query2.png)

### Create a Databricks job to run the pipeline

![](Results/pipeline.png)

### Automated Trigger
![](Results/trigger.png)

### Result

![](Results/dv.png)

## Reference

1. https://github.com/nogibjj/python-template
2. https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html
3. https://www.kaggle.com/datasets/dparas01/global-ai-ml-data-science-salary/