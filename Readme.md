# Netdata System Monitoring

This project demonstrates real-time system resource monitoring using [Netdata](https://www.netdata.cloud/) via Docker.

## 🚀 Task Objective
Install and run Netdata using Docker Desktop to visualize system and application performance metrics in a web-based dashboard.

## 📦 Tools Used
- Docker
- Netdata

## 🛠️ Setup Instructions
1. Pull and run Netdata container:
   
   docker run -d --name=netdata -p 19999:19999 netdata/netdata

2. Access the Netdata Dashboard

Once your Netdata container is running, open your browser and go to: http://localhost:19999 ✅ 

3. Explore Key Metrics & Features
Once you're on the Netdata dashboard at http://localhost:19999, take a few minutes to look around. Here's what you should explore:

📊 Important Metrics to Observe:
CPU Usage (overall + per core)

Memory & Swap Usage
Disk Usage (read/write IOPS, bandwidth)
Network Traffic (per interface)
Docker Containers (if you have others running)

🚨 Alerts & Alarms Panel
Netdata automatically raises warnings when system resources cross thresholds.

Look for colored dots or labels like “Warning” or “Critical”
Click them to view the exact metric and trigger

🧩 Custom Panels & Charts
Each chart is interactive. You can:

Hover to see historical data
Click chart titles to expand
Toggle line graphs on/off
 
 
