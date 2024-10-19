<h1> ActiveDirectoryLab </h1>

 ### [Post Demonstration](https://medium.com/p/fd427964077f)

 <h2>Description</h2>
The implementation of an Active Directory Domain Services (AD DS) setup using Windows Server 2019 within a VMware environment. The architecture integrates DHCP for dynamic IP management, RAS/NAT for secure internet access, and a Windows 11 client, providing efficient network services and domain management for 1,000 users.
<br/>
<br/>
<br/>

<p align="center">
System Diagram<br/>
<img src="https://github.com/user-attachments/assets/e3b5c301-2f46-4e56-9443-c04de60d264d" height="80%" width="80%" alt="System Diagram"/>
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>VMware Workstation</b>

<h2>Environments Used </h2>

- <b>Windows 11</b>(Client1)
- <b>Windows Server 2019</b> (DC)

<h2>Program walk-through:</h2>

<h4>DC (SERVER 2019)</h4>

- External Network: DHCP.<br/>
- Internal Network: A static IP address (172.16.0.1).
<p align="center">
DC Network Interfaces <br/>

<img src="https://github.com/user-attachments/assets/db47a123-2fe6-421c-8ca7-15474b5fdafa" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br/>

- Active Directory Domain Services (AD DS)
<br/>
<p align="center">
Install Active directory domain service <br/>

<img src="https://github.com/user-attachments/assets/a2d88215-c5dd-4bb6-8b23-d4d278612fcd" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br />

- Promote the Server to Domain Controller
  
<p align="center">
Add domain name <br/>
<img src="https://github.com/user-attachments/assets/cd2527f5-064b-47bb-94dd-d17d4377619e" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br />

- RAS/NAT for Internet Access
  
<p align="center">
Add Remote Access <br/>
<img src="https://github.com/user-attachments/assets/69477bed-d082-4ee3-9dfe-d4a858c6685f" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br/>

<p align="center">
Add Routing <br/>
<img src="https://github.com/user-attachments/assets/a22def78-efe5-49a4-b6e9-02772d333b2a" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br />

<p align="center">
Enable Routing and Remote Access <br/>
<img src="https://github.com/user-attachments/assets/96818269-f441-4a16-b601-dbc87105fa1b" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br />

<p align="center">
Network Address Translation (NAT) <br/>
<img src="https://github.com/user-attachments/assets/63efc74b-dd09-46a6-bcb5-74612f1ccc7e" height="80%" width="80%" alt="Disk Sanitization Steps" title="Network"/>
<br />

 
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
