# Ian Douglas

**Senior Platform Engineer | Cloud Security & Identity**

Colorado · Remote · Open to Bay Area relocation | 303-335-9358 | [iancaseydouglas@gmail.com](mailto:iancaseydouglas@gmail.com) | [github.com/iancaseydouglas/resume](https://github.com/iancaseydouglas/resume)

## Professional Summary

Platform and security engineer with 15+ years building secure, code-driven infrastructure on Kubernetes, AWS, Azure, GCP, and bare metal. Ships platforms as versioned releases through gated, Git-driven pipelines. Deep experience across the full lifecycle of identity and secrets infrastructure.

## Technical Proficiencies

**Platforms & Cloud**: Kubernetes (EKS, AKS, GKE, self-managed control plane & etcd), Docker, Custom Operators; AWS (Organizations, EC2, VPC, IAM, KMS, Secrets Manager, Lambda); Azure (AKS, VNet, Entra ID); GCP (GKE)

**Identity & Security**: HashiCorp Vault (PKI), OpenLDAP, Kerberos v5, SAML/Shibboleth, Active Directory, AWS IAM & KMS, SOPS, Policy-as-Code (OPA), NIST SP 800-207 Zero Trust

**IaC & Delivery**: Terraform (composable module design), GitOps (Flux CD), GitHub Actions, GitLab Pipelines, Jenkins

**Networking**: IPv6, certificate-authenticated IPsec (IKEv2, transport mode, NAT-T), BGP, VPC/VNet (peering, VPN, Transit Gateway), DNS

**Software & Data**: Go, Python (Boto3, Pandas), Bash, PowerShell, SQL; PostgreSQL, RDS, Redis, Kafka; Prometheus, Grafana, Fluentd, Elasticsearch, Splunk; Claude Code

## Professional Experience

### The Motley Fool | Alexandria, VA (Remote)

*Senior Platform Engineer (Contract) | 04/2026 – Present*

- **CI/CD Migration:** Built reusable Python tooling, developed with Claude Code agentic workflows, that migrated ~200 repositories from Jenkins to GitHub Actions, replacing a manual repo-by-repo process, and moved their secrets from AWS Secrets Manager to dotenvx to decouple them from AWS.

### Kings Mountain Security | Palo Alto, CA (Remote)

*Co-Founder, DevSecOps Engineer & Security Architect (Part-time) | 01/2025 – Present*

- **Zero Trust Architecture:** Lead the architecture of Terraform-based "Zero Trust Capability Packages" modeled on NIST SP 800-207, including Security-as-Code modules that automate DoD Zero Trust compliance across the infrastructure lifecycle.

### FlowDelta Trading | Boulder, CO (Remote)

*Senior Software Engineer, Python/Data (Contract) | 01/2025 – 04/2026*

- **Backtesting Platform:** Developed a proprietary backtesting platform for a boutique trading desk, including a vectorized Monte Carlo engine for multi-dimensional parameter grid sweeps.

### ZagTech | San Jose, CA (Remote)

*Senior Platform Engineer (Contract) | 04/2024 – 12/2024*

- **Commercial Kubernetes Platform:** Engineered a proprietary Kubernetes platform on Azure (AKS), deployed across multiple enterprise clients; the firm's largest client adopted it immediately in a $250K engagement.
- **Fleet GitOps & Terraform:** Designed the Flux repository hierarchy and cluster bootstrap for AKS fleets, and a Terraform design for ordering complex clusters from a menu of profiles and feature sets ([Kate's Kitchen](https://github.com/iancaseydouglas/kates-kitchen)).
- **Azure Networking & Cost:** Designed client connectivity (VNet peering, site-to-site VPN, hub transit routing) and rightsized infrastructure to client cost targets.

### Invitae Biosciences | San Francisco, CA (Remote)

*Senior Platform Engineer | 07/2023 – 04/2024*

- **Research Compute Platform:** Built a self-service genomics research platform on self-managed Kubernetes and EKS (dozens of production clusters, five environments); ran zero-downtime upgrades and stateful migrations, and automated fleet-wide Flux bootstrap (Terraform, Go, Python).
- **Cluster Hardening:** Built a Python tool that audits every PodSecurityPolicy across clusters against the Pod Security Standards, producing the reports used to plan the move to Pod Security Admission ([Cluster Security Audit](https://github.com/iancaseydouglas/cluster-security-audit)).
- **Secrets Management Architecture:** Designed least-privilege secrets management using SOPS, AWS KMS, and Shamir secret sharing.

### Pearson | London, UK (Remote)

*Senior Cloud Platforms Engineer | 09/2019 – 08/2021*

- **Kubernetes Platform:** Operated and extended Bitesize, Pearson's self-managed Kubernetes platform on AWS (own control plane, etcd and Vault PKI) for ~400 development teams, with daily platform releases; wrote 30+ Terraform modules. The platform had been load-tested to 8.5M concurrent users at 150–250 ms ([case study](https://github.com/iancaseydouglas/resume/blob/main/files/bitesize/transforming-the-worlds-largest-education-company-with-kubernetes.pdf)).
- **Platform Release Pipeline:** Maintained the 121-job GitHub Actions pipeline promoting 14 versioned components through eight clusters to two production regions, gated by tests, approvals and ServiceNow changes; helped stand up the second region.
- **Centralized Logging:** Built a new log aggregation service as one of two engineers (Fluentd, Python, AWS Lambda, feeding Elasticsearch and Splunk).
- **Reusable Platform & Operators:** Generalized Bitesize's code modules into a reusable, white-box platform offering, and co-developed Go-based operators and CRDs that provisioned AWS VPCs and databases.

### Stanford University | Palo Alto, CA

*Windows Infrastructure Architect, then DevOps Engineer | 12/2015 – 09/2019*

- **Identity Modernization:** Owned the OpenLDAP modernization within the IAM team's move of the authentication stack (Kerberos/Heimdal, Shibboleth) onto Kubernetes: master/replica StatefulSets with automated restores and lifecycle automation, running in production as the directory for the entire university.
- **Zero Trust Active Directory:** Designed and deployed Active Directory in AWS over IPv6 with certificate-authenticated IPsec, letting client VPCs with overlapping address space reach domain controllers without peering or VPN ([paper](https://github.com/iancaseydouglas/resume/blob/main/files/new_directions_in_AD.pdf)).
- **Cloud Migration:** Delivered IaC and GKE-backed CI/CD that moved core services, including Puppet, to the cloud.
- **Secrets Infrastructure:** Ran multi-tenant HashiCorp Vault as one of a three-person team: PKI automation, a multi-tenant secrets store, and authentication proxies.

### Earlier Experience

- **Gazillion Entertainment (Marvel Heroes)**, DevOps Engineer: database and cluster-operations automation for an MMO with 40k+ daily active users and twice-weekly deployments.
- **Two Sigma Investments**, Systems Engineer: bare-metal provisioning for research and trading servers; zero-touch lifecycle for 1,000+ secure workstations.
- **Columbia University**, Systems Engineer: databases, ESX, storage, and VM infrastructure for 22 libraries.

## Education

**University of Denver** | BA, Mathematics & Philosophy (double major)
