# Docker-Assignment
1. Why is Docker useful in building and deploying microservices for a real-world product (like an e-commerce or banking app)?
Ans: Docker helps in building and deploying microservices by:

1: Efficient Resource Usage: Containers are lightweight compared to virtual machines and start much faster, which is crucial in high-load systems like e-commerce or banking.

2: Consistency Across Environments: Docker containers ensure that the app behaves the same in development, testing, staging, and production—eliminating the classic "it works on my machine" problem.

3: Improved CI/CD Pipelines: Docker integrates seamlessly into CI/CD workflows, making testing, building, and deployment automated and reproducible.

4: Isolation of Services: Each microservice (e.g., payment, catalog, authentication) runs in its own container, preventing conflicts (e.g., port or library version issues) and enabling independent scaling and deployment.

5: Rapid Deployment and Rollback: With containerized microservices, updates are quick and reversible. You can roll back to a previous image if something breaks.

2. What is the difference between a Docker image and a container in the context of scaling a web application?

Docker Image:
1. A blueprint or snapshot of an application, including code, runtime, libraries, and dependencies.
2. Read-only
3. Used to create multiple containers (instances).
4. Doesn’t consume system resources until instantiated.

Docker Container:
1. A running instance of a Docker image. It’s the actual environment where your app runs.
2. Read-write (once running)
3. One of potentially many instances of an image.
4. Consumes CPU, memory, and I/O while running.

3. How does Kubernetes complement Docker when running a product at scale (e.g., hundreds of containers)?

Ans: Kubernetes complements Docker by efficiently managing and orchestrating containers, especially when running large-scale applications with hundreds of containers. It automates the deployment and scaling of containers based on real-time usage and traffic. Kubernetes also ensures high availability through self-healing—automatically restarting containers that fail. It enables smooth updates without downtime and supports automatic rollback if something goes wrong. Additionally, Kubernetes provides built-in service discovery and load balancing, making it easier to manage traffic across services. It securely handles sensitive data like API keys and can run applications consistently across multiple cloud providers or on-premises environments.

Assignment Link:
http://localhost:8080/
![image](https://github.com/user-attachments/assets/e6a2292a-fb2c-4631-b448-1b24960d85e8)




