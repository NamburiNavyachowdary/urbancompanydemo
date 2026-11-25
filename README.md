# urbancompanydemo
# Urban Company – ASP.NET Core Application Deployment on Kubernetes Using Helm

## Project Overview

This project demonstrates the development, containerization, and deployment of a custom Urban Company web application built using ASP.NET Core Razor Pages.

The application was containerized using Docker, and the Docker image was pushed to Azure Container Registry (ACR). Kubernetes was used to deploy and manage the application, while Helm was used to simplify and manage the deployment configuration.

Kubernetes Secrets were configured to authenticate with Azure Container Registry and securely pull private container images into the Kubernetes cluster.

## Technology Stack

| Technology | Purpose |
|---|---|
| ASP.NET Core Razor Pages | Application development |
| C# | Backend programming |
| Docker | Application containerization |
| Azure Container Registry (ACR) | Docker image storage |
| Kubernetes | Container orchestration |
| Kubernetes Secrets | Private ACR authentication |
| Helm | Kubernetes application deployment |
| YAML | Kubernetes configuration |

## Architecture Overview

Application Development → Docker Build → Docker Image → Azure Container Registry → Kubernetes Image Pull → Helm Deployment → Running Application

## Project Implementation

The project implementation is documented in the following phases:

1. Application Development using ASP.NET Core Razor Pages
2. Dockerfile Creation
3. Building the Docker Image
4. Creating Azure Container Registry
5. Pushing Docker Images to ACR
6. Kubernetes Cluster Configuration
7. Configuring Kubernetes Secrets for ACR Authentication
8. Creating Helm Chart
9. Deploying the Application Using Helm
10. Verifying Application Deployment and Accessibility

