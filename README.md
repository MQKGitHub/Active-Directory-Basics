### 🛡️ Active Directory Basics

**Room:** [Active Directory Basics — TryHackMe](https://tryhackme.com/room/winadbasics)  
**Status:** ✅ Completed  
**Date:** *12 May 2025*  

### 🎯 Objective
This room provided a comprehensive introduction to Microsoft Active Directory (AD), covering its core components, management tools, and organisational structures. The goal was to understand how AD centralises network administration and enables efficient management of users, computers, and security policies in enterprise environments.

---

### 🗝️ Key Concepts  
- **Active Directory Domain** — Centralised network management system that authenticates and authorises all users and computers.  
- **Domain Controller (DC)** — Server running AD services that manages authentication and policy enforcement.  
- **Organisational Units (OUs)** — Containers for organising users/computers and applying group policies.  
- **Security Groups** — Collections of users/computers used to assign permissions (e.g., Domain Admins, Backup Operators).  
- **Group Policy Objects (GPOs)** — Sets of configurations applied to OUs to enforce security/compliance rules.  
- **Kerberos Authentication** — Default AD protocol using ticket-granting system for secure network authentication.  
- **Trust Relationships** — Connections between domains that allow cross-domain resource access.  
- **Forest/Tree Structure** — Hierarchical organisation of multiple domains sharing schema and configuration.  

---

### 🛠️ Tools Used
- **Active Directory Users and Computers** — Managed user accounts, groups, and OUs.  
- **Group Policy Management** — Created and linked GPOs to enforce security policies.  
- **PowerShell** — Used `Set-ADAccountPassword` for delegated password resets.  
- **RDP** — Connected to different user accounts to test policies and permissions.  

---

### ⚠️ Challenges Faced
- Initially confused the difference between Security Groups and OUs
- Had difficulty understanding Kerberos ticket flow
- Overcame by practising in the lab environment and mapping out authentication steps
- The hands-on exercises with GPO delegation helped solidify concepts

---

### 🧠 What I Learned
- How to properly structure OUs to mirror organisational hierarchy
- The process of delegating administrative tasks like password resets
- How GPOs propagate through domain structures
- Why machine accounts end with $ and their purpose
- The difference between Domain Admins and Enterprise Admins
- How trust relationships enable cross-domain resource access

---

### 🌐 Real-World Application:
> Active Directory skills are essential for any IT professional working in Windows environments. Understanding AD allows administrators to efficiently manage thousands of users/computers, enforce security policies through GPOs, and troubleshoot authentication issues. The delegation concepts are particularly valuable for implementing principle of least privilege in enterprise networks.

---

### 💭 Reflections:
- Most valuable: Hands-on experience with GPO creation and linking
- Most challenging: Fully grasping Kerberos authentication flow
- Interesting discovery: How machine accounts work and their automatic password rotation
- Key takeaway: "Proper OU structure and GPO design are foundational to secure AD management"
