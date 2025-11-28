# MEAN Stack DevOps Assessment

## 🛠 Deployment Infrastructure (Ubuntu Codespace)
**Important:** Due to the requirement of "Do not delete infrastructure" and restrictions on enterprise cloud verification, I have provisioned the solution on an **Ubuntu Virtual Machine via GitHub Codespaces**.

- **OS:** Ubuntu Linux (Standard Codespace image)
- **Containerization:** Docker & Docker Compose
- **Orchestration:** Nginx Reverse Proxy
- **Status:** The environment allows for stopping and restarting (saving state), fulfilling the requirement for a live demonstration in the next round.

## 🚀 How to Run (Instructions for Reviewer)
Since the live server link is ephemeral (sleeps on inactivity), please verify using the attached Screenshots or CI/CD logs.

To start the server (Demo steps):
1. Launch Terminal.
2. `docker-compose pull` (Pull latest images built by CI pipeline)
3. `docker-compose up -d` (Start application)
