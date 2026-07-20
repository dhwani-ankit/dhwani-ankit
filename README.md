<h1 align="center">Ankit Jangir</h1>

<p align="center">
  <strong>Sr. DevOps Engineer</strong> &nbsp;·&nbsp; Cloud Infrastructure &nbsp;·&nbsp; DevSecOps &nbsp;·&nbsp; Platform Engineering
</p>

<p align="center">
  <em>Infrastructure as code, evidence as a deliverable.</em>
</p>

<p align="center">
  <a href="https://ankitjangir.cloudsaathi.com"><img src="https://img.shields.io/badge/Portfolio-1B4332?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyYTEwIDEwIDAgMSAwIDAgMjAgMTAgMTAgMCAwIDAgMC0yMG02LjkgNmgtMi45NWExNS42IDE1LjYgMCAwIDAtMS4zOC0zLjU2QTguMDMgOC4wMyAwIDAgMSAxOC45MiA4TTEyIDQuMDRjLjgzIDEuMiAxLjQ4IDIuNTMgMS45MSAzLjk2aC0zLjgyYy40My0xLjQzIDEuMDgtMi43NiAxLjkxLTMuOTZNNC4yNiAxNGE3LjggNy44IDAgMCAxIDAtNGgzLjM4YTE2LjUgMTYuNSAwIDAgMCAwIDR6bS44MiAyaDIuOTVjLjMyIDEuMjUuNzggMi40NSAxLjM4IDMuNTZBNy45OSA3Ljk5IDAgMCAxIDUuMDggMTZtMi45NS04SDUuMDhhNy45OSA3Ljk5IDAgMCAxIDQuMzMtMy41NkExNS42IDE1LjYgMCAwIDAgOC4wMyA4TTEyIDE5Ljk2Yy0uODMtMS4yLTEuNDgtMi41My0xLjkxLTMuOTZoMy44MkExNS42IDE1LjYgMCAwIDEgMTIgMTkuOTZNMTQuMzQgMTRIOS42NmExNC43IDE0LjcgMCAwIDEgMC00aDQuNjhhMTQuNyAxNC43IDAgMCAxIDAgNG0uMjUgNS41NmMuNi0xLjExIDEuMDYtMi4zMSAxLjM4LTMuNTZoMi45NWE4LjAzIDguMDMgMCAwIDEtNC4zMyAzLjU2TTE2LjM2IDE0YTE2LjUgMTYuNSAwIDAgMCAwLTRoMy4zOGE3LjggNy44IDAgMCAxIDAgNHoiLz48L3N2Zz4=" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ankit-jangir-7a3955140/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:ankitjangir.1690@gmail.com"><img src="https://img.shields.io/badge/Email-2D6A4F?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMCA0SDRhMiAyIDAgMCAwLTIgMnYxMmEyIDIgMCAwIDAgMiAyaDE2YTIgMiAwIDAgMCAyLTJWNmEyIDIgMCAwIDAtMi0yem0wIDQtOCA1LTgtNVY2bDggNSA4LTV6Ii8+PC9zdmc+" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS%20Certified-DevOps%20Engineer%20Professional-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS DevOps Engineer – Professional" />
  <img src="https://img.shields.io/badge/AWS%20Certified-Security%20Specialty-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Security – Specialty" />
</p>

---

## About

I lead the DevOps practice at **[Dhwani RIS](https://github.com/dhwani-ris)** across two verticals: our SaaS
product line, and the custom platforms we build when the product doesn't fit the client. Enterprise, NGO and
government users, mostly on AWS.

The work runs the whole length of it — designing the architecture, provisioning it as code, holding the pager,
and carrying platforms through the security due-diligence of banks and Big Four assessors.

**📄 Written case studies with architecture diagrams → [ankitjangir.cloudsaathi.com](https://ankitjangir.cloudsaathi.com)**

## What I work on

**Cloud platforms** — EKS with Karpenter provisioning against pending pods, multi-AZ, 500+ AWS resources in
Terraform with remote state. Multi-account AWS Organizations with a dedicated security account aggregating
GuardDuty, Security Hub, Config and CloudTrail.

**Agent tooling** — an orchestrator running specialist agents across three surfaces: code and application
security, AWS posture and cost, and deployment. Detection stays rule-based and deterministic so findings are
reproducible between runs; the model only triages, remediates and summarises.

**Security programmes** — a 34-policy ISO 27001-aligned ISMS with 16 operational registers, vulnerability
management driven through to revalidation, and SAST/SCA as blocking release gates.

**Delivery** — CI/CD in GitHub Actions, Jenkins and Azure DevOps; observability on Prometheus, Grafana and
Loki with external synthetic checks.

## Open source

The pieces of my work that generalise — extracted, documented and published.

| | |
|---|---|
| **[terraform-aws-static-site](https://github.com/dhwani-ankit/terraform-aws-static-site)** | S3 + CloudFront + ACM + Route 53. Private origin reached only through Origin Access Control, bucket policy scoped by `SourceArn` to a single distribution. My portfolio runs on it. `Terraform` |
| **[github-actions-aws-oidc](https://github.com/dhwani-ankit/github-actions-aws-oidc)** | Keyless CI auth — and the failure I could not find documented anywhere: GitHub now emits subject claims embedding numeric org/repo IDs, so trust policies matching the documented format silently fail. `Terraform` |
| **[iso27001-isms-starter](https://github.com/dhwani-ankit/iso27001-isms-starter)** | 20 policy templates and the 9 registers that evidence them. Policies alone fail assessments — the next question is always "show me that this happened". `Markdown` |
| **[eks-karpenter-reference](https://github.com/dhwani-ankit/eks-karpenter-reference)** | EKS where Karpenter owns compute. Bootstrap node group deliberately tiny; spot interruption queue included rather than left as an exercise. `Terraform` |
| **[aws-cost-daily-report](https://github.com/dhwani-ankit/aws-cost-daily-report)** | Daily spend plus what to do about it — idle volumes, unassociated addresses, stopped instances still billing storage. 10 tests, no AWS account needed. `Python` |
| **[frappe-devops-toolkit](https://github.com/dhwani-ankit/frappe-devops-toolkit)** | Deploy, health check and backup verification for Frappe benches. The deploy script refuses any site whose name contains "prod". `Bash` |

## Stack

`AWS` `Azure` `Kubernetes / EKS` `Docker` `Terraform` `CloudFormation` `Helm`
`GitHub Actions` `Jenkins` `Azure DevOps` `Prometheus` `Grafana` `Loki`
`Python` `Bash` `PostgreSQL` `MySQL` `MongoDB`

## Get in touch

Open to conversations about platform engineering, cloud infrastructure and DevSecOps — and currently open
to new roles.

- 🌐 **[ankitjangir.cloudsaathi.com](https://ankitjangir.cloudsaathi.com)**
- 💼 [LinkedIn](https://www.linkedin.com/in/ankit-jangir-7a3955140/)
- 📫 ankitjangir.1690@gmail.com
- 📍 New Delhi, India
