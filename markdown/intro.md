# Interview Introduction

Greetings, I’m Stephen Card. I’ve always been interested in technology throughout my life, and have been searching for a way to make working with Linux and open source technologies my career.
Back in January 2022, I enrolled in a program called iDevOps which was an excellent opportunity to make use of my interests in technology and the IT space and taking that next step in my career path.

The program is divided up into two parts, with the first 10 weeks learning core technologies like: GIT, Bash, Python, Docker, Kubernetes, Terraform, Ansible; and cloud service providers such as: AWS and Azure. *(The usual suspects.)*

After the initial 10 weeks you start doing DevOps project work for open source projects.
I did this until I had about 500 story points worth of DevOps project work completed and have completed the: Certified Kubernetes Administrator Certification, and Certified Terraform Associate Certification.

One of the most important concepts I learned at iDevOps is the **deductive problem solving method (the DPSM).** *(also known as Engineering 101)*
This problem solving approach taught me how to adapt to and solve any engineering problem, by getting an overview of high level knowledge, breaking it down into steps, augmenting any missing knowledge I have through Google and other resources like stack overflow.

My earliest tasks in the program involved building Docker images, Kubernetes Manifest, and Github Action pipelines to build and deploy infrastructure services in a templated way. These were infrastructure services like: MySql, Redis, Grafana and Prometheus, and more.

These are in the process of being published as Composite GitHub Actions. This enables anyone to essentially copy and paste a step into their GitHub action pipelines and instantly build and deploy production quality infrastructure into their Kubernetes Clusters.

Terraform and Infrastructre as Code was another dimension of the early work I did at iDevOps. I built Terraform templates that could be executed as catalog items, by leveraging a Github repo of Terraform templates that could be deployed and tested through a single pipeline by name in a catalog.

Later I learned and applied advanced DevOps automation principals building complete CI/CD pipelines.
These pipelines would:  

- sonar scan,
- unit test,
- docker build,
- docker security scan,
- template a manifest file with proper readiness checks and health checks for kubernetes,
- deploy the service,
- validate successful deployment,
- and finally, regression test the service

That way every deployment was checked and validated at every step ensuring if the deployment wasn’t successful Kuberentes would roll-back to the old version. The goal of proper CI/CD is to catch and fail early so you don’t accidentally deploy broken code and if you do it reverts back to good code to minimize downtime to the consumer.
This also allowed us to push constant updates to live services. This is actually what Microsoft does they push straight to production *(which explains a lot)*. This isn’t always a good thing but definitely it’s gaining some traction in the industry.

The project that I am the most proud of is a kubernetes manifest generator which you can access at <http://k8ssoftner.idevops.io> ​ (I didn't name it)
The goal of this project is that anyone could easily create deployable kubernetes yaml files by filling out a form.
It consisted of two parts, the web UI which takes the user input and sends it to a python API which I wrote. The API dynamically processes the user input and returns a fully formatted kubernetes deployment manifest file that can be immediately deployed to a cluster.
The hardest part of this task was to process the dynamic inputs like multiple secrets, ports, etc and render them in a valid fashion.

I’ve been with iDevOps for about year now and I’m excited to take the experience I’ve gained in the last year and begin working in a larger environment.
