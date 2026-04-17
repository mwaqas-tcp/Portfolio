🚀 Cloud & DevOps Portfolio – Migration, LMS & E-Commerce Platforms

This repository showcases real-world production experience across AWS cloud migration, LMS platform engineering, CI/CD automation, containerization, and enterprise e-commerce architecture.

📌 Table of Contents
Project 1: AWS Migration – Laravel Application
Project 2: HPrime LMS Platform (Moodle + BigBlueButton)
Project 3: Magento E-Commerce Platform (Multi-Cloud Ready)
CI/CD & Automation Work
Tech Stack Overview
Key Skills Demonstrated
Contact
☁️ Project 1: AWS Migration – Laravel Application (Lift, Shift & Modernization)
🧠 Overview

Migrated a production PHP Laravel application from on-prem VMware ESXi to AWS cloud. The project included infrastructure modernization, database migration to managed services, and implementation of CI/CD pipelines for multi-environment deployment.

🏗 Architecture
VMware ESXi (On-prem source system)
Amazon EC2 (Application hosting)
Amazon RDS (MySQL database)
Amazon Route 53 (DNS management)
Amazon SES (Email services)
AWS IAM (Identity & Access Management)
🔄 Migration Strategy (Zero/Low Downtime Approach)
Step 1: Full Backup & Restore
Performed full system backup using Acronis True Image
Restored application on AWS EC2
Initial database restore into Amazon RDS
Step 2: Differential Sync
Applied incremental/differential backups to reduce data lag
Synchronized changes between on-prem and cloud environment
Step 3: Tail Log / Final Sync
Captured final transaction logs before cutover
Applied last updates to ensure data consistency
Executed controlled cutover with minimal downtime
🔁 CI/CD & Multi-Environment Automation
Implemented Jenkins-based CI/CD pipelines
Designed multi-environment strategy:
Development
Staging
Production
Automated build and deployment of Laravel applications
Reduced manual deployment effort and improved release reliability
Standardized deployments across environments
📈 Outcome
Successful migration of production application to AWS
Improved scalability and operational efficiency
Introduced automated CI/CD pipeline workflows
Reduced deployment errors and release time
🎓 Project 2: HPrime LMS Platform (Moodle + BigBlueButton Integration)

🌐 Live Product: https://hprime.com.au/

🧠 Overview

Designed, deployed, and supported a production Learning Management System for HPrime, enabling schools and physician training programs with real-time virtual classrooms and recorded sessions.

🏗 Architecture
Moodle LMS (core learning platform)
BigBlueButton (live video conferencing)
Docker-based deployment environment
Recording storage and playback system
⚙️ Responsibilities
📚 LMS Platform Engineering
Deployed and configured Moodle LMS for production usage
Managed courses, users, roles, and learning workflows
🎥 Real-Time Virtual Classrooms
Integrated BigBlueButton with Moodle
Enabled live video/audio sessions
Configured recording and playback functionality
🐳 Containerization & Modernization
Migrated monolithic system to Docker-based architecture
Improved deployment consistency and scalability
Standardized environments across deployments
📈 Outcome
Enabled scalable remote learning during COVID
Improved platform stability and maintainability
Delivered production-ready LMS for education and healthcare training
🛒 Project 3: Magento E-Commerce Platform (Multi-Cloud Architecture)
🧠 Overview

Designed and deployed a full Magento-based e-commerce platform from scratch for enterprise use. The architecture was designed with multi-cloud readiness to ensure scalability, high availability, and deployment flexibility.

🏗 Architecture Design
Web layer (Magento application servers)
Database layer (separated MySQL backend)
Storage layer for media/assets
Cloud-agnostic deployment structure
⚙️ Responsibilities
Installed and configured the Magento e-commerce platform from scratch
Designed infrastructure for multi-cloud compatibility
Separated application, database, and storage layers
Ensured scalable architecture for high traffic workloads
Optimized performance for production e-commerce usage
🧩 Engineering Focus
Cloud-agnostic deployment design
Horizontal scalability planning
High availability considerations
Modular infrastructure separation (web/db/storage)
📈 Outcome
Delivered an enterprise-grade e-commerce platform
Enabled scalable and flexible deployment strategy
Designed system ready for multi-cloud environments
🔁 CI/CD & Automation (Cross-Project Capability)
Built Jenkins-based CI/CD pipelines for application deployments
Implemented multi-environment workflows (Dev / Staging / Prod)
Automated build and deployment processes
Reduced manual intervention and deployment risk
Improved release consistency and delivery speed
🧰 Tech Stack Summary
☁️ Cloud & Infrastructure
Amazon Web Services (EC2, RDS, Route 53, SES, IAM)
🔁 CI/CD & Automation
Jenkins
Multi-environment deployment pipelines
🐳 Containers & Virtualization
Docker
VMware ESXi
💻 Application Stack
PHP Laravel
MySQL
Magento
Moodle LMS
🎥 Collaboration / Streaming
BigBlueButton
🛠 Tools & OS
Linux (Ubuntu/CentOS)
Apache / Nginx
Git

Key Skills Demonstrated
AWS Cloud Migration (Lift & Shift + phased DB migration)
CI/CD pipeline design using Jenkins
Multi-environment deployment strategy
Enterprise LMS platform engineering
Magento e-commerce architecture design
Docker-based modernization
Database migration engineering (full + differential + tail log approach)
Production system support and optimization
Cloud architecture planning and scalability design

Location: Remote 
Focus: AWS, DevOps, Cloud Architecture, CI/CD
Interests: Kubernetes, Terraform, Platform Engineering

Final Summary

This portfolio demonstrates real-world experience in:

Enterprise cloud migration
Production LMS systems with real-time video integration
E-commerce platform architecture (Magento)
CI/CD automation and multi-environment deployments
Containerization and modernization strategies
