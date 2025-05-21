# 🛠️ DevOps Playground – Scripts Repository

Welcome to the **DevOps Playground Scripts Repo** — a central place for all reusable scripts, automation helpers, and command-line tools used across our infrastructure, CI/CD, and containerization projects.

This repository contains various scripts used across the DevOps Playground, organized by tools and technologies. These scripts are shared across teams for launching infrastructure, automating pipelines, managing containers, and more.

---

## 📁 Folder Structure

```

scripts/
├── terraform/        # Scripts and templates for AWS resources
├── ansible/          # Patching and configuration automation
├── docker/           # Build and container image helpers
├── jenkins/          # Jenkins-specific pipeline and automation scripts
├── sonarqube/        # Sonarqube automation scripts
├── kubernetes/       # Scripts for deploying to and managing K8s clusters
├── monitoring/       # Prometheus, Grafana, and alerting setup
├── notifications/    # Sending notifications with or without attachments
└── utils/            # Miscellaneous helper scripts

````

---

## 🧪 How to Use

1. Navigate to the appropriate tool folder.
2. Ensure the script is executable:
   ```bash
   chmod +x script-name.sh
````

3. Run the script:

   ```bash
   ./script-name.sh
   ```

---

## 🛠 Examples

| Folder           | Sample Use Case                                 |
| ---------------- | ----------------------------------------------- |
| `terraform/`     | Launch EC2 instances, create VPCs, EKS clusters |
| `ansible/`       | Patch EC2 instances after deployment            |
| `docker/`        | Build and push Docker images                    |
| `jenkins/`       | Inject parameters or call reusable steps        |
| `kubernetes/`    | Deploy apps using kubectl or Helm               |
| `monitoring/`    | Set up Prometheus + Grafana                     |
| `notifications/` | Send email alerts with or without attachments   |

---

## 🤝 Contribution Guidelines

* Keep scripts modular and well-commented.
* Include a short description at the top of each script.
* Use folders based on the tool, not the task.
* Test locally before committing.

---

## 🙋 Maintainers

This repository is maintained by the **DevOps Playground volunteer team** across various working groups.
