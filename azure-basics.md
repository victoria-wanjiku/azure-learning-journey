# Azure Basics ☁️

## Scalability

### Vertical Scaling

Increasing resources on the same server.

Examples:

* More CPU
* More RAM
* More Storage

### Horizontal Scaling

Adding more servers to handle increased demand.

Examples:

* Server 1
* Server 2
* Server 3

---

# Cloud Service Types

## Infrastructure as a Service (IaaS)

Provides:

* Virtual Machines
* Storage
* Networking

Customer manages:

* Applications
* Data
* Operating System

**Use Case:** Moving infrastructure from on-premises to the cloud.

**Example:** Azure Virtual Machines

---

## Platform as a Service (PaaS)

Provides:

* Infrastructure
* Operating System
* Runtime Environment

Customer manages:

* Applications
* Data

**Use Case:** Developers focus on building applications without managing servers.

**Example:** Azure App Service

---

## Software as a Service (SaaS)

Provides:

* Complete software application

Customer manages:

* Data

**Examples:**

* Outlook
* Gmail
* Microsoft 365

**Memory Trick:**

* IaaS = Servers
* PaaS = Code
* SaaS = Use the App

---

# Azure Virtual Machines (VMs)

Azure Virtual Machines provide on-demand computing resources in Azure.

## Azure VM Families

| Family | Purpose                                   |
| ------ | ----------------------------------------- |
| B      | Budget - Cheap and burstable              |
| D      | Daily Use - General purpose               |
| E      | Extra Memory - Memory optimized           |
| F      | Fast CPU - Compute optimized              |
| M      | Massive Memory - Large databases          |
| L      | Lots of Storage Speed - Storage optimized |
| N      | NVIDIA GPU - AI and graphics workloads    |

### VM Naming Example

D2s_v5

* D = VM family
* 2 = Number of vCPUs
* s = Supports Premium SSD storage
* v5 = Hardware generation

---

# Azure Virtual Desktop (AVD)

Azure Virtual Desktop delivers Windows desktops and applications from Azure.

Features:

* Uses Microsoft Entra ID for authentication
* Keeps company data in Azure
* Supports secure remote work

### Session Types

**Single Session**

* One user per desktop

**Multi Session**

* Multiple users share Azure resources

---

# Virtual Machines vs Containers

A Virtual Machine virtualizes an entire computer including the operating system.

A Container virtualizes only the application and shares the operating system with other containers.

## Key Terms

### 🖥️ Virtual Machine (VM)

A complete virtual computer with its own operating system.

### 🍱 Container

A packaged application with everything it needs to run.

### 👨‍🍳 Docker

A tool used to create and run containers.

## VM vs Container

| Virtual Machine       | Container               |
| --------------------- | ----------------------- |
| Full operating system | Shares operating system |
| Heavier               | Lightweight             |
| Slower startup        | Faster startup          |

---

# Azure Container Services

## Azure Container Instances (ACI)

The fastest and simplest way to run containers in Azure.

Features:

* No VM management
* PaaS service
* Ideal for simple or short-lived workloads

### Memory Trick

🪑 ACI = Run one container quickly

---

## Azure Container Apps

Runs containers without managing infrastructure.

Features:

* Automatic scaling
* Load balancing
* Simplified container deployment

### Memory Trick

🍽️ Container Apps = Containers + Auto-scaling + Load Balancing

---

## Azure Kubernetes Service (AKS)

Manages and orchestrates large numbers of containers.

Features:

* High scalability
* Container orchestration
* Enterprise-grade container management

### Memory Trick

🧑‍💼 AKS = Manage many containers at scale

---

# Azure Functions

Azure Functions allow code to run on demand without managing servers (serverless computing).

## Stateless Functions

* Do not remember previous executions
* Start fresh every time

### Memory Trick

⚡ Stateless = Forgets everything

---

## Stateful Functions (Durable Functions)

* Remember previous steps
* Useful for long-running workflows

### Memory Trick

🧠 Stateful = Remembers progress

---

## Serverless Benefits

* No server management
* Automatic scaling
* Pay only when code runs

### Memory Trick

☁️ Functions = Run code only when needed
