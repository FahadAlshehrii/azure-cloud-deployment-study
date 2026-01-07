# ☁️ Multi-Platform Cloud Deployment & Comparative Analysis (Azure)

## 📌 Overview
This repository contains a professional technical study comparing three different deployment models on **Microsoft Azure**. The project evaluates the deployment of a static web application (built with the Hugo engine) to determine the most efficient hosting environment for real-world business scenarios.

[cite_start]As a **Technical Team Lead** and **Information Technology student at KAU** (GPA 4.85/5.0) [cite: 80, 86, 118][cite_start], I conducted this research to bridge the gap between architectural design and cost-effective operational excellence[cite: 85, 87].

## 🚀 Deployment Models Explored
I implemented and documented the deployment process across three distinct Azure service models:

1.  **IaaS (Infrastructure as a Service):** * Deployment on an **Azure Virtual Machine (VM)**.
    * Configured **Nginx** as the web server and used Git for file synchronization.
2.  **PaaS (Platform as a Service):** * Utilized **Azure App Services**.
    * Optimized deployment using **SCM & FTP** via Kudo File Manager for fast artifact transfer.
3.  **Serverless / Object Storage:** * Deployed via **Azure Blob Storage**.
    * Configured static website hosting endpoints with zero server management overhead.

## 📊 Key Findings & Benchmarking
The study focused on two critical metrics: **Monthly Cost** (for 10k visitors) and **Service Level Agreements (SLAs)**.

| Metric | Virtual Machine (IaaS) | App Service (PaaS) | Object Storage (Serverless) |
| :--- | :--- | :--- | :--- |
| **Monthly Cost** | $19.27 | $14.45 | **$1.15** |
| **Availability (SLA)** | 95.0% | **99.95%** | 99.9% |
| **Management Risk** | High (OS/Disk failure) | Moderate | **Minimal** |

## 💡 Strategic Recommendation
Based on the analysis, **Object Storage** was recommended as the optimal solution for static hosting due to a **94% cost reduction** compared to VM models and significantly lower operational risk.

## 🛠 Tech Stack
* **Cloud Platform:** Microsoft Azure
* **Static Site Generator:** Hugo
* **Web Server:** Nginx
* **Tools:** Git, Azure CLI, Kudo File Manager

## 🔮 Future Roadmap (DevOps)
To further align with the **Saudi digital transformation market**, I am currently working on:
* [ ] **Infrastructure as Code (IaC):** Automating resource provisioning using **Terraform**.
* [ ] **CI/CD Pipelines:** Implementing automated build and deploy workflows using **Azure Pipelines (Azure DevOps)**.

---
[cite_start]**Author:** [Fahad Alshehri](https://linkedin.com/in/f-alshehrii) [cite: 82]
