<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:232F3E,100:FF9900&height=180&section=header&text=Van%20Hoang%20Kha&fontColor=ffffff&fontSize=42&fontAlignY=38&desc=Cloud%20Security%20Engineer%20%7C%20Multi-Cloud%20Security%20%7C%20Zero%20Trust%20%7C%20Workload%20Identity&descAlignY=62&descSize=14" alt="Header"/>
</p>

<p align="center">
  <a href="https://cloudsecop.net"><img src="https://img.shields.io/badge/Blog-cloudsecop.net-0A66C2?style=flat-square&logo=hashnode&logoColor=white" alt="Blog"/></a>
  <a href="https://www.linkedin.com/in/vanhoangkha/"><img src="https://img.shields.io/badge/LinkedIn-vanhoangkha-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://cloudjourney.awsstudygroup.com"><img src="https://img.shields.io/badge/AWS%20Learning%20Hub-First%20Cloud%20Journey-FF9900?style=flat-square" alt="AWS Learning Hub"/></a>
  <a href="https://twitter.com/WorkKhavan"><img src="https://img.shields.io/badge/X-@WorkKhavan-000000?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
</p>

## Cloud Security Engineering

I work on security architecture and engineering across **AWS, Azure, GCP, Cloudflare, Huawei Cloud, and Yandex Cloud**, with a focus on identity, network security, cloud-native workloads, Zero Trust, and security automation.

My engineering approach is centered on **short-lived identity, least privilege, defense in depth, measurable security controls, and infrastructure as code**.

### Focus Areas

| Domain | Engineering focus |
| --- | --- |
| **Cloud Security Architecture** | Landing zones, shared security services, segmentation, centralized inspection, guardrails |
| **IAM & Workload Identity** | OIDC, federation, IAM Roles Anywhere, CIEM, ABAC, permission boundaries, short-lived credentials |
| **Zero Trust / SASE** | ZTNA, device posture, identity-aware access, policy enforcement, SIEM integration |
| **Kubernetes & Container Security** | EKS/Kubernetes hardening, workload identity, supply chain, runtime security, network policy |
| **CNAPP / CSPM / CWPP** | posture management, attack paths, exposure analysis, workload protection, cloud detection |
| **Cloud Network Security** | egress control, NGFW, WAF, VPC/VNet segmentation, Transit Gateway, hybrid networking |
| **DevSecOps / IaC Security** | Terraform, policy-as-code, CI security gates, secret scanning, SAST/SCA, automated validation |

```mermaid
flowchart LR
    A[Cloud Platforms] --> B[Identity & Trust]
    A --> C[Network Security]
    A --> D[Cloud-Native Workloads]
    B --> E[Zero Trust]
    C --> E
    D --> F[CNAPP / Detection]
    E --> G[Security Automation]
    F --> G
```

## Selected Engineering Work

### Security Architecture & IAM

