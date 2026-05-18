# ☁️ AWS Solutions Architect Learning Path

<div align="center">

![Track](https://img.shields.io/badge/Track-Cloud_Architecture-006F5D?style=for-the-badge)
![Cert](https://img.shields.io/badge/Cert-SAA--C03-C8A45D?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-12--16_weeks-00A884?style=for-the-badge)

</div>

---

## 🎯 Goal

Master AWS architecture patterns at the Solutions Architect Associate level — then go beyond with real production patterns used in enterprise DevOps.

---

## 📚 Learning Modules

### Module 1: Networking & VPC Design (Week 1-2)
- [ ] VPC architecture: subnets, route tables, IGW, NAT Gateway
- [ ] Multi-AZ and multi-region design patterns
- [ ] VPC Peering vs Transit Gateway vs PrivateLink
- [ ] Security Groups vs NACLs — layered defense
- [ ] VPN & Direct Connect for hybrid cloud
- **Lab**: Design a 3-tier VPC with public/private/isolated subnets across 3 AZs

### Module 2: Compute & Containers (Week 3-4)
- [ ] EC2 instance types, placement groups, pricing models
- [ ] Auto Scaling Groups — target tracking vs step scaling
- [ ] ECS vs EKS — when to use which
- [ ] Fargate vs EC2 launch types
- [ ] Lambda — event-driven architecture patterns
- **Lab**: Deploy a containerized app on EKS with HPA and cluster autoscaler

### Module 3: Storage & Data (Week 5-6)
- [ ] S3 storage classes, lifecycle policies, versioning
- [ ] EBS vs EFS vs FSx — choosing the right storage
- [ ] RDS Multi-AZ vs Aurora Global Database
- [ ] DynamoDB design patterns (GSI, LSI, single-table)
- [ ] Data migration: DMS, Snow Family, Transfer Family
- **Lab**: Build a multi-region Aurora Global Database with automated failover

### Module 4: Security & Identity (Week 7-8)
- [ ] IAM policies deep dive — policy evaluation logic
- [ ] AWS Organizations, SCPs, Control Tower
- [ ] Multi-account strategy (landing zone patterns)
- [ ] KMS, Secrets Manager, Parameter Store
- [ ] GuardDuty, Security Hub, Config Rules
- **Lab**: Implement multi-account landing zone with Organization SCPs

### Module 5: High Availability & Disaster Recovery (Week 9-10)
- [ ] DR strategies: Backup/Restore, Pilot Light, Warm Standby, Active-Active
- [ ] Route 53 routing policies for failover
- [ ] CloudFront + S3 for global content delivery
- [ ] Well-Architected Framework — 6 pillars deep dive
- [ ] Cost optimization patterns (RI, SP, Spot)
- **Lab**: Build active-passive DR across 2 regions with automated failover

### Module 6: IaC & Automation (Week 11-12)
- [ ] CloudFormation vs Terraform on AWS
- [ ] CDK (Cloud Development Kit) patterns
- [ ] Systems Manager: Session Manager, Patch Manager, Run Command
- [ ] EventBridge for event-driven automation
- [ ] Step Functions for workflow orchestration
- **Lab**: Terraform modules for full VPC + EKS + RDS deployment

### Module 7: Exam Prep & Practice (Week 13-16)
- [ ] Review all AWS whitepapers (Well-Architected, Disaster Recovery)
- [ ] Practice exams: Tutorials Dojo, Stephane Maarek
- [ ] Weak area deep dives
- [ ] Time-boxed practice tests (65 questions / 130 minutes)

---

## 🔗 Key Resources

| Resource | Type |
|---|---|
| [Stephane Maarek — SAA-C03 Course](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c03/) | Video Course |
| [Tutorials Dojo Practice Exams](https://tutorialsdojo.com/aws-certified-solutions-architect-associate-saa-c03/) | Practice Tests |
| [AWS Well-Architected Labs](https://www.wellarchitectedlabs.com/) | Hands-on Labs |
| [AWS Whitepapers](https://aws.amazon.com/whitepapers/) | Official Docs |
| [Adrian Cantrill — SAA Course](https://learn.cantrill.io/) | Video Course (Advanced) |

---

## ✅ Completion Criteria

- [ ] Pass SAA-C03 practice exams consistently (>85%)
- [ ] Build 3+ production-pattern labs with Terraform
- [ ] Write blog posts on key architecture patterns
- [ ] Achieve AWS Solutions Architect Associate certification
