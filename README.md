---

# Project: CloudBuild - Scalable Infrastructure on GCP

---

Project CloudBuild: A scalable cloud infrastructure on GCP using Terraform, developed for the "CSY Network Structures and Cloud Computing" course. Integrates Compute Engine, Cloud SQL, and Cloud Pub/Sub for a secure, high-availability web application with automated deployments and robust monitoring.

# Project Overview: CloudBuild ☁️

## Objective 🎯
This project, completed as part of the "CSY Network Structures and Cloud Computing" course at Northeastern University, focuses on creating a scalable and secure cloud infrastructure on Google Cloud Platform (GCP). Under Professor Deas Parik's guidance, we used Terraform to automate the setup and management of GCP services, supporting a web application with robust deployment processes, enhanced security, and comprehensive monitoring.

## Architecture Design 🏗️


![CloudBuild Pipeline](https://github.com/CSYE-6225-2024-Cloud-Computing/Project-CloudBuild-Scalable-Infrastructure-on-GCP/blob/main/images/cloudbuild-pipeline.svg)

### 1. Infrastructure Automation with Terraform 🔧
- **Terraform** was used to define and manage the cloud infrastructure, allowing us to treat infrastructure as code. This made it easy to replicate environments, manage changes, and ensure consistency.

### 2. Key GCP Components ☁️
- **Compute Engine**: Hosted the web application with managed instance groups to auto-scale based on traffic, ensuring high availability and efficient resource use.
- **Cloud SQL**: Provided a fully managed relational database with automatic scaling, high availability, and data integrity.
- **Cloud Pub/Sub**: Enabled asynchronous messaging and an event-driven architecture, decoupling system components for a more flexible design.
- **Cloud Functions**: Facilitated serverless execution of lightweight code in response to Cloud Pub/Sub events, allowing dynamic processing without managing infrastructure.

### 3. Security and Networking 🔒
- **VPC Peering**: Secured connections between services across multiple VPC networks, maintaining network isolation while enabling efficient communication.
- **Private IPs and Firewall Configurations**: Enhanced internal communication security with private IPs and carefully configured firewall rules.
- **Encryption**: Ensured data privacy and compliance by encrypting data at rest and in transit.

### 4. Automated Deployment Pipeline 🚀
- **GitHub Actions**: Streamlined deployment with CI/CD pipelines, automating updates and reducing manual effort.
- **Packer**: Created consistent machine images with pre-installed software and configurations, making deployments faster and smoother.

### 5. Monitoring and Logging 📊
- **Cloud Logging and Monitoring**: Centralized logs, set up alerts for key metrics, and visualized performance data for proactive management and timely incident response.

### 6. Load Balancing and High Availability ⚖️
- Implemented load balancing to evenly distribute traffic across instances, ensuring high availability and handling varying traffic levels seamlessly.

### 7. Domain and DNS Management 🌐
- Managed DNS settings to map a custom domain to the application, improving user access and reinforcing brand identity.

# Project Repositories for CloudBuild ☁️

The **CSYE-6225-2024-Cloud-Computing** organization has created several repositories for the CloudBuild project. Each repository serves a specific purpose in building and managing the cloud infrastructure and application. 

### Repositories 📦

### 1. **webapp** 🌐
- **Repository Link**: [webapp](https://github.com/CSYE-6225-2024-Cloud-Computing/webapp)
- **Description**: This repository contains the code for building and deploying a FastAPI-based backend web application. It includes important information on prerequisites for building and deploying the application locally, as well as detailed instructions for deployment.

### 2. **tf-gcp-infra** 🛠️
- **Description**: This private repository provides Terraform templates for setting up networking resources in Google Cloud Platform (GCP). It includes configurations for Virtual Private Cloud (VPC), subnets, routes, and other essential networking components.

### 3. **serverless** 🚀
- **Description**: This private repository contains configurations and code for implementing serverless functions and services. It supports the serverless aspects of the CloudBuild project, enabling event-driven architectures and lightweight, scalable computing.

Feel free to explore the public repository for more details and reach out if you have any questions. Thank you for your interest!


## Conclusion 🏅
We successfully built a secure, scalable, and efficient cloud infrastructure on GCP. Thanks to the collaboration and guidance from Professor Deas Parik and the teaching assistants, this project was a great success. Feel free to reach out if you have any questions or need more details. Thank you for your interest!

