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

- Create Virtual Machine in Azure
- Install / Enable IIS in Windows
- Download and install MySQL
- Install OsTicket
- Download and install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/96sOLGt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create your virtual machine and Remote Desktop connect to it.
</p>
<br />

<p>
<img src="https://i.imgur.com/D09dibZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In control panel go to programs, 'Turn Windows features on or off'.
Go to World Wide Web Services -> Application Development Features -> check CGI and Common HTTP Features box.
Internet Information Services -> Web Management Tools -> IIS Management Console -> check IIS Management Console box.
</p>
<br />

<p>
<img src="https://imgur.com/lzD3Yho.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Register PHP from within IIS after downloading and installing both.
</p>
<br />
