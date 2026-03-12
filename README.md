Project Summary

This project demonstrates a complete end-to-end Data Engineering and Business Intelligence workflow using relational datasets containing information about Artists, Albums, and Tracks. The goal of the project was to design a scalable analytics pipeline that transforms raw data into meaningful business insights using Python, data modeling techniques, and Power BI visualization.

The project begins with raw CSV datasets, which are processed using Python (Pandas) in Google Colab to perform data cleaning, transformation, and integration. After preparing the data, a star schema data model is created consisting of fact and dimension tables optimized for analytical queries.

The transformed data is then imported into Power BI, where relationships are established between tables, and DAX measures are created to calculate key business metrics such as total tracks, total artists, album counts, track popularity, and average track duration.

Finally, an interactive Power BI dashboard is built to visualize insights such as artist productivity, album release trends, genre distribution, and track popularity rankings. The dashboard enables users to explore the data through filters and dynamic visualizations, providing an intuitive view of music analytics.

This project highlights the entire analytics lifecycle, including data ingestion, transformation, data modeling, and visualization, following best practices used in real-world data engineering and BI solutions.# -Music-Analytics-End-to-End-Data-Engineering-Power-BI-Project
Project Architecture

The architecture follows a typical modern analytics pipeline, moving data from raw sources to business intelligence dashboards.
Raw CSV Datasets
(Artists, Albums, Tracks)
        │
        │
        ▼
Google Colab (Python + Pandas)
Data Ingestion & Data Cleaning
        │
        │
        ▼
Data Transformation & Integration
Join datasets using relational keys
        │
        │
        ▼
Star Schema Data Model
Fact Table + Dimension Tables
        │
        │
        ▼
Power BI Data Modeling
Relationships & DAX Measures
        │
        │
        ▼
Interactive Dashboard
Business Insights & Visualization
Tools & Technologies
| Tool         | Purpose                           |
| ------------ | --------------------------------- |
| Python       | Data Processing                   |
| Pandas       | Data Cleaning & Transformation    |
| Google Colab | Data Engineering Environment      |
| Power BI     | Data Visualization                |
| DAX          | KPI Calculations                  |
| GitHub       | Version Control & Project Hosting |
