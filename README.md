# 📊 AI-Driven Executive Business Intelligence Dashboard for SMEs
*(Bachelor's Thesis – In Progress)*

## 📝 Project Overview
This project is an automated Executive Business Intelligence (BI) Dashboard designed to support strategic decision-making for a **Villa & Cafe business**. It integrates Data Engineering, AI-driven workflow automation, and an interactive web dashboard to transform raw Point of Sale (POS) data into actionable business insights.

## 🏗️ System Architecture & Workflow
*(💡 Note: Replace this text with a brief description or an image of your workflow. e.g., `<img src="link_to_your_n8n_flowchart.png">`)*

The system operates through an end-to-end data pipeline:
1. **Data Preparation:** Raw POS data extraction and cleaning.
2. **Automation (n8n):** Scheduled data processing and transformation.
3. **AI Analysis (Google Gemini):** Generating strategic insights based on structured sales data.
4. **Presentation (Streamlit):** Secure executive dashboard with real-time interactivity.

## ✨ Key Features & System Implementation
* **Data Ingestion & Engineering:** Extracted and cleaned preliminary Point of Sale (POS) sales data using **Power Query**, handling missing values, filtering out internal staff welfare transactions, and structuring an optimized dataset of 8 core variables for enterprise analytics.
* **Automated Insights Pipeline (n8n & GenAI):** Designed and deployed an end-to-end automation workflow using **n8n** integrated with **Google Gemini AI (gemini-1.5-flash)** to autonomously process daily sales data, synthesize strategic management recommendations, and sync structured insights to a cloud database in real-time.
* **Executive Decision Support System (Streamlit BI Dashboard):** Developed a responsive, enterprise-grade web application using **Python (Streamlit)** featuring secure executive authentication (Secure Login), dynamic date filtering, and a real-time **What-If Simulation** module (price and marketing budget adjustment).
* **Advanced Analytics & Smart Monitoring:** Built 8 multi-dimensional deep-dive analytics modules using **Plotly** (covering sales trends, product mix, golden hours heatmaps, and RFM Customer Segmentation Proxy) alongside an automated **Smart Alerts** system to evaluate business health thresholds instantly.
* **Enterprise Reporting & Multi-Format Export:** Implemented custom executive tools allowing seamless data extraction and offline reporting across multiple formats (Excel, CSV, and browser-based Print-to-PDF).

## 💻 Tech Stack & Tools
* **Data Preparation:** Microsoft Excel (Power Query)
* **Workflow Automation:** n8n, Google Gemini AI (LLM)
* **Web Application:** Python, Streamlit
* **Data Visualization:** Plotly
* **Data Storage:** Google Sheets (Cloud DB)

## 📸 Screenshots / System Preview
*(💡 Note: Add screenshots of your Streamlit Dashboard here to showcase the UI)*
<details>
  <summary>Click to view system screenshots</summary>
  
  <!-- Add your image links here like this: -->
  <!-- ![Dashboard Preview](link_to_your_image.png) -->
  
</details>

## 🚧 Current Status
**In Progress:** This project is part of an ongoing Bachelor's Thesis. The core data engineering pipelines, AI automation logic, and primary dashboard functionalities have been successfully implemented. Further UI enhancements and system optimizations are currently under active development.
