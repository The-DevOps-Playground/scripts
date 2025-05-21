# 🛠️ DevOps Playground – Scripts Repository

Welcome to the **DevOps Playground Scripts Repo** — a central place for all reusable scripts, automation helpers, and command-line tools used across our infrastructure, CI/CD, and containerization projects.

---

## 📁 Structure

All scripts are organized by topic or purpose in subdirectories:

```

scripts/
├── infra/                  # Infrastructure-related scripts (Terraform, AWS CLI, etc.)
├── cicd/                   # CI/CD helper scripts (Jenkins, GitHub Actions, etc.)
├── containers/             # Docker/Kubernetes/Helm related scripts
├── ansible/                # Ansible playbooks and patching automation
├── monitoring/             # Prometheus, Grafana setups
└── utils/                  # Misc utilities and helper tools

````

---

## 🚀 Getting Started

> These scripts are meant to be used as modular helpers for larger workflows, not full applications.

### 🔧 Requirements

- Bash or Zsh (Unix-based systems)
- Terraform (if using infra scripts)
- AWS CLI (if deploying to AWS)
- Ansible (for patching)
- Docker / kubectl / Helm (for container scripts)

### ✅ Usage Example

```bash
# Example: Launch EC2 instance with user data
cd scripts/infra
chmod +x launch_ec2.sh
./launch_ec2.sh
````

---

## 📦 Available Scripts

| Category      | Description                                           |
| ------------- | ----------------------------------------------------- |
| `infra/`      | Launch EC2, patch with Ansible, deploy with Terraform |
| `cicd/`       | CI/CD pipeline scripts, parameter injection           |
| `containers/` | Helm install, Docker build/push, K8s deploy           |
| `ansible/`    | Patch EC2 instances, install packages                 |
| `monitoring/` | Install Prometheus, Grafana                           |
| `utils/`      | Misc: cleanup, validate, common ops                   |

---

## ✍️ Contributing

We encourage contributions from all teams!

1. Follow the folder structure.
2. Use descriptive names and shebangs (`#!/bin/bash`).
3. Include inline comments and `README.md` if needed inside your folder.
4. Test before pushing.

---

## 🙋‍♂️ Maintainers

This repo is maintained by the **DevOps Playground Volunteer Team**.

* Infra & Cloud
* CI/CD & Automation
* Container & Orchestration
