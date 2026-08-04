# Active Directory & Group Policy Implementation Lab

## 🧠 Objective
Simulate a small enterprise network by setting up a Windows Server domain controller, joining client machines, managing users/OUs, and enforcing GPOs.

## 🛠️ Tools Used
- VirtualBox (Oracle)
- Windows Server 2022
- Windows 10 (Client VMs)
- Group Policy Management Console (GPMC)
- Active Directory Users & Computers (ADUC)

## 🔄 Project Phases

### ✅ Phase 1: Environment Setup
- Installed VirtualBox, created 1 DC01 VM + 2 Client VMs.
![DC Setup](docs/Phase1-EnvironmentSetup.jpeg)
- Configured networking and static IPs.


### ✅ Phase 2: Domain Controller Configuration
- Promoted Server to DC using AD DS.
- Created `shashank.local` domain.
![DC Setup](docs/AD_DHCP-setup.JPG)

### ✅ Phase 3–6: Domain Join, User/OU Setup, GPOs
- Joined clients to domain.
![DC Setup](docs/client-domain_join.JPG)
- Created OUs (HR, IT, Finance), users, and security groups.
![DC Setup](docs/User_creation.JPG)
- Implemented GPOs: password policy, login restrictions, wallpaper setting, etc.
![DC Setup](docs/GPO-settings.JPG)

### ✅ Phase 7: Validation & Documentation
- Verified GPOs using `gpresult` OR `rsop.msc`.
![DC Setup](docs/rsop-output.jpeg)
- Attached screenshots and documented structure.

## 📷 Screenshots
- [x] Domain Controller Setup
![DC Setup](docs/dc-setup.JPG)

- [x] OU/User/Group Creation

![DC Setup](docs/OU-structure.JPG)

- [x] GPO Implemented for client machines
![DC Setup](docs/desktopwallpaper-GPO_alicehr.JPG)

## ✅ Outcome
Hands-on experience with:
- Active Directory Management
- GPO Enforcement & Validation
- Simulated Enterprise Network

## 📂 Documentation
Refer to the `/docs` folder for all screenshots and configuration steps.

---

👤 Author: Shashank Awadhoot  
📧 Email: shashankawadhoot8967@gmail.com   
🔗 LinkedIn: https://www.linkedin.com/in/shashank-awdhoot-139b06225/
