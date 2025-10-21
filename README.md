**Professional CV Web App Deployment with CI/CD**
-------------------------------------------------
> This project is a web application that collects personal and career information from users and generates a professional CV. 
> The deployment is fully automated using Kubernetes, Docker, Git, and Jenkins, enabling seamless updates whenever changes are pushed to the repository.
------------------------------------------------------------------------------------------------------------------------------------------------------

**Features**
------------
> Collects personal and career details from users.
> Generates a professional CV dynamically.
> Containerized web application with enhanced httpd image.
> Kubernetes deployment with multiple service types: ClusterIP, NodePort, LoadBalancer.
> Continuous Integration and Continuous Deployment (CI/CD) with Jenkins.
------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Structure**
---------------------
> Docker & HTTPD
> Enhanced httpd image prepared with specific configurations.
> Custom index.html to display the web interface.
> Kubernetes Resources
> Namespace YAML file.
> Deployment YAML file for web application pods.
> Services YAML files: ClusterIP, NodePort, LoadBalancer.
> Git Integration
> All YAML files setup pushed to remote GitHub repository.
> Version control enabled for tracking changes and triggering CI/CD pipeline.
------------------------------------------------------------------------------------------------------------------------------------------------------

**Jenkins Pipeline**
--------------------
> Monitors GitHub repository for changes (e.g., image updates).
> Automatically deletes the existing deployment and pods.
> Deploys new pods and deployment based on updated image or YAML files.
> Ensures zero manual intervention for updates.
------------------------------------------------------------------------------------------------------------------------------------------------------

**Prerequisites**
-----------------
> Docker installed locally.
> Kubernetes cluster (minikube, kind, or cloud provider).
> Jenkins server setup with GitHub integration.
> kubectl configured to access the cluster.
------------------------------------------------------------------------------------------------------------------------------------------------------

**Usage**
---------
> Access the web application via the LoadBalancer or NodePort service URL.
> Fill in personal and career details.
> Generate a professional CV instantly.
------------------------------------------------------------------------------------------------------------------------------------------------------

**GitHub Repository**
---------------------
> [https://github.com/Sembawey/Resume_Maker.git]
------------------------------------------------------------------------------------------------------------------------------------------------------

**Technologies Used**
---------------------
> Frontend/Backend: HTML, CSS, JS (within index.html)
> Containerization: Docker
> Web Server: Apache HTTPD
> Orchestration: Kubernetes (Deployment, Services, Namespace)
> CI/CD: Jenkins
> Version Control: Git & GitHub
------------------------------------------------------------------------------------------------------------------------------------------------------

**Future Enhancements**
-----------------------
> Dynamic CV templates selection.
> Export CV as PDF.
> User authentication for saving multiple CVs.
> Multi-environment deployments (Dev/Staging/Production).
------------------------------------------------------------------------------------------------------------------------------------------------------

**Author**
----------
> Ahmed El-Sembawey
> Email: ahmedelsembaweyofficial@gmail.com
> LinkedIn: [https://www.linkedin.com/in/ahmed-elsembawey/]
------------------------------------------------------------------------------------------------------------------------------------------------------
