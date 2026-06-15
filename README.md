# ☁️ Hybrid Cloud IAM, Security & Microsoft 365 Tenant Administration

## 📋 Project Overview
This project documents the deployment, identity lifecycle architecture, and security hardening of a cloud-native tenant for **Plush Realty Group**. Built entirely within the Microsoft Entra admin center, Azure Portal, and Microsoft 365 Admin Center, this environment simulates a real-world enterprise infrastructure deployment. This lab acts as the practical validation framework for the Microsoft SC-300 (Identity & Access Administrator) and SC-900 (Security & Compliance) tracks.

### 🛠️ Core Technologies Documented
* **Identity Management:** Microsoft Entra ID (Azure Active Directory)
* **Tenant Administration:** Microsoft 365 Admin Center, Exchange Admin Center
* **Security & Hardening:** Per-User Multi-Factor Authentication (MFA), Self-Service Password Reset (SSPR)
* **Lifecycle Management:** Security Group Architecture, Offboarding Protocols, and Sign-In Mitigation

---

## 🏢 Enterprise Topology: Tenant & Regional Branches

To support regional growth, the corporate directory is organized by specialized geographic attributes to segment users by their physical office locations.

```text
Plush Realty Group Tenant (JRinc364.onmicrosoft.com)
├── 🏢 PRG Headquarters (Saint Paul HQ)
└── 📍 PRG Branches
    ├── 🌲 Duluth Office
    ├── 🏙️ Minneapolis Office
    └── ⛵ Rochester Office (Planned)
