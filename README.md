# Azure Entra ID User Access Lab

## Overview
This project simulates a real-world Identity and Access Management scenario using Microsoft Entra ID. The goal was to build a small lab environment to practice user provisioning, group-based organization, role assignment, MFA onboarding, and enterprise application access control.

## Objectives
- Create and manage users in Microsoft Entra ID
- Create and manage security groups
- Assign administrative roles using RBAC
- Configure and validate MFA onboarding
- Create an enterprise application
- Assign access to the application
- Validate user access through the My Apps portal

## Environment
- Microsoft Azure
- Microsoft Entra ID (Free)
- Enterprise Applications
- My Apps portal

## Tasks Completed

### 1. Entra ID environment validation
Confirmed tenant access and reviewed the Microsoft Entra ID overview page.

### 2. User creation
Created a new user account:
- Display name: João Silva
- Username: `joao.silva@...onmicrosoft.com`

### 3. Group creation
Created a security group:
- Group name: `IT-Team`

### 4. Group membership
Added João Silva to the IT-Team security group.

### 5. RBAC configuration
Assigned the following administrative roles to João Silva:
- User Administrator
- Security Administrator

### 6. MFA onboarding
Logged in with the new user and completed the initial MFA/security setup process.

### 7. Enterprise application creation
Created a non-gallery enterprise application:
- App name: `App-Interna-IT`

### 8. Application access assignment
Due to Microsoft Entra ID Free plan limitations, group-based assignment to the enterprise application was not available. As a workaround, direct user assignment was used.

Assigned:
- João Silva → App-Interna-IT

### 9. Access validation
Validated that the assigned application appeared in the My Apps portal when logged in as João Silva.

## Key Learnings
- How Microsoft Entra ID handles user and role management
- How RBAC is applied in real IAM scenarios
- How MFA onboarding works for new users
- How enterprise applications are created and assigned
- How licensing limitations in Microsoft Entra ID Free affect group-based assignment
- How to adapt using direct user assignment when required

## Screenshots

### 1. Entra Overview
![01](./screenshots/01-entra-overview.png)

### 2. Create User Form
![02](./screenshots/02-create-user-form.png)

### 3. User Created
![03](./screenshots/03-user-created-list.png)

### 4. Create Group
![04](./screenshots/04-create-group-form.png)

### 5. Group Membership
![05](./screenshots/05-group-member-added.png)

### 6. RBAC Role Assignment
![06](./screenshots/06-rbac-role-assigned.png)

### 7. Multiple Roles Assigned
![07](./screenshots/07-multiple-roles-assigned.png)

### 8. MFA Setup
![08](./screenshots/08-mfa-setup.png)

### 9. User Login Success
![09](./screenshots/09-user-login-success.png)

### 10. Enterprise App Creation Form
![10](./screenshots/10-create-enterprise-app-form.png)

### 11. Enterprise App Overview
![11](./screenshots/11-enterprise-app-overview.png)

### 12. App User Assignment
![12](./screenshots/12-app-user-assigned.png)

### 13. My Apps Validation
![13](./screenshots/13-myapps-visible-app.png)

## Notes
This lab was created for learning and portfolio purposes. Some configuration decisions were adapted to the Microsoft Entra ID Free plan limitations.
