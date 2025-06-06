Let's set up a Kubernetes environment and install Chaos Mesh

Set up environment

```
minikube start
```

Check Kubernetes Installation

```
kubectl version 
```

Install chaos mesh

```
curl -sSL https://mirrors.chaos-mesh.org/v1.0.3/install.sh | bash
```

Verify installation

```
kubectl get pod -n chaos-testing
```

