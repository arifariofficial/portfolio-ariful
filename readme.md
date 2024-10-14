# Portfolio of Ariful

## Repository: 
This repository consists of multiple submodules, each utilizing different technologies tailored to their specific functionalities.

To clone the parent repository along with all its submodules, follow the steps below.
```bash
git clone https://github.com/arifariofficial/portfolio-ariful.git
cd portfolio-ariful
git submodule init
git submodule update

```

### [nextjs-postgres-gcp-org.git](https://github.com/arifariofficial/nextjs-postgres-gcp-org.git)
Demo: [https://ariful.org](https://ariful.org)

This project is a modern, scalable web application built with **Next.js** and **TypeScript**, offering a maintainable and high-performing frontend and backend. It utilizes **PostgreSQL** as the core database to ensure data consistency, reliability, and optimal performance. Authentication is handled through **NextAuth**, providing a secure and flexible solution for user management and sign-ins.

The application architecture is modular, incorporating multiple sub-projects to cater to specific functionalities. A highlight among these is the **RAG (Retrieval-Augmented Generation) Application**, which leverages **AI-SDK** to introduce advanced, AI-powered capabilities for more intelligent data handling and retrieval.

To ensure consistent development and deployment environments, the entire project is fully containerized with **Docker**. The application is deployed on **Google Cloud Platform (GCP)** using VM instances, offering scalability, reliability, and enhanced resource management. Continuous Integration and Continuous Deployment (CI/CD) are facilitated using **Jenkins**, enabling a smooth, automated build and deployment pipeline.

### Technologies Used:
- **Frontend and Backend**: Next.js (TypeScript)
- **Database**: PostgreSQL
- **Authentication**: NextAuth
- **Containerization**: Docker
- **Cloud Hosting**: GCP VM Instances
- **CI/CD**: Jenkins
- **Sub-project**: RAG Application (AI-SDK integration)
