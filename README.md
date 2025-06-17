
# 🚀 Project 1: Ansible Cluster Setup in Docker 🐳

This project sets up an **Ansible Cluster** using Docker containers — manually built with no pre-pulled images.  
You'll create an Ansible Master container and two Ansible Node containers that communicate over SSH.

---

## 📦 What’s Inside

- 🐳 Custom Dockerfiles:
  - `ansible-master`: Installs Ansible, SSH, sudo
  - `ansible-node`: Installs Python, SSH, sudo
- 🔐 SSH key setup between containers
- 🧪 Ansible ping test between Master → Nodes

---

## 🔧 Requirements

- Docker 🐳
- Linux/MacOS or WSL (Windows Subsystem for Linux)
- Basic knowledge of terminal and Docker


## 🧱 Folder Structure
ansible-cluster-docker/
├── Dockerfile.master
├── Dockerfile.node


