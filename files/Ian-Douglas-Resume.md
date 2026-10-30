# **Ian Douglas**

**Senior Platform Engineer | Cloud & Security Architect**

303-335-9358 | [iancasey.douglas@gmail.com](mailto:iancasey.douglas@gmail.com) | [github.com/iancaseydouglas](https://github.com/iancaseydouglas/resume)


**PROFESSIONAL SUMMARY**

Platform and security engineer with 12+ years delivering secure, code-driven infrastructure for mission-critical services across Kubernetes, AWS, Azure, GCP, and bare metal. Ships platforms as versioned releases through Git-driven automation. Deep experience across the full lifecycle of identity and secrets infrastructure.

**TECHNICAL PROFICIENCIES**

**Platforms & Containers**: Kubernetes (EKS, AKS, GKE, self-managed control plane & etcd, bare metal), Docker, Custom Operators, Versioned Platform Releases, Linux Internals

**Cloud**: AWS (Organizations, multi-account, EC2, VPC, Transit Gateway, Route 53, IAM, KMS, Secrets Manager, Lambda), Azure (AKS, VMSS, Entra ID), GCP (GKE), Hybrid & Multi-Cloud Integration

**Infrastructure as Code & Delivery**: Terraform at scale (à la carte-as-code module design), GitOps (Argo CD, Flux CD), GitHub Actions, GitLab Pipelines, Jenkins, Git & Pull-Request Workflows

**Software & Automation**: Go (Golang), Python (Boto3, Pandas), Bash, PowerShell, SQL, API-Driven Automation, Agentic Development (Claude Code, Codex)

**Identity & Security**: HashiCorp Vault (PKI), SAML/Shibboleth SSO, Kerberos v5, OpenLDAP, Active Directory, Microsoft Entra ID, AWS IAM, AWS KMS, SOPS, Policy-as-Code (OPA), NIST SP 800-207 Zero Trust, Least-Privilege Design

**Networking**: Hybrid Connectivity, Transit Gateway, Site-to-Site VPN, VPC/VNet Peering, Hybrid DNS, IPv6, IPsec, Firewalls, Certificates & PKI

**Databases & Messaging**: Amazon RDS, PostgreSQL, SQL Server, Redis, Memcached, MongoDB, DynamoDB, Cassandra, Kafka, High-Throughput Data Pipelines

**Observability**: Splunk, Prometheus, Grafana, Fluentd, Elasticsearch, Centralized Log Aggregation

**PROFESSIONAL EXPERIENCE**

<div style="break-inside: avoid;">

**The Motley Fool** | Alexandria, VA (Remote)

*Senior Platform Engineer (Contract)* | 04/2026 – Present

* **CI/CD Migration Automation:** Built reusable Python tooling that migrated ~200 repositories from Jenkins to GitHub Actions, including moving secrets from AWS Secrets Manager to dotenvx, saving months of manual effort.

</div>

* **Cloud Infrastructure:** Operate production AWS and Kubernetes infrastructure.
* **AI-Accelerated Engineering:** Developed the migration toolchain with Claude Code agentic workflows, shipping production-grade automation in a fraction of the usual time.

<div style="break-inside: avoid;">

**Kings Mountain Security** | Palo Alto, CA (Remote)

*Co-Founder, DevSecOps Engineer & Security Architect* | 01/2025 – Present

* **Zero Trust Architecture:** Co-founded a security consultancy delivering Terraform-based "Zero Trust Capability Packages" modeled on NIST SP 800-207, turning security requirements into deployable guardrails and technical controls.

</div>

* **Compliance Automation:** Developing Security-as-Code modules that automate DoD Zero Trust compliance across the infrastructure lifecycle.

<div style="break-inside: avoid;">

**FlowDelta Trading** | Boulder, CO (Remote)

*Senior Software Engineer, Python/Data (Contract)* | 01/2025 – 04/2026

* **Backtesting Platform:** Developed a proprietary, multi-horizon analysis platform for a boutique trading desk, enabling rapid backtesting and validation of medium-frequency algorithms.

</div>

* **Data-Intensive Systems:** Engineered a vectorized Monte Carlo simulation engine to perform multi-dimensional parameter grid sweeps.

<div style="break-inside: avoid;">

**ZagTech** | San Jose, CA (Remote)

*Senior Platform Engineer* | 04/2024 – 12/2024

* **À La Carte-as-Code:** Created a radically simple Terraform design for ordering complex Kubernetes clusters from a menu ([Kate's Kitchen](https://github.com/iancaseydouglas/kates-kitchen)).
* **Fleet GitOps:** Designed the Flux repository hierarchy and cluster bootstrap for the commercial platform.

</div>

* **Commercial Platform:** Engineered a proprietary Kubernetes platform deployed across multiple enterprise clients; the codebase was a primary value driver in the firm's subsequent acquisition.
* **Cloud Networking:** Designed Azure network connectivity for client environments, including VNet peering, site-to-site VPN, and hub transit routing.
* **Cost Optimization:** Rightsized and tuned Azure infrastructure to meet client cost requirements.
* **Documentation & Runbooks:** Wrote implementation guides and operational runbooks for client handoff and internal teams.

<div style="break-inside: avoid;">

**Invitae Biosciences** | San Francisco, CA (Remote)

*Senior Platform Engineer* | 07/2023 – 04/2024

* **Research Compute Platform:** Built a self-service platform on self-managed Kubernetes on AWS EC2 for petabyte-scale genomics workloads; executed zero-downtime cluster upgrades and stateful migrations.

</div>

* **Fleet GitOps:** Automated Flux across multi-project, multi-environment cluster fleets with Terraform, Go, and Python, increasing deployment velocity while reducing change failure rates.
* **Cluster Hardening:** Built an automated audit framework enforcing CIS Benchmarks and Pod Security Standards ([Cluster Security Audit](https://github.com/iancaseydouglas/cluster-security-audit)).
* **Secrets Management Architecture:** Designed least-privilege secrets management using SOPS, AWS KMS, and Shamir secret sharing.

<div style="break-inside: avoid;">

**Pearson** | London, UK (Remote)

*Senior Cloud Platforms Engineer* | 09/2019 – 08/2021

* **Multi-Account AWS:** Built and operated platform infrastructure across a multi-account AWS environment managed with AWS Organizations.

</div>

* **GitOps Platform:** Built and operated self-service developer platforms on Kubernetes with GitOps-based continuous delivery, including ephemeral Kubernetes environments for development and testing.
* **Custom Kubernetes Operators:** Wrote Go-based operators to orchestrate AWS services from self-managed Kubernetes on EC2.
* **Centralized Logging:** Implemented log aggregation with a distributed pipeline (Fluentd, Python, AWS Lambda) feeding Elasticsearch and Splunk for real-time analysis.

<div style="break-inside: avoid;">

**Stanford University** | Palo Alto, CA

*DevOps Engineer & Security Architect* | 12/2015 – 09/2019

* **Identity Modernization:** Partnered with Infrastructure teams to move the university's authentication and authorization stack (SAML/Shibboleth SSO, Kerberos v5, OpenLDAP) from legacy servers onto Kubernetes.

</div>

* **Zero-Trust Active Directory:** Architected AD whose domain controllers stay invisible until clients establish IPsec with ephemeral Vault certificates ([paper](https://github.com/iancaseydouglas/resume/blob/main/files/new_directions_in_AD.pdf)).
* **Self-Service Cloud Identity:** Shipped it to production in Terraform over IPv6, so any VPC could join without IP coordination, peering, or NAT/Transit Gateway costs; scales to thousands of VPCs.
* **Hybrid Cloud Networking:** Built connectivity between on-premises infrastructure and AWS using Transit Gateway, site-to-site VPN, and VPC peering.
* **Multi-Account & Multi-Cloud:** Operated AWS Organizations multi-account environments and supported the university's growing GKE footprint alongside self-hosted Kubernetes.
* **Secrets Infrastructure:** Managed multi-tenant HashiCorp Vault clusters providing automated PKI, authentication proxies, and encryption as part of a three-person team.
* **Security Monitoring:** Integrated services with Splunk for centralized logging and security visibility.

<div style="break-inside: avoid;">

**Marvel Heroes (Gazillion Entertainment)** | Foster City, CA

*DevOps Engineer* | 06/2014 – 12/2015

* **Cluster Ops Tooling:** Built PowerShell and SQL Server Management Objects (SMO) tooling to automate database operations and co-developed cluster operations tools for the flagship MMO with 40k+ daily active users and twice weekly deployment cadence. 

</div>

* **Observability at Scale:** Operated large metrics and log aggregation servers for production game infrastructure.

<div style="break-inside: avoid;">

**Two Sigma** | New York, NY

*Systems Engineer* | 05/2012 – 06/2014

* **High-Performance Fleet:** Automated bare-metal provisioning and configuration management for high-performance servers supporting research and trading operations.

</div>

* **Lifecycle Automation:** Orchestrated zero-touch deployment and lifecycle operations of 1,000+ secure workstations firm-wide.

<div style="break-inside: avoid;">

**Columbia University** | New York, NY

*Systems Engineer* | 06/2010 – 05/2012

* **Infrastructure Operations:** Ran databases, ESX, storage, and VM infrastructure supporting Columbia's 22 libraries.

</div>

**EDUCATION**

**University of Denver** | Denver, CO

Bachelor of Arts (BA), Double Major: Mathematics & Philosophy

* **Mathematics:** Completed Bachelor of Science curriculum including grad-level coursework.
* **Philosophy:** Specialized in Formal Logic and Epistemology.