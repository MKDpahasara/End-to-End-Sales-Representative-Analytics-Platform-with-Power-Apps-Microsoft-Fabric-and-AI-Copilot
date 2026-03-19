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

<img width="191" height="340" alt="Image" src="https://github.com/user-attachments/assets/ed7d9dbf-9402-4df5-9b47-908c98d37a99" />

This ensures a structured and user-friendly data entry process.

### Data Storage in SharePoint

All collected data is stored in a SharePoint List, providing a centralized and easily accessible data source for further processing.

### Data Ingestion using Copy Data Activity

The data is ingested into Microsoft Fabric using the Copy Data Activity. This pipeline extracts data from SharePoint and loads it into the Lakehouse environment for further processing.

<img width="918" height="261" alt="Image" src="https://github.com/user-attachments/assets/fb0344c6-66dc-4744-baa0-7271b5ac85ad" />

### Data Preprocessing with Notebooks

Data preprocessing is performed using notebooks, where the raw data is cleaned, transformed, and structured into a final dataset suitable for analysis. This step ensures data quality and consistency.

<img width="554" height="413" alt="Image" src="https://github.com/user-attachments/assets/299dbf10-2ca9-4ca2-b303-108f8adce5a0" />

### Semantic Model and Dashboard Development

A semantic model is created on top of the processed dataset, enabling efficient querying and reporting. An interactive dashboard is developed to visualize:

Sales performance
Area-wise analysis
Shop-wise analysis


<img width="728" height="398" alt="Image" src="https://github.com/user-attachments/assets/0c7070dd-308d-4354-a9cb-a1d0c819bafd" />

An AI Copilot Studio agent is integrated to enable conversational analytics. Users can interact with the system using natural language queries to retrieve insights directly from the Lakehouse data.

<img width="821" height="463" alt="Image" src="https://github.com/user-attachments/assets/0755c7da-80cb-4a5f-aaf1-6bc78ce8dc53" />

This project showcases how modern tools can be integrated to build a scalable and intelligent data platform. It highlights the use of low-code applications, data engineering, and AI-driven analytics to support data-driven decision-making.
