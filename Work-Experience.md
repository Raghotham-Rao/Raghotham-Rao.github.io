---
layout: page
title: "Work Experience"
permalink: /Work-Experience
---


### **Accenture**

##### _Data Engineering Senior Analyst ~ 2021 - Present_

##### **Ingestion As Service**
- Metadata-driven Python tool to automate data transformation. The tool was developed to handle multiple scenarios that were
encountered during the process of data transformation, reducing the number of pipelines to be built by **60%**.
- The tool can handle flattening of deeply nested fields, perform joins with other tables to enrich the data, and derive new fields using
SQL or PySpark functions.
- Supports append only writes as well as Upserts into the target. Also supports **SCD-1** Updates based on the given key columns and the
sort column to pick the latest instance.
- **80+** data pipelines were built using thetool and accelerated the time to production. The code base was more compact avoiding the
need to maintain transformation files for each pipeline.

##### **Job Details Dashboard**
- A parametrized Databricks dashboard to view the table stats of all the tables associated with the workspace's catalog (**300+** tables). 
- The dashboard could give information about the data lineage, the size of the table, the type of compute being used by the associated jobs, the status of the job in the past runs, partition size details, the table schema and also the type of operation being performed on the table.

##### **Business report queries**
- Hourly Sales report: A near real-time hourly report capturing essential store transaction metrics, including transaction count, units sold, and total retail revenue, across a vast network of **2000+** stores


##### _Data Engineering Analyst ~ 2020 - 2021_
##### **Data Transformations** 
- Created transformation pipelines to load tables worth over *15TB* and curate data across multiple curated layers with low latencies.
- Leveraged Spark Structured Streaming concepts to develop over *20* continuous and scheduled streaming pipelines for real-time and near real-time data.
- Created utility functions to perform common tasks such as data read-write across different file formats(csv, json, delta) and perform optimized Upserts on the target, reducing code duplication by over *40%*.


<br>
### **Betsol**

##### _Software Engineer Intern - Jan, Feb 2020_

##### **SwiftCode**: 
SwiftCode, an in-house online technical assessment platform using which the applicants could provide their technical assessment. My responsibilities included:
- UI Enhancements: 
    - Enhanced handheld device support using CSS Grid and Flex concepts.
    - Developed and improved Profile creation and update sections.
- Bug fixes: 
    - Rectified assessment timer resetting on page refresh by preserving test start and elapsed time on the server, ensuring seamless resumption from the paused point. 
    - Resolved issue of inaccurate candidate assessment progress tracking by implementing server-side parameter tracking, enhancing the overall test experience.