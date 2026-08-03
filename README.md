# ☁️ Self-Optimizing Cloud Network Traffic Management System

A cloud infrastructure project built on **Microsoft Azure** that demonstrates intelligent traffic routing, application hosting, and real-time monitoring using Azure Traffic Manager, Azure App Service, Azure Virtual Machines, and Azure Monitor. The project focuses on improving application availability and performance through efficient traffic management.

---

## 📌 Project Overview

Modern cloud applications require high availability and efficient traffic distribution to ensure a seamless user experience.

This project demonstrates how Azure services can be used to deploy cloud applications, distribute incoming traffic across application endpoints, and monitor resource health in real time.

The project is based on the concept of a **Self-Optimizing Cloud Network Traffic Management System**, where cloud resources are monitored continuously, enabling intelligent traffic management and improved reliability.

---

## 🎯 Objectives

- Improve application availability.
- Optimize network traffic routing.
- Monitor cloud resources in real time.
- Reduce downtime using health-based traffic routing.
- Demonstrate Azure cloud infrastructure deployment.

---

## 🏗️ Architecture

```text
                 Internet Users
                       │
                       ▼
        +-----------------------------+
        | Azure Traffic Manager       |
        +-----------------------------+
                 │              │
                 ▼              ▼
      +----------------+   +----------------+
      | Azure App      |   | Azure Virtual  |
      | Service        |   | Machine        |
      +----------------+   +----------------+
                 │              │
                 └──────┬───────┘
                        ▼
              Azure Monitor & Alerts
```

---

## 🚀 Features

- Intelligent traffic routing using Azure Traffic Manager
- Application deployment on Azure App Service
- Cloud infrastructure using Azure Virtual Machines
- Real-time monitoring with Azure Monitor
- Health-based routing for improved reliability
- Scalable cloud architecture

---

## 🛠️ Azure Services Used

- Microsoft Azure
- Azure App Service
- Azure Virtual Machines
- Azure Traffic Manager
- Azure Monitor

---

## 📋 Prerequisites

- Microsoft Azure Account
- Basic knowledge of cloud computing
- Azure Portal access

---

## ⚙️ Project Workflow

### Step 1: Deploy the Application

Deploy the application using Azure App Service and Azure Virtual Machines.

---

### Step 2: Configure Azure Traffic Manager

- Create a Traffic Manager profile.
- Add application endpoints.
- Configure routing method.
- Enable endpoint health monitoring.

---

### Step 3: Configure Azure Monitor

- Enable diagnostic monitoring.
- Configure performance metrics.
- Create alert rules.
- Monitor application availability.

---

### Step 4: Test Traffic Routing

- Access the application.
- Verify Traffic Manager routes requests correctly.
- Observe health metrics in Azure Monitor.

---

## 📊 Project Flow

1. User sends a request.
2. Azure Traffic Manager receives the request.
3. Traffic Manager selects the best available endpoint.
4. Request is forwarded to Azure App Service or Virtual Machine.
5. Azure Monitor continuously tracks resource health.
6. Alerts are generated if abnormal conditions are detected.

---

## 📚 Learning Outcomes

- Azure cloud infrastructure deployment
- Azure App Service hosting
- Azure Virtual Machine management
- Azure Traffic Manager configuration
- Azure Monitor and Alerts
- High Availability concepts
- Cloud traffic management

---

## 💡 Future Enhancements

- Implement AI-based traffic prediction.
- Automatic traffic optimization using Machine Learning.
- Dynamic resource scaling.
- Multi-region deployment.
- Integration with Azure Load Balancer.
- Infrastructure as Code using Terraform or Bicep.

---

## 📷 Screenshots

Add screenshots of:

- Azure Resource Group
- Azure App Service
- Azure Virtual Machine
- Azure Traffic Manager
- Azure Monitor Dashboard
- Alert Configuration

---

## 🧰 Technologies Used

| Category | Technology |
|----------|------------|
| Cloud Platform | Microsoft Azure |
| Compute | Azure Virtual Machines |
| Platform Service | Azure App Service |
| Traffic Management | Azure Traffic Manager |
| Monitoring | Azure Monitor |

---

## 🎓 Skills Demonstrated

- Cloud Infrastructure Deployment
- Azure Resource Management
- Traffic Routing
- Cloud Monitoring
- High Availability
- Performance Monitoring
- Infrastructure Management

---

## 👨‍💻 Author

**Basil Ibnu Haris**

B.Tech Computer Science & Engineering

Cloud Computing | Microsoft Azure | AWS | Apache CloudStack | SQL | Power BI 
