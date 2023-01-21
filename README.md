<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-Premises Active Directory Implementation (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure](https://youtu.be/1ykkNbECq84)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Set Domain Controller’s NIC Private IP address to be static.
- Step 2: Login to the Domain Controller and enable ICMPv4 on the local windows Firewall.
- Step 3: Login to DC-1 and install Active Directory Domain Services.
- Step 4: Join second VM to the domain.
- Step 5: Enable remote desktop for non-administrative users on second VM.
- Step 6: Open PowerShell_ise as an administrator to generate users.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/dtWikXX.png" height="80%" width="80%" alt="Enable ICMPv4 on Firewall"/>
</p>
<p>
Enable ICMPv4 on the Domain Controller's local windows firewall.
</p>
<br />

<p>
<img src="https://i.imgur.com/XXmOzbs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Active Directory Domain Services on the Domain Controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/iiI8beg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open PowerShell_ise as an administrator to generate users.
</p>
<br />
