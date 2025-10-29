# 🧠 N8N Quote Orchestrator Workflow

## Overview
The **N8N Quote Orchestrator** is an intelligent automation workflow designed to manage and streamline the generation of detailed, AI-assisted service quotes.  
It acts as the **core orchestration layer**, coordinating data intake, retrieval, and AI-powered generation using a **Supabase vector store** for advanced context management.

This workflow performs **multi-step reasoning and routing**, ensuring that each quote request is classified, contextually enriched, and expanded into a comprehensive, professional output.

![Workflow Screenshot](https://github.com/user-attachments/assets/39c211ac-4190-4d31-a0c1-f5641091ab95)

---

## ⚙️ Key Functional Components

### 1. Request Routing & Intake
- Captures incoming quote requests from multiple service channels  
  *(WordPress, Webflow, Ecommerce, GHL, etc.)*  
- Classifies the service type and routes the request to the appropriate processing branch.  
- Conducts **targeted intake questioning** to collect detailed project requirements and goals.

---

### 2. Data Feeding into Supabase Vector Store
- Extracts relevant documents, historical data, and context from quote submissions.  
- Embeds all information into the **Supabase vector database** for efficient retrieval.  
- Enables **multi-pass Retrieval-Augmented Generation (RAG)** by allowing semantic searches and contextual lookups.  
- Continuously updates the vector store for improved AI performance and knowledge accuracy.

---

### 3. AI-Powered Quote Generation
- Leverages retrieved vector data to produce **comprehensive 1200+ word quotes**.  
- Ensures professional structure, contextual accuracy, and completeness.  
- Includes **hours estimation (no pricing)** to support transparent project planning.  

---

### 4. Multi-Pass RAG Retrieval Process
- Executes multiple retrieval passes to refine context and improve precision.  
- Incorporates prior client data, related projects, and contextual records to strengthen each generated quote.  

---

### 5. Output Assembly & Delivery
- Combines generated content, retrieved data, and metadata into a unified quote document.  
- Formats the final output for easy review, approval, or client delivery.

---

## 🚀 Purpose & Benefits
- **Automates** end-to-end quote generation.  
- **Enhances accuracy** with semantic, vector-based retrieval.  
- **Saves time** through intelligent intake and routing automation.  
- **Generates professional, long-form outputs** ideal for proposals and client communications.  
- **Continuously improves** via iterative learning and data enrichment in Supabase.

---

## 🧩 Tech Stack
- **n8n** – Workflow orchestration and automation engine  
- **Supabase Vector Store** – Context storage and semantic retrieval  
- **OpenAI / GPT Agent** – AI reasoning and long-form quote generation  
- **Webflow / WordPress / GHL** – Input sources and service routing  

---
