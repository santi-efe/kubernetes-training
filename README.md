# Kubernetes Training Project

## Project Description

The main goal of this project is to learn how to deploy an example application on a local Kubernetes cluster using Helm charts. This is my first Kubernetes project as I begin my journey as a Trainee DevOps, focusing on building a strong foundation in container orchestration and deployment strategies.

## Prerequisites

Before you begin, make sure you have the following tools installed on your system:

- [Docker](https://docs.docker.com/get-docker/)
- [Minikube](https://minikube.sigs.k8s.io/docs/start/)
- [Helm](https://helm.sh/docs/intro/install/)

## Getting Started

# 1. Start Minikube
```minikube start ```

# 2. Clone the Repository
```git clone https://github.com/santi-efe/kubernetes-training.git```

```cd kubernetes-training```

# 3. Deploy with Helm
```helm install my-app ./(your-path-to-Chart.yaml)```

# 4. Verify the Deployment
```kubectl get pods```

```kubectl get services```

# 5. Access the Application
```minikube service my-app-service```

# Cleanup: To delete the deployment and free up resources
```helm uninstall my-app```

```minikube stop```

# Conclusion
 This project serves as a starting point for understanding Kubernetes deployments using Helm charts.
 As I continue to learn and gain more experience, I plan to upload more projects and explore more advanced Kubernetes features.
