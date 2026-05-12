# Airlines ETL - Staging Database

A SQL Server Integration Services (SSIS) project that handles the Extract, Transform, and Load (ETL) phase of the Airlines Data Warehouse pipeline. This is the first stage of a 3-part data warehousing system.

## Project Overview
Raw airline data is extracted from source files, cleaned and transformed, then loaded into a structured SQL Server staging database — ready for the next phase of the data warehouse pipeline.

## Architecture
Raw Data (CSV/DB) → [SSIS ETL] → Staging Database (SQL Server)

## Technologies
- SQL Server Integration Services (SSIS)
- SQL Server
- T-SQL

## Part of a 3-Repo Data Warehouse System
| Repo | Role |
|------|------|
| **AirlinesLoad_Staging** (this repo) | ETL Pipeline & Staging |
| [AirlinesCube_IT23599604](https://github.com/JaneeshaPabasara/AirlinesCube_IT23599604) | Data Warehouse Cube |
| [Airlines_SSAS](https://github.com/JaneeshaPabasara/Airlines_SSAS) | OLAP Analysis & Reporting |
