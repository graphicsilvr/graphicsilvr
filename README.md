# Hi, I'm Sylvion 👋
 
**Data Platform Architect · Microsoft Fabric & Azure · Implementation-Led**
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sylvion%20Finisie-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sylvion-finisie-124399205)
[![DataCamp](https://img.shields.io/badge/DataCamp-Certified-03EF62?style=flat-square&logo=datacamp&logoColor=white)](https://www.datacamp.com/portfolio/virtualsenzu)
[![Virtual Labs](https://img.shields.io/badge/Virtual%20Labs-Founder-5C2D91?style=flat-square&logo=microsoftazure&logoColor=white)](https://www.labsvirtual.com)
 
---
 
I design and deliver end-to-end data platforms for enterprise clients in **healthcare, government, and energy** — from architecture through working pipelines.
 
My work runs the full stack: medallion architecture (bronze–silver–gold), OneLake integration, ELT/ETL automation, self-service BI, and DataOps. I combine hands-on implementation with a product mindset — I think in systems, not just scripts.
 
> *"I build innovative platforms that bridge data analytics, automation, and AI."*

For a full work history, certifications, and client references → LinkedIn · CV available on request via support@labsvirtual.com

---
 
## 🏗️ Projects & Builds
 
> Most projects are in active development. Each has an architecture doc or folder structure below — full code and READMEs publish as builds complete.
 
---
 
### 🔧 Retail-Intelligence-Platform
![Status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Python%20%7C%20Flask%20%7C%20CLI-3776AB?style=flat-square)
 
CLI inventory management tool with a Flask web front-end in progress.
 
```
octo-inventory-management/
├── cli/
│   ├── main.py           # Entry point
│   ├── commands/         # buy, sell, report, export
│   └── models/           # Product, Transaction, Report
├── web/                  # Flask front-end (in progress)
│   ├── app.py
│   ├── templates/
│   └── static/
├── data/
│   └── inventory.csv
├── tests/
└── README.md
```
 
---
 
### ☁️ Azure DevOps & Automation Suite
![Status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Azure%20%7C%20Docker%20%7C%20CI%2FCD-0078D4?style=flat-square)
 
CI/CD pipelines, workflow automation, and container orchestration for Virtual Labs infrastructure.
 
```
azure-devops-suite/
├── pipelines/
│   ├── build.yml         # Azure DevOps build pipeline
│   ├── deploy.yml        # Release to Azure Container Instances
│   └── pr-checks.yml     # Pull request validation
├── infrastructure/
│   ├── main.bicep        # IaC: resource group, ACR, ACI
│   └── parameters/
├── containers/
│   ├── Dockerfile
│   └── docker-compose.yml
├── scripts/
│   └── setup.sh
└── README.md
```
 
---
 
### 🏭 Labs Virtual — Data Platform Accelerator (Medallion Architecture)
![Status](https://img.shields.io/badge/status-architecture%20phase-blue?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Microsoft%20Fabric%20%7C%20PySpark%20%7C%20KQL-purple?style=flat-square)
 
Internal data platform built on Microsoft Fabric. Implements the medallion pattern with OneLake as the storage layer.
 
```
virtual-labs-platform/
├── bronze/               # Raw ingestion layer
│   ├── ingest_api.py     # REST / webhook ingestion
│   └── ingest_files.py   # Blob / SharePoint landing
├── silver/               # Cleaned & conformed layer
│   ├── transform.py      # PySpark transformation jobs
│   └── schema/           # Delta schema definitions
├── gold/                 # Aggregated / BI-ready layer
│   ├── semantic_model/   # Power BI dataset definitions
│   └── kql_queries/      # KQL for real-time analytics
├── pipelines/
│   ├── adf_templates/    # Azure Data Factory templates
│   └── fabric_notebooks/ # Fabric notebook configs
├── docs/
│   ├── architecture.md   # Full architecture document
│   └── diagrams/         # Draw.io / Mermaid diagrams
└── README.md
```
 
---
 
## ⚡ Tech Stack
 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-742774?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
 
---
 
## 🏅 Certifications
 
| Certification | Issuer | Year |
|---|---|---|
| Microsoft Fabric Analytics Engineer Associate | Microsoft | 2026 |
| Azure Fundamentals (AZ-900) | Microsoft | 2024 |
| Azure Data Fundamentals (DP-900) | Microsoft | 2023 |
 
---
 
## 🌍 Find me
 
| Platform | Link | Purpose |
|---|---|---|
| LinkedIn | [sylvion-finisie](https://www.linkedin.com/in/sylvion-finisie-124399205) | Full profile & endorsements |
| DataCamp | [virtualsenzu](https://www.datacamp.com/portfolio/virtualsenzu) | Certified portfolio & data projects |
| Virtual Labs | [labsvirtual.com](https://www.labsvirtual.com) | Data Platform Architecture Studio |
| Virtual Silvr | [labsvirtual.com](https://www.virtualsilvr.com) | Markets Intelligence |
| Email | [support@labsvirtual.com](mailto:support@labsvirtual.com) | Direct contact |
 
---
 
## 📅 Book a meeting
 
Want to talk data engineering, Microsoft Fabric, or a potential collaboration?
 
🔗 **[Schedule via Microsoft Bookings](https://outlook.office.com/bookwithme/user/b6d131eccaf2459e8f5c13203b50c751@virtualsilvr.com/meetingtype/20QamxUfJ0G6ofZlp8Pitw2?anonymous&ep=mlink)**
 
---
 
Haarlem, Netherlands
