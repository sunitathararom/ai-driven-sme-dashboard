# 📊 AI-Driven Executive Business Intelligence Dashboard for SMEs
*(Bachelor's Thesis – In Progress)*

## 📝 Project Overview
This project is an automated Executive Business Intelligence (BI) Dashboard designed to support strategic decision-making for a **Villa & Cafe business**. It integrates Data Engineering, AI-driven workflow automation, and an interactive web dashboard to transform raw Point of Sale (POS) data into actionable business insights.

## 🏗️ System Architecture & Workflow
<img width="1623" height="535" alt="Screenshot 2026-07-27 192837" src="https://github.com/user-attachments/assets/90d5b502-501e-4c0d-a46b-dd2582df1f76" />


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
<details>
  <summary><b>Click to view system screenshots</b></summary>
  
  <br>

  **1. Executive Dashboard Overview**
  <p><i>หน้าจอแสดงภาพรวมยอดขายรายวันและสถิติสำคัญของธุรกิจ</i></p>
  <img alt="Dashboard Overview" src="https://github.com/user-attachments/assets/5d0125f6-ccb6-400e-9f57-dcbc31f4b6fa" width="800" />
  
  <br><br>
  <hr>
  <br>

  **2. Advanced Analytics & Plotly Charts**
  <p><i>โมดูลวิเคราะห์ข้อมูลเชิงลึก 8 มิติ (คุณสามารถดูรายละเอียดแต่ละกราฟได้ด้านล่าง)</i></p>
  
  *📊 2.1 Sales Trends & Revenue Analysis (วิเคราะห์แนวโน้มยอดขาย)*
  <img alt="Plotly Chart 1" src="https://github.com/user-attachments/assets/d8482707-2605-4550-8f7b-dfc851921bd7" width="800" />
  <br><br>

  *📦 2.2 Product Mix & Category Performance (วิเคราะห์หมวดหมู่สินค้าขายดี)*
  <img alt="Plotly Chart 2" src="https://github.com/user-attachments/assets/06707a38-c6c2-47ff-a6d5-fd8de9c249a7" width="800" />
  <br><br>

  *🕒 2.3 Golden Hours Heatmap (วิเคราะห์ช่วงเวลาที่มียอดขายสูงสุด)*
  <img alt="Plotly Chart 3" src="https://github.com/user-attachments/assets/c5d98cf3-830b-452c-a5d6-943a243781a9" width="800" />
  <br><br>

  *👥 2.4 Customer Segmentation / RFM Proxy (วิเคราะห์พฤติกรรมลูกค้า)*
  <img alt="Plotly Chart 4" src="https://github.com/user-attachments/assets/9aff8b95-4bda-4b11-bea5-931ab7c8b9a9" width="800" />
  <br><br>

  *📈 2.5 Business Health & Growth Metrics (สถิติการเติบโตของธุรกิจ)*
  <img alt="Plotly Chart 5" src="https://github.com/user-attachments/assets/8f9dba34-ebc4-4c68-b577-3c247348e2db" width="800" />
  <br><br>

  *🛒 2.6 Average Order Value / Ticket Size (วิเคราะห์มูลค่าเฉลี่ยต่อบิล)*
  <img alt="Plotly Chart 6" src="https://github.com/user-attachments/assets/3242b8fc-fb5c-431a-be72-72a97d663271" width="800" />
  <br><br>

  *🎯 2.7 Cross-Selling Opportunities (วิเคราะห์โอกาสในการขายพ่วง)*
  <img alt="Plotly Chart 7" src="https://github.com/user-attachments/assets/84f5694b-5151-4b02-b296-d4b6f05137f8" width="800" />
  <br><br>

  *📊 2.8 Comprehensive Data Breakdown (ข้อมูลเชิงลึกสรุปรายวัน)*
  <img alt="Plotly Chart 8" src="https://github.com/user-attachments/assets/a606c32a-3c54-499a-b4c5-262fc651d08f" width="800" />
  
  <br><br>
  <hr>
  <br>

  **3. What-If Simulation Module**
  <p><i>หน้าต่างจำลองสถานการณ์เพื่อคาดการณ์ผลกำไรจากการปรับราคาและงบการตลาด</i></p>
  <img alt="What-If Simulation" src="https://github.com/user-attachments/assets/37c6573c-806b-4e62-9a66-8769b6126de0" width="800" />
  
</details>

## 🚧 Current Status
**In Progress:** This project is part of an ongoing Bachelor's Thesis. The core data engineering pipelines, AI automation logic, and primary dashboard functionalities have been successfully implemented. Further UI enhancements and system optimizations are currently under active development.
