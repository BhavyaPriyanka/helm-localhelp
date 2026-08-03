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

## Version
helm version

## Create Helm Chart
helm create <chart-name>

## Validate Chart
helm lint <chart-path>

## Package Chart
helm package <chart-path>

## Add Helm Repository
helm repo add <repo-name> <repo-url>

## List Helm Repositories
helm repo list

## Update Helm Repository
helm repo update

## Search Helm Charts
helm search repo <keyword>

## Install Helm Chart
helm install <release-name> <chart-path>

## Install with Namespace
helm install <release-name> <chart-path> -n <namespace>

## Install and Create Namespace
helm install <release-name> <chart-path> -n <namespace> --create-namespace

## List Helm Releases
helm list

## List Releases in All Namespaces
helm list -A

## Check Release Status
helm status <release-name> -n <namespace>

## Upgrade Release
helm upgrade <release-name> <chart-path> -n <namespace>

## Rollback Release
helm rollback <release-name> <revision-number> -n <namespace>

## View Release History
helm history <release-name> -n <namespace>

## Uninstall Release
helm uninstall <release-name> -n <namespace>

## Render Templates
helm template <release-name> <chart-path>

## Dry Run Installation
helm install <release-name> <chart-path> --dry-run

## Show Installed Manifest
helm get manifest <release-name> -n <namespace>

## Show Release Values
helm get values <release-name> -n <namespace>

## Show Complete Release Information
helm get all <release-name> -n <namespace>

## Update Chart Dependencies
helm dependency update

## List Chart Dependencies
helm dependency list

## Helm Environment Information
helm env

This command creates all required Kubernetes resources defined inside the Helm chart of frontend component.
