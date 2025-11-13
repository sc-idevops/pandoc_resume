Stephen M Card
============

> <stephenmcard@gmail.com> - 814-572-0798

> 2118 Shadyside Rd. Clymer, NY 14724

> [GitHub](https://github.com/sc-idevops)

> [LinkedIn](https://www.linkedin.com/in/stephenmcard/)

----
<!--- rewrite introduction --->
Open Source DevOps Engineer who has had a natural aptitude with technology since grade school.
Extensively experienced with helping smaller businesses, and ready to enter Enterprise level IT.

Constantly intrigued by new technology, and endeavors to learn more and improve.

----

Work History
----------

**Contracted DevOps Engineer - Insight Global assigned to Pricewaterhouse Coopers (PwC): 2023-04 to Present**

- Airflow
- Kubernetes 
- Postgres SQL 
- 

- Change Management
    - Deployed software through Azure pipelines
    - Helped orchestrate testing with quality assurance teams

- Incident Tickets
    - Analyzed software and system failures
    - Intermediary between subject matter specialists and end users requesting help
    - Escalated tickets to the appropriate SMEs and ensured they were resolved in a timely manner
    - 

- Special Projects
    - Health checks and alerting
    - Automations for our own team's internal uses
    -

- General Administration
    - Assisted developers needing special access to systems we managed
    - 

--- 

**DevOps Engineer:** 2022-01 - 2023-04

*iDevops, Online*

*DevOps:*

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

- Built Docker Images and deployed into an AWS Kubernetes cluster as a test for: 
  - bitnami/nginx and Kibana
- Created Jenkins Dockerfile from Scratch.
  - Setup simple Hello-world pipeline in Jenkins to test Docker deployment of Jenkins.
- Created an AWS Kubernetes ingress controller for xtermjs as a test.
- Co-Developed a web project that generates a Kubernetes deployment file based on user inputted criteria. (See k8 Softner Project)
- Analyzed and troubleshoot issues with Kubernetes deployments when testing deployments for open source automation catalog including: persistent volume mount issues, ingress controller issues, services accessibility issues and more.
- Created [bash scripts](https://github.com/sc-idevops/devops-notes/tree/master/class-podcheck) to audit Kubernetes pods for liveness probes, readiness probes, and resource limits/requests and then reported which pods had probes in their spec.
- Created [a python script](https://github.com/sc-idevops/devops-notes/blob/master/class-podcheck/liveliness.py) to produce audit report of Kubernetes pod report of if liveness and readiness probes are enabled as well as if resource requests and limit are enabled.
- Deployed the [Kubernetes Dashboard](https://github.com/sc-idevops/devops-notes/tree/master/k8-dashboard) onto an AWS Cluster.

*Github & Pipelines:*

- Enforced version control best practices, including pruning over 100 dead branches from Github repositories, and secrets management.
- Developed a Github Actions Pipeline step to ensure users could be automatically logged in with their Azure credentials, and ensured these credentials were protected using Github secrets.
- Refined a Github Actions pipeline to list existing deployments in a combo box to reduce user error for pipeline input.
- Converted a [Github reusable action](https://github.com/iDevOps-io/idevops-git-actions/commit/e4688060884fe237a888a936b575b8f5dc0df889#diff-a2044e9a351d077e351a69853991725cc81be47b86687cb285c50d34a153e6d2) from docker type to composite type (for better code re-usability) which pulled the kube configuration for an AWS Kubernetes.
- Converted a [Github reusable action](https://github.com/iDevOps-io/idevops-git-actions/commit/36fa72ffaf9e88654781460654def4a459df9336) from docker type to composite type that validated a successful rollout of a deployment on an AWS Kubernetes cluster.
- Wrote a [Github reusable action](https://github.com/iDevOps-io/idevops-git-actions/tree/main/kubernetes_deploy_helm_chart) that Deploys a Helm Chart into a Kubernetes Cluster.
- Wrote a [Github reusable action](https://github.com/iDevOps-io/idevops-git-actions/tree/main/docker_google_osv_scan) that scans a docker image using Google’s new Open Source Vulnerability Scanner.
- Wrote a [Github reusable action](https://github.com/iDevOps-io/idevops-git-actions/tree/main/aws_deploy_remote_terraform) that can deploy a terraform file to an AWS Kubernetes Cluster.

*Terraform & Ansible:*

- Deployed Terraform Infrastructure-as-code to automatically create the following for pipeline testing: 
  - Azure Data Blob Storage, Azure Kubernetes Cluster, and Azure Data Factory
- Wrote terraform to deploy s3 buckets in AWS with lifecycle options
- Wrote terraform to build and deploy virtual machine for nginx server in AWS.
- Wrote terraform to setup IAM role and policy for reading and writing from s3 bucket.
- Wrote Terraform module to deploy an AWS SQS service and queues, along with custom Python script for testing SQS deployment.
- Wrote terraform to deploy a ec2 instance with a security group that allows ports 80 and 22.
  - Created [ansible playbook](https://github.com/sc-idevops/devops-notes/tree/master/flask-ansible-task) that configured the ec2 instance to run python api by installing python, cloning repository and setting up nginx reverse proxy to server gunicorn on port 80.
  - Deployed and validated python api application with ansible and terraform.

*Linux & Scripting:*

- Strong background in Linux including: shell scripting (bash), git, package management, and general system administration.

--*Python Scripts:*

  - Wrote Python script to scrape text from a website and parse it using the Beautifulsoup library to find specific data from the website.
  - Wrote a Python script that recursively looped over the file system searching for specific files and made a list report of those files.
  - Wrote Python script to retrieve JSON payloads from REST API.

--[*Bash Scripts:*](https://github.com/sc-idevops/devops-notes/tree/master/bash_examples)

  - Wrote Bash Script to take website as input and curl the input as data for automation.
  - Wrote a Bash Script to make a report of all resources in all subscriptions and resources groups within Azure utilizing the Azure CLI.
  - Wrote a Bash Script to install Nginx on a Ubuntu machine and update the default HTML file with a pre-built file automating the standup and serving of a basic html file.
  - Created bash script to template replace variables in config files using environment variables.
  - Created bash script that dynamically creates terraform to deploy AWS ec2 instances with prompts based on input.
  
-- *Misc Scripting:*

- Synchronized package installation states over several servers using [Ansible.](https://github.com/sc-idevops/devops-notes/tree/master/ansible)
- Create script to pull password for use in pipeline using bash. Read from [password.idevops.io](password.idevops.io) and save to variable.
- Created AWS command to list out all AWS resources using *the AWS cli and JQ*
- Delete AWS cloud 9 resource using AWS CLI (environment cleanup)


[*Redis Project:*](https://github.com/sc-idevops/devops-notes/tree/master/helm)

- Installed Redis Via Helm and tested functionality through Kubernetes port forwarding.
- Wrote python script to test password protected Redis utilizing Kubernetes port forwarding through local host.
- Created and modified values.yaml file to change Redis helm chart service type from ClusterIP to LoadBalancer in order to test through public internet.
- Wrote python script to test password protected Redis utilizing Kubernetes load balancer.
- Wrote Terraform to deploy AWS VPC with 3 subnets: 1 public, 2 private, with a layer networking setup routing traffic through internet gateway to setup segregated networking layer for application stack.
- Wrote Terraform to deploy pay_per_request dynamoDB table for test application in AWS.
- Wrote Terraform to deploy custom ECR's on demand for test application docker images in AWS.

[*Django Project (Codename Thoughts):*](https://github.com/iDevOps-io/thoughts-sc)

- Built a Django based website that allows users to login/sign up and post thoughts like twitter
- Containerized the Django site into a custom docker image and uploaded it to Docker Hub.
- Built Kubernetes deployment manifest to deploy the Django site into Kubernetes.
- Created Github Action Pipeline to Build, Scan, and Deploy the custom Docker Image using CI/CD into Kubernetes.
- Created MYSQL sidecar for local network database to implement persistent storage for the Django website.
- Created separate deployment with persistent data of MySQL to reference using Kubernetes DNS for Django project.
- Created new pipeline steps to deploy MySQL for Django project.
- Setup Django to use Redis for login caching for load balanced Django services using Kubernetes DNS to reference Redis.
- Created deployment and service for Redis and added steps to the project pipeline
- Troubleshot why MySQL wasn't starting correctly and resolved issue with deployment manifest which was referencing the wrong port.
- Created Django unit tests for Django app to have 100% code coverage
- Add functionality to CI/CD pipeline to deploy Django app that starts ephemeral test infrastructure using docker in the git action pipeline to start MySQL and Redis for the Django unit tests to utilize before building docker image.
- Added ZAProxy Scan to Django deployment pipeline to test OWASP vulnerabilities and fail pipeline on failed scans.
- Added automatic route53 domain name updating in the pipeline to deploy route53 dns for the Django website.
- Added automatic SSL generation using cert-manager to our ingress for Django project to serve site on https endpoint
- Implement regression/UE testing for Django site functionality.
- Troubleshooting errors in pipeline, ephemeral environments, and UE regression testing to make full CI pipeline work.

[*k8 Softner Project:*](http://k8ssoftner.idevops.io/)

- Designed a webapp that takes user input from a javascript frontend and generates a deployable kubernetes manifest through a python backend.
- The Python backend processes a JSON payload dynamically through an API.
- The app is capable of processing replicas, secrets, persistent volume claims, and probes.

--- 

**Office Administrator:** 2016-07 - Current

*Howard & Associates Real Estate, Findley Lake, NY*

- Automated generation of forms by using word templates and fields.
- Semi-Automated Quickbooks bank reconciliations by centralizing data sources and financial information entry.
- Maintained company's online presence and real estate listings across multiple websites.
- Established data backup policy for all computers in office.

--- 

**Information Technology Specialist:** 2015-07 - Current

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
