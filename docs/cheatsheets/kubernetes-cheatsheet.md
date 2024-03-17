---
title: Kubernetes Cheat Sheet (Kubectl)
sidebar_position: 3
---

**Basic Pod Management:**

- `kubectl get pods`: List all pods
- `kubectl describe pod <pod_name>`: View details of a pod
- `kubectl delete pod <pod_name>`: Delete a pod
- `kubectl run <pod_name> --image=<image>`: Create a simple pod from an image

**Viewing Resources:**

- `kubectl get nodes`: List all nodes in the cluster
- `kubectl get deployments`: List all deployments
- `kubectl get services`: List all services

**Logs:**

- `kubectl logs <pod_name>`: View logs of a running pod

**Advanced:**

- `kubectl exec -it <pod_name> bash`: Get an interactive shell in a pod
- `kubectl apply -f <yaml_file>`: Apply configurations from a YAML file

**Remember:** `<pod_name>`, `<image>`, and `<yaml_file>` are placeholders for your specific names.

**Bonus:**

- `kubectl port-forward <pod_name> <local_port>:<container_port>`: Forward a port from your machine to a pod
- `kubectl get events`: View recent events in the cluster
- `kubectl top pods`: View resource usage of pods
