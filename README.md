# devsecops-project-netflix
This is an example of how I set up a DevSecOps Pipeline from scratch, deploying an application, using most AWS resources, security and observability tools.

This DevSecOps project is deploying a Netflix clone application as a Docker container on a Kubernetes cluster through a secure pipeline that I will build from scratch which is Jenkins. Along with Jenkins, I will be using Docker for containerisation, SonarCloud for reporting back how the builds have worked, Trivy to scan for vulnerabilities inside the containers that are running, Prometheus for observing and collecting data in realtime along with Grafana. Agro CD to monitor the cluster and using Helm configuration (with Terraform) for the K8s deployment.

Project Roadmap:

![DevSecOps](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/9fa1e5cd-44b3-4ac4-bccc-28751c149e74)

The Netflix Clone dashboard:

![home-page](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/99ad7df9-3e5e-4ff8-9a7c-c11bf59a1fac)

Jenkins CI/CD:

![Screenshot 2024-02-09 at 05 38 40](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/63a3d35d-abf8-499f-88c0-84a8c6b765f2)

SonarQube:

![Screenshot 2024-02-09 at 05 39 18](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/c32d0d88-3cf1-48e5-bbb6-07f9b3c6b97a)

Prometheus:

![Screenshot 2024-02-09 at 07 17 42](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/ff73a707-edd2-456c-89e9-9401711a1ebf)

Other features:

![Screenshot 2024-02-10 at 02 39 57](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/9a058e9d-c2b9-463a-87aa-463fc3ce5381)

![Screenshot 2024-02-10 at 02 39 45](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/7935a982-228a-49ba-af9c-0fc57fbdd97a)

![Screenshot 2024-02-10 at 05 15 47](https://github.com/dnanak/devsecops-project-netflix/assets/147429909/a81daeec-668b-4206-94c0-157545e0c909)
