<div align="center">
  <img src="https://github.com/user-attachments/assets/71d12403-299a-4b04-ae18-2b042664fa22">
</div>

# 👨‍🚀 NLW Journey

Welcome to the **NLW Journey** repository! This repository is set up for the deployment of the `Journey API`

This project leverages `Docker` and `Kubernetes` to streamline deployment and ensure scalability. `Continuous Integration` is integrated to automate the process of building and pushing Docker images to DockerHub.

## Key Features

- **Docker**: Containerization for consistent and portable application environments.
- **Kubernetes**: Orchestration for easy replication and scalability using Infrastructure as Code (IaC).
- **CI Integration**: Automated build and push of Docker images to DockerHub.

## Getting Started

### Prerequisites

- Docker
- Kubernetes

### Usage
You can either **run the Docker container locally:**
```sh
docker run -p 8080:8080 rodrigomolter/nlw-journey:latest
```
or **run the docker-compose**
```sh
docker-compose up
```

Also, you can create replicas by **deploying to Kubernetes:**
```sh
kubectl apply -f k8s
```

## Support this project 🙌

If you want to support this project, leave a ⭐.

Happy coding! 🚀

___

Made with ❤️ by [Rodrigo Molter](https://www.linkedin.com/in/rodrigo-molter/).
