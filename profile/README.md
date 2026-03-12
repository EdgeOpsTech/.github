# 👋 Welcome to EdgeOpsTech

We build and maintain automation, DevOps, and cloud infrastructure projects for modern engineering teams.
This organization hosts reusable modules, CI/CD workflows, Kubernetes tooling, and full-stack service deployments.

---

## 🚀 Projects

### ☸️ Kubernetes & Helm

| Project | Description |
|---|---|
| **edgeops-helmchart-service** | Custom Helm chart library for deploying services to Kubernetes. Supports multi-environment rollout across dev and failover clusters. |
| **edgeops-superapp-service** | Backend microservice for the SuperApp platform. Deployed via CD pipelines with Prometheus monitoring integration. |
| **edgeops-superapp-web** | Frontend web application for the SuperApp platform. React-based UI with modern e-commerce styling, containerized and deployed alongside the backend service. |

---

### 🔁 CI/CD & GitOps

| Project | Description |
|---|---|
| **edgeops-harness-config** | Harness pipeline definitions for rolling deployments targeting AKS and failover clusters. Includes service definitions, connector configs, and environment infrastructure mappings. |
| **GitHub Actions Workflows** | Reusable GitHub Actions workflows for CI automation, cron scheduling, Dependabot configuration, and ARM template deployments. |

---

### ☁️ Infrastructure as Code

| Project | Description |
|---|---|
| **Azure Data Factory Pipelines** | ARM template–based CI/CD for ADF across multiple environments. Includes managed private endpoint provisioning, parameterized deployments, and Terraform-based managed identity migration. |
| **Terraform Modules** | Cloud infrastructure modules for Azure, AWS, and GCP. Covers landing zones, managed identities, networking, and service provisioning patterns. |

---

### 📊 Observability & Tooling

| Project | Description |
|---|---|
| **KontainMonitor** | Container monitoring dashboard for local Docker environments with real-time visibility into running workloads. |
| **Prometheus Monitoring Stack** | Kubernetes-native monitoring configuration supporting multi-cluster observability across dev and failover environments. |

---

## 🛠️ Stack & Tooling

- **Orchestration**: Kubernetes · Helm · Rancher Desktop · k9s
- **CI/CD**: GitHub Actions · Harness · GitOps workflows
- **Cloud**: Azure · AWS · GCP
- **Observability**: Prometheus · Grafana
- **Languages & Frameworks**: Java (Spring Boot) · React · Python
- **Containers**: Docker · GitHub Container Registry

---

## 🤝 Contributing

All projects follow GitOps principles — changes go through PRs and are deployed via pipelines.

- Open an **Issue** to report bugs or propose features
- Start a **Discussion** for architectural questions or ideas
- Check individual repo READMEs for local setup and contribution guidelines

---

📫 For questions or contributions, open an issue or reach out via Discussions.
