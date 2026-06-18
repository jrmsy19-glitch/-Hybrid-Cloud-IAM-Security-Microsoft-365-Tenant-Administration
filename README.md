## ☁️ Hybrid Cloud IAM, Security & Microsoft 365 Tenant Administration

## 📋 Project Overview

This project demonstrates the deployment, administration, and security hardening of a cloud-native Microsoft 365 tenant for Plush Realty Group (PRG).

The environment was built using Microsoft Entra ID, Microsoft 365 Admin Center, and the Azure Portal to simulate real-world enterprise identity and access management operations.

This lab focuses on user lifecycle management, identity governance, authentication security, self-service account recovery, security group administration, and employee offboarding procedures. Administrative actions were validated across multiple Microsoft management portals to demonstrate an understanding of Microsoft’s integrated cloud ecosystem and centralized identity architecture.

⸻

## 🎯 Project Objectives

* Provision and manage cloud identities within Microsoft Entra ID
* Configure organizational user attributes and branch office segmentation
* Implement Multi-Factor Authentication (MFA) security controls
* Deploy Self-Service Password Reset (SSPR)
* Create and manage role-based security groups
* Simulate employee offboarding and account disablement procedures
* Validate identity synchronization across Microsoft administrative portals

⸻

## 🛠️ Technologies Used

Identity & Access Management

* Microsoft Entra ID (Azure Active Directory)
* Microsoft Entra Admin Center

Cloud Administration

* Microsoft 365 Admin Center
* Azure Portal
* Exchange Admin Center

Security & Governance

* Multi-Factor Authentication (MFA)
* Self-Service Password Reset (SSPR)
* Security Groups
* User Lifecycle Management

⸻

## 🏢 Enterprise Directory Topology

The tenant was structured to represent a growing real estate organization with multiple regional office locations. User objects were categorized using organizational metadata and location-based attributes to support administrative segmentation and future scalability.

Plush Realty Group Tenant (JRinc364.onmicrosoft.com)
├── 🏢 Saint Paul Headquarters
│
└── 📍 Regional Offices
    ├── 🌲 Duluth Office
    ├── 🏙️ Minneapolis Office
    └── ⛵ Rochester Office (Planned Expansion)

⸻

## 🚀 Implementation Phases

## Phase 1 — Tenant Provisioning & Identity Deployment

Cloud-native user accounts were created directly within Microsoft Entra ID. Each account was configured with foundational identity attributes including:

* Display Name
* Username
* Mail Nickname
* Organizational Information
* Licensing Assignments

Identity creation was then validated across multiple Microsoft management portals to confirm successful synchronization and object availability throughout the tenant.

Key Skills Demonstrated

* User Provisioning
* Directory Object Management
* Identity Synchronization Validation
* Microsoft 365 Tenant Administration

Screenshots

Figure 1.1 — Entra ID User Creation Interface

<p align="center">
<img src="https://github.com/user-attachments/assets/8a88e2c9-e077-4621-ae06-f007ddf37036" width="850">
</p>


Figure 1.2 — Microsoft 365 Admin Center Active Users

<p align="center">
<img src="https://github.com/user-attachments/assets/e835004e-1f63-4d8e-8b36-8c867c3cee15"width="850">
</p>



Figure 1.3 — Azure Portal Directory Validation

<p align="center">
<img src="https://github.com/user-attachments/assets/248e3c87-5911-40a1-8ac3-43e29d552ae3" width="850">
</p>

⸻

## Phase 2 — Organizational Structure & Branch Segmentation

Directory attributes were configured to simulate a multi-office enterprise environment. Users were assigned geographic and organizational metadata to represent employees working from different PRG locations.

This segmentation strategy provides a foundation for future administrative policies, reporting, and access governance initiatives.

Branch Assignments

* Saint Paul Headquarters
* Duluth Office
* Minneapolis Office

Key Skills Demonstrated

* User Attribute Management
* Organizational Directory Design
* Geographic User Segmentation
* Enterprise Directory Administration

Screenshots

Figure 2.1 — Directory Query & Filtering Configuration

<p align="center">
<img src="https://github.com/user-attachments/assets/481395a3-6e00-4e49-abb2-c6f3333a1250" width="850">
</p>

Figure 2.2 — Duluth Office User Profile

<p align="center">
<img src="https://github.com/user-attachments/assets/5931c9f2-08dc-4d13-acd9-db50bd143b15" width="850">
</p>


Figure 2.3 — Saint Paul Headquarters User Profile

<p align="center">
<img src="https://github.com/user-attachments/assets/f13e6a28-aecc-40a9-957c-ba7d030c8b8a" width="850">
</p>


Figure 2.4 — Minneapolis Office User Profile

<p align="center">
<img src="https://github.com/user-attachments/assets/6d2d94fe-d9a9-4bb5-8ce3-ba9a41c98256" width="850">
</p>

⸻

## Phase 3 — Identity Security & MFA Implementation

To strengthen account security and reduce the risk of credential compromise, Multi-Factor Authentication (MFA) was enabled across tenant identities.

User authentication states were reviewed and validated to ensure accounts complied with baseline security requirements.

Security Controls Implemented

* Per-User MFA Enablement
* Identity Verification Requirements
* Administrative Account Protection
* Authentication Status Auditing

