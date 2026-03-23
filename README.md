# 🚀 AI-Powered Marketing Automation System

## 📌 Overview
This project is an end-to-end AI-driven marketing automation system that generates campaign content and automatically sends emails to customers.

The system integrates workflow automation, large language models (LLMs), and APIs to streamline marketing operations and reduce manual effort.

## 🎯 Problem
Businesses often struggle with:
- Time-consuming manual campaign creation
- Inconsistent marketing content
- Inefficient customer outreach

## 💡 Solution
I built an automated pipeline that:
- Generates marketing content using AI (LLM)
- Sends personalized emails automatically
- Logs campaign data for tracking and analysis

## ⚙️ System Architecture
![Workflow](./screenshots/workflow.png)
### Workflow Steps:
1. Schedule Trigger – runs automation at defined intervals  
2. Get Contacts – retrieves customer data from Google Sheets  
3. Filter Active Subscribers – selects valid users  
4. Set Campaign Brief – defines campaign content input  
5. AI Agent (Gemini) – generates marketing content  
6. Parse Response – formats AI output  
7. Send Email – sends campaigns via Gmail API  
8. Log Results – stores campaign logs in Google Sheets  

## 🧱 Tech Stack
- **Workflow Automation:** n8n  
- **Programming:** JavaScript  
- **AI / LLM:** Google Gemini API  
- **APIs & Integration:** Gmail API, Google Sheets API  
- **Data Handling:** Google Sheets  

## ✨ Key Features
- 🤖 AI-generated marketing content  
- 📧 Automated email campaign delivery  
- 🔄 End-to-end workflow automation  
- 📊 Real-time logging and tracking  
- ⚡ Scalable campaign execution  

## 🧪 Demo
### 🔹 Workflow
![Workflow](./screenshots/workflow.png)

### 🔹 Email Output
![Email](./screenshots/result.png)

## 📈 Impact
- Reduced manual marketing workload  
- Improved campaign efficiency and scalability  
- Enabled automated customer engagement  

