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


## NODE
A node in Kubernetes is a physical or virtual machine that is part of a Kubernetes cluster. It provides the computational resources necessary to run Pods, which are the smallest deployable units in Kubernetes
#### SINGLE NODE
A single-node Kubernetes cluster is a setup where both the control plane (master) and worker components run on the same machine. It is typically used for development or testing purposes.
#### MULTINODE
A multi-node Kubernetes cluster consists of multiple machines (nodes), where one or more serve as control plane nodes (masters) to manage the cluster, and the rest as worker nodes to run application workloads. This setup improves scalability, fault tolerance, and high availability.

# MINIKUBE
Minikube is a tool that allows you to set up a single-node Kubernetes cluster on your local computer. It is a great way to experiment with Kubernetes before deploying it in production. Minikube is easy to install and use, and it supports all major operating systems.

## How does Minikube work?
 Minikube creates a single-node Kubernetes cluster on your local computer. This cluster includes all of the components that are needed to run Kubernetes, such as the API server, the controller manager, and the scheduler. Minikube also includes a Kubernetes client, which you can use to interact with the cluster.
 ### Why use Minikube?
 
There are many reasons to use Minikube. Here are a few:
 
 
Experiment with Kubernetes: Minikube is a great way to experiment with Kubernetes before deploying it in production. You can use Minikube to learn how to deploy and manage applications in Kubernetes.
 Develop Kubernetes applications: Minikube can be used to develop Kubernetes applications. You can use Minikube to test your applications before deploying them to production.
 Troubleshoot Kubernetes problems: Minikube can be used to troubleshoot Kubernetes problems. You can use Minikube to isolate problems and test fixes.
