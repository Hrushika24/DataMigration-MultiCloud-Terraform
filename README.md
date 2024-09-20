# DataMigration-MultiCloud-Terraform
"Cloud migration project involving the transition of on-premises data to a multi-cloud environment, with migration automation implemented using Terraform."

# Project Overview

### Project: 
A hotel migrating its application from on-premises infrastructure to the cloud.

### Problem:
Due to the COVID-19 situation, the hotel planned to collect incoming guests' COVID-19 test details and store a PDF of their test results. Initially, this setup worked fine, but with a surge in traffic, the hotel needed to scale up quickly. However, they lacked the financial resources and time to purchase and set up additional hardware. As a result, they decided to migrate their application to the cloud for better scalability and flexibility.

### Solution:
The following cloud services and tools were utilized to enable the migration and scale the application:

- **Google Cloud SQL**: Used to manage the hotel's MySQL database in a scalable and fully managed cloud environment.
- **Google Container Registry**: A modern solution to host and manage the application, which runs within Docker containers.
- **Google Kubernetes Engine (GKE)**: Deployed the containerized application for efficient scaling and orchestration.
- **AWS S3**: Chosen to store PDF files of guests' COVID-19 test reports, leveraging a hybrid cloud setup.

All deployments and infrastructure provisioning were automated using **Terraform**, ensuring a consistent and streamlined DevOps process.

### Solution Architecture:
![image](https://github.com/user-attachments/assets/9f45bceb-4e19-4056-897c-5867fefbf71f)

### Credits:
- Project developed during the FREE Intensive Cloud Training with Jean Rodrigues, CEO & CTO of The Cloud Bootcamp.
- LinkedIn profile: linkedin.com/in/jean-rod
