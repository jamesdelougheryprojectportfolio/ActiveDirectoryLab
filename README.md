<h1>Active Directory Home Lab</h1>



<h2>Description</h2>
Project consists of a setting up an Active Directory lab environment on a personal computer using VirtualBox. During this project I used a powershell script to automate the creation of user accounts and configured the domain to allow a client to connect to the internet using the domain controller as a default gateway. The goal of this project was to set up and simulate office network environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Windows Server 2019</b>
- <b>Oracle VirtualBox</b>

<h2>Learning Outcomes</h2>

- <b>Set up and configuration of Windows OS VMs</b> 
- <b>Creation of AD OU and User objects</b>
- <b>Understanding of Network Fundamentals in Windows Domain Environment</b>
- <b>Configuration of DHCP Server</b>
- <b>Exposure to PowerShell syntax, variables and loops</b> 
- <b>Experience adding client machine to AD domain</b>
  
<h2>Project walk-through:</h2>

<p align="center">
Domain Environment Diagram: <br/>
<img src="https://i.imgur.com/kQjlP3y.png" height="80%" width="80%" alt="Domain Environment Diagram"/>
<br />
<br />
Configure Internal Network Adapter:  <br/>
<img src="https://i.imgur.com/5P51pp3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Admin OU: <br/>
<img src="https://i.imgur.com/7qh6vrA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Admin User:  <br/>
<img src="https://i.imgur.com/ZFhkCmV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure NAT:  <br/>
<img src="https://i.imgur.com/uvvWNeL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure DHCP Server:  <br/>
<img src="https://i.imgur.com/dJXtQUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PowerShell User Account Generation Script:  <br/>
<img src="https://i.imgur.com/xxkFfqE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
Creation of User Accounts: <br/>
<img src="https://i.imgur.com/HPynmfQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify User Account Creation:  <br/>
<img src="https://i.imgur.com/MUeEjum.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Spin Up Client Machine: <br/>
<img src="https://i.imgur.com/8rdG38t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verify Network Connectivity:  <br/>
<img src="https://i.imgur.com/MGTNQ5D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Client to Domain:  <br/>
<img src="https://i.imgur.com/vqzTHal.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm Domain Addition:  <br/>
<img src="https://i.imgur.com/tTdFeSQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
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
