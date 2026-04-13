<div align="center">

# Jalil Abdollahi

**Infrastructure Engineer · AI Tooling · Platform Education**

I build tools that make cloud infrastructure approachable — AI-powered copilots that translate intent into real deployments, and hands-on training platforms where engineers learn by breaking real systems and fixing them.

[![Email](https://img.shields.io/badge/Email-jalil.abdollahi@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jalil.abdollahi@gmail.com)

</div>

---

## Mission-Based Learning Platforms

A series of fully local, game-based training platforms. Each one drops you into a deliberately broken environment and makes you fix it with real CLI commands — no cloud bill, no account required.

---

### [K8sMissions](https://github.com/jalilabdollahi/k8smissions) — Learn Kubernetes by breaking it

> 200 progressive challenges · 12 modules · Beginner to production SRE

Each mission presents a deliberately broken Kubernetes cluster. Diagnose and fix it using real `kubectl` commands. Features a rich terminal UI with XP progression, hint unlocking, watch mode, dry-run support, and module certificates.

**Stack:** Python · Rich · kind · kubectl

---

### [AWSMissions](https://github.com/jalilabdollahi/awsmissions) — Learn AWS by fixing it locally

> 196 progressive missions · 12 modules · No AWS account required

A fully local AWS training game powered by LocalStack. Each mission drops you into a broken cloud environment — investigate what went wrong and repair it with the real `aws` CLI. Every level includes hints, a reference solution, and a debrief explaining the failure.

**Stack:** Python · Rich · LocalStack · AWS CLI · Docker

---

### [TerraformMissions](https://github.com/jalilabdollahi/terraformissions) — Learn Terraform by breaking it

> 272 missions · 15 modules · Fundamentals to production war games

Each mission delivers a broken `.tf` configuration. Fix it using real Terraform commands — `init`, `validate`, `plan`, `apply`. Covers HCL, state management, modules, testing, debugging, and production patterns.

**Stack:** Python · Rich · Terraform · local providers

---

### [LinuxMissions](https://github.com/jalilabdollahi/linuxmissions) — Learn Linux by fixing real terminal problems

> 500 challenges · 26 modules · Navigation to Linux war games

A game-based Linux training platform with sandboxed missions under `/tmp/linuxmissions/`. Each level has a broken or incomplete state to fix with shell commands. Includes debriefs, tab autocomplete, XP tracking, and progressive hints.

**Stack:** Python · Rich · Bash · sandbox isolation

---

### [BashMissions](https://github.com/jalilabdollahi/bashmissions) — Learn Bash scripting through short, progressive challenges

> 500 levels · 26 modules · Beginner to expert scripting

Each level gives you a real scripting task with automated tests, hints that escalate into walkthroughs, and a reference solution. Watch mode reruns validation automatically as you write. Includes a general Bash handbook via `guide bash`.

**Stack:** Python · Rich · Bash · automated test runner

---

### [GitMissions](https://github.com/jalilabdollahi/gitmissions) — Learn Git by breaking it — then fixing it

> 225 challenges · 14 modules · First commits to incident war games

Each mission drops you into a deliberately broken Git repository. Diagnose the state, fix it with real `git` commands, and pass automated validation. Post-mission debriefs explain why your fix worked.

**Stack:** Python · Rich · Git

---

### [DockerMissions](https://github.com/jalilabdollahi/dockermissions) — Learn Docker in a real terminal, in your browser

> 54 missions · 8 modules · Containers to production patterns

A browser-based Docker training game with an in-browser bash session connected to a live Docker environment. Instant automated validation, smart error analysis, XP progression, badges, and a leaderboard — all running locally.

**Stack:** Node.js · React · xterm.js · Docker · Socket.IO

---

## AI & Cloud Tools

---

### [InfraPilot](https://github.com/jalilabdollahi/InfraPilot) — AI infrastructure copilot for AWS

> Plain-English requests → Terraform plans → approval gates → real deployments

InfraPilot translates natural-language AWS requests into structured Terraform configurations, runs them through approval workflows, applies them, validates the result, and produces a deployment report. Available as a CLI, REST API, and web app — all backed by the same core agent runtime.

**Highlights:**
- Natural-language intent captured and converted to Terraform specs
- Approval-first workflow with pre-deployment cost estimates
- Pluggable LLM providers: Bedrock, Anthropic, OpenAI, or mock
- Git-aware sessions with sync and report export
- Local demo mode — explore the product without touching AWS

**Stack:** Python · Next.js · Terraform · AWS · FastAPI

---

### [KubeGuardian](https://github.com/jalilabdollahi/kubeguardian) — Kubernetes operations and risk detection

> Connect to any cluster · detect misconfigurations · output JSON, table, or Markdown

KubeGuardian scans your cluster state — nodes, pods, deployments, replicasets, namespaces — and surfaces operational misconfigurations, security risks, and availability issues using a set of built-in detection rules. CI/CD ready with configurable severity thresholds.

**Stack:** Python · Kubernetes API · fully typed

---

### [Datadog Log Analyzer](https://github.com/jalilabdollahi/datadog-log-analyzer) — Anomaly detection and incident reporting for Datadog logs

> CLI · Web dashboard · AWS Lambda — same analysis engine across all modes

Turns noisy Datadog log streams into actionable findings. Features pattern detection via tokenization and fingerprinting, spike detection, error correlation across services, trend analysis with rolling baselines, and AI-assisted incident summaries via Bedrock. Outputs Slack alerts, Jira tickets, HTML and JSON reports.

**Stack:** Python · Datadog API · AWS Lambda · DynamoDB · Bedrock · Docker · Helm

---

### [Log Generator](https://github.com/jalilabdollahi/log-generator) — Realistic microservice log simulator for observability testing

> 10 simulated microservices · structured JSON · scenario-based incidents · Datadog-ready

Simulates believable operational noise and targeted failure bursts for testing log pipelines, alerting rules, and anomaly detection workflows — without waiting for a real outage. Pure Python standard library, local file output, and optional Docker support.

**Stack:** Python · Docker · Datadog host-agent integration

---

## Web Applications

---

### [Agency SaaS Platform](https://github.com/jalilabdollahi/agency-saas-platform) — Full-stack agency website and client operations platform

> Lead capture · client portal · support tickets · admin console · multilingual

A production-style Next.js application combining a marketing site with client onboarding, a support ticket system, admin workflows, blog content, authentication, and email integration. Built for real agency operations, not a landing page demo.

**Stack:** Next.js 14 · PostgreSQL · Prisma · NextAuth · Resend · Upstash Redis · next-intl

---

### [Daily Report App](https://github.com/jalilabdollahi/daily-report-app) — Structured daily work reporting platform for engineering teams

> Task logging · admin oversight · export · analytics · production-ready deployment

A full-stack reporting system for recording daily technical work by date, tracking progress, and producing operational reports. Includes search and filtering, attachments, bulk workflows, a duplicate-previous-day shortcut, admin controls, and production tooling with Docker, Terraform, and GHCR image publishing.

**Stack:** Next.js 14 · PostgreSQL · Prisma · NextAuth v5 · Docker · Terraform

---

### [AI Chat](https://github.com/jalilabdollahi/ai-chat-backend) — Real-time chat with optional AI-powered responses

> WebSocket messaging · JWT auth · PostgreSQL · OpenAI integration

A real-time chat backend built with Express and Socket.IO, with JWT-secured REST and WebSocket endpoints, PostgreSQL persistence, and optional OpenAI-powered responses. Paired with a modern React frontend.

**Stack:** Node.js · Express · Socket.IO · PostgreSQL · JWT · React · OpenAI API

---

<div align="center">

**jalil.abdollahi@gmail.com**

</div>
