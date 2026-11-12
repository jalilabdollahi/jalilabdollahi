# Hi, I'm Jalil 👋

**Cloud DevOps & Platform Engineer** · Duisburg, Germany

I'm the person who gets curious when something breaks. A deploy that fails for no clear reason, a pod that won't schedule, an IAM policy that denies when it shouldn't: that's the part of the job I enjoy most. I like problems that don't have an answer on the first page of search results, and I stay with them until I understand *why* the fix works, not just *that* it works.

---

## What drives me

**I like a challenge.**
Over the years I've kept moving toward the harder problems: from writing C#/.NET applications, to building a data center, to running production AWS and Kubernetes platforms. The work nobody wants to touch is usually the work I volunteer for, like upgrading five EKS clusters across ten Kubernetes versions without a minute of downtime, or rebuilding the legacy Jenkins setup the whole team was afraid of.

**I never stop learning.**
I learn a tool properly by breaking it and fixing it, again and again. That habit grew into the Missions projects below: you don't really understand Helm until you've debugged a few dozen broken releases. Outside of tech, I'm learning German (B2 so far) and still going.

**I build tools so nobody has to suffer twice.**
If something slows me or my teammates down more than once, I'd rather build a tool than repeat the pain. That's how I ended up writing Go tools for SSH and day-to-day infrastructure work, and an LLM-assisted log analyzer that reads application and infrastructure logs and points at the likely root cause. Today most of these tools are built together with Claude.

---

## How I work with AI

AI is part of how I work every day, not a side experiment.

- **Claude is my pair programmer.** I design the idea, the structure and the quality bar, and build it together with Claude Code. Most of the projects on this profile were made that way.
- **I connect models to real systems** through MCP servers, n8n workflows, Amazon Bedrock, and the Claude and OpenAI APIs.
- **I design LLM steps to be reliable**, with structured outputs, guardrails and validation, so they behave like any other component in a pipeline.
- **I stay in charge of the result.** AI makes me much faster, but it doesn't make the decisions. I read what it writes, and I prove it works with tests: every one of the 2,450+ missions below has a check that its broken state fails and its solution passes.
- **I know where it fits.** It's great for log triage, first drafts, tooling and test coverage. It doesn't touch production without a human in the loop.

---

## Things I've built

### Missions: learn DevOps by fixing broken things

A series of free, fully local training games. Each mission drops you into a deliberately broken environment on your own machine. You fix it with the real CLI, and a validator checks the result the way production would. No cloud account, no bill.

| Project | What you fix | Size |
|---|---|---|
| [**AWSMissions**](https://github.com/jalilabdollahi/awsmissions) | IAM, S3, Lambda, VPC, ECS and more, on a local AWS emulator with real IAM evaluation | 268 missions |
| [**K8sMissions**](https://github.com/jalilabdollahi/k8smissions) | Broken clusters, from pod crashes to multi-failure war games | 200 missions |
| [**HelmMissions**](https://github.com/jalilabdollahi/helmmissions) | Broken charts, releases and upgrade paths, with a local OCI registry | 133 missions |
| [**TerraformMissions**](https://github.com/jalilabdollahi/terraformmissions) | Broken HCL, state, modules and tests | 272 missions |
| [**DockerMissions**](https://github.com/jalilabdollahi/dockermissions) | Containers, images, networks and Compose, in a browser terminal | 54 missions |
| [**LinuxMissions**](https://github.com/jalilabdollahi/linuxmissions) | Services, packages, cron, users and networking | 500 missions |
| [**BashMissions**](https://github.com/jalilabdollahi/bashmissions) | Real scripting tasks with automated tests | 500 levels |
| [**GitMissions**](https://github.com/jalilabdollahi/gitmissions) | Broken repositories, up to incident war games | 225 missions |
| [**PythonMissions**](https://github.com/jalilabdollahi/pythonmissions) | Broken DevOps scripts, checked by 2,080 tests | 300 missions |

### Tools for my own work (private)

- **InfraPilot**: an AI infrastructure copilot that turns plain-English AWS requests into Terraform plans, with approval gates and cost estimates
- **Datadog Log Analyzer**: anomaly and spike detection with AI-written incident summaries, as a CLI, a web dashboard or on AWS Lambda

Happy to walk through either of them.

---

## Toolbox

- **Cloud & platforms:** AWS (EKS, ECS, Lambda, Bedrock) · Kubernetes · Helm · Docker
- **Infrastructure & delivery:** Terraform · Ansible · Jenkins · GitHub Actions · Argo CD · Flux
- **Observability & security:** Datadog · Prometheus · Grafana · CloudWatch · Vault · WIZ
- **Code:** Go · Bash · Python · C#/.NET
- **AI:** Claude · Claude Code · MCP · Amazon Bedrock · OpenAI · n8n

---

Always happy to talk about platforms, broken clusters, or how to get more out of AI in day-to-day engineering.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jalil--abdollahi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/jalil-abdollahi)
[![Email](https://img.shields.io/badge/Email-jalil.abdollahi@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jalil.abdollahi@gmail.com)
