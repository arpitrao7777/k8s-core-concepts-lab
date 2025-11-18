# k8s-core-concepts-lab

This repository contains a complete collection of Kubernetes practice files, covering all major concepts required for real-world Kubernetes usage. Each folder represents a specific Kubernetes concept and includes its own **pod.yaml** or related YAML manifests.  
All examples are implemented using clean, production-style Kubernetes YAML files.

---

## **📘 What This Repository Includes**

This repo contains practical implementations of:

- **Pods**
- **Multi-container Pods**
- **Namespaces**
- **Deployments**
- **ReplicaSets**
- **Services (ClusterIP, NodePort, LoadBalancer)**
- **Persistent Volumes (PV)**
- **Persistent Volume Claims (PVC)**
- **Volume concepts**
- **emptyDir volumes**
- **Secrets & ConfigMaps**
- **Network Policies**
- **Resource Requests & Limits**
- **Nginx, Linuxserver, and custom app images**
- **All manifests structured in separate concept folders**

Each concept is written as an individual YAML file to help understand how resources work independently and together.

---

## **🚀 How to Apply YAML Files**

### Apply a single YAML file:

```bash
kubectl apply -f pod.yaml
```
### Apply a full concept folder:

```bash
kubectl apply -f <folder-name>/
```
### View created resources:

```bash
kubectl get pods
kubectl get deployments
kubectl get svc
kubectl get pv
kubectl get pvc
```

---

## **🧩 Concepts Practiced in This Repository**

**✔ Pods**

Simple pods, Nginx pods, resource limits, multi-container pods.

**✔ Deployments**

Rolling updates, replica sets, label selectors.

**✔ Namespaces**
Isolated environments for resource separation.

**✔ Services**
- ClusterIP

- NodePort

- LoadBalancer

Connecting internal and external traffic.

**✔ Volumes**
- emptyDir

- Persistent Volumes (PV)

- Persistent Volume Claims (PVC)

- Mounting volumes inside pods

**✔ Resource Management**
- CPU & memory requests

- CPU & memory limits

**✔ Secrets and ConfigMaps**

Environment variables, volumes, sensitive data handling.

**✔ Network Policies**

Allow/deny traffic between pods.

---

## **📚 Purpose of This Repository**
This repo is designed for:

- Practicing Kubernetes YAML files

- Learning every core concept with hands-on examples

- Preparing for DevOps & Kubernetes interviews

- Understanding real-world cluster configurations

- Running locally using Minikube or Kubernetes in Docker Desktop

---

## **🧪 Recommended Setup**
Use Minikube for testing:

```bash
minikube start
kubectl apply -f .
```

To access NodePort services:

```bash
minikube service <service-name>
```

---

## **📬 Contact**
- Arpit Yadav
- 📱 8307532971
- ✉️ arpit32971@gmail.com
- LinkedIn: https://www.linkedin.com/in/arpit-yadav-786b1622b
