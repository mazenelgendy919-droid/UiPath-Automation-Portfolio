# Enterprise UiPath RPA & GenAI Portfolio 🤖⚙️

A production-grade portfolio showcasing end-to-end **Robotic Process Automation (RPA)** solutions and **Generative AI Workflows** engineered using **UiPath Studio**, **UiPath Studio Web**, **REFramework**, and **UiPath Orchestrator**.

---

## 📌 Executive Summary

This repository demonstrates the integration of enterprise-level automation patterns to streamline back-office operations:
* **Transactional Reliability**: Leveraging the REFramework (State Machine) to ensure robust exception handling, data validation, and auto-retry logic.
* **Scalable Queue Management**: Utilizing Orchestrator Queues in a Producer/Consumer (Dispatcher/Performer) architecture for asynchronous processing.
* **GenAI & Integration Services**: Automating unstructured communications via LLM intent extraction and decision workflows in UiPath Studio Web.
* **Resilient UI Automation**: Handling dynamic DOM selectors, web scraping, and native desktop app interactions.

---

## 📂 Featured Automation Projects

### 1. 🏬 [ACME System 1 — WI5 Queue Dispatcher](./ACME-Dispatcher-WI5/)
* **Type**: REFramework Producer Architecture
* **Summary**: Authenticates to ACME System 1, scrapes pending Work Items (WI5), and dispatches structured transaction payloads into Orchestrator Queues.

### 2. ⚡ [ACME System 1 — WI5 Transaction Performer](./ACME-Performer-WI5/)
* **Type**: REFramework Consumer Architecture
* **Summary**: Consumes Queue transactions, extracts client details, computes SHA-256 security hashes, and updates ACME transaction status with full error logging.

### 3. 📧 [GenAI Email Processing Agent](./Final_Email_Summarizer_Agent.uis)
* **Type**: UiPath Studio Web & Integration Service (.uis Package)
* **Summary**: Monitors incoming emails, extracts intent using Generative AI, drafts automated context-aware responses, and routes actions. *(Download .uis file to import into UiPath Studio Web)*.

### 4. 🎯 [Dynamic Web Form Automation Engine](./Dynamic-Form-Automation/)
* **Type**: Web Automation (RPA Challenge)
* **Summary**: High-speed dynamic UI form processing handling shifting input fields and dynamic DOM element attributes without losing selector accuracy.

### 5. 🎓 [Academic Onboarding & Data Validation System](./Student-Registration-System/)
* **Type**: Data Entry & Validation Pipeline
* **Summary**: Automated pipeline reading structured datasets, validating constraint logic, and registering student records across web portals.

### 6. 🧮 [Desktop Application Control & Math Automation](./Desktop-Calculator-Automation/)
* **Type**: Desktop UI Automation
* **Summary**: Interacts natively with Windows desktop application controls, performs numerical verification, and generates system audit logs.

### 7. 🎬 [IMDb Data Scraping & Analytics Pipeline](./IMDb-Data-Scraping-Pipeline/)
* **Type**: Web Scraping & Data Extraction
* **Summary**: Automated data extraction pipeline gathering movie ratings, metadata, and structuring unstructured web content for downstream analytics.

---

## 🛠️ Stack & Tools
* **RPA Software**: UiPath Studio, UiPath Studio Web, UiPath Orchestrator
* **Architecture Patterns**: REFramework (State Machine), Dispatcher/Performer Pattern, Queue Management
* **Integrations**: Generative AI Models, Web Scraping, Excel/CSV Processing, Desktop Applications
