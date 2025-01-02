# metabase-helm-chart
A Helm chart for deploying Metabase on Kubernetes

This chart supports StatefulSet deployment, persistent volume storage, and ingress configuration for secure and scalable Metabase instances.

**Key Features:

StatefulSet Deployment: Ensures Metabase runs in a stateful environment, retaining data across pod restarts.
Customizable Resources: Easily configure CPU, memory, and storage requirements.
Ingress Support: Preconfigured ingress with support for ALB annotations and HTTPS.
Environment Configuration: Set database paths and Java options via environment variables.
Persistent Storage: PVC-backed storage for database files to ensure data persistence.
**Usage:

1. Clone the repository or add it as a Helm repo.
2. Configure settings in values.yaml to suit your environment.

**Deploy using Helm:
helm install metabase ./metabase-helm-chart --values values.yaml

**Ideal For:
1. Teams deploying Metabase on Kubernetes clusters.
2. Environments requiring persistent data storage and scalable configurations.
3. Organizations using AWS ALB ingress for secure external access.
