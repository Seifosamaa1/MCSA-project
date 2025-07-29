# 🖥️ MCSA Infrastructure Project

A team-based implementation of a Windows Server infrastructure using MCSA (Microsoft Certified Solutions Associate) principles. This project simulates a real-world enterprise IT environment with user policies, domain services, and secure web/FTP hosting.

---

## 📌 Project Overview

The goal of this project was to design and deploy a fully functional Windows Server environment. It includes Active Directory, DNS/DHCP configuration, Group Policies, delegated administration, IIS/FTP hosting, and disk management.

---

## 🛠️ Technologies Used

- Windows Server
- Active Directory Domain Services (AD DS)
- Group Policy Objects (GPO)
- Organizational Units (OUs)
- Delegation Control
- Domain Name System (DNS)
- Dynamic Host Configuration Protocol (DHCP)
- Internet Information Services (IIS)
- File Transfer Protocol (FTP)
- NTFS Permissions
- Disk Management

---

## 🧩 Project Components

### 1️⃣ Active Directory & Group Policy
- Configured AD DS and domain structure.
- Created Organizational Units (OUs) for departments.
- Applied Group Policy Objects (GPOs) for user restrictions and security settings.
- Set file and folder permissions using NTFS.

### 2️⃣ DNS & DHCP
- Created internal DNS zones and A/CNAME records.
- Set up DHCP scopes for automatic IP address assignment.

### 3️⃣ Delegation & Permissions
- Delegated OU control to department admins.
- Applied NTFS and share permissions for secure file access.

### 4️⃣ IIS & FTP Deployment
- Installed IIS to host an internal website.
- Deployed FTP server with access control and authentication.

### 5️⃣ Storage & Disk Management
- Configured disk quotas per user.
- Applied storage policies for space management.

---

## 🧑‍💼 How the Infrastructure Works

### 🔹 User Access & Policies
- Users are placed into OUs and automatically receive the correct policies.
- GPOs manage desktop restrictions, password settings, and user experience.
- NTFS permissions restrict sensitive files to specific roles.

### 🔹 Website & FTP Access
- Internal website hosted via IIS for company resources.
- FTP server allows secure upload/download for department users.

---

## ✅ Learning Outcomes

- Hands-on implementation of enterprise infrastructure.
- Deep understanding of Windows Server services and user management.
- Practical experience with GPOs, DNS/DHCP, and web/FTP hosting.

---

> 🚀 This project was built as part of an MCSA learning initiative to simulate real-world IT administration.

