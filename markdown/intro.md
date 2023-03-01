Greetings, I’m Stephen Card. I’ve always been interested in technology throughout my life, but never quite figured out what I specialized in.
Back in January 2022, I enrolled in a program called iDevOps which was an excellent opportunity to make use of my interests in technology and the IT space and taking that next step in my career path.

The program is divided up into two parts, with the first 10 weeks learning core technologies like: GIT, Bash, Python, Docker, Kubernetes, Terraform, Ansible, and cloud service providers such as: AWS and Azure.
After the initial10 weeks you start doing DevOps project work for open source projects.
You do this until you have about 500 story points worth of DevOps project work completed and have completed the: Certified Kubernetes Administrator Certification, and Certified Terraform Associate Certification.

One of the most important concepts we learned at iDevOps is the **deductive problem solving method (the DPSM).**
This problem solving approach taught me how to adapt to and solve any engineering problem, by getting an overview of high level knowledge, breaking it down into steps, augmenting any missing knowledge I have through Google and other resources like Youtube.

My earliest tasks in the program involved building Docker images, Kubernetes Manifest, and Github Action pipelines to build and deploy infrastructure services in a templated way. These were infrastructure services like: MySql, Redis, Grafana and Prometheus, and more.
These are in the process of being published as Composite GitHub Actions. This enables anyone to essentially copy and paste a step into their GitHub action pipelines and instantly build and deploy production quality infrastructure into their Kubernetes Clusters.

Terraform was another dimension of the early work I did at iDevOps.
We would build templatized Terraform templates that could be executed as catalog items.
We leveraged a Github repo as a stored catalog of Terraform templates that could be deployed and tested through a single pipeline by name reference.
Once we tested our templates the goal is to convert them to composite GitHub actions that can be re-used by the community the same way we have with the Kubernetes manifests.

We also learned and applied advanced DevOps automation principals building complete CI/CD pipelines.
Pipelines that would:  

- sonar scan,
- unit test,
- docker build,
- docker security scan,
- template a manifest file with proper readiness checks and health checks for kubernetes,
- deploy the service,
- validate successful deployment,
- regression test the service, and then finally
- execute an OWASP top 10 vulnerability scan on the service we deployed to development.

That way every deployment was checked and validated at every step ensuring if the deployment wasn’t successful Kuberentes would roll-back to the old version.
This allowed us to push constant updates to live services. This is actually what Microsoft does they push straight to production. This isn’t always a good thing but definitely it’s gaining some traction in the industry.
The goal of proper CI/CD is to catch and fail early so you don’t accidentally deploy broken code and if you do it reverts back to good code to minimize downtime to the consumer.

The project that I am the most proud of is a kubernetes manifest generator which you can access at <http://k8ssoftner.idevops.io> ​  
The goal of this project was to generate a kubernetes manifest based entirely from a web UI. It sends a json payload to a python API which I wrote running in kubernetes. This API processes it dynamically and returns a fully formatted kubernetes deployment manifest file that can be immediately deployed to a cluster based on user inputted values. The hardest part of this task was to process the dynamic inputs like multiple secrets, ports, etc and render them in a valid fashion.

Another project we recently started is called RawInput.
This is a DevOps SaaS product that is going to handle configuration and service variable templating.
Essentially it is an API of store key value pairs that represent variables for config files or Kubernetes manifest.
Variables that will be mapped to environment variables and template replaced in files.
Basically a config store for your application that can be referenced by name and environment.  
There is also a built in templating system that you can send a formatted file with the correct template syntax with application and environment name and it will return the file to you in with the values template replaced.
Abstracting the need to build that logic into your pipelines and allowing you to store your config state as referenceable items so you can make state independent pipelines and re-use automation by having it load the variables it needs from the remote config store.
A cool thing about this project is it was purposefully given to us in NodeJS because we didn’t know Node and we had to build a working POC with user authentication and management system and deploy it in Kubernetes with a CI pipeline. We did this in 2 weeks in a language we didn’t know.

I’ve been with iDevOps for about year now and I’m excited to take the experience I’ve gained in the last year and start for a company that will, you know, actually pay me for my skillset. I love working for iDevOps but I would also like to get paid for the work I am doing.
I am also no stranger to working with technology. Technology is a passion I’ve had throughout my life and it is something I am known for by everyone who knows me. I’m excited for new opportunities in a field that I’ve loved since grade school, and I am certain that this my experience will serve your company as well and I’m ready to put in the work to ensure that it does.
