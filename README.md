# Active Directory \& Group Policy Implementation Lab

## 🧠 Objective

Simulate a small enterprise network by setting up a Windows Server domain controller, joining client machines, managing users/OUs, and enforcing GPOs.

## 🛠️ Tools Used

* VirtualBox (Oracle)
* Windows Server 2022
* Windows 10 (pc01 VMs)
* Group Policy Management Console (GPMC)
* Active Directory Users \& Computers (ADUC)

## 🔄 Project Phases

### ✅ Phase 1: Environment Setup

* Installed VirtualBox, created 1 DC VM + 1 pc01 VMs.
![DC Setup](docs/Phase1-EnvironmentSetup.jpeg)
* Configured networking and static IPs.



### ✅ Phase 2: Domain Controller Configuration

* Promoted Server to DC using AD DS.
* Created `manish` domain.
![DC Setup](docs/AD\_DHCP-setup.JPG)

### ✅ Phase 3–6: Domain Join, User/OU Setup, GPOs

* Joined clients to domain.
![DC Setup](docs/client-domain\_join.JPG)
* Created OUs (HR, IT, ADMIN), users, and security groups.
![DC Setup](docs/User\_creation.JPG)
* Implemented GPOs: password policy, login restrictions, wallpaper setting, etc.
![DC Setup](docs/GPO-settings.JPG)

### ✅ Phase 7: Validation \& Documentation

* Verified GPOs using `gpresult` OR `rsop.msc`.
![DC Setup](docs/rsop-output.jpeg)
* Attached screenshots and documented structure.

## 📷 Screenshots

* \[x] Domain Controller Setup
![DC Setup](docs/dc-setup.JPG)
* \[x] OU/User/Group Creation

![DC Setup](docs/OU-structure.JPG)

* \[x] GPO Implemented for client machines
  
![DC Setup](docs/desktopwallpaper-GPO\_alicehr.JPG)

## ✅ Outcome

Hands-on experience with:

* Active Directory Management
* GPO Enforcement \& Validation
* Simulated Enterprise Network

## 📂 Documentation

Refer to the `/docs` folder for all screenshots and configuration steps.

\---

👤 Author: Manish Bhatnagar  
📧 Email: manishjon1065@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/manish-b-734537168/

