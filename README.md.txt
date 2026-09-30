# Enterprise Active Directory & Infrastructure Deployment

## 📌 Project Overview
This project demonstrates the configuration and deployment of an Active Directory Domain Services (AD DS) environment using **Windows Server 2016 Standard** running on a virtualized infrastructure (**VMware Workstation**). The configuration includes active domain management, DNS integration, and host-client domain integration.

---

## 🛠️ System Specifications & Environment

* **Operating System:** Windows Server 2016 Standard
* **Environment Type:** Virtualized via VMware Workstation
* **Domain Name (FQDN):** `ayman.com`
* **Computer Name (DC):** `WIN-F3OQ3VS1CAM`
* **Roles & Features Installed:**
  * Active Directory Domain Services (AD DS)
  * Domain Name System (DNS)
* **Client Workstation:** Windows 10 Virtual Machine (Domain Joined)

---

## 🚀 Key Implementations & Tasks Completed

1. **Active Directory Domain Services Setup:**
   * Promoted Windows Server 2016 to a Primary Domain Controller (PDC) for `ayman.com`.
   * Verified identity and active directory services status via Server Manager Dashboard.

2. **DNS Integration:**
   * Configured forward and reverse lookup zones to ensure proper domain name resolution within the virtual network.

3. **Client Integration & Connectivity:**
   * Connected client nodes (Windows 10) to the `ayman.com` domain to test authentication and domain control capabilities.

---

## 📊 Verification & Screenshots

* **Server Manager Dashboard:** Active Directory Domain Services (AD DS) and DNS roles are fully operational without issues.
* **Local Server Properties:** Domain identity verified as `ayman.com`.
*