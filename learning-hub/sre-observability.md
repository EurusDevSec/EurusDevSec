# 📊 SRE & Observability Learning Path

<div align="center">

![Track](https://img.shields.io/badge/Track-Site_Reliability_Engineering-006F5D?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Observability_+_Incident_Mgmt-C8A45D?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-10--14_weeks-00A884?style=for-the-badge)

</div>

---

## 🎯 Goal

Build SRE skills from Google's playbook — SLI/SLO/SLA, error budgets, incident management, chaos engineering, and full-stack observability with OpenTelemetry.

---

## 📚 Learning Modules

### Module 1: SRE Foundations (Week 1-2)
- [ ] SRE principles: embracing risk, eliminating toil
- [ ] SLI/SLO/SLA — definitions, relationships, examples
- [ ] Error budgets — calculation and policy
- [ ] Toil identification and automation strategies
- [ ] SRE team structure and responsibilities
- **Lab**: Define SLIs/SLOs for a 3-service application, calculate error budgets

### Module 2: Monitoring vs Observability (Week 3-4)
- [ ] Four golden signals: latency, traffic, errors, saturation
- [ ] RED method (Rate, Errors, Duration) for microservices
- [ ] USE method (Utilization, Saturation, Errors) for infrastructure
- [ ] Metrics, logs, traces — the three pillars
- [ ] Structured logging best practices
- **Lab**: Instrument a microservices app with all three pillars

### Module 3: OpenTelemetry Deep Dive (Week 5-6)
- [ ] OTel architecture: SDK, API, Collector, Exporters
- [ ] Auto-instrumentation vs manual instrumentation
- [ ] Collector deployment patterns (agent, gateway, sidecar)
- [ ] Context propagation and baggage
- [ ] OTel for Kubernetes (Operator, DaemonSet patterns)
- **Lab**: Deploy OTel Collector pipeline with Prometheus + Loki + Tempo

### Module 4: Alerting Engineering (Week 7-8)
- [ ] Alert quality: actionable, relevant, timely
- [ ] Multi-window burn-rate alerting for SLOs
- [ ] Alert routing, escalation, deduplication
- [ ] On-call best practices, rotation design
- [ ] PagerDuty / Opsgenie integration
- **Lab**: Build intelligent alerting pipeline with burn-rate alerts + Slack/PagerDuty

### Module 5: Incident Management (Week 9-10)
- [ ] Incident response process: detect, triage, mitigate, resolve
- [ ] Incident Commander role and responsibilities
- [ ] Communication during incidents (internal + external)
- [ ] Blameless post-mortems — writing effective ones
- [ ] Incident metrics: MTTD, MTTR, TTM
- **Lab**: Run a simulated incident with full post-mortem report

### Module 6: Chaos Engineering (Week 11-12)
- [ ] Principles of chaos engineering
- [ ] Hypothesis-driven experimentation
- [ ] Chaos Mesh / LitmusChaos on Kubernetes
- [ ] Game Day planning and execution
- [ ] Steady-state hypothesis and blast radius control
- **Lab**: Execute 5 chaos experiments, document findings and improvements

### Module 7: Advanced SRE (Week 13-14)
- [ ] Capacity planning and forecasting
- [ ] Release engineering and canary deployments
- [ ] SLO-driven development (SLOs in CI/CD gates)
- [ ] AIOps — AI-assisted root cause analysis
- [ ] Building SRE culture in an organization
- **Lab**: Implement canary deployment with SLO-based auto-promotion/rollback

---

## 🔗 Key Resources

| Resource | Type |
|---|---|
| [Google SRE Book](https://sre.google/sre-book/table-of-contents/) | Free Book |
| [Google SRE Workbook](https://sre.google/workbook/table-of-contents/) | Free Book |
| [Observability Engineering (O'Reilly)](https://www.oreilly.com/library/view/observability-engineering/9781492076438/) | Book |
| [OpenTelemetry Documentation](https://opentelemetry.io/docs/) | Official Docs |
| [Chaos Mesh Documentation](https://chaos-mesh.org/docs/) | Chaos Tool |

---

## ✅ Completion Criteria

- [ ] Define and implement SLOs for a production-like system
- [ ] Build full-stack observability with OTel + Grafana stack
- [ ] Execute 5+ chaos experiments with documented outcomes
- [ ] Conduct a simulated incident with blameless post-mortem
- [ ] Write 3+ blog posts on SRE practices
