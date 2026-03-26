# 📘 Raft Consensus Algorithm using Docker

## 🧪 Lab Title
Implementation of Raft Consensus Algorithm using Docker Containers

---

## 🎯 Aim
To implement a distributed system using the Raft Consensus Algorithm in Docker containers and observe:
- Leader election  
- Follower behavior  
- Fault tolerance  
- Quorum (majority)  

---

## 📚 Objectives
- Understand distributed systems and consensus algorithms  
- Implement Raft using multiple nodes  
- Simulate distributed environments using Docker  
- Observe leader election and re-election  
- Understand quorum and fault tolerance  

---

## 🛠️ Requirements

### Software
- Docker Desktop  
- Python (inside container)  
- Terminal / Command Prompt  

### Verify Docker Installation
```bash
docker --version

##📁 Project Structure
raft_docker_lab/
│
├── node.py
├── Dockerfile
├── docker-compose.yml
└── requirements.txt

##Setup Instructions
1. Create Project Folder
mkdir raft_docker_lab
cd raft_docker_lab
2. Create Required Files
type nul > node.py
type nul > Dockerfile
type nul > requirements.txt
type nul > docker-compose.yml
3. Add Dependency

Edit requirements.txt:

raftos
4. Add Code

Paste the required code into:

node.py
Dockerfile
docker-compose.yml
▶️ Running the Cluster
docker compose up --build

This starts a 3-node Raft cluster.

