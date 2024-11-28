# microservice-app

## Challenge

### Objective

- Deploy a Web Server that prints “Hello, World!” using the specified technologies and best practices.

### Technologies Required

- **Kubernetes**: Use a Kubernetes cluster for deployment.
- **Helm**: Utilize Helm for managing the Kubernetes manifests.
- **Ingress Controller**: Preferably use Traefik, but other options are acceptable.
- **LoadBalancer Service**: Ensure the Ingress controller Service is of type LoadBalancer.

### Requirements

#### Kubernetes Cluster Setup

- Deploy a Kubernetes cluster. You may use any local setup like Minikube, Kind, or Docker Desktop, or a cloud provider like GKE, AKS, or EKS.

#### Web Server Deployment

- Deploy a web server that serves the text “Hello, World!”. You can use an existing Docker image or create your own simple web server image.
- Create a Helm chart for deploying the web server.

#### Ingress Configuration

- Configure an Ingress resource to route traffic from http://localhost:80 (or a custom domain name of your choice) to your web server.
- Ensure the Ingress controller Service is of type LoadBalancer.
- The Ingress controller should be part of the Helm chart deployment, either as a Helm dependency or included in the templates.

#### Runbook Creation

- Create a runbook outlining the steps to administer and maintain the "Hello, World!" web server. This should include common operational tasks such as scaling, logging, monitoring, and troubleshooting.