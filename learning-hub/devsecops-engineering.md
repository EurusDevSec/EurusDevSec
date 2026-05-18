# 🔐 DevSecOps Engineering Learning Path

<div align="center">

![Track](https://img.shields.io/badge/Track-Security_Engineering-006F5D?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Supply_Chain_+_Pipeline-C8A45D?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-10--14_weeks-00A884?style=for-the-badge)

</div>

---

## 🎯 Goal

Build the skills to embed security into every stage of the software delivery lifecycle — from IDE to runtime. Focus on "Shift Smart" (not just "Shift Left") security that developers actually adopt.

---

## 📚 Learning Modules

### Module 1: Security Fundamentals for DevOps (Week 1-2)
- [ ] OWASP Top 10 (2025) — understanding each vulnerability class
- [ ] CIA Triad, threat modeling (STRIDE), attack surface analysis
- [ ] Linux security fundamentals (permissions, PAM, SELinux/AppArmor)
- [ ] Cryptography basics: TLS, PKI, certificate management
- [ ] Network security: firewalls, VPNs, zero-trust principles
- **Lab**: Threat model a microservices application, identify top 5 risks

### Module 2: Secure CI/CD Pipelines (Week 3-4)
- [ ] CI/CD attack vectors (OWASP CI/CD Top 10)
- [ ] Pipeline hardening: least-privilege runners, ephemeral environments
- [ ] Secret management in pipelines (Vault, GitHub Secrets, OIDC)
- [ ] Branch protection, code review enforcement
- [ ] Build provenance and reproducibility
- **Lab**: Build a hardened GitHub Actions pipeline with secret scanning + OIDC auth

### Module 3: Static & Dynamic Analysis (Week 5-6)
- [ ] SAST tools: Semgrep, CodeQL — writing custom rules
- [ ] SCA tools: Trivy, Grype, Snyk — dependency vulnerability scanning
- [ ] DAST fundamentals: ZAP, Nuclei
- [ ] IaC scanning: Checkov, tfsec, KICS
- [ ] Reducing false positives — triage and prioritization strategies
- **Lab**: Integrate SAST + SCA + IaC scanning into a CI pipeline with quality gates

### Module 4: Container & Kubernetes Security (Week 7-8)
- [ ] Dockerfile best practices (multi-stage, non-root, minimal base)
- [ ] Image scanning and base image policies
- [ ] Kubernetes security: RBAC, PSA, NetworkPolicies
- [ ] Admission controllers: Kyverno, OPA Gatekeeper
- [ ] Runtime security: Falco, Tetragon (eBPF)
- **Lab**: Secure a K8s cluster with PSA + Kyverno + Falco + NetworkPolicies

### Module 5: Supply Chain Security (Week 9-10)
- [ ] SLSA framework (Levels 1-4)
- [ ] Sigstore ecosystem: Cosign, Fulcio, Rekor
- [ ] SBOM standards: CycloneDX, SPDX
- [ ] SBOM generation, storage, and querying
- [ ] Dependency management and lockfile verification
- **Lab**: Implement SLSA L3 pipeline with Cosign signing + SBOM generation

### Module 6: Compliance Automation (Week 11-12)
- [ ] Policy-as-Code with OPA/Rego
- [ ] Compliance frameworks mapping: SOC2, PCI-DSS, HIPAA
- [ ] Automated evidence collection
- [ ] Audit trail implementation
- [ ] Continuous compliance monitoring
- **Lab**: Build automated SOC2 evidence collection from CI/CD pipelines

### Module 7: Advanced Topics (Week 13-14)
- [ ] Cloud security posture management (CSPM)
- [ ] Secret rotation automation with Vault
- [ ] Incident response for DevSecOps teams
- [ ] AI-generated code security risks
- [ ] Zero-trust architecture for microservices
- **Lab**: Implement Vault dynamic secrets with auto-rotation for database credentials

---

## 🔗 Key Resources

| Resource | Type |
|---|---|
| [OWASP CI/CD Security Top 10](https://owasp.org/www-project-top-10-ci-cd-security-risks/) | Security Guide |
| [SLSA Framework](https://slsa.dev/) | Supply Chain Standard |
| [Practical DevSecOps](https://www.practical-devsecops.com/) | Certification Course |
| [Hacking Kubernetes (O'Reilly)](https://www.oreilly.com/library/view/hacking-kubernetes/9781492081722/) | Book |
| [Aqua Security Blog](https://blog.aquasec.com/) | Industry Blog |

---

## ✅ Completion Criteria

- [ ] Build a complete zero-trust CI/CD pipeline
- [ ] Implement SLSA L3 with SBOM in a real project
- [ ] Pass at least one security certification (CDP, CKS, or Practical DevSecOps)
- [ ] Write 3+ blog posts on DevSecOps patterns
- [ ] Contribute to an open-source security tool
