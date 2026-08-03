# Helm

Helm is a package manager for Kubernetes that helps deploy, manage, and upgrade Kubernetes applications easily.

It packages Kubernetes resources like Deployments, Services, ConfigMaps, and Secrets into reusable Helm Charts.

Using Helm, we can:

* Deploy applications with a single command
* Manage Kubernetes YAML files using templates
* Maintain different environments using values files
* Upgrade or rollback application versions easily
* Reuse the same deployment configuration across multiple environments

Example:

```bash
helm install frontend ./frontend
```

This command creates all required Kubernetes resources defined inside the Helm chart of frontend component.
