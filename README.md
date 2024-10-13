# MINIKUBE

## WHAT IS KUBERNETES
Kubernetes, also known as K8s, is an open source system for managing containerized applications across multiple hosts. It provides basic mechanisms for the deployment, maintenance, and scaling of applications.
Kubernetes builds upon a decade and a half of experience at Google running production workloads at scale using a system called Borg, combined with best-of-breed ideas and practices from the community.
Kubernetes is hosted by the Cloud Native Computing Foundation (CNCF).

## key features of Kubernetes:
1. Container Orchestration: Kubernetes automates the management of containers across multiple hosts. It coordinates container scheduling and execution, ensuring they run efficiently and reliably.


2. Self-Healing: It can automatically replace and restart containers that fail, ensuring high availability. Kubernetes monitors the health of your containers and nodes, and if an issue arises, it restarts or replaces them as needed.


3. Scalability: Kubernetes can scale applications up and down automatically based on traffic or load. You can define scaling policies, and Kubernetes will handle the rest.


4. Load Balancing: It can distribute network traffic across multiple containers, ensuring no single container is overwhelmed with requests.


5. Service Discovery: It helps automatically discover services and ensures that containers can communicate with one another through a DNS name or IP address.


6. Storage Management: Kubernetes can automatically mount local, cloud, or networked storage to your containers, making it easier to manage data persistence.


7. Rollouts and Rollbacks: Kubernetes manages updates to your application, allowing you to roll out new features or versions without downtime. If an update fails, it can automatically roll back to the previous version.


8. Multi-Cloud and Hybrid Deployments: Kubernetes can run on different environments, including public clouds (like AWS, Google Cloud, Azure), on-premise data centers, and hybrid cloud setups.


