# 🚀 Kubernetes Mastery Learning Path

<div align="center">

![Track](https://img.shields.io/badge/Track-Container_Orchestration-006F5D?style=for-the-badge)
![Cert](https://img.shields.io/badge/Cert-CKA_/_CKAD-C8A45D?style=for-the-badge)
![Duration](https://img.shields.io/badge/Duration-14--18_weeks-00A884?style=for-the-badge)

</div>

---

## 🎯 Goal

Go from Kubernetes fundamentals to production-grade multi-cluster operations. Prepare for CKA/CKAD certifications while building real enterprise skills.

---

## 📚 Learning Modules

### Module 1: Core Concepts (Week 1-3)
- [ ] Kubernetes architecture: API server, etcd, scheduler, kubelet
- [ ] Pods, ReplicaSets, Deployments, StatefulSets, DaemonSets
- [ ] Services: ClusterIP, NodePort, LoadBalancer, ExternalName
- [ ] ConfigMaps, Secrets, Volumes (PV/PVC/StorageClass)
- [ ] Namespaces, Labels, Selectors, Annotations
- **Lab**: Deploy a multi-tier app (frontend + backend + DB) with proper resource management

### Module 2: Networking Deep Dive (Week 4-5)
- [ ] CNI plugins (Calico, Cilium, Flannel) — how they work
- [ ] NetworkPolicies — ingress/egress rules
- [ ] Ingress controllers (NGINX, Traefik, Istio Gateway)
- [ ] DNS in K8s: CoreDNS, service discovery
- [ ] Service Mesh fundamentals (Istio / Linkerd)
- **Lab**: Implement network segmentation with Calico + Ingress routing

### Module 3: Security (Week 6-7)
- [ ] RBAC: Roles, ClusterRoles, Bindings
- [ ] ServiceAccounts, token projection
- [ ] Pod Security Standards/Admission
- [ ] Security Contexts, seccomp, AppArmor
- [ ] Image scanning, admission controllers (Kyverno/OPA)
- **Lab**: Implement multi-tenant cluster with RBAC + NetworkPolicy + PSA

### Module 4: Storage & State (Week 8-9)
- [ ] CSI drivers, StorageClasses, dynamic provisioning
- [ ] StatefulSets for databases (PostgreSQL, MongoDB)
- [ ] Backup strategies (Velero)
- [ ] etcd backup and restore
- **Lab**: Deploy PostgreSQL HA with StatefulSet + Velero backup

### Module 5: Production Operations (Week 10-12)
- [ ] HPA, VPA, Cluster Autoscaler, KEDA
- [ ] Resource requests/limits — QoS classes
- [ ] Monitoring with Prometheus + Grafana
- [ ] Logging with Loki + Promtail
- [ ] Troubleshooting: kubectl debug, ephemeral containers
- **Lab**: Production-ready cluster with autoscaling + monitoring + alerting

### Module 6: Advanced Patterns (Week 13-15)
- [ ] Helm chart development (best practices)
- [ ] Kustomize for environment management
- [ ] Custom Resource Definitions (CRDs)
- [ ] Operator pattern (building custom operators)
- [ ] GitOps with ArgoCD
- **Lab**: Build custom Helm chart + ArgoCD GitOps deployment

### Module 7: CKA/CKAD Exam Prep (Week 16-18)
- [ ] CKA domains: cluster architecture, workloads, services, storage, troubleshooting
- [ ] CKAD domains: app design, deployment, observability, services
- [ ] Timed practice in killer.sh
- [ ] kubectl speed drills (imperative commands)

---

## 🔗 Key Resources

| Resource | Type |
|---|---|
| [Mumshad — CKA Course (KodeKloud)](https://kodekloud.com/courses/certified-kubernetes-administrator-cka/) | Video + Labs |
| [killer.sh CKA Simulator](https://killer.sh/) | Exam Simulator |
| [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) | Deep Dive Lab |
| [CNCF Kubernetes Documentation](https://kubernetes.io/docs/) | Official Docs |
| [Learnk8s](https://learnk8s.io/) | Production Patterns |

---

## ✅ Completion Criteria

- [ ] Pass CKA/CKAD practice exams consistently (>85%)
- [ ] Deploy production-grade cluster with monitoring + GitOps
- [ ] Build a custom K8s operator
- [ ] Write blog posts on production K8s patterns
- [ ] Achieve CKA and/or CKAD certification
