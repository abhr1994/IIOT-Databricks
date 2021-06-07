# IIOT-Databricks

This project demonstrates the following architecture for IIoT Ingest, Processing and Analytics on Azure. 
The following architecture is implemented in this project. 

<img src="https://sguptasa.blob.core.windows.net/random/iiot_blog/end_to_end_architecture.png" width=800>

```markdown
DBR 8.2 (includes Apache Spark 3.1.1, Scala 2.12) used for this project

Libraries needed for this project:

	1. com.microsoft.azure:azure-eventhubs-spark_2.12:2.3.18
	2. com.microsoft.azure:azure-eventhubs:3.2.2
	3. com.google.cloud.spark:spark-bigquery-with-dependencies_2.12:0.20.0

Advanced Environment Variables set at Cluster
	1. GOOGLE_CLOUD_PROJECT=<gcp_project_id>
	2. GOOGLE_APPLICATION_CREDENTIALS=/dbfs/<path_to_service_prinicpal_cred_json_file>

```

