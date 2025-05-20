# Divyesh Bhandari

Image - https://hub.docker.com/repository/docker/divyeshxnash/hello-world/general

![alt text](image.png)

# Core Concept Question:  (Add in read me of repo)

1. Why is Docker useful in building and deploying microservices for a real-world product (like an e-commerce or banking app)?

For making applications portable, easily reproducible and secure environment for running applications. Also, allows application to be easily scalable with orchestration.

2. What is the difference between a Docker image and a container in the context of scaling a web application?

Docker image is created at build time which is immutable. A docker image is used to start a container, same image can be used to start multiple containers to horizontally scale an application.

3. How does Kubernetes complement Docker when running a product at scale (e.g., hundreds of containers)?

When we want to manage many services and their containers lifetime, scale them based on load, etc, this is where kubernetes helps to orchestrate and configure everything.