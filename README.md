# VCC_Assignment
# VCC Assignment – VirtualBox Microservice Deployment

## Overview
This repository contains the implementation of Assignment 1 for Virtualization and Cloud Computing (VCC).  
The objective of this assignment is to create multiple virtual machines using Oracle VirtualBox, establish network connectivity between them, and deploy a simple microservice-based application.

## Architecture
- VM1: Client VM
- VM2: Microservice Server (Node.js, Port 3000)
- VM3: Client VM
- Network Type: NAT + Host-Only Adapter
- Communication Protocol: HTTP (REST API)

## Technologies Used
- Oracle VirtualBox
- Ubuntu Server 20.04 LTS
- Node.js & Express.js
- systemd
- Git & GitHub

## Project Structure
- `microservice/` – Node.js microservice source code
- `systemd/` – systemd service configuration
- `diagrams/` – architecture diagram
- `screenshots/` – command execution and outputs
- `report/` – final assignment report

## How to Run the Microservice
1. Start all Virtual Machines
2. Verify network connectivity using:
ping
3. start thw microservice
sudo systemctl start microservice
4. Test from client VM:
curl http://:3000/hello
##output
Hello from VM2
##author
Muskaan
