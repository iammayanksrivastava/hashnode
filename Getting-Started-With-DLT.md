---
title: Getting Started with Databricks Delta Live Tables
domain: factorsense.nl 
tags: databricks, azure
subtitle: Incremental processing of new data as they arrive in cloud storage without any additional setup.
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1658824807546/fxJUh0mxf.jpg?auto=compress 
---
# Background
One of the most common use cases we have had in the ETL workloads is tracking which incoming files have been processed and incremental processing of the new data coming in from the sources. During early days of career, I still remember we had this File Watcher component in our framework which used to keep watching for the files in the landing folder. The file watcher used to register each file coming into the landing layer and once all the required conditions were met the component used to process all the data into the DataWarehouse.
