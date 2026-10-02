# SQL Data Warehouse Project

A modern data warehouse built using PostgreSQL, following the **Medallion Architecture** (Bronze → Silver → Gold).

## 📌 Overview

This project demonstrates how to build a data warehouse from scratch using SQL. It ingests raw data from CRM and ERP source systems, cleans and transforms it, and produces analytics-ready datasets for reporting and business intelligence.

## 🏗️ Architecture

The project follows a three-layer Medallion Architecture:

| Layer | Purpose |
|-------|---------|
| **Bronze** | Stores raw data ingested directly from source CSV files |
| **Silver** | Stores cleaned, standardized, and transformed data |
| **Gold** | Stores business-ready data modeled as dimension and fact tables |
