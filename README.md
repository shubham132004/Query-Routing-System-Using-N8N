# Query-Routing-System-Using-N8N


https://github.com/user-attachments/assets/8d2b7458-259e-411f-a3b7-6cce2a6c1634


# Agentic AI Query Automation System using n8n & Google Gemini

An automated, AI-powered workflow built using **n8n**, **Google Gemini**, **Google Forms**, and **Google Sheets** to streamline student query management.  
This system intelligently classifies queries, detects urgency, identifies the correct department, and sends automated email responses — reducing manual workload and improving response time.

---

## 🚀 Project Overview

This project automates the entire lifecycle of handling student queries for educational institutes.  
From sending the query form to routing each issue to the correct department, everything is handled by an Agentic AI workflow powered by n8n.

---

## 🧩 Workflow Breakdown

### **1️⃣ Sending Query Form to Students**
The workflow begins by emailing a Google Form link to all registered students.

---

### **2️⃣ Google Forms → Google Sheets Integration**
When a student submits the form, the response updates Google Sheets.  
This update triggers the main n8n workflow.

---

### **3️⃣ Sentiment Analysis with Google Gemini**
Each incoming query is processed using the **Google Gemini Chat Model** to classify it into:

- 🔥 Urgent  
- 📘 Normal  

This helps prioritize and route critical issues faster.

---

### **4️⃣ Category Detection with LLM Chain**
Both urgent and normal queries are forwarded to a **Basic LLM Chain (Gemini)** to identify the specific category such as:

- Placement  
- WiFi Issues  
- Certificate Requests  
- Technical Support  
- NASSCOM  
- Batch Change  
- LMS Access  
- Assignments  
- Payment Issues  
- Tasks  

---

### **5️⃣ Smart Switch Routing**
A **Switch Node** evaluates the identified category and automatically sends the query to the corresponding department through email.

Each department has a dedicated email node to ensure accurate and timely communication.

---

## 🎯 Key Features

- ✔ Fully automated query handling  
- ✔ AI-driven sentiment and category classification  
- ✔ Smart departmental routing  
- ✔ Reduces manual workload  
- ✔ Improves student satisfaction  
- ✔ Built using open-source n8n automation  

---

📁 Workflow JSON File
You can find the exported n8n workflow JSON here: https://github.com/shubham132004/Query-Routing-System-Using-N8N/tree/main/JSON%20FILE



## 🛠️ Tech Stack

- **n8n** (Automation platform)  
- **Google Forms**  
- **Google Sheets**  
- **Google Gemini Model**  
- **LLM Chain**  
- **SMTP Email / Gmail**  

---

## 🖥️ Workflow Architecture

<img width="430" height="179" alt="Screenshot 2025-11-17 134938" src="https://github.com/user-attachments/assets/38342f7c-9d4d-485a-b615-f5e5b7c3e413" />



