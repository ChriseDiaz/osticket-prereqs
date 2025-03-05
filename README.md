<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [ClipChamp: How To Install osTicket with Prerequisites](https://1drv.ms/v/c/5dac4edc6b620d54/EVp75XjxqfFDpNtROIv56CgBtBB0w9x_YFm18g4scVjIxQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure account
- Virtual Machines
- Remote Desktop
- osTicket installation files
- SQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Create Azure Virtual Machine:
Name: osticket-vm
Username: labuser
Password: osTicketPassword1!
Size: 4 vCPUs (Windows 10 Pro)
2. Log into VM via Remote Desktop:
Use the provided username and password to connect to the VM.
3. Prepare VM for osTicket Installation:
Download osTicket Files: Download osTicket-Installation-Files.zip and unzip it on the desktop into a folder called osTicket-Installation-Files.
4. Enable IIS with CGI Support:
Go to Control Panel > Programs and Features > Turn Windows Features On/Off.
Enable IIS with CGI under World Wide Web Services > Application Development Features.
5. Install Dependencies:
PHP Manager for IIS: Install PHPManagerForIIS_V1.5.0.msi from the folder.
URL Rewrite Module: Install rewrite_amd64_en-US.msi from the folder.
PHP: Create C:\PHP and unzip php-7.3.8-nts-Win32-VC15-x86.zip into it.
VC Redistributable: Install VC_redist.x86.exe.
MySQL 5.5.62: Install mysql-5.5.62-win32.msi with Typical Setup. Configure MySQL with:
Username: root
Password: root
After these steps, your VM will be set up with IIS, PHP, and MySQL, ready to install osTicket.




</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
