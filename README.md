🔍 KQL Queries for OSINT & Data Analysis

Welcome to the KQL Queries Repository! 🚀 This repository is designed for public sharing of Kusto Query Language (KQL) queries, particularly for OSINT (Open-Source Intelligence), log analysis, and data enrichment using CSV files and various data sources.

📌 About

This repository contains a collection of KQL queries useful for:

✅ OSINT Investigations
✅ Security & Threat Hunting
✅ Log & Event Analysis
✅ CSV & Data Enrichment
✅ Azure Sentinel & Log Analytics
✅ Microsoft Defender Data Exploration

📑 CSV Data Import & Analysis
let csv_data = externaldata(type:string, value:string, source:string )
['https://github.com/mattie1/KQL/blob/main/DefenderOSINT10Mar.csv']
with (format='csv');
