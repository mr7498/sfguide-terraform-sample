# sfguide-terraform-sample
This repository provides a comprehensive Terraform setup for managing Snowflake infrastructure as code. It includes modules and examples for provisioning and managing essential Snowflake resources such as users, roles, databases, schemas, warehouses, and cloud storage integrations.

## 🔧 Features

- **Basic Terraform Usage**: Initialize and manage Snowflake infrastructure declaratively using Terraform.
- **Resource Provisioning**:
  - Create Snowflake **users**, **roles**, **databases**, **schemas**, and **warehouses**
  - Define **custom roles**, grant privileges, and assign them to users
- **Object Management via Source Control**:
  - Version control of Snowflake objects like **streams**, **tasks**, **views**, and more
- **Cloud Storage Integration**:
  - Configure external **stages** and **Snowpipe** with cloud providers (e.g., AWS S3, Azure Blob, GCS)
  - Push service user keys to a **secrets manager** (e.g., AWS Secrets Manager, Azure Key Vault)
- **Secure Service User Setup**:
  - Create and rotate keys for non-interactive service accounts used by Snowflake or pipelines

## 🚀 Getting Started

This project includes examples for:

- Initializing a new Terraform project
- Adding a new:
  - **Database**
  - **Warehouse**
  - **Schema**
  - **User**
  - **Role**
  - **Role-based access control (RBAC) grants**
 
## 📝 Prerequisites

- Terraform CLI (v1.0+)
- Snowflake provider for Terraform
- Access to a Snowflake account
- Optional: AWS/GCP/Azure CLI for stage & secrets manager setup

## 📌 Notes

This repository is intended for educational/demo purposes and should be customized for production use. Always follow your organization's security and infrastructure best practices.

---

**Author**: Mayank Rupareliya
