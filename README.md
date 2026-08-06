<h1 align="center">Hey, I'm Elvir 👋</h1>

<p align="center">
DevOps Engineer • RHCSA Certified • Kubernetes • Cloud & Infrastructure Automation
</p>

<p align="center">
Building production-style infrastructure with Linux, Kubernetes, Docker, Terraform, AWS/EKS, Ansible, GitOps, ArgoCD, Vault, and CI/CD.
</p>

---

# 👨‍💻 About Me

- 🌍 Based in Warsaw, Poland
- 🐧 RHCSA Certified Linux Administrator
- 🚀 DevOps Engineer passionate about automation, Kubernetes, and cloud-native technologies
- ☸️ Experienced building production-style Kubernetes environments in a home lab
- ⚙️ Skilled in Infrastructure as Code, GitOps, CI/CD, Linux administration, and infrastructure automation
- ☁️ Currently expanding my AWS and cloud architecture knowledge
- 📚 Continuously learning modern DevOps tools and best practices

---

# 🚀 Featured Project

## 🔹 Family App (LinatrixSite) – Production-Ready DevOps Platform

A full-stack Family Task Management application deployed on a self-managed **3-node Kubernetes cluster** (RHEL & Ubuntu), demonstrating a complete production-style DevOps workflow: containerization, Helm packaging, automated CI/CD, GitOps deployment, secrets management, and full observability.

### Architecture

```mermaid
graph LR
    A[Developer Push] --> B[GitLab CI/CD]
    B --> C[Container Registry]
    C --> D[ArgoCD - GitOps]
    D --> E[Kubernetes Cluster]
    E --> F[Frontend]
    E --> G[Backend]
    E --> H[PostgreSQL]
    E --> I[Prometheus / Grafana / Loki]
```

### Technologies

- Linux (RHEL & Ubuntu)
- Docker
- Kubernetes (kubeadm, Calico CNI)
- NGINX Ingress
- Helm
- GitLab CI/CD
- ArgoCD (GitOps)
- HashiCorp Vault
- Prometheus & Grafana
- Loki (log aggregation)
- PostgreSQL
- Node.js / Express

### Highlights

- Built a GitLab CI/CD pipeline: automated image builds, registry pushes, and Helm value updates on every push to `main`
- Implemented GitOps with ArgoCD — the cluster's live state is continuously reconciled against Git, with zero manual `kubectl apply`
- Integrated HashiCorp Vault for centralized secrets management, migrating all secrets out of plaintext Git history
- Deployed Prometheus, Grafana, and Loki for full metrics + log observability
- Configured NGINX Ingress for unified routing to frontend and backend services
- Implemented Horizontal Pod Autoscaling, verified with a real synthetic load test (1 → 2 replicas, live)
- Built and executed a full disaster recovery drill: simulated total namespace loss, automatic GitOps rebuild via ArgoCD, and data restore from an S3-backed PostgreSQL backup — verified end-to-end
- Provisioned a parallel AWS EKS cluster using Terraform (VPC, IAM, managed node group, remote state in S3 + DynamoDB), including resolving a real IAM/IRSA storage-provisioning issue

🔗 Repository (GitLab, primary): https://gitlab.com/elvir.osmanov.1989/linatrixsite
🔗 Repository (GitHub mirror): https://github.com/elvirosmanov1989-alt/linatrixsite

🌐 App (public demo): https://linatrixsite.site *(hosted via Firebase/Cloudflare — separate from the Kubernetes infrastructure above)*


---

## 🚀 Other Projects

| Project | Description |
|---------|-------------|
| **DevOps Portfolio** | Personal GitHub profile and portfolio showcasing DevOps projects and technologies. |
| **GitLab CI/CD Assignment** | Automated CI/CD pipelines using GitLab CI for building, testing, and deployment. |
| **Multi-Service Web Application** | Dockerized React, Node.js, and PostgreSQL application serving as the foundation for Kubernetes deployment. |
| **Kubernetes Multi-Tier Deployment** | Kubernetes manifests for deploying a multi-tier application with networking, storage, and service discovery. |
| **Ansible Multi-Tier Project** | Infrastructure automation and configuration management using Ansible roles and playbooks. |
| **Vault HA Cluster** | High-availability HashiCorp Vault deployment on Kubernetes for secure secrets management. |

---

# 🛠️ Tech Stack

### Operating Systems

![Linux](https://img.shields.io/badge/Linux-black?style=for-the-badge&logo=linux)
![RHEL](https://img.shields.io/badge/RHEL-red?style=for-the-badge&logo=redhat)
![Ubuntu](https://img.shields.io/badge/Ubuntu-orange?style=for-the-badge&logo=ubuntu)

### Containers & Orchestration

![Docker](https://img.shields.io/badge/Docker-blue?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-blue?style=for-the-badge&logo=kubernetes)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm)

### Infrastructure as Code & Automation

![Ansible](https://img.shields.io/badge/Ansible-red?style=for-the-badge&logo=ansible)
![Terraform](https://img.shields.io/badge/Terraform-purple?style=for-the-badge&logo=terraform)
![Vault](https://img.shields.io/badge/Vault-black?style=for-the-badge&logo=vault)

### GitOps & CI/CD

![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-black?style=for-the-badge&logo=githubactions)

### Monitoring & Logging

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana)
![Loki](https://img.shields.io/badge/Loki-0A1A2F?style=for-the-badge&logo=grafana)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql)

### Version Control

![Git](https://img.shields.io/badge/Git-orange?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab)

### Cloud

![AWS](https://img.shields.io/badge/AWS-orange?style=for-the-badge&logo=amazonaws)

---

# 🏆 Certifications

- ✅ RHCSA (Red Hat Certified System Administrator)

---

## 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=elvirosmanov1989-alt&theme=github-dark" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=elvirosmanov1989-alt&show_icons=true&theme=github_dark" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=elvirosmanov1989-alt&layout=compact&theme=github_dark" />
</p>

---

# 🎯 Current Focus

✅ Linux Administration

✅ Docker

✅ Kubernetes

✅ Helm

✅ GitLab CI/CD

✅ GitOps with ArgoCD

✅ Infrastructure as Code

✅ Ansible

✅ Terraform

✅ HashiCorp Vault

✅ Monitoring & Logging

🔄 AWS Cloud

🔄 Amazon EKS

🔄 Terraform on AWS

🔄 Cloud Infrastructure Architecture

---
# ✅ Recently Completed

- 🔐 Kubernetes Security & RBAC (least-privilege service accounts, Vault-integrated secrets)
- 📊 Kubernetes Scaling (HPA, load-tested)
- 💾 Backup & Disaster Recovery (Velero + PostgreSQL backups, full DR drill verified)
- ☁️ AWS Migration with Terraform
- 🚀 Amazon EKS (provisioned, deployed to, and safely torn down)
# 📈 Currently Working On

- 🔐 Kubernetes Security & RBAC
- ☁️ AWS Migration with Terraform
- 🚀 Amazon EKS
- 📊 Kubernetes Scaling
- 💾 Backup & Disaster Recovery
```
