### Hi there, I'm **Nguyen Ngoc Anh Tuan**! 👋

**Security Engineer**

**Co-founder of [Synapse CE](https://github.com/KKloudTarus/synapse-ce)**

Ho Chi Minh City, Vietnam

![Animated introduction: Security Engineer, Co-founder of Synapse CE](https://readme-typing-svg.demolab.com?font=Roboto&weight=500&size=21&duration=3000&pause=1000&color=31F781&width=600&lines=Security+Engineer;Co-founder+of+Synapse+CE)

![Profile Views](https://komarev.com/ghpvc/?username=nnatuan03&color=red)
![GitHub Followers](https://img.shields.io/github/followers/nnatuan03?style=social)
![GitHub Stars](https://img.shields.io/github/stars/nnatuan03?affiliations=OWNER&style=social)

---

## 🚀 About Me

I'm a Security Engineer at **Galaxy FinX**, where I work on the security of a digital bank running on AWS. I review code, manage vulnerabilities through to the fix, and build the cloud and CI/CD controls around them.

- 🛡️ **Application security:** white-box code review of banking services, from login and onboarding to partner integrations.
- 🔍 **Vulnerability management:** triage, severity, remediation and retest, tracked in Jira with the engineering leads who own the fix.
- ☁️ **Cloud security:** AWS WAF, Network Firewall, landing zone and account vending (AFT), written in Terraform.
- ⚙️ **DevSecOps:** SAST, SCA and IaC scanning in CI/CD, with results collected in DefectDojo.
- 🤖 **Automation:** agent workflows for security validation, code review and reporting.
- 🎓 **Education:** BSc in Information Assurance, FPT University (2025). MBA student at University of Finance & Marketing (UFM) since 2025.

> Still learning. Building security into everyday engineering.

---

## 💼 Current Work

**🏦 Leading application security for a digital bank**

I run the white-box security assessment program across more than 15 production services of a digital bank and a second financial platform: authentication, Keycloak realms, onboarding and eKYC, accounts, transactions, term deposits, teller, partner and back-office integrations, the API gateway, the CMS and the mobile host app. I own it end to end. I set the review rounds, find and rate the issues, agree on severity with the security lead, assign fixes to dev leads on Jira, retest each fix against the commit that shipped it, and close it with evidence. In one production audit alone I raised 64 findings, and in one retest round I verified 33 fixes on `main`. The program also feeds the company's PCI DSS work.

**☁️ Building secure AWS infrastructure from zero**

I designed and shipped a FleetDM endpoint management platform for the company's devices, in Terraform, starting from a new AWS account vended through Account Factory for Terraform (AFT). The admin console is reachable only over VPN. Apple MDM enrollment and OTA profiles go out through a WAF-protected public path. Every outbound connection is allow-listed in AWS Network Firewall, and DNS and TLS run on ACM. That took more than 40 pull requests across the landing zone, the network firewall, the shared EKS platform and the Fleet stack itself.

**🛡️ Hardening the edge of the shared platform**

I built the layered AWS WAF web ACLs that protect the public load balancers of the shared EKS platform, with one ACL per gateway and full request logging to CloudWatch and S3.

**⚙️ Running the security pipeline**

I work on the pipeline that feeds scanner results into DefectDojo, so each vulnerability appears exactly once with its source. I also maintain the AI review gates that check infrastructure and release changes before they merge.

---

## 🌍 Open Source Contributions

I contribute to AWS Labs security tools that I use every day. Running AWS Security Hub and these scanners on a real banking workload showed me gaps in what they report, so I fix them upstream.

- [**Automated Security Helper (ASH)**](https://github.com/awslabs/automated-security-helper): SAST, SCA and IaC scanner orchestration
- [**IAM Policy Autopilot**](https://github.com/awslabs/iam-policy-autopilot): least-privilege IAM policies generated from application code

---

## 🧩 Building Synapse CE

I co-founded [**Synapse CE**](https://github.com/KKloudTarus/synapse-ce), an open-source security assessment platform. It runs supply chain analysis, code scanning, reconnaissance, cloud posture checks and runtime defense in one workflow, and ties every finding to the evidence behind it.

My work there covers the assessment lifecycle (snapshots, finding lineage, retests and closure), vulnerability intelligence, CI/CD integrations, asset management and the guided [playground](https://github.com/KKloudTarus/synapse-ce/pull/1568).

[Explore the repository →](https://github.com/KKloudTarus/synapse-ce) · [Website](https://synapse.kkloudtarus.net/) · [Documentation](https://github.com/KKloudTarus/synapse-ce/tree/main/docs/guide)

---

## 🏅 Certifications & Training

| Credential | Issuer | Issued |
| --- | --- | --- |
| **HTB Certified Penetration Testing Specialist (CPTS)** | Hack The Box | May 2026 |
| Google Project Management | Google | Sep 2025 |
| IBM Cybersecurity Analyst Specialization | IBM | Aug 2023 |
| Web Penetration Testing | CyberJutsu Academy | Jul 2023 |

[View credentials on LinkedIn →](https://www.linkedin.com/in/nguyen-ngoc-anh-tuan/)

---

## 📊 GitHub Stats & Activity

<div align="center">
  <img width="48%" src="https://github-readme-stats-fast.vercel.app/api?username=nnatuan03&amp;show_icons=true&amp;theme=react&amp;hide_border=true" alt="GitHub statistics for nnatuan03" />
  <img width="48%" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=nnatuan03&amp;theme=react&amp;layout=compact&amp;hide_border=true" alt="Most used languages in nnatuan03's public repositories" />
</div>

---

## 🛠️ Development & Automation

### 🖥️ Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ☁️ Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### 🔐 Security Tooling

![DefectDojo](https://img.shields.io/badge/DefectDojo-1E3A5F?style=for-the-badge)
![Grype](https://img.shields.io/badge/Grype-0B5FFF?style=for-the-badge)
![Checkov](https://img.shields.io/badge/Checkov-6B47ED?style=for-the-badge)

### ⚡ Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📫 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anh%20Tuan-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/nguyen-ngoc-anh-tuan/)
[![GitHub](https://img.shields.io/badge/GitHub-nnatuan03-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nnatuan03)
