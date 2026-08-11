# Kubernetes – Hands-on Learning & Practice

## 📌 Description

This repository contains my hands-on learning and practical practice with **Kubernetes (K8s)**.

The repository covers core Kubernetes concepts, workloads, networking, storage, configuration, scaling, scheduling, and Helm. Each topic includes Kubernetes YAML manifests, commands, and practical examples that I used while learning and practicing Kubernetes.

## 🎯 Objective

The main objective of this repository is to build a strong practical understanding of Kubernetes and learn how to deploy, manage, configure, scale, and troubleshoot applications running in a Kubernetes cluster.

## 📚 Topics Covered

### Kubernetes Fundamentals
- Kubernetes Architecture
- Cluster
- Nodes
- Pods
- Containers
- Namespaces
- `kubectl` commands

### Workloads
- Pods
- Deployments
- ReplicaSets
- DaemonSets
- StatefulSets
- Jobs
- CronJobs

### Networking
- Kubernetes Services
- ClusterIP
- NodePort
- LoadBalancer
- Headless Services
- Ingress
- Ingress Controller
- Network Policies

### Configuration & Security
- ConfigMaps
- Secrets
- Environment Variables
- Annotations
- Labels
- Namespaces

### Storage
- Kubernetes Volumes
- `emptyDir`
- PersistentVolumes (PV)
- PersistentVolumeClaims (PVC)
- StorageClasses
- Static Provisioning
- Dynamic Provisioning
- NFS Storage

### Scheduling
- Node Selectors
- Node Affinity
- Pod Affinity
- Pod Anti-Affinity
- Taints
- Tolerations

### Scaling & Availability
- Horizontal Pod Autoscaler (HPA)
- Metrics Server
- Pod Disruption Budgets (PDB)

### Helm
- Helm Fundamentals
- Helm Repositories
- Helm Charts
- Helm Releases
- `values.yaml`
- `helm install`
- `helm upgrade`
- `helm history`
- `helm rollback`
- `helm uninstall`
- Creating Custom Helm Charts

## 🛠️ Tools & Technologies

- Kubernetes
- kubectl
- Helm
- Docker
- Docker Desktop
- YAML
- Linux
- Windows
- PowerShell
- Git
- GitHub

What I Learned

Through these hands-on Kubernetes labs, I gained practical experience in:

Understanding Kubernetes architecture and core components
Creating and managing Pods
Deploying applications using Deployments and ReplicaSets
Exposing applications using Kubernetes Services
Configuring applications using ConfigMaps and Secrets
Managing persistent storage using PVs, PVCs, and StorageClasses
Configuring application networking using Ingress
Implementing Network Policies
Running workloads using StatefulSets and DaemonSets
Scheduling workloads using Jobs and CronJobs
Configuring Pod Affinity, Anti-Affinity, and Node Affinity
Using Taints and Tolerations for workload scheduling
Configuring Horizontal Pod Autoscaling (HPA)
Managing application availability using Pod Disruption Budgets (PDB)
Deploying and managing applications using Helm
Troubleshooting Kubernetes issues using kubectl commands

## 🛠️ Hands-on Practice

The repository contains YAML manifests, configuration files, commands, and practical examples for each Kubernetes topic. These labs were performed in a local Kubernetes environment and are organized topic-wise for easy reference.

## 📁 Repository Structure

KUBERNETES/
│
├── 01_simple_pod/
├── 02_deployments/
├── 03_ingress/
├── 04_configmaps_secrets/
├── 05_namespaces/
├── 06_volumes/
├── 07_statefulsets/
├── 08_HPA/
├── 09_jobs_cronjobs/
├── 10_PDB/
├── 11_miscellaneous_topics/
└── 12_Helm/

