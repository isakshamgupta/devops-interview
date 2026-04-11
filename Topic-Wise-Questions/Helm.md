# Helm Interview Questions (Topic-wise Collection)

---

## Helm Usage

- Its quite difficult to manage manifest files for different services or files like deployments, HPA, secrets, services, ingress. How are you managing them? Did you evaluate any other tools to manage manifest files? *(Entain)*
  - *Answer context: We can actually use helm charts or GitOps tools like ArgoCD for the same. Helm is for complex templating and chart reusability*

---

> **Note:** Helm was not directly asked as a standalone topic across interviews, but was referenced in context of Kubernetes manifest management. Key Helm concepts to prepare:
> - Helm charts structure (Chart.yaml, values.yaml, templates/)
> - Helm install, upgrade, rollback commands
> - Helm release management
> - Values override (--set, -f values.yaml)
> - Helm hooks
> - Chart repositories
> - Helm vs Kustomize
> - Helm templating with Go templates
> - Helm chart versioning and dependency management
