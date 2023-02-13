<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Account
- Resource Group
- Virtual Machine using Windows 10
- IIS in Windows with CGI
- Inside the VM install PHP Manager, Rewrite Module, MySQL, OsTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/dpiCMn6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Microsoft azure account and create a Resouce Group. Inside the resource grouop, install a virtial machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/HlmIQau.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I created the vm with a Windows 10 OS. Then I create a user name and password to log into the virtual machine. Next I set up the NIC to finalize the creation of the vm.
</p>
<br />

<p>
<img src="https://i.imgur.com/ErugrwQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using Desktop remote, login to the virtual machine using the IP address. Once inside the vm, download the necessary programs including: IIS in Windows with CGI, PHP Manager, Rewrite Module, PHP, MySQL, HeidiSQL, and OsTicket.
</p>
<br />
