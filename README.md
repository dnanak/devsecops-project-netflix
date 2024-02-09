# devsecops-project-netflix
This is an example of how I set up a DevSecOps Pipeline from scratch, deploying an application, using most AWS resources, security and observability tools.

This DevSecOps project is deploying a Netflix clone application as a Docker container on an EKS cluster through a secure pipeline that I will build from scratch which is Jenkins. Along with Jenkins, I will be using Docker for containerisation, SonarCloud for reporting back how the builds have worked, Trivy to scan for vulnerabilities inside the containers that are running, Prometheus for observing and collecting data in realtime along with Grafana. Agro CD to monitor the cluster and using Helm configuration (with Terraform) for the K8s deployment.

Project Roadmap:

![DevSecOps](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/9fa1e5cd-44b3-4ac4-bccc-28751c149e74)

The Netflix Clone dashboard:

![home-page](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/99ad7df9-3e5e-4ff8-9a7c-c11bf59a1fac)

