The **Coworking Space Service Extension** is a microservice-based API system enabling user token requests and admin authorization for coworking spaces. This project tasks a DevOps engineer to build a pipeline for deploying an analytics API in Kubernetes, providing business analysts with user activity data.

### **Getting Started**

#### **Local Requirements**

1.  A Python 3.6+ environment for running applications and managing dependencies.
    
2.  Docker CLI for building and running images locally.
    
3.  kubectl for interacting with Kubernetes clusters.
    
4.  helm for applying Helm Charts.
    

#### **Remote Dependencies**

1.  AWS services like CodeBuild (for building images), ECR (for hosting), and EKS (for Kubernetes).
    
2.  CloudWatch for monitoring logs and activity.
    
3.  GitHub for code access.
    

### **Setup**

1.  **Database Configuration**: Use a Helm Chart to set up PostgreSQL, accessible via Kubernetes. Seed tables and test connections using port forwarding or accessing a pod directly.
    
2.  **Local Analytics Application**:
    
    *   Install Python dependencies with pip.
        
    *   Set environment variables (e.g., database credentials) and run the app.
        
    *   Verify functionality through API calls to generate usage reports.
        

### **Project Deliverables**

1.  A Dockerfile based on a Python image for building the application.
    
2.  An AWS CodeBuild pipeline to push Docker images to AWS ECR.
    
3.  Kubernetes configuration files for deploying the service, database, and associated resources.
    
4.  Screenshots verifying deployment steps, including services, pods, deployments, and AWS CloudWatch logs.
    
5.  A comprehensive README.md explaining deployment workflows, tools, and releasing updates.
    

### **Standout Suggestions**

1.  Complete CI-CD flow using CodePipeline, ECR & Codebuild
    
2.  Monitor tools with Cloudwatch
    
3.  High Avaibility with K8s and EKS
