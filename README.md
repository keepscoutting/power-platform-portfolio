# Long Au | Power Platform & Application Support Portfolio

Welcome to my technical portfolio. I am a **Power Platform Developer** experienced in designing, deploying, and supporting business-critical Microsoft Power Platform solutions (**Power Apps, Power Automate, Power BI, Dataverse, SharePoint**) for **500+ users across UK and Irish operations**.

*🔒 **Confidentiality & GDPR Note:** Because these solutions were architected for enterprise production environments, all screenshots, schemas, and Power Fx (`.fx.yaml`) code snippets in this repository have been sanitized and anonymized.*

---

## 🚀 Featured Enterprise Projects

1. **Travel Request & Dynamic Policy Management Solution** *(Power Apps, Power Automate, Dynamic Rule Engine, In-App Chat)*
2. **Social Values & Sustainability Compliance Tracker - Transport Scotland Contract** *(Power Apps, Power Automate, Contractual Reporting)*
3. **Enterprise Staff Holiday & Leave Management System - 500+ Users** *(Power Apps, Multi-Tier Approval Matrix, Calendar Sync, Support Runbooks)*

---
## 🏗️ Project 1: Travel Request & Policy Management Solution

### Architecture & Workflow
```mermaid
graph LR
    A[Travelling Staff - Power Apps] --> B{Dynamic Policy Rule Engine}
    B -->|Compliant| C[Power Automate Approval Flow]
    B -->|Out of Policy| D[Justification & Escalation Routing]
    A <--> E[In-App Real-Time Chat Module]
    C --> F[(Backend Data Store)]
    D --> C
