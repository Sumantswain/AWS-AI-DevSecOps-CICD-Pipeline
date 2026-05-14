# ![aws](https://github.com/julien-muke/Search-Engine-Website-using-AWS/assets/110755734/01cd6124-8014-4baa-a5fe-bd227844d263)🚀 AWS-AI-DevSecOps-CICD-Pipeline

<div align="center">

  <br />
    <a href="[https://youtu.be/0A46RQiLCBE](https://github.com/Sumantswain/AWS-AI-DevSecOps-CICD-Pipeline)" target="_blank">
      <img src="https://github.com/user-attachments/assets/c07f2ed3-a000-459c-ab2a-a58565470c9a" alt="Project Banner">
    </a>
  <br />

<h3 align="center">Build an AI-Powered DevSecOps CI/CD Pipeline on AWS using Amazon CodeBuild, Amazon CodePipeline, Amazon S3, Amazon Inspector, Amazon Q and Amazon DevOps Guru.</h3>

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![React](https://img.shields.io/badge/React-Frontend-blue?logo=react)
![CodePipeline](https://img.shields.io/badge/AWS-CodePipeline-yellow)
![CodeBuild](https://img.shields.io/badge/AWS-CodeBuild-orange)
![Amazon Inspector](https://img.shields.io/badge/AWS-Inspector-red)
![Amazon Q](https://img.shields.io/badge/Amazon-Q-purple)
![Amazon DevOps Guru](https://img.shields.io/badge/AWS-DevOps_Guru-blue)

## 📌 Project Overview

This project demonstrates a complete AI-enhanced CI/CD pipeline for deploying a React.js application on AWS using modern DevOps and DevSecOps practices.

The pipeline automatically:

* Pulls source code from GitHub
* Integrates Amazon Inspector for automated code security scanning
* Builds the React/Vite application using AWS CodeBuild
* Uses Amazon Q Developer for AI-assisted development and DevOps support
* Deploys the application to Amazon S3
* Integrates Amazon DevOps Guru for AI-powered operational monitoring and anomaly detection

This project showcases how AI-powered AWS services can improve deployment automation, security, and developer productivity.

---

# 🏗️ Architecture

```text
GitHub Repository
        ↓
Amazon Inspector Code Security Scan
        ↓
Manual Security Approval Stage
        ↓
AWS CodePipeline
        ↓
AWS CodeBuild
        ↓
Amazon S3 Static Website Hosting
        ↓
Amazon DevOps Guru Monitoring

Additional AI Integration:
- Amazon Q Developer → AI-assisted coding and DevOps support
```

---

# ⚙️ AWS Services Used

| Service            | Purpose                           |
| ------------------ | --------------------------------- |
| AWS CodePipeline   | Automates CI/CD workflow          |
| AWS CodeBuild      | Builds the React application      |
| Amazon S3          | Hosts static website              |
| Amazon Inspector   | Performs vulnerability scanning   |
| Amazon DevOps Guru | AI-powered operational monitoring |
| Amazon Q Developer | AI coding assistant               |
| IAM                | Access management                 |
| GitHub             | Source code repository            |

---

# ✨ Features

* ✅ Fully automated CI/CD pipeline
* ✅ Automatic deployment on GitHub push
* ✅ React/Vite application deployment
* ✅ Static website hosting using Amazon S3
* ✅ AI-powered security scanning with Amazon Inspector
* ✅ AI-assisted development using Amazon Q
* ✅ DevSecOps workflow integration
* ✅ Cloud-native deployment architecture

---

# 🛠️ Tech Stack

* React.js
* Vite
* Node.js
* AWS CodePipeline
* AWS CodeBuild
* Amazon S3
* Amazon Inspector
* Amazon DevOps Guru
* Amazon Q Developer
* GitHub

---

# 📂 Project Workflow

```text
Developer Pushes Code → GitHub Repository
        ↓
Amazon Inspector scans source code and dependencies
        ↓
Manual approval stage validates security findings
        ↓
CodePipeline triggers AWS CodeBuild
        ↓
CodeBuild installs dependencies and builds React/Vite application
        ↓
Build artifacts generated in dist/
        ↓
Artifacts deployed to Amazon S3
        ↓
Amazon DevOps Guru monitors deployed application
```

---

# 🔐 Amazon Inspector Integration

Amazon Inspector was integrated to improve application security.

### Features Used:

* Code repository scanning
* Dependency vulnerability scanning
* Static Application Security Testing (SAST)
* Infrastructure as Code (IaC) scanning
* Continuous scanning configuration

### Scan Types Enabled:

* SAST
* SCA
* IaC

---

# 📊 Amazon DevOps Guru Integration

Amazon DevOps Guru was integrated to provide AI-powered operational monitoring and anomaly detection for the deployed application.

### Features Used:

* Proactive operational monitoring
* Machine learning-based anomaly detection
* Performance issue recommendations
* Automated insights generation
* Cloud operational intelligence

### Benefits:

* Detects application issues before impacting users
* Provides intelligent operational recommendations
* Improves application reliability and observability
* Supports AIOps workflow implementation

---

# 🤖 Amazon Q Developer Integration

Amazon Q Developer was integrated with VS Code using AWS Toolkit.

### Use Cases:

* AI code suggestions
* DevOps assistance
* Security recommendations
* Cloud development support
* Troubleshooting AWS resources

---


# ☁️ S3 Static Website Hosting

The React application is hosted on Amazon S3 using static website hosting.

### Configuration:

* Static website hosting enabled
* Public access configured
* Bucket policy added for public read access
* `index.html` configured as default document

---

# 🔄 CI/CD Pipeline Stages

## 1. Source Stage

* Source Provider: GitHub
* Repository connected using AWS Connector for GitHub
* Code automatically fetched from GitHub repository

## 2. Amazon Inspector Security Stage

* Amazon Inspector scans source code repositories
* Performs SAST, SCA and IaC scanning
* Detects dependency vulnerabilities and security risks
* Security findings generated automatically

## 3. Manual Approval Stage

* Manual approval added after Inspector scan
* Security findings reviewed before deployment
* Prevents insecure code from reaching production
* Implements DevSecOps approval workflow

## 4. Build Stage

* AWS CodeBuild used for building application
* Node.js 18 runtime configured
* Dependencies installed using npm
* Vite build output generated in `dist/`

## 5. Deploy Stage

* Amazon S3 deployment
* Automatic extraction enabled
* Static website updated after every successful build

## 6. AI Monitoring Stage

* Amazon DevOps Guru monitors application behavior
* Detects anomalies using machine learning
* Provides operational recommendations and insights

## 7. Amazon Q Developer Integration

* Amazon Q used inside VS Code
* AI-assisted coding support
* Security recommendations
* DevOps troubleshooting assistance
* Cloud development productivity enhancement

---

# 📸 Screenshots

## 🔹 CodePipeline Success

<img width="2559" height="1532" alt="Screenshot 2026-05-06 181449" src="https://github.com/user-attachments/assets/4eff9ee4-5a1c-4a17-8ddf-5c2543814828" />
<img width="2548" height="1518" alt="Screenshot 2026-05-06 153454" src="https://github.com/user-attachments/assets/da0a2bd4-1502-44e6-b7f5-23d3bbe85a31" />


---

## 🔹 Amazon S3 Website Hosting

<img width="2552" height="1519" alt="Screenshot 2026-05-06 153402" src="https://github.com/user-attachments/assets/93281d61-62dc-457c-baa2-e0367d4b1b84" />
<img width="2558" height="1519" alt="Screenshot 2026-05-06 153323" src="https://github.com/user-attachments/assets/79dda9c8-acbd-411e-b1df-ac8168ce1295" />

---

## 🔹 Amazon Inspector Dashboard

<img width="2554" height="1523" alt="Screenshot 2026-05-06 181522" src="https://github.com/user-attachments/assets/4c9b83c7-3326-4399-82dd-e46754d491cc" />


---

## 🔹 Amazon Q in VS Code

<img width="2559" height="1530" alt="Screenshot 2026-05-06 181643" src="https://github.com/user-attachments/assets/3211b4fa-a94a-4355-b8e4-82052e7f722a" />
<img width="2556" height="1532" alt="Screenshot 2026-05-06 181615" src="https://github.com/user-attachments/assets/c8bac88e-6fb4-4951-a551-3a814a7b12ca" />

---

# 🚀 How to Run Locally

```bash
# Clone repository
git clone <your-repo-url>

# Install dependencies
npm install --legacy-peer-deps

# Start development server
npm run dev
```

---

# 📈 Future Improvements

* Add manual approval stage
* Add Docker containerization
* Integrate Kubernetes deployment
* Add Terraform IaC
* Integrate Trivy security scanning
* Add CloudFront CDN
* Add Route53 custom domain

---

# 🧠 DevOps & DevSecOps Concepts Used

* Continuous Integration (CI)
* Continuous Deployment (CD)
* Infrastructure Automation
* AI-assisted DevOps
* DevSecOps
* Static Website Hosting
* Automated Security Scanning
* Cloud-native Deployment

---

# 👨‍💻 Author

**Sumant Swain**

---

# ⭐ Conclusion

This project demonstrates a modern AI-enhanced DevOps workflow using AWS cloud-native services. It combines automation, cloud deployment, AI-powered development assistance, and security scanning into a complete CI/CD ecosystem.

The project highlights practical implementation of:

* AWS DevOps Services
* CI/CD Automation
* AI-powered Developer Tools
* AIOps Monitoring with Amazon DevOps Guru
* Security-first DevOps Practices
* Cloud Deployment Architecture

---

