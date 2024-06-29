# Table of Contents

- [Module 1 - Docker Fundamentals](#module-1---docker-fundamentals)
- [Module 2 - CLI Installation](#module-2---cli-installation)
- [Module 3 - Kubernetes Overview](#module-3---kubernetes-overview)
- [Module 4 - Getting Started with Amazon EKS](#module-4---getting-started-with-amazon-eks)
- [Module 5 - YAML Basics](#module-5---yaml-basics)
- [Module 6 - Kubernetes Basics](#module-6---kubernetes-basics)
- [Module 7 - Kubernetes Services](#module-7---kubernetes-services)
- [Module 8 - Kubernetes Ingress Controller](#module-8---kubernetes-ingress-controller)
- [Module 9 - Kubernetes ConfigMaps and Secrets](#module-9---kubernetes-configmaps-and-secrets)
- [Module 10 - Kubernetes DaemonSets](#module-10---kubernetes-daemonsets)
- [Module 11 - Kubernetes StatefulSets](#module-11---kubernetes-statefulsets)
- [Module 12 - Kubernetes Volumes](#module-12---kubernetes-volumes)
- [Module 13 - Resource Monitoring using Metrics Server](#module-13---resource-monitoring-using-metrics-server)
- [Module 14 - Kubernetes Autoscaling (HPA, VPA)](#module-14---kubernetes-autoscaling-hpa-vpa)
- [Module 15 - Kubernetes Cluster AutoScaler](#module-15---kubernetes-cluster-autoscaler)
- [Module 16 - Kubernetes Probes](#module-16---kubernetes-probes)
- [Module 17 - Kubernetes Administration](#module-17---kubernetes-administration)
- [Module 18 - Kubernetes Taints and Tolerations](#module-18---kubernetes-taints-and-tolerations)
- [Module 19 - Logging in Kubernetes](#module-19---logging-in-kubernetes)
- [Module 20 - Monitoring in Kubernetes](#module-20---monitoring-in-kubernetes)
- [Module 21 - Helm with Kubernetes](#module-21---helm-with-kubernetes)
- [Module 22 - EKS Upgrade Process](#module-22---eks-upgrade-process)

---

## Module 1 - Docker Fundamentals

- Difference between Containerization & virtual machines
- Docker Overview
- Exploring the available docker components
- Installation of docker in Linux
- Installation of docker in Ubuntu
- Installation of docker in Windows
- Dockerfile Overview
- Dockerfile Demo Part 1
- Dockerfile Demo Part 2
- Overview of DockerHub
- Docker image commands Part 1
- Docker image commands Part 2
- What is AWS ECR?
- Pushing docker image to AWS ECR

## Module 2 - CLI Installation

- Installation of AWS CLI in Windows
- Installation of AWS CLI in Linux
- Installation of AWS CLI in Ubuntu
- Creation of AWS IAM User
- Install kubectl CLI in Windows
- Install kubectl CLI in Linux
- Install eksctl CLI in Windows
- Install eksctl CLI in Linux

## Module 3 - Kubernetes Overview

- What is Kubernetes
- Why Kubernetes
- Advantages of Kubernetes
- Kubernetes Architecture

## Module 4 - Getting Started with Amazon EKS

- Introduction about AWS EKS
- Creation of AWS EKS Cluster
- Adding Worker Nodes to EKS Cluster
- How to Connect to an Amazon EKS Cluster Using the Command Line Interface (CLI)
- Deleting an Amazon EKS Cluster

## Module 5 - YAML Basics

- Introduction to YAML
- YAML Syntax and Structure

## Module 6 - Kubernetes Basics

- Kubernetes Objects and API Versions
- Lab Session - Creating a Pod Using Imperative Commands in Kubernetes
- Lab Session - Creating Pods with YAML using Declarative Syntax
- Developing Kubernetes Manifest Files using Editor.
- Lab Session - Replication Controllers and ReplicaSets
- Lab Session - Deployments
- Lab Session - Updating and Rolling Back Deployments

## Module 7 - Kubernetes Services

- What are Kubernetes Services
- Types of Kubernetes Services
- What is ClusterIP
- Lab Session - ClusterIP
- Lab Session - NodePort
- Lab Session - Load Balancer

## Module 8 - Kubernetes Ingress Controller

- What is Kubernetes Ingress Controller
- Ingress Controller Features
- Lab Session - Installing and Configuring an Ingress Controller

## Module 9 - Kubernetes ConfigMaps and Secrets

- Introduction to Kubernetes ConfigMaps
- Lab Session - Kubernetes ConfigMaps
- Introduction to Kubernetes Secrets
- Lab Session - Kubernetes Secrets

## Module 10 - Kubernetes DaemonSets

- What are Kubernetes DaemonSets
- Purpose of DaemonSets
- Lab Session - Deploying DaemonSets

## Module 11 - Kubernetes StatefulSets

- What are Kubernetes StatefulSets
- Use Cases for StatefulSets
- Lab Session - Kubernetes StatefulSets

## Module 12 - Kubernetes Volumes

- Overview of Volumes
- Types of Volumes
- What is Persistent Volumes and Claims
- Lab Session - Provisioning and Managing PVs and PVCs
- What is Storage Classes
- Lab Session - Storage Classes

## Module 13 - Resource Monitoring using Metrics Server

- What is Metrics Server
- Metrics Server Architecture
- Resource Metrics in Kubernetes
- Lab Session - Installation and Configuration of Metrics Server

## Module 14 - Kubernetes Autoscaling (HPA, VPA)

- Introduction to Horizontal Pod Autoscaling (HPA)
- Lab Session - Creating and Managing HPA Resources
- Introduction to Vertical Pod Autoscaling (VPA)
- Lab Session - Creating and Managing VPA Resources

## Module 15 - Kubernetes Cluster AutoScaler

- What is Cluster Autoscaler
- Create IAM OIDC provider
- Create IAM policy for Cluster Autoscaler
- Create IAM role for Cluster Autoscaler
- Deploy Kubernetes Cluster Autoscaler
- Create an Nginx deployment to test the Cluster Autoscaler functionality

## Module 16 - Kubernetes Probes

- What are Probes in Kubernetes
- Types of Probes (Readiness, Liveness)
- Lab Session - Configuring Readiness Probes
- Lab Session - Configuring Liveness Probes
- Simulating Application Failures

## Module 17 - Kubernetes Administration

- What are Kubernetes Namespaces?
- Why use Namespaces for workload isolation and organization?
- Default Namespaces and system Namespaces.
- Lab Session - Creating and deleting Namespaces.
- What are Resource Quotas?
- Why use Resource Quotas for resource management?
- Resource Quotas vs. LimitRanges.
- Lab Session - Configuring Resource Quotas
- What is RBAC in Kubernetes?
- Why is RBAC important for cluster security?
- RBAC components: Roles, RoleBindings, ClusterRoles, and ClusterRoleBindings.
- What is Role and RoleBinding in Kubernetes
- Lab Session - Creating and testing Roles and RoleBindings.
- What is ClusterRoles and ClusterRoleBindings
- Lab Session - Creating and testing ClusterRoles and ClusterRoleBindings.

## Module 18 - Kubernetes Taints and Tolerations

- What is Taints and Tolerations
- Lab Session - Applying Taints to Nodes
- Creating Toleration Specifications
- Lab Session - Implementing Taints and Tolerations
- Node Affinity and Node Anti-Affinity in Kubernetes
- Lab Session - Implementing Node Affinity and Node Anti-Affinity

## Module 19 - Logging in Kubernetes

- Explanation of EFK: Elasticsearch, Fluentd, Kibana
- What is Elasticsearch?
- What is Kibana?
- Lab Session - Setting up Elasticsearch and Kibana in AWS
- What is Fluentd?
- Lab Session - Deploying Fluentd as a Daemonset for Log Collection and sending logs to Elasticsearch

## Module 20 - Monitoring in Kubernetes

- What is Monitoring in Kubernetes
- What is Prometheus
- Lab Session - Installing and configuring Prometheus in a Kubernetes cluster.
- What is Grafana?
- Lab Session - Deploying Grafana in Kubernetes for visualization.
- Lab Session - Configuring data sources and dashboards in Grafana.

## Module 21 - Helm with Kubernetes

- What is Helm?
- Lab Session - Installation of Helm 2 in Linux
- Lab Session - Installation of Helm 2 in Windows
- Lab Session - Installation of Helm 3 in Linux
- Lab Session - Installation of Helm 3 in Windows
- What is Helm Charts
- Lab Session - Deploying the application in Kubernetes using Helm

## Module 22 - EKS Upgrade Process

- Preparing for EKS Upgrade
- Lab Session - Upgrading AWS EKS
