<h1 align="center">Hi, I'm David Essien 👋</h1>

<p align="center">
  <img src="./assets/david-essien.jpg" width="150" alt="David Essien" style="border-radius: 50%;" />
</p>

<h3 align="center">DevOps Engineer | Software Engineer</h3>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=I+help+teams+ship+software+reliably;I+build+cloud+infrastructure+that+stays+up;Automation+plus+Observability+plus+Security" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/davidshare"><img src="https://img.shields.io/badge/GitHub-davidshare-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/iamdavidshare/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://davidessien.com"><img src="https://img.shields.io/badge/Website-davidessien.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://devopsforger.com"><img src="https://img.shields.io/badge/DevOps%20Forger-Course%20Platform-FF6B35?style=for-the-badge&logo=readthedocs&logoColor=white" /></a>
  <a href="mailto:davidessienshare@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## What I Do

I work at the intersection of software development, cloud infrastructure, and operations, helping teams move from manually managed infrastructure and fragile deployments to automated, observable, secure, and resilient systems.

```
Automate the path from code to production
Reduce deployment complexity and operational overhead
Improve reliability, availability, and incident response
Give engineering teams visibility into the systems they operate
Build infrastructure that scales with demand
```

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,terraform,kubernetes,docker,ansible,jenkins,githubactions,gitlab,nginx,prometheus,grafana,python,bash,ts,js,nodejs,nestjs,react,nextjs,postgres,mysql,mongodb,linux,git,github&perline=9" />
</p>

<p align="center"><i>Click a category below to expand the full tool list.</i></p>

<details>
<summary><b>Cloud & Infrastructure (click to expand)</b></summary>
<br>

| Area | Tools |
|---|---|
| Cloud Platforms | AWS, GCP, DigitalOcean |
| Infrastructure as Code | Terraform, Ansible, AWS CloudFormation |
| Compute | Amazon EC2, AWS Lambda |
| Networking | AWS VPC, Public/Private Subnets, NAT Gateways, Security Groups |
| Traffic & Edge | Load Balancing, DNS, Cloudflare |
| Reverse Proxy | Nginx, Traefik |

</details>

<details>
<summary><b>Containers, Kubernetes & GitOps (click to expand)</b></summary>
<br>

| Area | Tools |
|---|---|
| Containers | Docker |
| Orchestration | Kubernetes, Amazon EKS, Google GKE, OpenShift |
| Packaging | Helm |
| GitOps | Argo CD |
| Networking | Ingress, Service Discovery |
| Scaling | Kubernetes Autoscaling, AWS Auto Scaling |
| Configuration | ConfigMaps, Secrets |

</details>

<details>
<summary><b>CI/CD & Software Delivery (click to expand)</b></summary>
<br>

| Area | Tools |
|---|---|
| CI/CD | Jenkins, GitHub Actions, GitLab CI/CD, Bitbucket Pipelines |
| GitOps Delivery | Argo CD |
| Build & Release | Cloud Build, Docker |
| Version Control | Git, GitHub, GitLab, Bitbucket |
| Automation | Bash, Python |

</details>

<details>
<summary><b>Observability & SRE (click to expand)</b></summary>
<br>

| Area | Tools |
|---|---|
| Metrics | Prometheus |
| Dashboards | Grafana |
| Logging | Loki, Promtail |
| Cloud Monitoring | Google Cloud Monitoring / Stackdriver |
| Reliability | High Availability, Failover, Autoscaling |
| Recovery | Backup & Restore, Disaster Recovery |

**Focus areas:** Monitoring and alerting, incident response, capacity planning, failure detection, backup and restore testing, reducing operational toil

</details>

<details>
<summary><b>DevSecOps (click to expand)</b></summary>
<br>

| Area | Tools |
|---|---|
| Secret Detection | Gitleaks |
| Infrastructure Security | Checkov, tfsec |
| Container Security | Trivy |
| Code Security | SonarQube |
| Dependency Security | Snyk |
| Policy Enforcement | Open Policy Agent, Kyverno |
| Kubernetes Security | Trivy, Falco, Kyverno |
| Cloud Security | AWS IAM, Security Groups, VPC Controls |

</details>

<details>
<summary><b>Software Development (click to expand)</b></summary>
<br>

| Area | Technologies |
|---|---|
| Languages | Python, Bash, TypeScript, JavaScript |
| Backend | Node.js, NestJS, Express |
| Frontend | React, Next.js |
| Databases | PostgreSQL, MySQL, MongoDB |
| Performance | Caching, Query Optimisation, Connection Pooling |

</details>

---

## Personal Philosophy: Build for Failure

I assume **everything has the capacity to fail**: an oversight, a config error, hardware failure, a software defect, wear and tear, human error, a dependency going down, or malicious intent.

> The goal isn't to build systems that never fail. The goal is to build systems that are **prepared for failure**, able to **detect it**, **recover from it**, and **minimise its impact**.

This shapes how I approach infrastructure and delivery:

- **Security by design:** assume systems will be targeted, and protect them accordingly
- **Defence in depth:** never depend on a single security or reliability mechanism
- **Failure planning:** identify known failure modes and design around them
- **High availability:** remove unnecessary single points of failure
- **Multiple recovery strategies:** redundancy, failover, backups, recovery procedures
- **Backup validation:** a backup that's never been restored is an assumption, not a strategy
- **Observability:** logs, metrics, traces, dashboards, alerts
- **Automation:** reduce failure-prone manual operations
- **Infrastructure as Code:** reproducible, reviewable, recoverable
- **Continuous testing:** of deployments, failure scenarios, recovery procedures, and backups
- **Least privilege:** limit what systems, services, and people can do
- **Graceful degradation:** fail safely, preserve critical functionality
- **Continuous improvement:** use incidents as evidence for improving the system

*This is where DevOps, SRE, and DevSecOps intersect for me: systems delivered safely, operated reliably, observed clearly, secured continuously, and recovered when things inevitably go wrong.*

---

## Featured Projects

### AWS VPC & Autoscaling
A secure three-tier AWS architecture supporting applications across public and private network tiers.

**Built with:** AWS, VPC, Terraform, NAT Gateway, Security Groups, CloudWatch, Auto Scaling

### Full-Stack Monitoring Setup
A complete monitoring and logging environment for a containerised application.

**Built with:** FastAPI, Next.js, Docker Compose, Terraform, Prometheus, Grafana, Loki, Promtail, Traefik

> *Add a screenshot or architecture diagram here. A Grafana dashboard or a system diagram will make this section far more compelling than text alone.*

---

## What I'm Building

### [DevOps Forger](https://devopsforger.com)
My course platform for practical DevOps and cloud engineering education, built to make complex infrastructure concepts easier to understand through hands-on learning.

---

## Writing & Knowledge

I write about DevOps, cloud engineering, software development, and personal growth.

- [davidessien.com/blog](https://davidessien.com/blog): technical and personal writing
- [devopsforger.com/blog](https://devopsforger.com/blog): practical DevOps and cloud engineering content

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=davidshare&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=davidshare&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=davidshare&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <i>Build for failure. Automate what can be automated. Make systems observable, secure, and recoverable.</i>
</p>
