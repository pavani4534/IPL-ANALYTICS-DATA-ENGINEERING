# 🏏 IPL Analytics Data Engineering Project

An end-to-end IPL data engineering and analytics project built using **Databricks, PySpark, Delta Lake, SQL, and Power BI**.

This project processes IPL datasets through a **Medallion Architecture (Bronze → Silver → Gold)** and creates analytics-ready fact and dimension tables that are used to build an interactive Power BI dashboard.

---

## 📌 Project Overview

The main objective of this project is to transform raw IPL data into clean, structured, and analytics-ready data.

The project covers:

- Data ingestion
- Data cleaning
- Data transformation
- ETL using PySpark
- Delta Lake tables
- Fact and Dimension modeling
- Power BI dashboard development
- GitHub-based project collaboration

---

## 🏗️ Architecture

```text
                IPL CSV DATA
                     │
                     ▼
              ┌─────────────┐
              │   BRONZE    │
              │  Raw Data   │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │   SILVER    │
              │ Clean Data  │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │    GOLD     │
              │ Fact + Dim  │
              └──────┬──────┘
                     │
                     ▼
              ┌─────────────┐
              │  POWER BI   │
              │  Dashboard  │
              └─────────────┘