Key Skills Demonstrated

* Identity Security Administration
* MFA Deployment
* Authentication Policy Management
* Security Baseline Implementation

Screenshots

Figure 3.1 — Per-User MFA Enforcement Console

<p align="center">
<img src="https://github.com/user-attachments/assets/60204d90-a165-449b-97b5-4a4c7a419020" width="850">
</p>


⸻

## Phase 4 — Security Group Architecture & Self-Service Password Reset (SSPR)

To support future Role-Based Access Control (RBAC) initiatives, departmental security groups were created and validated throughout the Microsoft ecosystem.

In addition, Self-Service Password Reset (SSPR) was configured to reduce Help Desk workload and improve user account recovery capabilities.

Security Groups Created

* HR Staff
* IT Staff
* Payroll Staff

SSPR Configuration Highlights

* Tenant-Wide SSPR Enablement
* Password Reset Notifications
* Administrative Reset Policies
* Authentication Method Validation

## Key Skills Demonstrated

* Security Group Administration
* Access Governance Preparation
* Password Management Policies
* Identity Self-Service Configuration

Screenshots

Figure 4.1 — Entra ID Security Group Directory

<p align="center">
<img src="https://github.com/user-attachments/assets/b3851f64-e5d4-4293-a996-44777d24cf88" width="850">
</p>


Figure 4.2 — Azure Portal Group Synchronization View

<p align="center">
<img src"https://github.com/user-attachments/assets/d063207c-7f13-4cab-b347-3839308212bb" width="850">
</p>

Figure 4.3 — SSPR Enablement Properties

<p align="center">
<img src="https://github.com/user-attachments/assets/b3afc0e6-05b8-4f03-9145-11685dd19a55" width="850">
</p>


Figure 4.4 — Password Reset Notification Settings

<p align="center">
<img src="https://github.com/user-attachments/assets/399d9257-03cb-4672-98d4-1fcec5340755" width="850">
</p>


Figure 4.5 — Administrator Authentication Policy Rules

<p align="center">
<img src="https://github.com/user-attachments/assets/90841a94-cfb3-40dc-9413-9bb0265103f9" width="850">
</p>


⸻

## Phase 5 — User Offboarding & Incident Response Simulation

A user offboarding scenario was conducted to simulate a compromised account or employee termination event.

Administrative controls were used to immediately revoke user access, invalidate active sessions, and disable account sign-in capabilities.

The account status was then validated across multiple management portals to confirm successful enforcement.

Actions Performed

* Blocked User Sign-In
* Disabled Account Access
* Revoked Active Sessions
* Verified Directory Status Changes

## Key Skills Demonstrated

* User Lifecycle Management
* Incident Response Procedures
* Identity Containment Actions
* Access Revocation Workflows

Screenshots

Figure 5.1 — Microsoft 365 Sign-In Block

<p align="center">
<img src="https://github.com/user-attachments/assets/4f28dc07-3eee-4d03-8d33-24b86140f6d7" width="850">
</p>

Figure 5.2 — Entra ID Disabled Account Validation

<p align="center">
<img src="https://github.com/user-attachments/assets/ba5fb750-7485-4a60-b370-44085375a1a1" width="850">
</p>
⸻

## 🔄 Cross-Portal Validation & Microsoft Cloud Integration

One of the primary goals of this project was to demonstrate an understanding of Microsoft’s centralized identity architecture.

Although administrative tasks were performed within different portals, all actions ultimately interacted with the same underlying Microsoft Entra ID directory.

Validation Examples

* Created users in Microsoft Entra ID and verified synchronization within Microsoft 365 Admin Center and Azure Portal.
* Created security groups and validated object propagation throughout the tenant.
* Blocked user sign-in within Microsoft 365 Admin Center and confirmed account status changes within Microsoft Entra ID.
* Verified identity consistency across administrative interfaces.

This validation process demonstrates practical knowledge of Microsoft’s cloud identity ecosystem and highlights an understanding of how administrative changes propagate throughout enterprise services.

⸻

## 📈 Skills Demonstrated

Identity & Access Management

* User Provisioning
* User Lifecycle Management
* Directory Administration
* Identity Governance Fundamentals

Security Administration

* Multi-Factor Authentication (MFA)
* Self-Service Password Reset (SSPR)
* Security Group Management
* Account Recovery Controls

Microsoft Cloud Administration

* Microsoft Entra ID
* Microsoft 365 Admin Center
* Azure Portal
* Exchange Administration

Operational Support

* Incident Response Procedures
* Employee Offboarding
* Access Revocation
* Cross-Platform Validation

⸻

## 🏆 Professional Relevance

This project mirrors responsibilities commonly performed by:

* IT Support Specialists
* Help Desk Technicians
* Microsoft 365 Administrators
* Identity & Access Administrators
* Junior Systems Administrators
* Cloud Support Engineers

The environment demonstrates hands-on experience with identity administration, security controls, user lifecycle management, and Microsoft cloud platform operations commonly encountered in enterprise environments.

⸻

## 👤 Author

Jamal D. Ramsey

Aspiring Microsoft 365 Administrator | IT Support Professional | Cloud & Identity Management Enthusiast

Connect With Me

* LinkedIn: INSERT_LINKEDIN_URL

