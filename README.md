# Microsoft Fabric Dataflow (Gen2) Project

This project demonstrates how to use **Dataflows (Gen2)** in Microsoft Fabric to ingest data into a Lakehouse and orchestrate the process using a Data Pipeline.

## 💡 Overview

The following steps were completed as part of this exercise:

1. **Created a Fabric-enabled Workspace**
2. **Created a Lakehouse in the Workspace**
3. **Created a Dataflow Gen2** that:
   - Imported data from a public CSV file
   - Applied a transformation to extract the month from `OrderDate`
4. **Set the Lakehouse as the data destination**
5. **Published the Dataflow**
6. **Created a Data Pipeline** with the Dataflow as an activity
7. **Ran the Pipeline** to load data into the Lakehouse
8. **Verified** the `orders` table was created successfully in the Lakehouse

## 📸 Screenshots

Screenshots of each step can be found in the `/screenshots` folder:

- `step1_workspace.png` – Creating the workspace
- `step2_lakehouse.png` – Creating the lakehouse
- `step3_dataflow_source.png` – Importing data into Dataflow
- `step4_custom_column.png` – Adding MonthNo column
- `step5_lakehouse_destination.png` – Setting lakehouse destination
- `step6_publish_dataflow.png` – Publishing the Dataflow
- `step7_pipeline_create.png` – Creating the pipeline
- `step8_pipeline_run.png` – Running the pipeline
- `step9_orders_table.png` – Verifying the table in lakehouse

## 🔧 Tools Used

- Microsoft Fabric (Trial)
- Power Query Online
- Dataflows Gen2
- Lakehouse
- Data Pipelines
- Power BI (optional for analysis)

## ✅ Outcome

A working ETL process using Microsoft Fabric’s Dataflow Gen2 and Pipelines was successfully created, tested, and verified.

---

🧪 *Note: This setup is for educational purposes and simulates enterprise data processing workflows.*
