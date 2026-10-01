# Hi, I'm Suman Neupane 👋
**M.Sc. Software Engineering Student in Germany | Cloud & DevOps Platform Builder**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/suman-neupane/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Website-blue?style=flat&logo=google-chrome&logoColor=white)](https://sumannpn.com.np)
[![Email](https://img.shields.io/badge/Email-itsmesumannpn%40gmail.com-red?style=flat&logo=gmail&logoColor=white)](mailto:itsmesumannpn@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Suman--Neupane-black?style=flat&logo=github&logoColor=white)](https://github.com/Suman-Neupane)

I design resilient, cost-conscious cloud infrastructure and automated GitOps delivery pipelines. Rather than collecting tool logos, I focus on **engineering judgment**: understanding how systems break, designing for low recovery time (MTTR), enforcing security guardrails in CI/CD, and eliminating unnecessary cloud complexity.

📍 **Based in:** Germany  
🎯 **Targeting:** DevOps / Cloud Platform Engineering (*Werkstudent* & Junior Roles)  
📜 **Certifications & Preparation:** Certified Kubernetes Administrator (CKA in prep), AWS Cloud Practitioner (CLF-C02 in prep)

---

## 🚀 Featured Flagship Project

### [CloudOps Floci Platform: End-to-End GitOps & Cloud Emulation](https://github.com/Suman-Neupane/devops-floci-platform)
*A zero-cost GitOps and cloud infrastructure platform designed for rapid local testing, automated security, and CI verification.*

* **Key Architectural Decision:** Replaced heavy LocalStack with **Floci** (high-performance GraalVM/Quarkus AWS emulator), slashing local integration test boot times from ~45 seconds to **25ms** and cutting memory consumption from **1.2GB to 15MB**.
* **GitOps & Delivery:** Automated Kubernetes (k3d) deployment using **ArgoCD** and **Helm** with self-healing reconciliation.
* **Shift-Left Security:** Automated container vulnerability scanning (**Trivy**) and IaC policy-as-code linting (**Checkov** & **TFLint**).
* **Observability:** Custom **Prometheus** instrumentation tracking RED metrics (Rate, Errors, Duration) and **Grafana** visualization.
* [Explore the Architecture Decision Records (ADRs) →](https://github.com/Suman-Neupane/devops-floci-platform#%EF%B8%8F-architecture-decisions--trade-offs)

---

## 🛠️ Core Engineering Toolkit

| Domain | Technologies & Practices |
| :--- | :--- |
| **Cloud & IaC** | AWS (S3, DynamoDB, SQS, IAM, VPC), Terraform (Modular IaC, Infracost, State Locking) |
| **Container & Orchestration** | Docker (Multi-stage builds, non-root security), Kubernetes, Helm, k3d / Kind |
| **GitOps & CI/CD** | ArgoCD (Declarative GitOps), GitHub Actions (Layer Caching, Automated Gating) |
| **DevSecOps** | Trivy (Vulnerability Scanning), Checkov (IaC Static Analysis), Gitleaks |
| **Observability** | Prometheus (Alerting, ServiceMonitors, RED metrics), Grafana |
| **Languages & Systems** | Python (FastAPI, Boto3), Go, Bash scripting, Linux System Administration |

---

## 💡 How I Approach DevOps Engineering
1. **Right-Sizing Over Hype:** Knowing when *not* to add a Kubernetes cluster is just as important as knowing how to manage one.
2. **Shift-Left Security & Fast Feedback:** If a vulnerability or infrastructure misconfiguration can be caught in CI in 30 seconds with Trivy or Checkov, it shouldn't reach staging.
3. **Blameless Failure Analysis:** Systems will fail; the measure of good engineering is having actionable alerts, fast MTTR, and blameless post-mortems that turn incidents into preventive guardrails.

---

### 📬 Connect With Me
* **LinkedIn:** [linkedin.com/in/suman-neupane](https://www.linkedin.com/in/suman-neupane/)
* **Portfolio:** [sumannpn.com.np](https://sumannpn.com.np)
* **Email:** [itsmesumannpn@gmail.com](mailto:itsmesumannpn@gmail.com)
