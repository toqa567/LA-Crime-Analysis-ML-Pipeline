🚔 Los Angeles Crime Data: End-to-End Analysis & Visual Insights
📌 Project Overview
This project represents a comprehensive analytical pipeline for the "Crime Data from 2020 to Present" dataset. It demonstrates a full data science lifecycle, from complex cleaning in Python to interactive storytelling in Power BI.

📊 Interactive Dashboard Showcase
Since the full .pbix file is large, I have documented the key analytical views below to provide a transparent look into the findings.

1. Executive Summary & Trends
This view provides a high-level overview of crime volumes (over 925K records) and their progression over the years.

Key Visuals: Time-series analysis of crime counts and a treemap breakdown of crime categories.

2. Geospatial & District Analysis
Mapping the crimes allowed for identifying "Hot Zones" and analyzing how different police districts respond to report volumes.

Key Visuals: Map visualization of crime coordinates and report delay analysis by district.

3. Demographic & Weaponry Insights
A deep dive into victim demographics and the types of weapons used across different areas of Los Angeles.

Key Visuals: Victim descent/sex distribution and frequency of weapons used by area.

⚙️ Technical Deep Dive
Data Engineering (Python): Implemented custom address parsing, IQR-based coordinate filtering, and regex text normalization.

Advanced Modeling: Developed and compared Random Forest and Logistic Regression models for crime classification.

Visualization (Power BI): Created multi-page interactive reports with complex DAX measures for dynamic filtering.# LA-Crime-Analysis-ML-Pipeline
