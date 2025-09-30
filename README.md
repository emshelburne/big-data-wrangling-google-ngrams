# Big Data Wrangling with Google Books Ngrams

This project demonstrates a reproducible big-data workflow on the **Google Books Ngrams** corpus using **AWS EMR, Spark, HDFS, and S3**.  
It was originally completed as part of the **BrainStation Data Science bootcamp**, and it highlights skills in **distributed computing, cloud infrastructure, and large-scale data wrangling**.

---

## 📊 Project Overview
We spin up an EMR cluster, ingest and filter a large public dataset from S3 into HDFS, process it with PySpark and Spark SQL, export the results back to S3, and finally analyze and visualize trends locally with pandas.  

Key components:
- Provisioning and configuring **AWS EMR clusters** (Spark + HDFS + JupyterHub)
- Using **SSH and JupyterHub tunnels** to interact with the cluster
- Ingesting and validating the Ngrams dataset in **HDFS**
- Filtering tokens (example: `"data"`) using **Spark SQL**
- Writing results back to HDFS and exporting to **S3**
- Local analysis and visualization with **pandas + matplotlib**
- Comparative discussion of **Hadoop vs. Spark** and **HDFS architecture**

---
