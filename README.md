# Cloud Infrastructure & Data Engineer

Systems Administrator | Cloud Infrastructure & Data Engineer | AWS Solutions Architect Associate | Microsoft Azure Administrator Associate (AZ-104)

5+ years of hands-on experience across systems administration, cloud infrastructure, and data engineering, with a strong foundation in both operational reliability and structured data management.

I build and document end-to-end projects across cloud platforms and database environments: real deployments, genuine constraints, and honest writeups of what broke and how it was fixed. Every project includes a full architecture writeup, a reproducible setup guide, and working evidence.

**🌐 Portfolio: [janeologhadien.github.io](https://janeologhadien.github.io)**

> 🔒 Project source code is private. Request access through the [portfolio site](https://janeologhadien.github.io) and I'll share the repository.

## Latest Projects

**AWS Production Infrastructure**
- **AWS Terraform Production Stack** - Production-style AWS deployment built and run with Terraform: Graviton EC2 with a containerised app, Postgres and Caddy, keyless GitHub Actions deploys via OIDC and SSM (no SSH), secrets in Parameter Store, nightly S3 backups, budget alerts, and CI with Terraform tests, tflint and Checkov. Includes a real incident write-up.

**Developer Tooling**
- **CloudCheck** - VS Code extension for inline compliance linting of Bicep, Terraform and ARM templates. 38 rules across 11 categories mapped to CIS Azure Benchmark and CAF. Published on the VS Code Marketplace.
- **CloudCheck Action** - GitHub Action that scans IaC changed in a pull request, posts a compliance score and findings table as a PR comment, and fails the build on critical issues.

**FinOps & Tooling**
- **Cloud Cost Anomaly Alerter** - Detects Azure spend spikes against a rolling 7-day baseline, explains the likely cause in plain English, gives the exact CLI fix, and alerts via Slack or Teams.
- **[Cloud Engineering Toolkit](https://janeologhadien.github.io/cloud-engineering-toolkit/)** - Free, open-source toolkit for Azure, AWS and Google Cloud: check templates against CIS Azure Benchmark security rules, compare services across clouds, plan networks and generate Terraform, Bicep and Kubernetes code in the browser. [Try it live](https://janeologhadien.github.io/cloud-engineering-toolkit/) · [View code](https://github.com/janeologhadien/cloud-engineering-toolkit)

## Cloud & Infrastructure (Azure)

**Infrastructure as Code & Networking**
- **Azure IaC Deployment with Bicep** - Modular Bicep deployment covering network segmentation, least-privilege NSGs, compute and Key Vault secrets isolation.
- **Cloud Network Foundation** - VNets, subnets, NSGs, application security groups, public and private DNS zones.

**Identity & Governance**
- **Azure RBAC & Identity Baseline Governance** - Security Defaults, custom least-privilege RBAC roles, sign-in monitoring.
- **Cloud Cost Governance & Tag Compliance** - Azure Policy tag enforcement, budgets, automated cost control.

**Data & Storage**
- **On-Premise to Cloud Data Migration** - Storage design, redundancy trade-offs, lifecycle management.
- **Batch & Streaming Data Pipeline** - Azure Data Factory batch ETL, event-driven queue processing.
- **Data Backup & Recovery** - Soft delete, versioning, point-in-time restore, tested against real incidents.

**Security**
- **Cloud Security Posture & Secrets Management** - Defender for Cloud Secure Score, Key Vault with RBAC authorization.
- **Network Security: Segmentation & Private Endpoints** - Least-privilege NSGs, Private Endpoint removing public access entirely.
- **Azure SQL Database Security Baseline** - Entra-only authentication, firewall restriction, audit logging.

**DevOps & Observability**
- **CI/CD Pipeline: GitHub Actions + Bicep** - Infrastructure as Code, OIDC federated authentication, zero stored secrets.
- **Monitoring & Observability Capstone** - Unified Log Analytics workspace and KQL across the whole portfolio.

## Skills

Azure administration and security | AWS | Identity & access management (RBAC, Entra ID) | Infrastructure as Code (Bicep, Terraform) | CI/CD (GitHub Actions, OIDC) | Compliance as code (CIS Azure Benchmark, CAF) | VS Code extension development | FinOps and cost monitoring | PowerShell automation | KQL and observability | Network security | Database security.
