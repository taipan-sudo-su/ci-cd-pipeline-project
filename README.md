Jenkins Pipeline for Java Application with Maven, SonarQube, Argo CD, Helm, and Kubernetes
This Jenkins pipeline automates the build, test, deployment, and monitoring of a Java-based application using Maven, SonarQube for code quality analysis, Argo CD for continuous delivery and Kubernetes for container orchestration.

Prerequisites
Jenkins: Ensure Jenkins is installed and configured with necessary plugins including Maven Integration, Kubernetes, SonarQube Scanner, and Argo CD plugin.
Kubernetes Cluster: Access to a Kubernetes cluster where applications will be deployed (i used minikube).
SonarQube: SonarQube server setup for code quality analysis.
