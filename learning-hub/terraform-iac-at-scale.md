# 🏗️ Terraform & IaC at Scale Learning Path

<div align="center">

![Track](https://img.shields.io/badge/Track-Infrastructure_as_Code-006F5D?style=for-the-badge)
![Cert](https://img.shields.io/badge/Cert-Terraform_Associate-C8A45D?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-10--12_weeks-00A884?style=for-the-badge)

</div>

---

## 🎯 Goal

Master Terraform from basics to enterprise-scale patterns. Learn modular design, state management, CI/CD integration, and multi-cloud IaC strategies used by platform teams.

---

## 📚 Learning Modules

### Module 1: Terraform Fundamentals (Week 1-2)
- [ ] HCL syntax, providers, resources, data sources
- [ ] Variables, outputs, locals, expressions
- [ ] State management: local vs remote (S3, GCS, Azure Blob)
- [ ] State locking with DynamoDB / Consul
- [ ] Terraform workflow: init → plan → apply → destroy
- **Lab**: Deploy a VPC + EC2 + RDS stack on AWS with remote state

### Module 2: Module Design Patterns (Week 3-4)
- [ ] Module structure: inputs, outputs, versioning
- [ ] Composable modules vs monolithic modules
- [ ] Module registry (public + private)
- [ ] Module testing with Terratest
- [ ] Module documentation generation
- **Lab**: Build reusable VPC, EKS, and RDS modules with versioning

### Module 3: State Management at Scale (Week 5-6)
- [ ] Workspace strategies (per-env vs per-component)
- [ ] State file structure for large organizations
- [ ] State import, move, and refactoring
- [ ] Handling state drift and remediation
- [ ] Terragrunt for DRY configuration
- **Lab**: Set up Terragrunt project with separate state per environment

### Module 4: CI/CD for Terraform (Week 7-8)
- [ ] GitHub Actions / GitLab CI for Terraform
- [ ] Plan → review → apply workflow with PR approvals
- [ ] Automated plan comments on PRs (Atlantis / custom)
- [ ] Policy-as-Code with Sentinel / OPA / Checkov
- [ ] Drift detection scheduled pipelines
- **Lab**: Complete Terraform CI/CD with Atlantis-style workflow + Checkov

### Module 5: Multi-Cloud & Advanced Patterns (Week 9-10)
- [ ] Multi-cloud Terraform (AWS + Azure + GCP in same project)
- [ ] Terraform Cloud / Enterprise features
- [ ] Dynamic blocks, for_each, count patterns
- [ ] Provider aliasing for multi-region/account
- [ ] Custom providers and provisioners
- **Lab**: Multi-cloud deployment with shared networking (AWS VPC ↔ Azure VNet peering)

### Module 6: Certification & Mastery (Week 11-12)
- [ ] HashiCorp Terraform Associate exam domains
- [ ] Practice exams and weak area review
- [ ] Advanced patterns: moved blocks, import blocks (Terraform 1.5+)
- [ ] Pulumi / OpenTofu comparison awareness
- **Lab**: Full enterprise landing zone with modules + CI/CD + policies

---

## 🔗 Key Resources

| Resource | Type |
|---|---|
| [HashiCorp Learn](https://developer.hashicorp.com/terraform/tutorials) | Official Tutorials |
| [Terraform: Up & Running (O'Reilly)](https://www.oreilly.com/library/view/terraform-up-and/9781098116736/) | Book |
| [Terratest](https://terratest.gruntwork.io/) | Testing Framework |
| [Spacelift Blog](https://spacelift.io/blog) | Advanced Patterns |
| [Gruntwork IaC Library](https://gruntwork.io/) | Enterprise Patterns |

---

## ✅ Completion Criteria

- [ ] Build modular, reusable Terraform modules with tests
- [ ] Implement CI/CD for Terraform with policy gates
- [ ] Set up multi-environment infrastructure with Terragrunt
- [ ] Pass Terraform Associate certification
- [ ] Write blog posts on enterprise IaC patterns
