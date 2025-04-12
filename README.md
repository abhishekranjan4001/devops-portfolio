# DevOps Portfolio CI/CD Pipeline

This project demonstrates a full CI/CD pipeline using:

- GitHub for version control
- Jenkins for automation
- Docker for containerization
- Kubernetes for deployment

## How it works

1. Code pushed to GitHub
2. Jenkins pulls code, builds image
3. Docker image is pushed to DockerHub
4. Jenkins deploys app to Kubernetes

## Usage

To run locally:

```bash
docker build -t devops-portfolio .
docker run -p 3000:3000 devops-portfolio
