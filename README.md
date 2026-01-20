# Ansible Zero to Hero Course 

A **Beginner to Advanced Ansible learning path** covering real-world automation, configuration management, application deployment, & so on.

---

### Course Requirements:

 1. **Laptop (with admin privileges)**
 2. **Desire to Learn**.

---

### 📌 What You’ll Learn
1. Ansible fundamentals, architecture, and core concepts
2. Writing clean, reusable, and idempotent playbooks
3. Managing variables, facts, and conditional logic
4. Structuring automation with roles and collections
5. Securing secrets, handling errors, and debugging playbooks
6. Automating multi-server deployments with dynamic inventories

---

### 🛠 Tools & Technologies
- Ansible
- Virtual Studio Code 
- Vagrant (used only for local lab setup in projects to create VMs)

---
## **Episode 1: Ansible Basics & Architecture**

- **Goal:**  Understand Ansible fundamentals and how automation works.

- **Topics**
    - What is Ansible and why it is used
    - Agentless architecture
    - Control node and managed nodes
    - Inventory basics
    - Ad-hoc commands
    - Ansible configuration file

- **📁 Project 1: Basic System Audit Automation**
   - **Objective:** Validate connectivity, OS, uptime, and disk usage using ad-hoc commands and static inventory

---

## Episode 2: Playbooks, Variables & Facts

- **Goal:** Write flexible and reusable automation workflows.
- **Topics:**
   - YAML fundamentals
   - Playbook structure
   - Tasks and handlers
   - Variables and variable precedence
   - Facts and `gather_facts`
   - Conditionals and loops

- **📁 Project 2: Web Server Deployment**
   - **Objective:** Install and configure Nginx/Apache using playbooks, variables, and facts

---

## Episode 3: Modules, Roles & Collections

- **Goal:** Build scalable and maintainable Ansible code.

- **Topics:**
   - Common Ansible Episodes
   - File, package, and service management
   - Role structure and best practices
   - Role dependencies
   - Ansible Galaxy
   - Collections overview

- **📁 Project 3: Role-Based Web Application Deployment**
   - **Objective:** Create separate roles for web server & use templates for configuration files  

---

## Episode 4: Vault, Error Handling & Debugging

- **Goal:** Secure automation and handle failures gracefully.

- **Topics:** 
   - Ansible Vault concepts
   - Encrypting and managing secrets
   - Error handling with ignore_errors
   - `block`, `rescue`, and `always`
   - Debug module and verbose execution

- **📁 Project 4: Secure Database Deployment**
   - **Objective:** Deploy a database using Vault-encrypted credentials and structured error handling

---

## Episode 5: Dynamic Inventory

- **Goal**  Integrate Ansible into modern DevOps workflows.

- **Topics**
   - Static vs dynamic inventories
   - Inventory scripts and plugins
   - Cloud inventory concepts
   - CI/CD fundamentals
   - Running Ansible from pipelines

- **📁 Project 5: Multi-Host Inventory Automation**
   - **Objective:** Create a script-based dynamic inventory for local hosts
  
---

## Episode 6: End-to-End Automation Project

- **Goal**
   - Apply all concepts in a real-world automation scenario.

- **Scope**
   - Web server deployment
   - Database server setup
   - Role-based architecture
   - Secure secrets with Vault
   - Automated service management
   - Configuration updates and maintenance
   - Local virtual machines (e.g., Vagrant) may be used only for testing and practice.

- **📁 Project 6: Local Multi-Tier Application Deployment**
   - **Objective:** Deploy a web server and database across multiple nodes
 
---
