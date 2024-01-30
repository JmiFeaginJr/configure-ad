<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Prepare the Environment
- Ensure Connectivity between the client and Domain Controller
- Install Active Directory
- Restart the Server

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/J2L7fbc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/VtE21WS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We are in the process of establishing two virtual machines within the Microsoft Azure environment. The first virtual machine is designated as the domain controller, while the second virtual machine serves as the client machine in this configuration.
</p>
<br />

<p>
<img src="https://i.imgur.com/2bU72no.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/vD8mjDT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
</p>
<p>
To facilitate seamless connectivity between the client and the domain controller, our approach involves utilizing remote desktop functionality along with conducting a ping operation directed towards the private IP address of the domain controller (DC-1). Subsequently, we access the domain controller and proceed to enable ICMPv4 within the local Windows Firewall settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/a8UM06B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/dXnfVOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
