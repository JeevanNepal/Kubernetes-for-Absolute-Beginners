# Kubernetes-for-Absolute-Beginners



What is kubernetes?
Ans: 

WHat is minikube?
Minikube is an open source tool that enables you to run Kubernetes on your laptop or other local machine.


The upcoming demo is completely optional, unless you want to setup a local environment on your laptop. Our hands-on labs will be sufficient for you to practice.

Some links used in the upcoming demo may have changed. Please find the latest links to the documentation topics below:

Install MiniKube: https://kubernetes.io/docs/tasks/tools/install-minikube/

VirtualBox: https://www.virtualbox.org/wiki/Downloads

MiniKube Download page for  Windows: https://github.com/kubernetes/minikube/releases



While using Minikube with  Virtualization technologies, specify the --vm-driver option like this:

minikube start --vm-driver=<driver_name>
More about it here: https://kubernetes.io/docs/setup/learning-environment/minikube/#specifying-the-vm-driver



A POD is a single instance of an application.

Create an NGINX Pod

kubectl run nginx --image=nginx



Kubernetes Concepts - https://kubernetes.io/docs/concepts/

Pod Overview- https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/
