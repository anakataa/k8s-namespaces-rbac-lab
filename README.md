# Kubernetes – Namespaces & RBAC (Light) – Self-Guided Labs

📅 **Date:** 27/05/2025 & 03/06/2025  

📦 **Topic:** Kubernetes Namespaces & Role-Based Access Control (RBAC)

👤 **Author:** Staroshchuk Kirill (anakata), StudentID: 29933

---

## 📍 Part 1: Why Namespaces?

Namespaces help organize your Kubernetes cluster into logical environments like:

- `dev`
- `test`
- `prod`

They provide:
- Resource isolation
- Quota management
- Separation between teams/projects

🔗 [Read more about Namespaces](https://kubernetes.io/docs/concepts/overview/working-with-objects/namespaces/)

---

## 🛠️ Part 2: Create a Namespace

Create a `dev` namespace:

```bash
kubectl create namespace dev
