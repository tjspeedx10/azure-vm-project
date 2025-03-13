# Azure Virtual Machine Creation

## Project Summary

### Brief Description:
This project is a tutorial that demonstrates how to create a Virtual Machine (VM) in Azure using the Azure Portal and automates the process using an Azure Resource Manager (ARM) template. It provides the necessary steps to configure, deploy, and manage a Virtual Machine on Microsoft Azure, and is intended to be a guide for beginners looking to learn about cloud computing and infrastructure-as-code.



### Environments Used:
- **Microsoft Azure** (Cloud Environment)
- **Windows 10** or **Windows Server** (for using the Azure Portal)

### Technology/Applications/Services Used:
- **Azure Resource Manager (ARM) Templates**
- **Azure Virtual Machines** (VMs)
- **Azure CLI** (for command-line operations)

---

## Media




[Watch the tutorial video](https://youtu.be/GEc155TvTqs?si=WED7GBft8IwcMRAh)

---

## Demonstration

This section will walk through the steps of creating a Virtual Machine in Azure.

### Step 1: Create a Resource Group in Azure
First, go to the Azure Portal and create a resource group:
1. Navigate to the **Resource Groups** section.
2. Click **Create**, name your resource group, and select the region.

### Step 2: Create a Virtual Machine Using the Azure Portal
1. Go to the **Create a resource** page in the Azure Portal.
2. Go to search bar and type in Virtual Machine Create a Windows 10 Virtual Machine (VM)
While creating the VM, select the previously created Resource Group
While creating the VM, allow it to create a new Virtual Network (Vnet) and Subnet

3. Fill in the required fields:
   - Choose the **Subscription** and **Resource Group** you created.
   - Choose an **Image** (e.g., Ubuntu or Windows).
   - Configure the **Size** based on your requirements.
   - Set up authentication (Username/Password or SSH keys).
  

### Step 3:  Review and click **Create** to deploy the VM.
1. the Virtual machine might take a while to deploy vut once its
   done the virtual machine will be done and running

