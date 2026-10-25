---
title: Jerome Hunter | Cloud DevSecOps Engineer
---

# Jerome Hunter

**Cloud DevSecOps Engineer · AI-Enabled Security Automation**

DFW, TX · [cloud.jobs.contact@gmail.com](mailto:cloud.jobs.contact@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jerome-hunter-sr) · [Portfolio](https://jhuntersr.com) · [GitHub](https://github.com/jhuntersr1-first/cloud-portfolio)

---

## Professional Summary

Cloud DevSecOps Engineer with hands-on experience securing AWS infrastructure across compliance-sensitive environments, including HIPAA-aligned healthcare systems and PCI-DSS payment platforms. HashiCorp Terraform Associate and AWS Solutions Architect Associate certified. Builds secured, auditable infrastructure with embedded guardrails, least-privilege IAM, encryption at rest and in transit, and network segmentation, using Terraform IaC and CI/CD automation (Jenkins, GitLab CI/CD, GitHub Actions, Azure DevOps). Applies AI to security work safely: building Amazon Bedrock agents that analyze security findings and generate reports, with prompt-injection defenses (OWASP LLM01) designed in from the start.

---

## Core Competencies

| Area | Skills |
|---|---|
| **Cloud Platforms** | AWS: EC2, S3, IAM, VPC, Lambda, API Gateway, EventBridge, SNS, SQS, DynamoDB, RDS, CloudFront, WAF, Route 53, CloudWatch, CloudTrail, Secrets Manager, SSM, EKS, ECS, ECR |
| **IaC & Automation** | Terraform (modules, remote state, workspaces), AWS CloudFormation |
| **CI/CD** | Jenkins, GitLab CI/CD, GitHub Actions (OIDC), Azure DevOps, blue-green deployments, automated rollbacks |
| **Security & Guardrails** | IAM least privilege, zero-trust VPC design, SAST, IaC and secrets scanning (Checkov, Trivy, Gitleaks, TruffleHog, SonarQube), AWS WAF OWASP rules, secrets management, vulnerability remediation, audit trails |
| **AI & Security Automation** | Amazon Bedrock agents, AI-assisted security triage and reporting, OWASP LLM01 prompt-injection mitigations, output validation |
| **Containers** | Kubernetes (EKS), Docker, ECR image lifecycle management, Helm |
| **Observability** | CloudWatch metrics, alarms and dashboards, CloudTrail auditing, Prometheus, Grafana, cost anomaly detection |
| **Scripting** | Python, Bash/Shell, PowerShell |
| **Operations** | System upgrades and patching, on-call support, root cause analysis, cross-team collaboration (Network, DB, Infra, Architecture) |

---

## Work Experience

### Cloud Modernization Engineer (Contract) · Bogg Express
*June 2026 – Present*

Contract engagement modernizing on-premises data flows and executive reporting on AWS through event-driven, serverless automation.

- Building a hybrid data sync between on-premises systems and AWS using API Gateway and Lambda, with SQS buffering for reliable, retryable transfers.
- Securing the on-premises-to-cloud data path with AWS WAF managed rules.
- Automating C-suite report output with EventBridge-scheduled Lambda functions, reducing manual report preparation.
- Configuring SNS notifications for report delivery and pipeline failure alerts.

### Cloud DevSecOps Engineer · Triphase Medical
*November 2025 – Present*

Responsible for security architecture of AWS infrastructure supporting a healthcare payment platform, embedding HIPAA and PCI-DSS-aligned controls across PHI and cardholder data environments.

- Architected and enforced PHI access controls and IAM scoping across AWS workloads, aligning access patterns with HIPAA Security Rule requirements.
- Implemented data residency controls and encryption at rest and in transit for PHI and payment data using AWS-native encryption (KMS, TLS), supporting HIPAA and PCI-DSS compliance objectives.
- Designed network segmentation isolating PHI and payment-processing workloads from general application infrastructure, reducing compliance scope and blast radius.
- Established audit logging across PHI and payment systems to support HIPAA and PCI-DSS audit trail requirements and incident investigation.
- Applied least-privilege IAM and encryption controls to a PCI-DSS-aligned payment processing environment, working within the cardholder data environment's security boundaries.
- Collaborated on infrastructure planning and security requirements for a customer-facing website with an integrated AI chatbot supporting the payment system.

### Cloud Engineer · Preston Transporters LLC
*June 2019 – November 2025*

Responsible for AWS infrastructure design, Terraform-driven environment provisioning, and CI/CD pipeline automation across dev, staging, and production environments.

- Developed and deployed AWS environments using CI/CD pipelines (Jenkins, GitLab CI/CD), building reusable Terraform modules for consistent, repeatable environment provisioning across dev, staging, and production.
- Managed AWS account configuration and image lifecycle practices, including ECR container image versioning and retirement, as part of ongoing platform operations.
- Embedded security guardrails directly into the CI/CD workflow: pre-merge linting, SAST, and IaC scanning (Gitleaks, TruffleHog) to catch misconfiguration before it reached infrastructure.
- Engineered multi-layer VPC network segmentation (subnets, NACLs, security groups) enforcing least-privilege traffic controls and full east-west observability.
- Resolved infrastructure vulnerabilities against defined SLAs, applying IAM least-privilege scoping and maintaining CloudTrail audit logs to support compliance review.
- Implemented centralized observability using CloudWatch metrics, dashboards, and alarms, enabling real-time alerting and reducing time to root cause during incidents.
- Performed infrastructure upgrades and patching with automated rollback logic, and provided on-call support to resolve production issues and roadblocks reported by development teams.
- Authored architecture runbooks, IaC templates, and audit documentation, and led root cause analysis and knowledge-transfer sessions to support platform continuity.
- Delivered a 27% cloud cost reduction through AWS Budgets, cost anomaly detection, and workload rightsizing.
- Configured AWS WAF and CloudFront to defend against OWASP Top 10 threats, and authored a multi-region Disaster Recovery Plan minimizing RTO/RPO for critical workloads.

### Owner / Operator · E.F. Corporation (Independent Contractor)
*June 2014 – April 2019*

- Owned and operated an independent freight operation across the US and Canada, managing federal compliance, logistics planning, and operational systems.

---

## Selected Projects

**[Cloud Portfolio Platform](https://github.com/jhuntersr1-first/cloud-portfolio)**: Production-style static site on S3 and CloudFront with dev, test, and prod environments, each with its own domain and certificate. Terraform deployed through GitHub Actions with per-environment OIDC roles (no stored keys), a manual approval gate for prod, and Gitleaks, Checkov, Trivy, and SonarQube on every change. Scores A+ on securityheaders.com and Mozilla HTTP Observatory.

**AI-Powered SOAR Agent**: Security orchestration agent on Amazon Bedrock that analyzes AWS WAF findings and assesses threat severity to support response decisions.

**Private AI Reporting Agent**: Python and Amazon Bedrock agent that writes project documentation from infrastructure data, with OWASP LLM01 defenses: delimited untrusted input, input screening, output validation, and redaction of AWS identifiers. Tested against injection attempts before use.

---

## Certifications & Education

- AWS Certified Solutions Architect – Associate · Amazon Web Services
- HashiCorp Certified: Terraform Associate · HashiCorp
- Computer Science Coursework · Mott Community College, Flint, MI

*Full resume with phone contact available on request.*
