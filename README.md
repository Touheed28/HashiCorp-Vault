This project focuses on securing cloud-native infrastructure and application components on AWS using HashiCorp Vault. The goal is to implement best practices for secrets management, access control, and CI/CD integration in a cloud environment.

🔐 Key Modules:
Securing AWS Cloud Infrastructure Management with HashiCorp Vault
Implemented fine-grained access control and secret storage for managing AWS IAM credentials, ensuring secure handling of AWS access keys and tokens.

CI/CD Pipeline Integration with HashiCorp Vault
Integrated Vault into a CI/CD pipeline to dynamically retrieve and inject secrets into the deployment workflow, enhancing pipeline security without hardcoding secrets.

Database Credentials Management with HashiCorp Vault
Used Vault's dynamic secrets engine to generate time-limited database credentials (e.g., for MySQL/PostgreSQL), reducing risks of credential leakage and improving rotation.

Cloud-Native Application Secrets Management with HashiCorp Vault
Managed application-level secrets (like API keys, tokens, config values) using Vault’s key-value store and accessed them securely via environment variables or Vault Agent.

Secure Access Management for Microservices with HashiCorp Vault
Enabled service-to-service authentication and secure secret sharing using Vault's identity-based access and AppRole authentication methods.

🧰 Tools & Technologies:
HashiCorp Vault (Open-source)

AWS Services (EC2, IAM, RDS, etc.)

Terraform (Infrastructure provisioning)

GitHub Actions / Jenkins (CI/CD)

Docker & Microservices Architecture

📘 Project Outcomes:
Enhanced cloud infrastructure security.

Automated secret lifecycle and rotation.

Removed hardcoded credentials from apps and pipelines.

Applied real-world DevSecOps practices.
