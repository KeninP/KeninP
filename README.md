# Hi, I'm Kenin Paradesi 👋

**Site Reliability Engineer** · ~4 years in cloud & platform operations · Hyderabad, India

I keep Kubernetes workloads on Azure and AWS observable, deployable and recoverable. Day to day I run the Dynatrace observability stack for a major UK bank (via TCS), build CI/CD and self-healing pipelines, and own P1/P2 incidents end to end.

- 🔭 **Observability:** Dynatrace (APM, distributed tracing, synthetics, SLOs, DQL), OpenTelemetry Collector on AKS → OTLP, Azure Monitor / KQL
- ⚙️ **Automation:** Azure DevOps pipelines that find zero-traffic namespaces via DQL for cleanup, and one-click remediation for CrashLoopBackOff / OOMKilled workloads
- 🚀 **Delivery:** Azure DevOps, GitHub Actions, Helm, ECR/EKS, AKS, Key Vault-backed secrets, SonarQube gates
- 🚨 **Reliability:** incident management, RCA, runbooks, 98–99% SLA compliance (ServiceNow, Jira)
- 🌱 **Currently learning:** Terraform
- 📜 **Certified:** Azure Administrator Associate (AZ-104), Azure Fundamentals (AZ-900)
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/kenin-paradeshi7788/)

## Tech

![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?logo=dynatrace&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)

## Featured projects

| Project | What it shows |
|---|---|
| [**voting-app on EKS**](https://github.com/KeninP/example-voting-app) | Multi-service app (Python, Node, .NET, Redis, Postgres). Gated GitHub Actions CI (syntax check → pytest → build), images tagged by commit SHA, pushed to ECR via **OIDC role assumption** (no stored AWS keys), rolled out to **EKS** with rollout verification; packaged as a **Helm** chart. |
| [**clothing-website on AKS**](https://github.com/KeninP/clothing-website) | Node.js app, Dockerised, two-stage **Azure DevOps** pipeline → **ACR** → **AKS**, Deployment + ConfigMap with resource limits; plus a GitHub Actions → Docker Hub workflow. |

> Most of my production work (Dynatrace, incident automation) lives in private enterprise repos. These public projects mirror the same patterns.
