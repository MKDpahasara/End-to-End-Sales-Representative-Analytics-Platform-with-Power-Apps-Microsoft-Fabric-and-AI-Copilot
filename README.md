# End-to-End-Sales-Representative-Analytics-Platform-with-Power-Apps-Microsoft-Fabric-and-AI-Copilot

## Sales Representative Data Analytics Platform

### Introduction

This project demonstrates an end-to-end data analytics solution designed to capture, process, and analyze sales representative activities. It leverages Microsoft Power Platform and Microsoft Fabric to transform raw field data into actionable business insights.

<img width="721" height="546" alt="Image" src="https://github.com/user-attachments/assets/90e2d9ca-5b87-441d-9f4b-1010edd2ce70" />

### Data Collection via Power Apps

A custom-built Power App is used by sales representatives to input their daily activities. The application captures key details such as:

Sales representative name
Visit date and time
Shop name
Area
Target limits and related metrics

This ensures a structured and user-friendly data entry process.

### Data Storage in SharePoint

All collected data is stored in a SharePoint List, providing a centralized and easily accessible data source for further processing.

### Data Ingestion using Copy Data Activity

The data is ingested into Microsoft Fabric using the Copy Data Activity. This pipeline extracts data from SharePoint and loads it into the Lakehouse environment for further processing.

### Data Preprocessing with Notebooks

Data preprocessing is performed using notebooks, where the raw data is cleaned, transformed, and structured into a final dataset suitable for analysis. This step ensures data quality and consistency.

### Semantic Model and Dashboard Development

A semantic model is created on top of the processed dataset, enabling efficient querying and reporting. An interactive dashboard is developed to visualize:

Sales performance
Area-wise analysis
Target vs actual comparisons
AI Copilot Agent Integration

An AI Copilot Studio agent is integrated to enable conversational analytics. Users can interact with the system using natural language queries to retrieve insights directly from the Lakehouse data.


This project showcases how modern tools can be integrated to build a scalable and intelligent data platform. It highlights the use of low-code applications, data engineering, and AI-driven analytics to support data-driven decision-making.
