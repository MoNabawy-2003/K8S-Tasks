# Task 5: Namespace Quota and Deployment Limitation

## 📋 Description
- Create a namespace named `depi`.
- Limit the namespace to **1 Pod** and **1 Deployment** using a ResourceQuota.
- Attempt to create a Deployment with 3 replicas and observe the behavior (quota restrictions).
- Show `kubectl get pods -n depi` output to demonstrate the effect.

## 🛠️ Components Used
- **Namespace**: Isolates resources (`depi`)
- **ResourceQuota**: Enforces resource limits on the namespace
- **Deployment**: Manages pod replicas (limited by quota)
