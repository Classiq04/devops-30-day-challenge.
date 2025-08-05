
# Day 01 - Dockerize NGINX and Deploy with Helm

## 🔧 What I Did
- Built a colorful NGINX web app
- Dockerized it with a custom `Dockerfile`
- Pushed the image locally (or to Docker Hub)
- Created a Helm chart to deploy it on Kubernetes

## 🚀 Technologies Used
- Docker
- Helm
- Kubernetes (minikube or kind)
- NGINX

## 🛠️ How to Run Locally

### 1. Build Docker Image
```bash
docker build -t helm-nginx:v2 .
````

### 2. Run Locally

```bash
docker run -d -p 3000:80 helm-nginx:v2
```

