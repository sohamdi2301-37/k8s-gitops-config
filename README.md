# End-to-End Production-Grade Kubernetes Platform

## Project Overview
This project establishes a production-ready, GitOps-driven Kubernetes platform featuring automated node provisioning, declarative application lifecycle management via ArgoCD, dynamic pod autoscaling, and cluster observability with Prometheus and Grafana.

## Key Capabilities & Architecture
* **Infrastructure Configuration (`k8s-ansible-config`):** Ansible playbooks for OS setup, containerd runtime configuration, and system-level Node Exporter metrics setup.
* **GitOps Engine (`k8s-gitops-config`):** Helm charts managing microservices across staging and production namespaces with declarative ArgoCD deployment patterns.
* **Autoscaling & Resilience:** Horizontal Pod Autoscaler (HPA) specs configured for dynamic load handling (2 to 8 replicas).
* **Monitoring & Observability:** Integrated Prometheus and Grafana stack with custom alerting rules for pod restarts and node health.

## Associated Repositories
* **GitOps Configuration Repository:** `https://github.com/sohamdi2301-37/k8s-gitops-config`
* **Ansible Infrastructure Repository:** `https://github.com/sohamdi2301-37/k8s-ansible-config`
