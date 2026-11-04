# Hi, I'm Sylvion 👋

**Builder · Data Platform Architect · End to End Engineer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sylvion%20Finisie-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sylvion-finisie-124399205)
[![Labs Virtual](https://img.shields.io/badge/Labs%20Virtual-Data%20Platform%20Studio-5C2D91?style=flat-square&logo=microsoftazure&logoColor=white)](https://www.labsvirtual.com)
[![Virtual Silvr](https://img.shields.io/badge/Virtual%20Silvr-Markets%20Intelligence-1a1a2e?style=flat-square&logo=chartdotjs&logoColor=white)](https://markets.virtualsilvr.com)

---

Virtual Silvr started as IT consulting.

Labs Virtual started as a personal environment to build, test, and validate independently, without depending on client access or approval cycles to the portals like Azure, Microsoft Fabric or Databricks environments or Foundry AI to deploy Data & AI workloads.

It became the place where I visualise and ship what I implement for clients.

The idea that became a lab became a studio. Virtual Silvr grew out of the same thinking: consulting work that turned into a fintech product.

Labs Virtual now builds and manages these platforms at enterprise grade.

**[Labs Virtual](https://www.labsvirtual.com)** is a Microsoft Solutions Partner and ISV — an independent data product studio. It builds enterprise data platforms for clients on Microsoft Fabric and Databricks, and runs its own intelligence products: a weekly AI publication, a scored company index, and a markets platform — all backed by the same data infrastructure.

**[Virtual Silvr](https://markets.virtualsilvr.com)** is the investing layer of that intelligence suite: pre-IPO AI intelligence, company profiles, watchlists and market data for the AI companies tracked across the platform. Next.js front-end, Python/Django API, Azure AI Foundry. Published on the Azure Marketplace.

Stack: Microsoft Fabric · Databricks · Python / PySpark · FastAPI · Next.js · Bicep / Terraform · GitHub Actions · Power BI Direct Lake

> *Data into direction. Complexity into clarity.*

---

## Products

### [Labs Virtual](https://www.labsvirtual.com) — Data Product Studio
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![Partner](https://img.shields.io/badge/Microsoft-Solutions%20Partner%20%C2%B7%20ISV-5C2D91?style=flat-square&logo=microsoftazure&logoColor=white)

Builds and manages digital platforms — from architecture design through production operations. Enterprise data infrastructure on Microsoft Fabric and Databricks; own intelligence products tracking AI companies from Asia and Europe; managed web and commerce platforms for clients.

**Platform portfolio**

| Platform | Description | Phase |
|---|---|---|
| [insights.labsvirtual.com](https://insights.labsvirtual.com) | READ — Weekly AI publication. Company tracking from Asia & Europe, research papers, tools tested. | 🟢 live |
| [index.labsvirtual.com](https://index.labsvirtual.com) | MEASURE — AI companies index. 23 companies scored on adoption, value, EU readiness and momentum. | 🔵 live · populating |
| [markets.virtualsilvr.com](https://markets.virtualsilvr.com) | INVEST — Pre-IPO AI intelligence. Company profiles, watchlists and market data. Published on Azure Marketplace. | 🟡 live · investment |
| [finisiea.nl](https://www.finisiea.nl) | MANAGED — NL tea-infusions webshop. WooCommerce storefront; Labs Virtual platform engagement. | 🟢 managed · active |

A part of this work is hosted here on GitHub. The data platform work — organisational demos, proofs of concept and enterprise-grade data engineering — is managed in Azure DevOps: [dev.azure.com/labsvirtual](https://dev.azure.com/labsvirtual) — Git-integrated workspaces, CI/CD per platform.

---

### Labs Virtual — Startup Enablement
![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)
![Programme](https://img.shields.io/badge/Microsoft%20for%20Startups-Founders%20Hub-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

Labs Virtual acts as a Microsoft Solutions Partner to help early-stage startups access the Microsoft for Startups programme — Founders Hub credits, Azure infrastructure, GitHub and AI tooling. Handles platform migration and adds data and AI layers to existing products.

- **Founders Hub** — up to $150k in Azure credits + GitHub Enterprise + Microsoft 365 + AI services
- **Platform migration** — existing stack (WooCommerce, Django, WordPress) moved to Azure-native architecture
- **AI / data layer** — Azure AI Foundry, Fabric or Databricks added to client products
- **Operational handoff** — CI/CD, monitoring and documentation set up in Azure DevOps

**Active engagements**

| Startup | Description | Phase |
|---|---|---|
| [Finisiea](https://www.finisiea.nl) | NL tea-infusions webshop. WooCommerce → Azure migration; Founders Hub pathway. | 🟢 managed · active |

---

### [Labs Virtual — Fabric Data Accelerator](https://github.com/graphicsilvr/labs-virtual-fabric-accelerator)
![Status](https://img.shields.io/badge/status-v1%20released-brightgreen?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Microsoft%20Fabric%20%7C%20PySpark%20%7C%20Azure%20SQL%20%7C%20Bicep-742774?style=flat-square)

Enterprise medallion lakehouse deployable on Microsoft Fabric. Metadata-driven ELT via a central `controlDB` — configure what to ingest, the platform handles the rest.

- **Bronze** — raw Parquet ingestion from Azure SQL, REST APIs, flat files
- **Silver** — cleansed Delta Lake tables via PySpark transforms
- **Gold** — aggregated Fabric Warehouse, ready for Power BI Direct Lake
- **IaC** — Bicep (current) + Terraform (roadmap) for one-command client deployment
- **CI/CD** — GitHub Actions + fabric-cicd deploys all notebooks and pipelines automatically

→ [View repository](https://github.com/graphicsilvr/labs-virtual-fabric-accelerator) · [Documentation](https://dev.azure.com/labsvirtual/fabric-data-accelerator/_wiki)

---

### [Virtual Silvr — Markets Intelligence Platform](https://markets.virtualsilvr.com)
![Status](https://img.shields.io/badge/status-live-brightgreen?style=flat-square)
![Phase](https://img.shields.io/badge/data%20layer-investment-9a6700?style=flat-square)
![Stack](https://img.shields.io/badge/stack-Next.js%20%7C%20Python%20%7C%20Django%20%7C%20Azure%20AI%20Foundry-0078D4?style=flat-square)

Pre-IPO AI intelligence for AI companies tracked across the Labs Virtual suite. Platform and UI are live; full data population (OpenFIGI, Tiingo, EDGAR Form D) requires investment to scale. Next.js front-end, Python/Django API layer, deployed on Azure App Service.

**Data layer**
- Instruments — OpenFIGI
- Funding rounds — EDGAR Form D
- End-of-day prices — Tiingo
- Company content → Azure AI Search

**AI layer** — Azure AI Foundry: model deployments, agents + tools, evaluations and tracing

**Observability** — App Insights · Log Analytics / KQL

- **[markets.virtualsilvr.com](https://markets.virtualsilvr.com)** — live markets intelligence platform

---

## Tech Stack

**Data & Analytics**

![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-742774?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**Full-Stack**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Infrastructure & DevOps**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure AI Foundry](https://img.shields.io/badge/Azure%20AI%20Foundry-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Certifications

| Certification | Issuer | Year |
|---|---|---|
| Microsoft Fabric Analytics Engineer Associate (DP-700) | Microsoft | 2026 |
| Azure Fundamentals (AZ-900) | Microsoft | 2024 |
| Azure Data Fundamentals (DP-900) | Microsoft | 2023 |

---

## Find me

| | |
|---|---|
| **LinkedIn** | [sylvion-finisie](https://www.linkedin.com/in/sylvion-finisie-124399205) |
| **Labs Virtual** | [labsvirtual.com](https://www.labsvirtual.com) — Data Platform Studio |
| **AI Intelligence** | [insights.labsvirtual.com](https://insights.labsvirtual.com) — weekly publication |
| **AI Companies Index** | [index.labsvirtual.com](https://index.labsvirtual.com) — scored metrics |
| **Markets Platform** | [markets.virtualsilvr.com](https://markets.virtualsilvr.com) |
| **Azure DevOps** | [dev.azure.com/labsvirtual](https://dev.azure.com/labsvirtual) — data project work |
| **Email** | [support@labsvirtual.com](mailto:support@labsvirtual.com) |

---

## Book a meeting

[Schedule via Microsoft Bookings](https://outlook.office.com/bookwithme/user/b6d131eccaf2459e8f5c13203b50c751@virtualsilvr.com/meetingtype/20QamxUfJ0G6ofZlp8Pitw2?anonymous&ep=mlink)

---

*Haarlem, Netherlands*
