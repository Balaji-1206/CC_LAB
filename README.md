# Cloud Computing Laboratory (CC_LAB)

A comprehensive repository containing practical lab experiments, implementation guides, source code, and configurations for the **Cloud Computing Laboratory** course.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [List of Experiments](#-list-of-experiments)
- [Experiment Details](#-experiment-details)
  - [Experiment 1: Virtual Workstation](#experiment-1--virtual-workstation)
  - [Experiment 2: Virtual Machine – C Compiler](#experiment-2--virtual-machine--c-compiler)
  - [Experiment 3: Google App Engine Hello World](#experiment-3--google-app-engine-hello-world)
  - [Experiment 4: GAE Launcher – Launch Web Applications](#experiment-4--gae-launcher--launch-web-applications)
  - [Experiment 5: CloudSim Simulation](#experiment-5--cloudsim-simulation)
  - [Experiment 6: Virtual Machine File Transfer](#experiment-6--virtual-machine-file-transfer)
  - [Experiment 7: Hadoop Single Node Cluster](#experiment-7--hadoop-single-node-cluster)
  - [Experiment 8: First Docker Container](#experiment-8--first-docker-container)
  - [Experiment 9: Run Containers from Docker Hub](#experiment-9--run-containers-from-docker-hub)
- [Repository Structure](#-repository-structure)
- [Prerequisites & Tools](#-prerequisites--tools)
- [Getting Started](#-getting-started)

---

## 🌟 Overview

This laboratory repository covers foundational and advanced topics in **Cloud Computing**, **Virtualization**, **Platform-as-a-Service (PaaS)**, **Cloud Simulation**, **Big Data / Distributed Processing**, and **Containerization (Docker)**:

- **Hypervisors & Virtual Machines**: Type-2 virtualization, minimal Linux operating systems, compiler provisioning, and inter-VM file transfer.
- **PaaS (Google App Engine)**: Java Servlets, deployment descriptors (`web.xml`, `appengine-web.xml`), static hosting, and `app.yaml` routing.
- **Cloud Simulation (CloudSim)**: Modeling datacenters, virtual machines, cloudlets, broker allocation, and execution scheduling.
- **Distributed Computing (Hadoop)**: Single-node cluster setup, HDFS storage, YARN resource management, and MapReduce processing.
- **Containerization (Docker)**: Dockerfile creation, image building, container execution, port forwarding, and multi-service lifecycle management with Docker Hub.

---

## 🧪 List of Experiments

| # | Experiment Name | Focus Area | Key Technologies / Tools | Directory |
|---|-----------------|------------|--------------------------|-----------|
| **1** | [Virtual Workstation](#experiment-1--virtual-workstation) | Virtualization / Hypervisors | Oracle VM VirtualBox, Windows 98 / Linux | [`Exp 1/`](./Exp%201/) |
| **2** | [Virtual Machine – C Compiler](#experiment-2--virtual-machine--c-compiler) | OS & Compiler Provisioning | Tiny Core Linux, `compiletc` (GCC), C | [`Exp 2/`](./Exp%202/) |
| **3** | [Google App Engine Hello World](#experiment-3--google-app-engine-hello-world) | PaaS / Java Web Apps | Google App Engine SDK, Eclipse IDE, Java Servlet | [`Exp 3/`](./Exp%203/) |
| **4** | [GAE Launcher – Web Applications](#experiment-4--gae-launcher--launch-web-applications) | PaaS / Static Web Hosting | Google Cloud SDK, `app.yaml`, Python 2.7, HTML/CSS | [`Exp 4/`](./Exp%204/) |
| **5** | [CloudSim Simulation](#experiment-5--cloudsim-simulation) | Cloud Modeling & Simulation | CloudSim 3.0.3, Apache Commons Math, Java | [`Exp 5/`](./Exp%205/) |
| **6** | [Virtual Machine File Transfer](#experiment-6--virtual-machine-file-transfer) | VM Networking & Storage | VirtualBox Guest Additions, USB Passthrough, Shared Folders | [`Exp 6/`](./Exp%206/) |
| **7** | [Hadoop Single Node Cluster](#experiment-7--hadoop-single-node-cluster) | Distributed Computing / Big Data | Apache Hadoop 2.7.0, HDFS, YARN, MapReduce, Ubuntu Linux | [`Exp 7/`](./Exp%207/) |
| **8** | [First Docker Container](#experiment-8--first-docker-container) | Containerization | Docker, Dockerfile, Python 3 | [`Exp 8/`](./Exp%208/) |
| **9** | [Run Containers from Docker Hub](#experiment-9--run-containers-from-docker-hub) | Container Orchestration & Registries | Docker CLI, Docker Hub, Nginx, MongoDB, Ubuntu | [`Exp 9/`](./Exp%209/) |

---

## 📖 Experiment Details

### Experiment 1 – Virtual Workstation
- **Aim:** Install VirtualBox / VMware / equivalent open-source cloud workstation with different flavours of Linux or Windows OS on top of Windows 8 and above.
- **Key Concepts:** Hypervisor (Type-2), Virtual Machines, Hardware Resource Allocation (RAM, vCPU, VDI Disk).
- **Key Files:** [`Exp 1/setup.txt`](./Exp%201/setup.txt), [`Exp 1/output.txt`](./Exp%201/output.txt), [`Exp 1/readme.md`](./Exp%201/readme.md)

---

### Experiment 2 – Virtual Machine: C Compiler
- **Aim:** Install a C compiler in the virtual machine created using VirtualBox and execute simple programs.
- **Key Concepts:** Minimal Linux distributions (Tiny Core Linux), package management (`tce-load`), C compilation toolchain (`compiletc`), and execution.
- **Key Files:** [`Exp 2/demo.c`](./Exp%202/demo.c), [`Exp 2/output.txt`](./Exp%202/output.txt), [`Exp 2/readme.md`](./Exp%202/readme.md)

---

### Experiment 3 – Google App Engine Hello World
- **Aim:** Install Google App Engine, create a Hello World web application, and run simple web applications using Java.
- **Key Concepts:** Platform-as-a-Service (PaaS), Eclipse Google Plugin, App Engine Java SDK, Java Servlets, `web.xml`, and `appengine-web.xml`.
- **Key Files:** [`Exp 3/HelloWorldServlet.java`](./Exp%203/HelloWorldServlet.java), [`Exp 3/appengine-web.xml`](./Exp%203/appengine-web.xml), [`Exp 3/web.xml`](./Exp%203/web.xml), [`Exp 3/index.html`](./Exp%203/index.html), [`Exp 3/readme.md`](./Exp%203/readme.md)

---

### Experiment 4 – GAE Launcher: Launch Web Applications
- **Aim:** Use GAE launcher to configure and launch web applications on Google App Engine.
- **Key Concepts:** Application configuration (`app.yaml`), static file handling, local development server (`dev_appserver.py`), and Google Cloud SDK deployment (`gcloud app deploy`).
- **Key Files:** [`Exp 4/app.yaml`](./Exp%204/app.yaml), [`Exp 4/deploy.txt`](./Exp%204/deploy.txt), [`Exp 4/www/index.html`](./Exp%204/www/index.html), [`Exp 4/www/css/style.css`](./Exp%204/www/css/style.css), [`Exp 4/readme.md`](./Exp%204/readme.md)

---

### Experiment 5 – CloudSim Simulation
- **Aim:** Simulate a cloud scenario using CloudSim and run a scheduling algorithm.
- **Key Concepts:** Cloud modeling, Datacenters, Host provisioning, Virtual Machines (VM), Cloudlets (tasks), DatacenterBroker, and discrete-event simulation.
- **Key Files:** [`Exp 5/CloudSimExample1.java`](./Exp%205/CloudSimExample1.java), [`Exp 5/output.txt`](./Exp%205/output.txt), [`Exp 5/readme.md`](./Exp%205/readme.md)

---

### Experiment 6 – Virtual Machine File Transfer
- **Aim:** Find a procedure to transfer files from one virtual machine to another virtual machine using VirtualBox.
- **Key Concepts:** Host-to-Guest and Guest-to-Guest file transfer via:
  1. Bidirectional Drag and Drop (Guest Additions)
  2. USB Controller & Device Filters (Extension Pack)
  3. Shared Folder mounting (`/media/sf_<name>` / Network Drive)
- **Key Files:** [`Exp 6/procedure.txt`](./Exp%206/procedure.txt), [`Exp 6/output.txt`](./Exp%206/output.txt), [`Exp 6/readme.md`](./Exp%206/readme.md)

---

### Experiment 7 – Hadoop Single Node Cluster
- **Aim:** Install Hadoop Single Node Cluster and run simple applications like WordCount.
- **Key Concepts:** Distributed storage and computing, HDFS (NameNode, DataNode, SecondaryNameNode), YARN (ResourceManager, NodeManager), passwordless SSH authentication, and XML configuration (`core-site.xml`, `hdfs-site.xml`, `mapred-site.xml`, `yarn-site.xml`).
- **Key Files:** [`Exp 7/setup.txt`](./Exp%207/setup.txt), [`Exp 7/output.txt`](./Exp%207/output.txt), [`Exp 7/readme.md`](./Exp%207/readme.md)

---

### Experiment 8 – Creating and Executing Your First Docker Container
- **Aim:** Create and execute a Docker container using a Python program.
- **Key Concepts:** Containerization vs. Virtualization, `Dockerfile` syntax (`FROM`, `COPY`, `CMD`), image building (`docker build`), container lifecycle (`docker run`, `docker ps`, `docker rm`).
- **Key Files:** [`Exp 8/Dockerfile`](./Exp%208/Dockerfile), [`Exp 8/main.py`](./Exp%208/main.py), [`Exp 8/output.txt`](./Exp%208/output.txt), [`Exp 8/readme.md`](./Exp%208/readme.md)

---

### Experiment 9 – Run a Container from Docker Hub
- **Aim:** Run containers from Docker Hub using Docker CLI commands.
- **Key Concepts:** Docker Hub registry, interactive containers (`ubuntu`), detached web servers (`nginx`), database services (`mongo:4.4`), port forwarding (`-p 8080:80`, `-p 8081:27017`), and container cleanup (`docker system prune`).
- **Key Files:** [`Exp 9/docker_commands.txt`](./Exp%209/docker_commands.txt), [`Exp 9/output.txt`](./Exp%209/output.txt), [`Exp 9/readme.md`](./Exp%209/readme.md)

---

## 📁 Repository Structure

```text
CC_LAB/
├── Exp 1/                        # Experiment 1: Virtual Workstation
│   ├── output.txt
│   ├── readme.md
│   └── setup.txt
├── Exp 2/                        # Experiment 2: Virtual Machine C Compiler
│   ├── demo.c
│   ├── output.txt
│   └── readme.md
├── Exp 3/                        # Experiment 3: Google App Engine Hello World
│   ├── HelloWorldServlet.java
│   ├── appengine-web.xml
│   ├── index.html
│   ├── output.txt
│   ├── readme.md
│   └── web.xml
├── Exp 4/                        # Experiment 4: GAE Launcher Web Applications
│   ├── app.yaml
│   ├── deploy.txt
│   ├── output.txt
│   ├── readme.md
│   └── www/
│       ├── css/style.css
│       └── index.html
├── Exp 5/                        # Experiment 5: CloudSim Simulation
│   ├── CloudSimExample1.java
│   ├── output.txt
│   └── readme.md
├── Exp 6/                        # Experiment 6: Virtual Machine File Transfer
│   ├── output.txt
│   ├── procedure.txt
│   └── readme.md
├── Exp 7/                        # Experiment 7: Hadoop Single Node Cluster
│   ├── output.txt
│   ├── readme.md
│   └── setup.txt
├── Exp 8/                        # Experiment 8: First Docker Container
│   ├── Dockerfile
│   ├── main.py
│   ├── output.txt
│   └── readme.md
├── Exp 9/                        # Experiment 9: Run Container from Docker Hub
│   ├── docker_commands.txt
│   ├── output.txt
│   └── readme.md
└── README.md                     # Root Documentation (This File)
```

---

## 🛠️ Prerequisites & Tools

| Software / Tool | Recommended Version | Purpose |
|-----------------|---------------------|---------|
| **Oracle VM VirtualBox** | 6.x or 7.x | Type-2 Hypervisor for VM experiments (Exp 1, 2, 6, 7) |
| **VirtualBox Extension Pack & Guest Additions** | Matching VirtualBox version | USB passthrough & Shared Folders (Exp 6) |
| **Java Development Kit (JDK)** | Java 7 / 8 / OpenJDK | GAE development, CloudSim, and Hadoop (Exp 3, 5, 7) |
| **Eclipse IDE** | Java / Java EE package | GAE Java apps and CloudSim execution (Exp 3, 5) |
| **CloudSim** | 3.0.3 | Cloud simulation toolkit (Exp 5) |
| **Apache Commons Math** | 3.6.1 | Math library required by CloudSim (Exp 5) |
| **Google Cloud SDK / GAE SDK** | Latest | App Engine local server & deployment (Exp 3, 4) |
| **Apache Hadoop** | 2.7.0 | Distributed cluster execution (Exp 7) |
| **Docker Desktop** | Latest | Container runtime & Docker CLI (Exp 8, 9) |
| **Python** | 3.x / 2.7 | Container script (Exp 8) & GAE runtime (Exp 4) |

---

## 🚀 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Aadhish23/CC_LAB.git
   cd CC_LAB
   ```

2. **Navigate to an Experiment:**
   Enter any experiment folder to access its dedicated `readme.md`, source files, configuration files, and setup instructions:
   ```bash
   cd "Exp 8"
   docker build -t python-test .
   docker run python-test
   ```

3. **Explore Individual Readmes:**
   Each experiment folder contains a complete guide with step-by-step instructions, code listings, execution steps, and sample outputs.
