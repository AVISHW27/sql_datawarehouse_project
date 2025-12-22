# Data Warehouse & Analytics Project 🚀

Welcome! This project is a step-by-step guide to building a modern **Data Warehouse** from scratch. It covers everything from moving raw data to creating final business reports, showcasing industry-standard practices in Data Engineering and Analytics.

---

## How the Data Flows (Architecture)

We use the **Medallion Architecture**, which organizes data into three simple stages:

1. **Bronze Layer (Raw Data)**: We take data exactly as it is from CSV files and load it into the SQL Server. No changes are made here.
2. **Silver Layer (Cleaned Data)**: We fix errors, remove duplicates, and format the data so it is consistent and reliable.
3. **Gold Layer (Business Ready)**: We organize the data into "Star Schemas" (Fact and Dimension tables). This layer is optimized specifically for fast reporting and dashboards.

<img width="1277" height="662" alt="image" src="https://github.com/user-attachments/assets/4c9a9dff-147e-4712-ba31-61a85a830935" />


---

## 📖 Project Highlights

In this project, you will find:

* **Architecture Design**: Building a warehouse using the Bronze, Silver, and Gold method.
* **ETL Pipelines**: Learning how to Extract, Transform, and Load data efficiently.
* **Data Modeling**: Designing tables that make complex data easy to understand.
* **Insights & Analytics**: Using SQL to answer real-world business questions.

---

## 🛠️ Tools You’ll Need

The best part? Every tool used in this project is **FREE**:

* **SQL Server Express**: To host your database.
* **SSMS**: The main software used to write and run SQL queries.
* **DrawIO**: To design and visualize the data flow.
* **GitHub**: To track your code and show off your work.
* **Notion**: To stay organized with project tasks.

---

## 🚀 Project Goals

### Phase 1: Data Engineering

The goal is to build a solid foundation. We take data from two different systems (**CRM** and **ERP**) and combine them into one single, high-quality source of truth. We focus on data quality and clear documentation so that anyone can understand the model.

### Phase 2: Data Analytics

Once the warehouse is ready, we use SQL to find out:

* **Customer Trends**: Who are our best customers?
* **Product Success**: Which products are driving the most revenue?
* **Sales Growth**: How is the business performing over time?

---

## 📂 Folder Structure

* `datasets/`: The original CSV files (Raw Data).
* `scripts/`:
* `bronze/`: Scripts to load raw data.
* `silver/`: Scripts to clean and fix data.
* `gold/`: Scripts for the final reporting models.


* `tests/`: Scripts to check if the data is accurate.

