<h1>Active Directory</h1>


<h2>Description</h2>
In this lab I am going to create an Active Directory home lab environment using Oracle Virtual Box.
<br />


<h2>Objectives</h2>

- <b>Configure Domain Controller: Set up a virtual machine as the domain controller housing Active Directory, with two network adapters—one for internet connectivity and one for the private network.</b> 
- <b>Assign Internal IP Addressing: Define IP addressing for the internal network, while external network addresses are automatically obtained from the home network.</b>
- <b>Install Active Directory: Name the server, install Active Directory, and create its domain. Configure routing to enable clients on the private network to access the internet through the domain controller.</b>
- <b>Implement DHCP: Configure DHCP on the domain controller to provide automatic IP addressing for other virtual machines on the network.</b>
- <b>User Management: Utilize a PowerShell script to create a thousand users within the Active Directory.</b>
- <b>Deploy Client Machine: Create a virtual machine using Windows 10 ISO, connect it to the private VirtualBox network, and join it to the domain. Log into the client machine using one of the domain accounts generated.</b>


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 2019</b> 
- <b>Windows 2022</b>

<h2>Program walk-through:</h2>

<p align="center">
Server Manager Dashboard: You can see what I have set up <br/>
<img src="https://imgur.com/Z0PQkqU" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory Domain Services: Showcasing the domain created <br/>
<img src="https://imgur.com/L8JSUTc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Network: I set up an external and internal network  <br/>
<img src="https://imgur.com/DiZ6QkK" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Network: Clients have a private network  <br/>
<img src="https://imgur.com/undefined" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Active Directory: You will see admins, users, and computers connected to the domain <br/>
<img src="https://imgur.com/EXr1umJ" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client: Shows lease expiration (can change depending who the clients are) <br/>
<img src="https://imgur.com/CaHZk9M" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
PowerShell: Script to create 1,000 users <br/>
<img src="https://imgur.com/WfOtKdz" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
<br />
Usernmaes and passwords created  <br/>
<img src="https://imgur.com/Ot3crRy" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Client: User can log on using the domain, while having access to the internet on a private network <br/>
<img src="https://imgur.com/undefined" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
