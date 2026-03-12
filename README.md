# terraform-aws-infrastructure
**Terraform AWS Infrastructure**

Infrastructure as Code project provisioning cloud resources using Terraform.

---

**Overview**

This project demonstrates how to provision cloud infrastructure using Terraform.
It includes modular configurations for networking and compute resources.

The goal is to manage infrastructure declaratively and maintain reproducible environments.

---

**Technologies**

- Terraform
- AWS
- Infrastructure as Code

---

**Architecture**

Terraform provisions infrastructure resources such as VPC and EC2 instances.

```
Terraform
   │
   ▼
AWS API
   │
   ▼
VPC + EC2
```

---

**Repository Structure**
```
terraform-aws-infrastructure
│
├ modules
│   ├ vpc
│   └ ec2
│
├ main.tf
├ variables.tf
└ outputs.tf
```

---

**Deployment**

**Initialize Terraform:**

terraform init

**Plan infrastructure:**

terraform plan

**Apply configuration:**

terraform apply

---


**Features**

- Modular infrastructure design
- Reproducible infrastructure deployments
- Infrastructure version control
