# Kubernetes
+ Kubernetes minikube & kubectl installation in aws ec2
+ Minikube install pre-required details link: https://minikube.sigs.k8s.io/docs/start/
- Choose the operation system required specifications

### minikube start
* minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.
* All you need is Docker (or similarly compatible) container or a Virtual Machine environment, and Kubernetes is a single command away: minikube start

## what is minikube & similar like minikube
- Minikube is a tool that sets up a Kubernetes environment on a local PC or laptop. It’s technically a Kubernetes distribution, but because it addresses a different type of use case than most other distributions (like Rancher, OpenShift, and EKS), it’s more common to hear folks refer to it as a tool rather than a distribution.
- Alternatives for minikube are MicroK8s, k3s, K3d, kind, Docker desktop ...etc
- Minikube supports all of the major operating systems – Windows, Linux, and macOS. (It doesn’t run on mobile devices, alas.
- 
## Minikube vs. Kubernetes
- Minikube is a version of Kubernetes, so it doesn’t really make sense to think of them as being binary opposites. However, there are important differences between Minikube and most other versions of Kubernetes, as summarized in this chart
- **Kubernetes** is a powerful and feature-rich platform for managing large-scale containerized applications, suitable for production environments and complex deployment.
- **Minikube** on the other hand, is a lightweight tool primarily used for local development and testing, offering simplicity and ease of use

- **Mininkube** to run need any driver link: https://minikube.sigs.k8s.io/docs/drivers/docker/ choose and run then minikube will work
- Also create the docker user id and group " docker' group: 'sudo usermod -aG docker $USER && newgrp docker " Link: https://docs.docker.com/engine/install/linux-postinstall/
- We wont face this below screen shot isses after installing driver for minikube
  ![Image1](https://github.com/sivakumaraddala26/Kubernetes/assets/80095151/9ab55f56-c81a-4be6-8c1f-e2997aa0f7a0)

# Install the Kubectl 
- Install kubectl in linux link: https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/ use the link and install it installed successfully
- command for starting `minikube start`
- command for cheking the Interact with your cluster to access  `kubectl get po -A` and similarly to minikube version aslo like this `minikube kubectl -- get po -A`
- Once done the this process complete and will get a output like the below screen shot
 ![imag2](https://github.com/sivakumaraddala26/Kubernetes/assets/80095151/395fcad6-cee2-4353-8b6b-95cb533869ab)




  
