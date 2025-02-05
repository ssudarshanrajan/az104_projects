# Azure VM Deployment – GUI & ARM Template

## Overview
This repository contains a **step-by-step guide** for deploying Virtual Machines (VMs) in Microsoft Azure using both the **Azure Portal (GUI)** and **Azure Resource Manager (ARM) Templates**. This project is designed to help Azure beginners and aspiring **AZ-104 certified professionals** understand VM provisioning and Infrastructure as Code (IaC) concepts.

## Features
- Deploy an Azure Virtual Machine using the **Azure Portal** (GUI-based approach).
- Deploy an Azure Virtual Machine using an **ARM Template** (Infrastructure as Code).
- Detailed documentation with screenshots and instructions.
- Public repository for educational and reference purposes.

## Prerequisites
Before following the deployment steps, ensure you have:
- An active **Azure Subscription** ([Get a free Azure account](https://azure.microsoft.com/en-us/free/)).
- Basic understanding of **Azure Virtual Machines** and **ARM Templates**.
- (For ARM Deployment) Access to the **Azure CLI or Azure PowerShell**.

## Deployment Methods
### 1️⃣ **Deploy VM via Azure Portal (GUI)**
- Log in to the [Azure Portal](https://portal.azure.com).
- Navigate to **Virtual Machines** > Click **Create**.
- Configure the **Resource Group, VM Name, Region, Image, and Size**.
- Set up **Networking, OS, and Storage**.
- Click **Review + Create** and Deploy the VM.
- More details available in the [GUI Deployment Guide](#).

### 2️⃣ **Deploy VM via ARM Template**
- Open **Azure Cloud Shell** or install **Azure CLI**.
- Clone this repository:  
  ```sh
  git clone https://github.com/ssudarshanrajan/az104_projects.git
  cd az104_projects
  ```
- Deploy using PowerShell:  
  ```sh
  New-AzResourceGroupDeployment -ResourceGroupName <YourResourceGroup> -TemplateFile <TemplateFilename>.json
  ```
- Deploy using Azure CLI:  
  ```sh
  az deployment group create --resource-group <YourResourceGroup> --template-file <TemplateFilename>.json
  ```
- More details available in the guides.
## Future Enhancements
- 🔹 Add **Azure CLI & PowerShell deployment** scripts.
- 🔹 Integrate **Bicep** for template-based deployments.
- 🔹 Automate deployments using **GitHub Actions**.
## Author
👤 **Sudarshan Rajan**  
🔗 [LinkedIn]((https://www.linkedin.com/in/sudarshan-rajan-292944a0/)) | 🔗 [GitHub](https://github.com/ssudarshanrajan)

## License
This project is licensed under the MIT License. Feel free to use and modify it for learning purposes.

---
✅ **If you find this helpful, give this repo a ⭐ and contribute to improving it!** 🚀
