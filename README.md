# Hi, I'm Sreeram Manjunath Reddy 👋

**Full-stack developer moving into Cloud & DevOps**
I build and secure AWS deployments: private networks, keyless CI/CD, no SSH.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manjunath139/)

---

### 🚀 Featured project: ApexBank, secure Django + MySQL on AWS

A containerised banking app deployed with a security-first design. The app code is vibe coded; the **infrastructure, security, CI/CD and runbook are my work**.

- **3-tier VPC across 2 AZs:** public ALB, private app server, private encrypted RDS MySQL
- **No SSH:** access through SSM Session Manager. **No stored AWS keys:** GitHub Actions deploys with OIDC
- **CI/CD:** tests → Docker build → ECR → database migration → rolling server replacement
- **Least privilege:** scoped IAM roles, three database users (admin, migration, app), secrets in Parameter Store
- **Operations:** Auto Scaling health checks, full teardown checklist, cost checked in Cost Explorer

🔗 [Repo](https://github.com/Manju1392k/ApexBank) · 🎥 [Demo video](https://lnkd.in/p/dByfhUkg) · 💼 [LinkedIn post](https://lnkd.in/p/dByfhUkg)

---

### About me

6+ years as an independent full-stack developer and consultant (Django, Node.js, React/Next.js).] Now I'm focused on **AWS, Linux, Docker and CI/CD**. I learn by building, breaking, and writing down what went wrong.

- 🎯 **Open to:** Full-time Junior / Associate Cloud or DevOps Engineer roles · contract and freelance projects
- 📚 **Learning next:** Jenkins (compared with GitHub Actions) and Terraform

---

### Toolkit

```text
├── Cloud (hands-on)   :: AWS: EC2, VPC, ALB, Auto Scaling, RDS, ECR, IAM, Route 53, ACM,
│                         Systems Manager (Session Manager, Parameter Store), CloudTrail
├── DevOps (hands-on)  :: Docker, GitHub Actions (CI/CD, OIDC), Git, Linux (Ubuntu)
├── Security practice  :: least-privilege IAM, MFA, private subnets, security groups, secrets management
├── Full-stack         :: Next.js, React.js, Django, Node.js
├── Databases          :: MySQL, PostgreSQL, MongoDB
└── Languages          :: Python, JavaScript, SQL
```

---

### How I work

- **Security first:** private subnets, no SSH, no long-lived keys
- **Evidence over guessing:** I debug with activity logs, route tables, and CloudTrail before changing anything
- **Cost-aware:** I tear stacks down and verify the bill
- **Documented:** step-by-step runbooks and a mistake log for every project

---

### Contact

💼 [LinkedIn](https://www.linkedin.com/in/manjunath139/) 

📧 manjunath853535@gmail.com
