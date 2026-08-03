# ☁️ Self-Optimizing Cloud Network Traffic Management System

A cloud infrastructure project built on Microsoft Azure that demonstrates intelligent traffic routing, application hosting, and real-time monitoring. The system is designed to improve application availability by distributing traffic across cloud resources while continuously monitoring performance.

> **Note:** This project implements the Azure infrastructure components. AI/ML-based predictive optimization is proposed as a future enhancement.

---

# 📌 Project Overview

Modern cloud applications require high availability, efficient traffic routing, and continuous monitoring.

This project demonstrates how Microsoft Azure services can be integrated to:

- Deploy cloud applications
- Route user traffic efficiently
- Monitor infrastructure health
- Improve application availability
- Build a scalable cloud architecture

---

# 🏗️ Architecture

```text
                    +----------------------+
                    |      End Users       |
                    +----------+-----------+
                               |
                               v
                 +------------------------------+
                 |     Azure Traffic Manager     |
                 +---------------+--------------+
                                 |
          +----------------------+----------------------+
          |                                             |
          |                                             |
          v                                             v
+-------------------------+              +-------------------------+
| Azure App Service       |              | Azure Virtual Machine   |
| (Web Application)       |              | (Application Instance)  |
+------------+------------+              +------------+------------+
             |                                          |
             +------------------+-----------------------+
                                |
                                v
                    +--------------------------+
                    |     Azure Monitor        |
                    | Metrics • Logs • Alerts  |
                    +--------------------------+
```

---

# 🚀 Features

- Intelligent traffic routing using Azure Traffic Manager
- Application hosting with Azure App Service
- Compute infrastructure using Azure Virtual Machines
- Real-time monitoring using Azure Monitor
- Improved availability through distributed cloud resources
- Cloud-native architecture for scalable deployments

---

# 🛠️ Azure Services Used

- Microsoft Azure
- Azure App Service
- Azure Virtual Machines
- Azure Traffic Manager
- Azure Monitor

---

# 📋 Prerequisites

- Microsoft Azure Account
- Azure Subscription
- Basic knowledge of Azure Portal
- Resource Group

---

# ⚙️ Project Workflow

## Step 1

Create a Resource Group.

---

## Step 2

Deploy the application using Azure App Service.

---

## Step 3

Create an Azure Virtual Machine.

---

## Step 4

Configure Azure Traffic Manager.

- Add application endpoints
- Configure routing method
- Enable endpoint monitoring

---

## Step 5

Configure Azure Monitor.

- Performance Metrics
- Activity Logs
- Alerts
- Health Monitoring

---

## Step 6

Access the application.

Traffic Manager automatically directs users to the available endpoint while Azure Monitor continuously tracks application performance.

---

# 🔄 Workflow

```text
User Request
      │
      ▼
Azure Traffic Manager
      │
      ▼
Select Healthy Endpoint
      │
      ├──────────────┐
      ▼              ▼
Azure App Service   Azure VM
      │              │
      └──────┬───────┘
             ▼
Application Response
             │
             ▼
Azure Monitor
(Metrics • Logs • Alerts)
```

---

# 📊 Project Objectives

- Improve application availability
- Distribute incoming traffic efficiently
- Monitor infrastructure health
- Reduce downtime
- Build a scalable cloud architecture

---

# 📖 Learning Outcomes

- Azure Resource Management
- Azure App Service deployment
- Azure Virtual Machine configuration
- Azure Traffic Manager routing
- Azure Monitor metrics and alerts
- Designing highly available cloud solutions

---

# 📈 Future Enhancements

- AI-based traffic prediction
- Automatic traffic optimization
- Auto Scaling using Azure Virtual Machine Scale Sets
- Azure Load Balancer integration
- Azure Application Gateway
- Azure Front Door
- Infrastructure as Code using Terraform
- Azure Functions for automation

---

# 💻 Technologies Used

| Category | Technology |
|----------|------------|
| Cloud Platform | Microsoft Azure |
| Compute | Azure Virtual Machines |
| PaaS | Azure App Service |
| Traffic Routing | Azure Traffic Manager |
| Monitoring | Azure Monitor |

---

# 📷 Suggested Screenshots

- Azure Portal Dashboard
- Resource Group
- Azure App Service
- Azure Virtual Machine
- Azure Traffic Manager
- Azure Monitor Dashboard
- Performance Metrics
- Alert Configuration

---

# 👨‍💻 Author

**Basil Ibnu Haris**

B.Tech Computer Science & Engineering

Cloud Computing | Microsoft Azure | AWS | Apache CloudStack | SQL
