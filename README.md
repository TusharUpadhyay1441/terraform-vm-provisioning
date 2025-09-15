# ☁️ Terraform VM Provisioning

## 📌 Project Overview
This project demonstrates provisioning a **Virtual Machine** using **Terraform**, applying Infrastructure as Code (IaC) practices.  
The configuration is modular, parameterized with variables, and allows easy customization via `terraform.tfvars`.

---

## 🛠 Features
- Automated VM creation with Terraform  
- Parameterized variables for flexibility  
- Clean teardown of resources  
- Reproducible infrastructure setup  

---

## 📂 Repository Structure
    main.tf # Core VM configuration
    variables.tf # Input variables for the VM
    terraform.tfvars # Variable values
    images/ # Screenshots of the setup

---

## 📸 Screenshots

### 1. Main Terraform File
*(Defines the VM configuration)*  
<img src="images">

### 2. Variables Definition
*(Reusable input variables for flexibility)*  
<img src="images">

### 3. Terraform Variables File
*(Custom values for VM configuration)*  
<img src="images">


---

## 🚀 How to Run

1. **Initialize Terraform**
   ```bash
   terraform init

2. **Preview Changes**
    ```bash
    terraform plan

3. **Apply Configuration**
    ```bash
    terraform apply -auto-approve

4. **Destroy Infrastructure**
    ```bash
    terraform destroy -auto-approve

## 🧰 Technologies

Terraform
Cloud Provider (Azure)

## ✅ Conclusion

This project showcases how Terraform can be used to define and manage infrastructure in a declarative and reusable way.
It highlights the power of IaC (Infrastructure as Code) for VM provisioning, making deployments more consistent and automated.