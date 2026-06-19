# Amit Singh

## Observability Architect · Patent Holder · SRE @ Scale

> Grafana Cloud · OpenTelemetry · Kubernetes · Terraform · Azure

---

I design and operate large-scale observability platforms. Currently leading a global observability
transformation at **McCain Foods** — 200+ workloads across Azure, on-premises, and SAP RISE —
reducing observability provisioning time **from 3 days to 30 minutes**, AIOps alert noise by
**80%+**, and SNOW ticket volume by **~60%**, using Grafana Cloud and OpenTelemetry.

📄 **Patent holder** in the observability domain.  
🕐 14 years across full-stack, performance engineering, platform engineering, and SRE.

---

## What I Build

| Project                                                                                                                             | Description                                                                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[app-signal-forge](https://github.com/shipsolid/app-signal-forge)** _(private)_                                                   | End-to-end OTel reference lab — Angular Faro, .NET gRPC services, Python FastAPI, RabbitMQ, Grafana Alloy DaemonSet                                 |
| **[app-online-boutique](https://github.com/shipsolid/app-online-boutique)** _(private)_                                             | Polyglot microservices demo — instrumented reference app for canary deployments and observability validation                                        |
| **[app-buddha](https://github.com/shipsolid/app-buddha)** _(private)_                                                               | .NET microservice with full OpenTelemetry instrumentation — traces, metrics, structured logs                                                        |
| **[app-saha-ai](https://github.com/shipsolid/app-saha-ai)** _(private)_                                                             | Mental-health AI companion — spec-first design with OpenAPI contract, versioned prompt registry, eval cases, and safety guardrails                  |
| **[app-fake-store-ingestor-dotnet](https://github.com/shipsolid/app-fake-store-ingestor-dotnet)** _(private)_                       | OTel-instrumented .NET ingestor for FakeStore API — generates realistic e-commerce telemetry signals for pipeline and dashboard validation          |
| **[platform-k8s-infra-terraform](https://github.com/shipsolid/platform-k8s-infra-terraform)** _(private)_                           | Azure platform Terraform — AKS, VNet, Key Vault modules; OPA/Rego policies; Infracost budgets                                                       |
| **[platform-k8s-runtime](https://github.com/shipsolid/platform-k8s-runtime)** _(private)_                                           | GitOps delivery platform — ArgoCD + Argo Rollouts canary, reusable GitHub Actions workflows                                                         |
| **[platform-grafana-cloud-terraform](https://github.com/shipsolid/platform-grafana-cloud-terraform)** _(private)_                   | HCP Terraform + VCS-driven Grafana Cloud management — Azure Blob state, PR-gated environment promotion                                              |
| **[platform-grafana-cloud-terraform-v1](https://github.com/shipsolid/platform-grafana-cloud-terraform-v1)** _(private)_             | Jinja2-rendered Terraform stack for Grafana Cloud — dual-environment (dev/prod) with `tf.sh` CLI driver                                             |
| **[reliability](https://github.com/shipsolid/reliability)** _(private)_                                                             | SRE practice surface — SLO/SLI catalog, error-budget policy, chaos runbooks, incident response, post-mortems                                        |
| **[observability](https://github.com/shipsolid/observability)** _(private)_                                                         | Production Grafana Cloud observability platform — Alloy pipelines, alert packs, synthetic monitoring, OPA conftest gates                            |
| **[devx-runway-backstage](https://github.com/shipsolid/devx-runway-backstage)** _(private)_                                         | Internal developer platform — Backstage + ArgoCD + Crossplane + Kyverno + Linkerd + Grafana Cloud on a 5-cluster k3d substrate                      |
| **[aiops-llm-wiki](https://github.com/shipsolid/aiops-llm-wiki)** _(private)_                                                       | LLM wiki pipeline — one-way Notion → Ollama → GitHub sync with domain-aware transformation and journal privacy guardrails                           |
| **[aiops-llm-local](https://github.com/shipsolid/aiops-llm-local)** _(private)_                                                     | Local LLM sandbox — Ollama-backed, catalog-driven model runner with a CLI harness for offline inference and prompt experiments                      |
| **[aiops-sre-agent](https://github.com/shipsolid/aiops-sre-agent)** _(private)_                                                     | SRE agent scaffold — MCP-backed agentic layer for alert triage, RCA playbook execution, and dry-run incident simulation                             |
| **[aiops-sre-assistant-v1](https://github.com/shipsolid/aiops-sre-assistant-v1)** _(private)_                                       | Full SRE assistant service — FastAPI + Streamlit, Redis state store, MCP sidecar, Azure AD RBAC, and validator gate architecture                    |
| **[ai-observability-platform](https://github.com/shipsolid/ai-observability-platform)** _(private)_                                 | AI-powered observability layer — ML-assisted anomaly detection, adaptive alerting, and AIOps signal enrichment on Grafana Cloud                     |
| **[observability-samples](https://github.com/shipsolid/observability-samples)** _(private)_                                         | Reference observability configs — Alloy pipelines, OTel collectors, alert rules, and SLO samples for common Kubernetes workload patterns            |
| **[platform-samples](https://github.com/shipsolid/platform-samples)** _(private)_                                                   | Platform infrastructure samples — Terraform modules, Helm charts, ArgoCD app templates, and OPA policies for common Azure patterns                  |
| **[app-samples](https://github.com/shipsolid/app-samples)** _(private)_                                                             | Polyglot demo services — Go, Python, and .NET apps with OTel instrumentation for testing observability pipelines and dashboards                     |
| **[obs-azure-resource-exporter-grafana-cloud](https://github.com/shipsolid/obs-azure-resource-exporter-grafana-cloud)** _(private)_ | Custom Azure resource exporter — scrapes Azure Monitor metrics and forwards to Grafana Cloud Mimir via remote-write                                 |
| **[agenticai-persona-harness](https://github.com/shipsolid/agenticai-persona-harness)** _(private)_                                 | Multi-persona agent harness — framework for composing and switching Claude AI personas with per-domain context, skills, and memory isolation        |
| **[agenticai-sre-war-room](https://github.com/shipsolid/agenticai-sre-war-room)** _(private)_                                       | Agentic SRE war room — multi-agent incident command system with real-time alert correlation, automated RCA, and coordinated response playbooks      |
| **[agentic-cerebral](https://github.com/shipsolid/agentic-cerebral)** _(private)_                                                   | Agentic AI layer for CEREBRAL PKM — Claude-powered knowledge flywheel (Capture → Refine → Atoms → Layers → Artifacts) with Notion as the data plane |

---

## Stack

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

---

## Currently

- Building **AIOps + LLMOps** tooling as a differentiated observability layer
- Actively engaged with the CNCF ecosystem — OpenTelemetry, Grafana Alloy
- Open to **Principal/Staff SRE and Observability Architect** opportunities in distributed systems

---

## Activity

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=shipsolid&theme=react-dark&hide_border=true&area=true)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-amitsingh007s-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/amitsingh007s)
[![X](https://img.shields.io/badge/X-@amitsingh007s-000000?style=flat&logo=x&logoColor=white)](https://twitter.com/amitsingh007s)
[![Portfolio](https://img.shields.io/badge/Portfolio-shipsolid.github.io-FF5722?style=flat&logo=github&logoColor=white)](https://shipsolid.github.io)

---

Views are my own. All implementations are personal/lab work, not employer IP.
