# Helm

Helm is a package manager for Kubernetes that helps deploy, manage, and upgrade Kubernetes applications easily.

It packages Kubernetes resources like Deployments, Services, ConfigMaps, and Secrets into reusable Helm Charts.

Using Helm, we can:

* Deploy applications with a single command
* Manage Kubernetes YAML files using templates
* Maintain different environments using values files
* Upgrade or rollback application versions easily
* Reuse the same deployment configuration across multiple environments

# Helm Commands

| Category | Command | Purpose |
|---|---|---|
| Version | `helm version` | Check Helm version |
| Create Chart | `helm create <chart-name>` | Create a new Helm chart |
| Validate | `helm lint <chart-path>` | Validate Helm chart |
| Package | `helm package <chart-path>` | Package chart into `.tgz` |
| Repository Add | `helm repo add <name> <url>` | Add Helm repository |
| Repository List | `helm repo list` | List Helm repositories |
| Repository Update | `helm repo update` | Update repository information |
| Search | `helm search repo <keyword>` | Search Helm charts |
| Install | `helm install <release> <chart>` | Deploy application |
| Install Namespace | `helm install <release> <chart> -n <namespace>` | Deploy in specific namespace |
| List Releases | `helm list` | List installed releases |
| Status | `helm status <release> -n <namespace>` | Check release status |
| Upgrade | `helm upgrade <release> <chart> -n <namespace>` | Update application deployment |
| History | `helm history <release>` | View release revisions |
| Rollback | `helm rollback <release> <revision>` | Rollback to previous version |
| Uninstall | `helm uninstall <release>` | Remove Helm deployment |
| Template | `helm template <release> <chart>` | Generate Kubernetes YAML |
| Dry Run | `helm install <release> <chart> --dry-run` | Test deployment without installing |
| Manifest | `helm get manifest <release>` | View deployed Kubernetes YAML |
| Values | `helm get values <release>` | View configured values |
| Dependencies | `helm dependency update` | Update chart dependencies |
