# 🚀 Kubernetes Practice Repository

This repository contains **hands-on Kubernetes YAML configuration files** created for learning and practicing core Kubernetes concepts step-by-step.

It covers important Kubernetes resources such as Pods, Deployments, Services, Namespaces, Storage, Ingress, CronJobs, and more.

---

# 📂 Project Structure

## 1️⃣ Workload Resources

### ✅ Pod

* `pod.yml`
* Basic Kubernetes Pod configuration.
* Used to run a single container application.

### ✅ Deployment

* `deployment.yml`
* Manages multiple replicas of Pods.
* Supports rolling updates and rollback.

### ✅ ReplicaSet

* `replicasets.yml`
* Maintains a stable set of running pod replicas.

### ✅ DaemonSet

* `daemonset.yml`
* `daemonsets.yml`
* Runs one Pod on every node in the cluster.

---

## 2️⃣ Networking

### ✅ Service

* `service.yml`
* Exposes Pods internally or externally.

### ✅ Ingress

* `ingress.yml`
* Manages HTTP/HTTPS routing using domain paths.

---

## 3️⃣ Scheduling & Automation

### ✅ Cron Job

* `cron-job.yml`
* Runs scheduled Kubernetes jobs automatically.

---

## 4️⃣ Namespace Management

### ✅ Namespace

* `namespace.yml`
* Logical separation of cluster resources.

---

## 5️⃣ Storage Management

### ✅ Persistent Volume (PV)

* `persistentvolume.yml`
* Provides storage resources inside cluster.

### ✅ Persistent Volume Claim (PVC)

* `persistentVolumeClaim.yml`
* Requests storage from available volumes.

---

## ⚙️ How to Use

Apply any resource using:

```bash
kubectl apply -f <filename>.yml
```

Example:

```bash
kubectl apply -f deployment.yml
```

---

## 🔎 Useful Commands

Check Pods:

```bash
kubectl get pods
```

Check Services:

```bash
kubectl get svc
```

Check All Resources:

```bash
kubectl get all
```

---

## 🎯 Purpose

* Kubernetes Hands-on Practice
* DevOps Learning
* YAML Configuration Understanding
* Real Cluster Testing

---

## 👨‍💻 Author

Himanshu Gohil

---

## ⭐ Notes

* These files are created for learning and experimentation.
* Modify configurations according to your cluster setup.

Happy Learning 🚀