| Project | What it demonstrates |
| --- | --- |
| [aws-security-patterns](https://github.com/vanhoangkha/aws-security-patterns) | AWS security reference architectures and reusable security patterns |
| [workload-identity-federation-guide](https://github.com/vanhoangkha/workload-identity-federation-guide) | Keyless cross-cloud authentication and workload identity federation |
| [aws-iam-accessadvisor-permissionboundary](https://github.com/vanhoangkha/aws-iam-accessadvisor-permissionboundary) | Least-privilege automation using Access Advisor and permission boundaries |
| [aws-iam-access-analyzer-solution](https://github.com/vanhoangkha/aws-iam-access-analyzer-solution) | External-access detection and IAM exposure analysis |

### Kubernetes, Containers & Cloud-Native Security

| Project | What it demonstrates |
| --- | --- |
| [container-security-series](https://github.com/vanhoangkha/container-security-series) | Container image security, runtime protection, Kubernetes hardening, supply-chain security and Zero Trust |
| [n8n-on-aws-eks](https://github.com/vanhoangkha/n8n-on-aws-eks) | Production-style Kubernetes deployment and AWS/EKS integration |
| [aws-eks-blueprints](https://github.com/vanhoangkha/aws-eks-blueprints) | EKS platform patterns and reusable cluster architecture |

### Security Platforms & Automation

| Project | What it demonstrates |
| --- | --- |
| [cloudsecop-platform-mvp](https://github.com/vanhoangkha/cloudsecop-platform-mvp) | Cloud security operations platform experimentation |
| [aws-iam-access-key-auto-rotation](https://github.com/vanhoangkha/aws-iam-access-key-auto-rotation) | IAM credential lifecycle automation and compliance controls |
| [aws-certification-prep-app](https://github.com/vanhoangkha/aws-certification-prep-app) | Full-stack AWS application and automation patterns |

## Open-Source Security Contributions

I contribute security research, tooling, and cloud hardening patterns upstream where possible.

- **Wiz Open Cloud Vulnerability Database** — contributions covering AWS, Azure, and GCP vulnerabilities, plus validation tooling.
- **Yandex Cloud Security Solutions Library** — VM metadata hardening and Terraform-based reference implementation.
- **Prowler ecosystem** — experimentation around security graph, attack paths, CIEM, CWPP, DSPM, and cloud detection capabilities.

## Security Engineering Principles

```text
Identity first
    ↓
Short-lived credentials
    ↓
Least privilege + explicit trust boundaries
    ↓
Network and workload segmentation
    ↓
Continuous posture and runtime visibility
    ↓
Detection, response and automated remediation
```

I prefer designs that are **auditable, reversible, automatable, and measurable** rather than relying on static credentials or manual operational controls.

## Writing & Research

Recent areas I write and experiment with:

- Workload identity and keyless authentication
- Zero Trust and Cloudflare One
- Kubernetes and container security
- IAM least privilege and cloud authorization
- CNAPP, attack paths, CSPM and workload protection
- Multi-cloud network security and centralized egress inspection
- AI-assisted cloud security operations

Technical notes and long-form posts: [cloudsecop.net](https://cloudsecop.net)

## Certifications & Community

- **AWS Community Builder** — Security category
- **Leader**, AWS User Group Vietnam
- **Leader**, MongoDB User Group Vietnam
- **Organizer & speaker**, AWS Community Day Vietnam

<p>
  <img src="https://img.shields.io/badge/AWS%20Certified-Security%20Specialty-FF9900?style=flat-square" alt="AWS Security Specialty"/>
  <img src="https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect-FF9900?style=flat-square" alt="AWS Solutions Architect"/>
  <img src="https://img.shields.io/badge/AWS%20Certified-SysOps%20Administrator-FF9900?style=flat-square" alt="AWS SysOps"/>
  <img src="https://img.shields.io/badge/AWS%20Certified-Developer-FF9900?style=flat-square" alt="AWS Developer"/>
  <img src="https://img.shields.io/badge/MongoDB-Associate%20Developer-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="CCNA"/>
</p>

## Community & Learning

| Project | Scope |
| --- | --- |
| [aws-first-cloud-journey](https://github.com/vanhoangkha/aws-first-cloud-journey) | Hands-on AWS learning path, workshops and certification resources |
| [aws-free-tier-optimization-guide](https://github.com/vanhoangkha/aws-free-tier-optimization-guide) | Practical AWS cost-optimization guide |
| [aws-community-event-handbook](https://github.com/vanhoangkha/aws-community-event-handbook) | Community event operating practices and reusable guidance |

## Technology

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

## Contact

- [LinkedIn](https://www.linkedin.com/in/vanhoangkha/)
- [cloudsecop.net](https://cloudsecop.net)
- [AWS First Cloud Journey](https://cloudjourney.awsstudygroup.com)
- [X / Twitter](https://twitter.com/WorkKhavan)

Open to collaboration on **cloud security engineering, workload identity, Zero Trust, Kubernetes security, cloud-native security platforms, and technical community initiatives**.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF9900,100:232F3E&height=100&section=footer" alt="Footer"/>
</p>
