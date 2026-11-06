# Ian Douglas

**Senior Platform Engineer | Cloud & Security Architect**

303-335-9358 | [iancaseydouglas@gmail.com](mailto:iancaseydouglas@gmail.com) | [github.com/iancaseydouglas](https://github.com/iancaseydouglas/resume)

## Professional Summary

Platform and security engineer with 12+ years delivering secure, code-driven infrastructure for mission-critical services across Kubernetes, AWS, Azure, GCP, and bare metal. Ships platforms as versioned releases through Git-driven automation. Deep experience across the full lifecycle of identity and secrets infrastructure.

## Technical Proficiencies

**Platforms & Containers**: Kubernetes (EKS, AKS, GKE, self-managed control plane & etcd, bare metal), Docker, Custom Operators, Versioned Platform Releases, Linux Internals

**Cloud**: AWS (Organizations, multi-account, EC2, VPC, Transit Gateway, Route 53, IAM, KMS, Secrets Manager, Lambda), Azure (AKS, VMSS, Entra ID), GCP (GKE), Hybrid & Multi-Cloud Integration

**Infrastructure as Code & Delivery**: Terraform at scale (a la carte-as-code module design), GitOps (Argo CD, Flux CD), GitHub Actions, GitLab Pipelines, Jenkins, Git & Pull-Request Workflows

**Software & Automation**: Go (Golang), Python (Boto3, Pandas), Bash, PowerShell, SQL, API-Driven Automation, Agentic Development (Claude Code, Codex)

**Identity & Security**: HashiCorp Vault (PKI), SAML/Shibboleth SSO, Kerberos v5, OpenLDAP, Active Directory, Microsoft Entra ID, AWS IAM, AWS KMS, SOPS, Policy-as-Code (OPA), NIST SP 800-207 Zero Trust, Least-Privilege Design

**Networking**: IPv6, cert-authenticated IPsec mesh (IKEv2, transport, NAT-T), BGP, VPC/VNet (multi-CIDR, Transit Gateway, peering, VPN), DNS (delegation, SRV, split-horizon), Zero Trust Domain Isolation

**Databases & Messaging**: Amazon RDS, PostgreSQL, SQL Server, Redis, Memcached, MongoDB, DynamoDB, Cassandra, Kafka, High-Throughput Data Pipelines

**Observability**: Splunk, Prometheus, Grafana, Fluentd, Elasticsearch, Centralized Log Aggregation

## Professional Experience

### The Motley Fool | Alexandria, VA (Remote)

*Senior Platform Engineer (Contract) | 04/2026 – Present*

- **CI/CD Migration Automation:** Built reusable Python tooling that migrated ~200 repositories from Jenkins to GitHub Actions, including moving secrets from AWS Secrets Manager to dotenvx, saving months of manual effort.
- **Cloud Infrastructure:** Operate production AWS and Kubernetes infrastructure.
- **AI-Accelerated Engineering:** Developed the migration toolchain with Claude Code agentic workflows, shipping production-grade automation in a fraction of the usual time.

### Kings Mountain Security | Palo Alto, CA (Remote)

*Co-Founder, DevSecOps Engineer & Security Architect | 01/2025 – Present*

- **Zero Trust Architecture:** Co-founded a security consultancy delivering Terraform-based "Zero Trust Capability Packages" modeled on NIST SP 800-207, turning security requirements into deployable guardrails and technical controls.
- **Compliance Automation:** Developing Security-as-Code modules that automate DoD Zero Trust compliance across the infrastructure lifecycle.

### FlowDelta Trading | Boulder, CO (Remote)

*Senior Software Engineer, Python/Data (Contract) | 01/2025 – 04/2026*

- **Backtesting Platform:** Developed a proprietary, multi-horizon analysis platform for a boutique trading desk, enabling rapid backtesting and validation of medium-frequency algorithms.
- **Data-Intensive Systems:** Engineered a vectorized Monte Carlo simulation engine to perform multi-dimensional parameter grid sweeps.

### ZagTech | San Jose, CA (Remote)

*Senior Platform Engineer (Contract) | 04/2024 – 12/2024*

- **Commercial Kubernetes Platform:** Engineered a proprietary platform on Azure (AKS), deployed across multiple enterprise clients; the codebase was a primary value driver in the firm's subsequent acquisition.
- **Fleet GitOps:** Designed the Flux repository hierarchy and cluster bootstrap for AKS fleets across the commercial platform.
- **Composable Terraform Design:** Created a radically simple Terraform design for ordering complex Kubernetes clusters from a menu ([Kate's Kitchen](https://github.com/iancaseydouglas/kates-kitchen)).
- **Cloud Networking:** Designed Azure network connectivity for client environments, including VNet peering, site-to-site VPN, and hub transit routing.
- **Cost Optimization:** Rightsized and tuned Azure infrastructure to meet client cost requirements.
- **Documentation & Runbooks:** Wrote implementation guides and operational runbooks for client handoff and internal teams.

### Invitae Biosciences | San Francisco, CA (Remote)

*Senior Platform Engineer | 07/2023 – 04/2024*

- **Research Compute Platform:** Built a self-service platform on self-managed Kubernetes on AWS EC2 for petabyte-scale genomics workloads; executed zero-downtime cluster upgrades and stateful migrations.
- **Fleet GitOps:** Automated Flux across multi-project, multi-environment cluster fleets with Terraform, Go, and Python, increasing deployment velocity while reducing change failure rates.
- **Cluster Hardening:** Built an automated audit framework enforcing CIS Benchmarks and Pod Security Standards ([Cluster Security Audit](https://github.com/iancaseydouglas/cluster-security-audit)).
- **Secrets Management Architecture:** Designed least-privilege secrets management using SOPS, AWS KMS, and Shamir secret sharing.

### Pearson | London, UK (Remote)

*Senior Cloud Platforms Engineer | 09/2019 – 08/2021*

- **Kubernetes Platform:** Built and operated Bitesize, Pearson's self-managed Kubernetes platform on AWS (own control plane, etcd and Vault PKI), behind a unified API for 400 development teams; proven under 8.5M concurrent users at sub-250 ms, sized to grow Pearson from 75M to 200M learners; releases went from 1–2 a year to several a day ([case study](https://github.com/iancaseydouglas/resume/blob/main/files/bitesize/transforming-the-worlds-largest-education-company-with-kubernetes.pdf)).
- **Platform as a Product:** Delivered the platform continuously as 14 independently versioned components (Terraform, declarative Ansible, upstream Kubernetes images), composed into platform releases and promoted by 121 GitHub Actions jobs through eight clusters to two production regions, gated by tests, human approvals and automated ServiceNow changes.
- **Custom Kubernetes Operators:** Co-developed Go-based operators and CRDs that provisioned AWS services such as VPCs and databases from self-managed Kubernetes on EC2, before AWS offered its own controllers.
- **Centralized Logging:** Implemented log aggregation with a distributed pipeline (Fluentd, Python, AWS Lambda) feeding Elasticsearch and Splunk.
- **Platform Operations:** Built and operated platform infrastructure across a multi-account AWS environment managed with AWS Organizations; contributed Terraform modules, database operations, and Vault CA and AWS certificate management.

### Stanford University | Palo Alto, CA

*DevOps Engineer & Security Architect | 12/2015 – 09/2019*

- **Identity Modernization:** Partnered with the IAM team to re-platform the authn/z stack (Heimdal, Shibboleth) onto Kubernetes: cloud-native patterns, Git-driven CI/CD, fully automated operations.
- **Stateful Services on Self-Managed Kubernetes:** Containerized the university's primary identity store, OpenLDAP, as a Kubernetes service: master/replica StatefulSets, lifecycle automation, deployable cloud-side, on-prem, or standalone. It underpinned identity and access for all of Stanford.
- **Zero-Trust Active Directory:** Authored the reference implementation for a cloud-resident Active Directory leveraging IPv6 and certificate-authenticated IPsec mesh networking for secure, boundary-less access ([paper](https://github.com/iancaseydouglas/resume/blob/main/files/new_directions_in_AD.pdf)).
- **Cloud Transformation:** Equipped infrastructure teams to migrate core services (Puppet and others) to the cloud, including GKE, delivering the IaC and CI/CD pipelines that made it repeatable.
- **Secrets Infrastructure:** Ran multi-tenant HashiCorp Vault as part of a three-person team: automated PKI, auth proxies, encryption-as-a-service.

### Marvel Heroes (Gazillion Entertainment) | Foster City, CA

*DevOps Engineer | 06/2014 – 12/2015*

- **Cluster Ops Tooling:** Built PowerShell and SQL Server Management Objects (SMO) tooling to automate database operations and co-developed cluster operations tools for the flagship MMO with 40k+ daily active users and twice weekly deployment cadence.
- **Observability at Scale:** Operated large metrics and log aggregation servers for production game infrastructure.

### Two Sigma | New York, NY

*Systems Engineer | 05/2012 – 06/2014*

- **High-Performance Fleet:** Automated bare-metal provisioning and configuration management for high-performance servers supporting research and trading operations.
- **Lifecycle Automation:** Orchestrated zero-touch deployment and lifecycle operations of 1,000+ secure workstations firm-wide.

### Columbia University | New York, NY

*Systems Engineer | 06/2010 – 05/2012*

- **Infrastructure Operations:** Ran databases, ESX, storage, and VM infrastructure supporting Columbia's 22 libraries.

## Education

### University of Denver | Denver, CO

*Bachelor of Arts (BA), Double Major: Mathematics & Philosophy*

- **Mathematics:** Completed Bachelor of Science curriculum including grad-level coursework.
- **Philosophy:** Specialized in Formal Logic and Epistemology.
