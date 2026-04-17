# Azure Entra ID User Access Lab

## Overview
This project simulates a real-world Identity and Access Management (IAM) scenario using Microsoft Entra ID.

The objective was to build a hands-on lab environment to practice user provisioning, role-based access control (RBAC), MFA onboarding, and enterprise application access management.

---

## Objectives
- Create and manage users in Microsoft Entra ID  
- Create and manage security groups  
- Assign administrative roles using RBAC  
- Configure and validate MFA onboarding  
- Create an enterprise application  
- Assign user access to the application  
- Validate user access through the My Apps portal  

---

## Environment
- Microsoft Azure  
- Microsoft Entra ID (Free Tier)  
- Enterprise Applications  
- My Apps Portal  

---

## Tasks Performed

### 1. Entra ID Environment Validation
Validated tenant access and reviewed the Microsoft Entra ID dashboard.

### 2. User Provisioning
Created a new user:
- **Name:** João Silva  
- **Username:** `joao.silva@...onmicrosoft.com`  

### 3. Group Management
Created a security group:
- **Name:** `IT-Team`  

Added the user to the group.

### 4. RBAC Configuration
Assigned administrative roles:
- User Administrator  
- Security Administrator  

### 5. MFA Onboarding
Configured and validated Multi-Factor Authentication (MFA) for the user.

### 6. Enterprise Application Setup
Created a non-gallery enterprise application:
- **App Name:** `App-Interna-IT`  

### 7. Access Assignment
Due to Microsoft Entra ID Free limitations, group-based assignment was not available.

Workaround implemented:
- Direct user assignment to the application  

### 8. Access Validation
Confirmed that the application appears in the **My Apps portal** for the assigned user.

---

## Key Learnings
- Identity lifecycle management in Microsoft Entra ID  
- Practical use of RBAC in cloud environments  
- MFA onboarding process and security implications  
- Enterprise application integration and assignment  
- Limitations of Entra ID Free tier  
- Workarounds using direct user assignment  

---

## Screenshots

### 1. Entra Overview
![01](screenshots/01-entra-overview.png)

### 2. Create User Form
![02](screenshots/02-create-user-form.png)

### 3. User Created
![03](screenshots/03-user-created-list.png)

### 4. Create Group
![04](screenshots/04-create-group-form.png)

### 5. Group Membership
![05](screenshots/05-group-member-added.png)

### 6. RBAC Role Assignment
![06](screenshots/06-rbac-role-assigned.png)

### 7. Multiple Roles Assigned
![07](screenshots/07-multiple-roles-assigned.png)

### 8. MFA Setup
![08](screenshots/08-mfa-setup.png)

### 9. User Login Success
![09](screenshots/09-user-login-success.png)

### 10. Enterprise App Creation
![10](screenshots/10-create-enterprise-app-form.png)

### 11. Enterprise App Overview
![11](screenshots/11-enterprise-app-overview.png)

### 12. App User Assignment
![12](screenshots/12-app-user-assigned.png)

### 13. My Apps Validation
![13](screenshots/13-myapps-visible-app.png)

---

## Notes
This project was developed for learning and portfolio purposes.

Some design decisions were influenced by the limitations of the Microsoft Entra ID Free tier.
