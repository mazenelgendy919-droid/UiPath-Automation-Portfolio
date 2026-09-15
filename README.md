# Enterprise UiPath RPA & Automation Portfolio 🤖⚙️

A production-grade portfolio showcasing end-to-end **Robotic Process Automation (RPA)** solutions and **GenAI Workflows** engineered using **UiPath Studio**, **REFramework**, and **UiPath Orchestrator**.

---

## 🏗️ Architecture & Core Engineering Concepts

* **Robotic Enterprise Framework (REFramework)**: Standardized state-machine architecture ensuring transactional isolation, automated initialization, and error recovery.
* **Orchestrator Queue Management**: Enterprise Producer/Consumer (Dispatcher/Performer) pattern utilizing Orchestrator Queues for scalable batch processing.
* **Exception Handling Architecture**: Strict decoupling of **Business Rule Exceptions** (data validation) and **System Exceptions** with automated retry mechanisms.
* **UI Selector Intelligence**: Implementation of anchor-based navigation, dynamic selectors, and fuzzy matching for unstable DOM environments.

---

## 📂 Enterprise Projects & Workflow Solutions

### 1. 🏬 ACME System 1 — WI5 Queue Dispatcher
* **Directory**: [MidTerm_ACME_Dispatcher_WI5](./MidTerm_ACME_Dispatcher_WI5)
* **Architecture**: REFramework (Producer Pattern)
* **Technical Scope**: Handles secure authentication to ACME System 1, scrapes Work Items, filters pending WI5 transaction items, and dispatches dynamic payloads into Orchestrator Queues.

### 2. ⚡ ACME System 1 — WI5 Transaction Performer
* **Directory**: [MidTerm_ACME_Performer_W15](./MidTerm_ACME_Performer_W15)
* **Architecture**: REFramework (Consumer Pattern)
* **Technical Scope**: Consumes queue transactions, extracts client metadata, computes SHA-256 security hash keys, updates ACME System 1 status, and logs execution analytics.

### 3. 📧 GenAI Automated Email Processing Agent
* **File**: [Final_Email_Summarizer_Agent.uis](./Final_Email_Summarizer_Agent.uis)
* **Technology**: UiPath Integration Service & Generative AI Workflow
* **Technical Scope**: Monitors incoming communication channels, performs intent extraction, generates structured summaries using GenAI models, and executes automated replies.

### 4. 🎯 Dynamic Web Form Automation Engine (RPA Challenge)
* **Directory**: [Task1_RPAChallenge_Automation](./Task1_RPAChallenge_Automation)
* **Technical Scope**: High-speed dynamic UI automation designed to navigate shifting input fields and changing DOM element attributes without losing selector accuracy.

### 5. 🎓 Automated Academic Onboarding & Data Validation System
* **Directory**: [Task2_StudentRegistration_Name](./Task2_StudentRegistration_Name)
* **Technical Scope**: Automated batch registration pipeline parsing structured Excel sheets, validating input constraints, and handling multi-step web entries.

### 6. 🧮 Desktop Application Control & Math Automation
* **Directory**: [Task3_Calculator_Automation](./Task3_Calculator_Automation)
* **Technical Scope**: Native desktop UI automation interacting with Windows application controls, verifying system outputs, and generating audit logs.

### 7. 🎬 IMDb Data Scraping & Analytics Pipeline
* **Directory**: [Task4_IMDb_Movie_Rating_Automation](./Task4_IMDb_Movie_Rating_Automation)
* **Technical Scope**: Automated web scraping workflow extracting movie ratings and metadata, transforming un-structured web data into formatted analytical datasets.

---

## 🛠️ Technical Stack & Tools

* **RPA Engine**: UiPath Studio 2024+, UiPath Orchestrator, UiPath Assistant
* **Design Patterns**: State Machine, REFramework, Dispatcher-Performer Pattern
* **Automation Types**: Web Automation, Desktop UI Automation, Data Extraction, GenAI (.uis)
* **Integrations**: Excel/CSV, Orchestrator Assets & Queues, Web Scraping
