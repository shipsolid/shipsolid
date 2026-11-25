# Amit Singh

**Observability Architect | Building Autonomous Reliability at Scale**  
Distributed Systems · SRE · Platform Engineering

I lead the architecture and adoption of observability platforms across complex enterprise
infrastructure. At **McCain Foods**, I lead a global transformation spanning Azure, Kubernetes, and
on-premises environments — connecting telemetry architecture, platform automation, application
onboarding, and incident response.

My work spans **15+ years in distributed systems and platform engineering**, with a patent in
observability and performance engineering. I stay close to implementation: collector behavior,
resource limits, telemetry schemas, and the failure modes that only become visible in production.

**Open to Principal / Staff engineering and Observability Architect roles.**
[LinkedIn](https://linkedin.com/in/amitsingh007s) · [Portfolio](https://shipsolid.github.io) ·
[Technical blog](https://shipsolid.github.io/blog)

---

## From Platform Architecture to Operational Impact

At McCain, the direction is **Reactive → Resilient → Autonomous**. I bring SRE, platform, and
application teams together around shared telemetry standards, repeatable onboarding, and clearer
operational ownership. Together, we have delivered:

| Outcome                     | Result                       |
| --------------------------- | ---------------------------- |
| Observability onboarding    | **3 days → 30 minutes**      |
| AIOps alert noise           | **80%+ reduction**           |
| ServiceNow ticket noise     | **~60% reduction**           |
| Digital Passport onboarding | **Under 1 hour, end to end** |

The platform combines **Grafana Cloud** as the telemetry data plane, **OpenTelemetry** for
instrumentation, **Grafana Alloy** for collection, and **Helm + Terraform** for repeatable delivery.

## Architecture in Practice

The decisions behind a reliable platform matter as much as the components in it. Recent work:

- **Collector sizing grounded in production behavior.** Derived Alloy resource sizing across six
  components and six environments from measured usage. Fixed a configuration path that declared
  limits without enforcing them, then caught and corrected CPU throttling during rollout validation
  that percentile-based sizing had missed.
- **Collector governance before fleet expansion.** Reviewed OT Alloy deployments for configuration
  drift, resource limits, and uncontrolled process cardinality. Applied hardening across labels,
  collector configuration, WAL governance, and runtime settings before broader rollout.
- **Observability checks that prove something.** Reviewed deployment gates for checks that could
  silently skip validation or fail to block promotion. Proposed environment-aware enforcement,
  accountable exceptions, and recurring signal-freshness checks to detect failures after deployment.

These are the problems I work on: translating platform intent into behavior that can be verified,
operated, and adopted across teams.

---

## Engineering Lab

My personal projects explore telemetry pipelines, infrastructure automation, and agent-assisted
operations. The repositories below are private; work in progress is marked explicitly.

| Project                                                                                                                                  | Focus                                                                                                      |
| ---------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **[app-buddha](https://github.com/shipsolid/app-buddha)**                                                                                | .NET microservice instrumented with OpenTelemetry traces, metrics, and structured logs.                    |
| **[obs-azure-resource-exporter-grafana-cloud](https://github.com/shipsolid/obs-azure-resource-exporter-grafana-cloud)** · in development | Azure Monitor metric collection with remote-write delivery to Grafana Cloud Mimir.                         |
| **[platform-grafana-cloud-terraform](https://github.com/shipsolid/platform-grafana-cloud-terraform)** · in development                   | Grafana Cloud infrastructure managed through Terraform, VCS workflows, and PR-gated environment promotion. |
| **[aiops-sre-agent](https://github.com/shipsolid/aiops-sre-agent)** · experimental                                                       | MCP-backed agent scaffold for alert triage, RCA playbooks, and dry-run incident simulation.                |

My current exploration is **agent-assisted reliability**: making operational knowledge executable
through explicit tool contracts, evaluation, and controlled execution.

## Writing & Speaking

I write about the details that change an architecture decision: telemetry cost, collector failure
modes, access-control gaps, and the limits of operational automation.

Selected writing from **[my technical blog](https://shipsolid.github.io/blog)**:

- _Why Cardinality Kills Observability Platforms (and How to Stop It)_
- _The Self-Silencing Anti-Pattern: Why Your Observability Stack Goes Blind When You Need It_
- _The Grafana Terraform Provider Silently Drops LBAC Rules — and the Three-Layer Fix_
- _Azure provisioning_state: Succeeded Is Not a Health Signal — It Never Was_

**Internal presentation to McCain's CTO:** _From Reactive to Resilient — McCain's Observability in
Motion_.

## Technical Foundation

| Area                      | Stack                                                                                  |
| ------------------------- | -------------------------------------------------------------------------------------- |
| Telemetry                 | OpenTelemetry · Grafana Alloy · Prometheus · Mimir · Loki · Tempo                      |
| Infrastructure & delivery | Azure · AKS / Kubernetes · Helm · Terraform · GitHub Actions · ArgoCD                  |
| Engineering               | Python · .NET · Bash · YAML · Go (learning)                                            |
| Reliability               | SLOs / SLIs · error budgets · alert routing · incident response · telemetry governance |

**M.Tech, Software Engineering — BITS, Pilani**  
GitHub Actions Certified · Microsoft Azure Fundamentals (AZ-900)

---

I'm interested in roles with responsibility for architecture, hands-on engineering, and adoption
across teams — building platforms whose value shows up in onboarding time, operational load, and
incident response.

[Connect on LinkedIn](https://linkedin.com/in/amitsingh007s) ·
[GitHub](https://github.com/shipsolid) · [Portfolio](https://shipsolid.github.io)

Views are my own. Project repositories contain personal lab work; McCain outcomes reflect shared
team delivery under my observability leadership.
