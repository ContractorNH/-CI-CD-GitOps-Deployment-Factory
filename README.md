# CI/CD GitOps Deployment Factory

**From Git to Production. Zero human touch.**

This module creates a full Terraform-backed GitOps delivery system using CodeCommit, CodeBuild, and CodePipeline. Push to Git → trigger infra rollout → monitored builds.

---

## ✅ Features

- CodeCommit repo for GitOps source  
- CodePipeline for secure infra deployment  
- CodeBuild with Terraform support  
- Tag-free, agentless CI/CD  
- End-to-end infrastructure automation

---

## ☁️ Tech Stack

- **Cloud**: AWS  
- **IaC**: Terraform  
- **CI/CD**: CodeCommit, CodeBuild, CodePipeline

---

## 🚀 Usage Example

```hcl
module "gitops_factory" {
  source           = "./modules/cicd_gitops_deployment_factory"
  region           = "us-east-1"
  repository_name  = "contractor-infra-repo"
}
```

> Ensure your IAM roles and `buildspec.yml` support Terraform plans & applies.

---

### [Launch GitOps Factory →](https://opscontractordev.super.site)

> Want access to the full Terraform deployment code?  
> Request private access at [your email] or through [your Super site].


*Generated on 2025-05-22 by The Contractor.*
