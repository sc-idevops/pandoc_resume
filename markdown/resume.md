Stephen M Card
============

> <stephenmcard@gmail.com> - 814-572-0798

> 2118 Shadyside Rd. Clymer, NY 14724

> [GitHub](https://github.com/sc-idevops)

> [LinkedIn](https://www.linkedin.com/in/stephenmcard/)

----

Open Source DevOps Engineer with 10 years of experience specializing in automations and deployment pipelines. Linux user since 2007. Current assignment specializes in Azure based cloud computing but the key core DevOps principles can be applied anywhere. Known for streamlining deployment processes, improving infrastructure efficiency, and having excellent communication.

----

Skillset
----------
- System Monitoring
- Infrastructure as Code
- Container Orchestration
- CI/CD Pipeline Development
- Cloud Architecture
- Infrastructure Automation
- Security & Compliance
- Cloud Networking
- Identity & Access Management
- Python & Bash Scripting


Work History
----------

**Contracted L3 DevOps Engineer with Insight Global assigned to Pricewaterhouse Coopers (PwC): 2023-04 to Present**

As part of the TechOps team, our primary responsibility is to serve as the stewards of the production environment for both the front end UI (Halo UI) and back end stack (Common Auditing Management System - CAMS). My other duties included managing enterprise CI/CD pipelines through Azure DevOps, ensuring consistent and reliable application deployments.
I also implemented Kubernetes orchestration with Helm for containerized applications and developed comprehensive Terraform
automation for infrastructure provisioning. 

Our secondary responsibility was providing operations support in a customer-facing role, resolving incident tickets and troubleshooting complex system issues through extensive Linux administration. Administered data processing workflows using
Apache Airflow and Databricks.
Developed Python automation scripts to streamline DevOps processes and performed extensive API testing and integration work
using Postman and GraphQL, documenting all procedures through Confluence SOPs.

- Tech Stack Highlights:
  - Azure Cloud
  - Airflow
  - Kubernetes
  - Postgres SQL
  - Azure Databricks

- Change Management via Service NOW
    - Deployed software through Azure pipelines according to runbook specifications
    - Helped orchestrate testing with quality assurance teams
    - Maintained secrets inside Hachicorp vault

- Incident Tickets in Service NOW
    - Analyzed software and system failures that happened in Airflow DAG runs or with failed Kubernetes Pods.
    - Intermediary between subject matter specialists (SMEs) and end users requesting help by escalating tickets to the appropriate SMEs and ensured they were resolved in a timely manner
    - Ensured compliance with requests for systems/database access

- General Administration
    - Assisted developers needing special access to systems we managed, or to provide logging information to help with debugging
    - Updated or created over 40 new Standard Operating Procedures in Confluence.
    - Health checks and alerting for critical systems
    - Administered Databricks workspaces and Apache Airflow data pipelines, implementing monitoring solutions that increased data processing reliability and reduced failed job incidents.

--- 

**DevOps Engineer:** 2022-01 - 2023-04

*iDevops, Online*

*DevOps Foundations:*

- Built a foundation on the CI/CD software lifecycle and the fundamentals of DevOps methodology.
- Rapidly adapted to new technologies introduced in the program both through self-education and class time.
- Documented project status and description on Confluence and updated JIRA tickets.
- Self-taught numerous technologies to implement DevOps tasks as part of various open-source projects at iDevOps.io.
- Responsible for completing online learning resources in 10 weeks, such as CodeCademy (Python, Command Line, Bash and HTML) to build requisite knowledge for daily learning rooms and status update meetings.

*Work Environment:*

- Mentored many other interns in technologies such as: Kubernetes, Python, Docker, Bash.
- Maintained positive work/learning atmosphere by building relationships with fellow interns and other senior engineers.
- Answered questions and taught several other interns how read error messages & diagnose failures when deploying on Github actions.

*Docker & Kubernetes:*

- Co-Developed a web project that generates a Kubernetes deployment file based on user inputted criteria. (See k8 Softner Project)
- Analyzed and troubleshoot issues with Kubernetes deployments when testing deployments for open source automation catalog including: persistent volume mount issues, ingress controller issues, services accessibility issues and more.
- Created [bash scripts](https://github.com/sc-idevops/devops-notes/tree/master/class-podcheck) to audit Kubernetes pods for liveness probes, readiness probes, and resource limits/requests and then reported which pods had probes in their spec.
- Created [a python script](https://github.com/sc-idevops/devops-notes/blob/master/class-podcheck/liveliness.py) to produce audit report of Kubernetes pod report of if liveness and readiness probes are enabled as well as if resource requests and limit are enabled.
- Deployed the [Kubernetes Dashboard](https://github.com/sc-idevops/devops-notes/tree/master/k8-dashboard) onto an AWS Cluster.

*Github & Pipelines:*

- Enforced version control best practices, including pruning over 100 dead branches from Github repositories, and secrets management.
- Developed a Github Actions Pipeline step to ensure users could be automatically logged in with their Azure credentials, and ensured these credentials were protected using Github secrets.
- Refined a Github Actions pipeline to list existing deployments in a combo box to reduce user error for pipeline input.
- Created and improved several github reusable actions including:
  - validation of successful deployments
  - scan a docker image with Google's Open Source Vulnerability Scanner
  - deploy a terraform file to an AWS Kubernetes Cluster

*Terraform & Ansible:*

- Deployed Terraform Infrastructure-as-code to automatically create the following for pipeline testing: 
  - Azure Data Blob Storage, Azure Kubernetes Cluster, and Azure Data Factory
- Wrote terraform to deploy a ec2 instance with a security group that allows ports 80 and 22.
  - Created [ansible playbook](https://github.com/sc-idevops/devops-notes/tree/master/flask-ansible-task) that configured the ec2 instance to run python api by installing python, cloning repository and setting up nginx reverse proxy to server gunicorn on port 80.
  - Deployed and validated python api application with ansible and terraform.

[*Redis Project:*](https://github.com/sc-idevops/devops-notes/tree/master/helm)

- AWS Infrastructure as Code (IaC): Designed a secure AWS VPC architecture with segregated public/private subnets using Terraform, including the automated provisioning of DynamoDB tables and on-demand Elastic Container Registries (ECR).
- Kubernetes & Helm Configuration: Deployed and customized Redis via Helm, modifying values.yaml configurations to transition service exposure strategies from ClusterIP to LoadBalancer for external access scenarios.
- Automated Connectivity Testing: Developed Python automation scripts to validate password-protected Redis connectivity, executing tests against both local port-forwarding and public load balancer endpoints.

[*Django Project (Codename Thoughts):*](https://github.com/iDevOps-io/thoughts-sc)

- Full-Stack Kubernetes Orchestration: Architected a scalable Django application using Docker and Kubernetes, integrating Redis for caching, MySQL sidecars for persistent storage, and automated SSL generation via cert-manager.
- Advanced CI/CD Pipeline: Engineered a comprehensive GitHub Actions pipeline that spins up ephemeral Docker environments for integration testing, enforcing 100% code coverage prior to deployment.
- Security & Network Automation: Implemented automated security gates using OWASP ZAProxy for vulnerability scanning and automated Route53 DNS record updates for seamless production releases.

--- 

**Office Administrator:** 2016-07 - 2023-04

*Howard & Associates Real Estate, Findley Lake, NY*

- Automated generation of forms by using word templates and fields.
- Semi-Automated Quickbooks bank reconciliations by centralizing data sources and financial information entry.
- Maintained company's online presence and real estate listings across multiple websites.
- Established data backup policy for all computers in office.

--- 

**Information Technology Specialist:** 2015-07 - 2023-04

*YMCA Of Corry, Corry, PA*

- Developed and enforced policy to ensure safety of user data and security of systems.
- Networking expansion from basic DSL to a central switch with various access points across the complex.
- Completely replaced outdated technology with currently supported desktop systems.
- Deployed digital advertising boards to keep customers updated on company events.

---------
Certifications
---------

**Terraform Associates Certification:** 2022-07


Education
---------

**Bachelor of Science: Computer Science**: 2007-09 - 2011-12

*SUNY Fredonia - Fredonia, NY*

* Dean's List Fall 2007 & Fall 2008
* Elected to Vice President of Service for Alpha Phi Omega, Community Service Fraternity
