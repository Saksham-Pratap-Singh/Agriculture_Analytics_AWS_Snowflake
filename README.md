# 🌾 Agriculture Analytics: AWS & Snowflake

### 🚀 Project Overview
This project demonstrates a scalable cloud-based data analytics pipeline designed to analyze agricultural data. The solution utilizes **Amazon Web Services (AWS)** for cloud storage, **Snowflake** for data warehousing and transformation, and visualization tools to derive actionable insights regarding crop yields, farming costs, and production trends.

### 🛠 Tech Stack
* **Cloud Storage:** AWS S3 (Simple Storage Service)
* **Data Warehouse:** Snowflake
* **Query Language:** Snowflake SQL
* **Visualization:** Microsoft Power BI
* **Data Source:** Flat files (CSV/Excel)

### 📊 Project Workflow
1.  **Data Ingestion (AWS S3):** * Raw agricultural datasets were uploaded to an **AWS S3 bucket** to act as the Data Lake.
2.  **Data Warehousing (Snowflake):** * Configured **Storage Integrations** and **Stages** in Snowflake to securely access S3 data.
    * Created **File Formats** and **Pipes** (or `COPY INTO` commands) to load data into Snowflake tables.
3.  **Data Transformation:** * Utilized **SQL** within Snowflake to clean, normalize, and aggregate the raw data for analysis.
4.  **Visualization:** * Connected the visualization tool to the Snowflake instance to build an interactive dashboard.

### 📂 Repository Structure
| File | Description |
| :--- | :--- |
| **`Agriculture_Report.pbix`** | 📈 **Dashboard File**. Interactive report visualizing the key metrics. |
| **`Snowflake_Queries.sql`** | ❄️ **SQL Script**. Contains the DDL (Table creation) and DML (Data loading/transformation) logic used in Snowflake. |
| **`AWS_Setup_Guide.pdf`** | ☁️ **Documentation**. Steps taken to configure AWS S3 buckets and IAM roles. |
| **`Agriculture_Data.csv`** | 💾 Raw dataset containing crop, region, and production metrics. |
| **`Project_Screenshots.pdf`** | 🖼️ **Visual Preview**. Static images of the final dashboard and Snowflake console. |

*(Note: Please verify the exact filenames above match your repository files)*

### 💡 Key Insights Generated
* **Production Trends:** Analysis of crop production over time across different regions.
* **Cost Efficiency:** Comparison of farming costs vs. output value.
* **Regional Performance:** Identification of high-yield farming zones.

---
*Created by [Saksham Pratap Singh](https://github.com/Saksham-Pratap-Singh)*
