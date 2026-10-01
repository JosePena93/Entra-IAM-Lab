# Microsoft Entra ID (Azure AD) Identity & Access Management Lab

## 🔹 Project Overview
This project demonstrates setting up cloud-based Identity and Access Management (IAM) using Microsoft Entra ID, focusing on user lifecycles, RBAC, and the Principle of Least Privilege.

## 🛠️ Tools & Features Used
* **Platform:** Microsoft Entra ID (Azure AD)
* **Features:** User Provisioning, Security Groups (RBAC), Security Defaults (MFA), Directory Roles.

---

## ⚙️ Step-by-Step Implementation

### Step 1: Creating the Enterprise Users
Provisioned test accounts under **Users** > **All Users** > **New user** with standardized UPN formats, job titles, and departments.

### Step 2: Setting up Role-Based Access Control (RBAC)
Created department-level Security Groups (e.g., *IT_Department*, *HR_Department*) via **Groups** > **New group** to manage permissions efficiently.

### Step 3: Hardening the Tenant with MFA
Enabled tenant-wide MFA via **Manage Security Defaults** to protect against password attacks and prompt users with Microsoft Authenticator.

### Step 4: Role Delegation (Principle of Least Privilege)
Assigned granular administrative access (such as **Helpdesk Administrator**) under user assigned roles to limit privileges appropriately.

