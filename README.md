<div align="center">

# Jalil Abdollahi

### Cloud DevOps & Platform Engineer

AWS · Kubernetes · Terraform · CI/CD · LLM-assisted automation

Duisburg, Germany · Open to remote roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jalil--abdollahi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jalil-abdollahi)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jalil.abdollahi@gmail.com)

</div>

---

I build and run production AWS and Kubernetes platforms, and I build the tooling that makes them safer to operate and easier to learn. 9 years in infrastructure and DevOps, 5+ of them on production AWS and Kubernetes, with a background in C#/.NET software engineering.

**Selected results**

- Led **zero-downtime EKS upgrades across five clusters**, from v1.26 to v1.36
- Rebuilt an unreliable legacy **Jenkins CI platform** into two masters and nine agents, restoring stability and parallel build capacity
- Migrated workloads from KIAM to **EKS Pod Identity**, removing static credentials from the cluster
- Built **LLM-assisted log analysis** that reads application and infrastructure logs and surfaces likely root causes
- Wrote internal **Go tools** for SSH connection management and day-to-day infrastructure administration
- Led a data-center build-out to **TIA-942 Tier 2**, with Ansible-automated network and VMware provisioning

---

## Experience

| Role | Company | Period |
|---|---|---|
| Cloud DevOps Engineer | JAJA Finance · London (remote) | 2023 – 2026 |
| Cloud DevOps Engineer | FleetSpark · Berlin (remote) | 2021 – 2023 |
| Cloud DevOps Engineer | Imperium Drive · Berlin (remote) | 2021 |
| NetOps & DevOps Engineer | Islamic Azad University · Tehran | 2017 – 2021 |
| Software Engineer (C#/.NET) | Freelance | 2015 – 2020 |

---

## Missions: hands-on DevOps training I build and maintain

**2,450+ hand-written troubleshooting missions across nine tools.** Each mission ships a deliberately broken environment on your own machine. You fix it with the real CLI, and a validator checks the result by behaviour, the way production would. No cloud account, no bill.

| Project | What you fix | Size | Built with |
|---|---|---|---|
| [**AWSMissions**](https://github.com/jalilabdollahi/awsmissions) | Broken IAM, S3, Lambda, VPC, ECS and more, on a local AWS emulator with real IAM evaluation | 268 missions · 16 modules | Python · Floci · AWS CLI · Docker |
| [**K8sMissions**](https://github.com/jalilabdollahi/k8smissions) | Broken clusters, from pod crashes to multi-failure war games | 200 missions · 12 modules | Python · kind · kubectl |
| [**HelmMissions**](https://github.com/jalilabdollahi/helmmissions) | Broken charts, releases and upgrade paths, against a local OCI registry | 133 missions · 10 modules | Python · Helm 3/4 · kind |
| [**TerraformMissions**](https://github.com/jalilabdollahi/terraformmissions) | Broken HCL, state, modules and tests, up to production war games | 272 missions · 15 modules | Python · Terraform |
| [**DockerMissions**](https://github.com/jalilabdollahi/dockermissions) | Containers, images, networks, Compose and registries, in a browser terminal | 54 missions · 8 modules | Node.js · React · xterm.js |
| [**LinuxMissions**](https://github.com/jalilabdollahi/linuxmissions) | Broken systems: services, packages, cron, users, networking | 500 missions · 26 modules | Python · Bash · Docker |
| [**BashMissions**](https://github.com/jalilabdollahi/bashmissions) | Real scripting tasks with isolated automated tests | 500 levels · 26 modules | Python · Bash |
| [**GitMissions**](https://github.com/jalilabdollahi/gitmissions) | Broken repositories, from first commits to incident war games | 225 missions · 14 modules | Python · Git |
| [**PythonMissions**](https://github.com/jalilabdollahi/pythonmissions) | Broken DevOps scripts, from basics to distributed-systems internals | 300 missions · 2,080 tests | Python · pytest |

**How they are engineered**

- **Behaviour-based validation.** A fix is proven by acting on it: assuming the role, invoking the function, upgrading the release. Over-broad fixes such as `"Action": "*"` or `0.0.0.0/0` are rejected.
- **Every level is tested.** Setup must succeed, a fresh sandbox must fail, and the reference solution must pass.
- **Safe by design.** Isolated sandboxes, local emulators and context guards mean a mission can never touch a real account or cluster.

---

## Other work

- [**Daily Report App**](https://github.com/jalilabdollahi/daily-report-app): full-stack daily work reporting for engineering teams, shipped with Docker, Terraform and GHCR image publishing. *Next.js · PostgreSQL · Prisma*
- **Private repositories**, happy to walk through them in an interview:
  - **InfraPilot**: an AI infrastructure copilot that turns plain-English AWS requests into Terraform plans, with approval gates and cost estimates
  - **Datadog Log Analyzer**: anomaly detection, spike detection and AI-assisted incident summaries for Datadog logs, running as a CLI, a web dashboard or on AWS Lambda
  - **Log Generator**: a realistic microservice log simulator for testing alerting and anomaly-detection pipelines

---

## Tech stack

| Area | Tools |
|---|---|
| **Cloud & containers** | AWS (EKS, ECS Fargate, EC2, Lambda, API Gateway, Kinesis, Bedrock, SSO) · Kubernetes · Docker · Helm |
| **Infrastructure as code** | Terraform · Ansible · Puppet |
| **CI/CD & GitOps** | Jenkins · GitHub Actions · GitLab CI · Argo CD · Flux |
| **Observability** | Datadog · CloudWatch · Prometheus · Grafana · Loki |
| **Security** | HashiCorp Vault · WIZ · CloudTrail · EKS Pod Identity · IAM |
| **Languages** | Go · Bash · Python · C#/.NET |
| **AI & automation** | Claude · OpenAI · Amazon Bedrock · MCP · n8n · structured LLM outputs |

**Languages:** English (professional working proficiency) · German (B2)
