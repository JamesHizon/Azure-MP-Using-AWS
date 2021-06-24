# Azure Mini-Project Using AWS

In this Mini-Project, I was originally tasked to use Azure to complete. Yet, since I was not able to get the HDInsight Cluster to work in a reasonable time period and wanted more exposure to AWS, I decided to work with AWS Solutions.

### Steps
1. Create EC2 Key Pair. 
2. Create S3 bucket to store Jupyter Notebook file and dataset.
3. Go to Create an EMR Cluster inside AWS Management Console.
4. Under Advanced Options, include Spark, JupyterHub and other Jupyter application to run.
5. Set Master and Worker node to be m4.large to reduce cost.
6. Include EC2 Key Pair that has been created for key pair option.
7. Create EMR Cluster in Step 4.
8. Go to EMR Notebooks.
9. After EMR Cluster is ready, choose recently created EMR Cluster inside EMR Notebook setting and specify file S3 file path that was used to store Jupyter Notebook file and CSV file.
10. Once EMR Notebook is ready, go to Open in Jupyter and select PySpark kernel to run.
11. Complete Spark DataFrame exercise.
12. Terminate cluster to eliminate incurring costs.

Attached are relevant screenshots, empty and finished Jupyter Notebook files and the walmart_stock.csv file.
