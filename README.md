# osTicket-Prerequisites

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

- Azure Virtual Machine (Windows 10, 4 vCPUs)
- Enable IIS with CGI
- Install PHP Manager for IIS
- Install Rewrite Module
- Install and Configure MySQL

<h2>Installation Steps</h2>
<img src="https://i.imgur.com/4HbnwDt.png" alt="Installation Steps" height="80%" width="80%">
<p>


</p>
<p>
Azure Virtual Machine successfully created with Windows 10 (4 vCPUs), configured with a username and secure password. IIS has been installed and configured with CGI enabled, laying the foundation for the osTicket installation process. The environment is now fully prepared for the next steps, including installing necessary software and setting up the osTicket application
</p>
<br />

<p>
<img src="https://imgur.com/erdhyFx.png" alt="Disk Sanitization Steps" height="80%" width="80%">


</p>
<p>
Installed necessary software from the osTicket installation files, including PHP Manager for IIS, Rewrite Module, VC_redist.x86.exe, and MySQL 5.5.62 (configured with root credentials). Configured PHP by creating a C:\PHP directory, unzipping PHP 7.3.8 files into it, and registering PHP in IIS. Finally, unzipped osTicket-v1.15.8 files, moved the 'upload' folder to c:\inetpub\wwwroot, and renamed it to 'osTicket,' completing the initial setup for the osTicket installation process..
</p>
<br />

<p>
<img src="https://i.imgur.com/y67vm05.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Enabled required PHP extensions (php_imap.dll, php_intl.dll, and php_opcache.dll) in PHP Manager to support osTicket functionality. Configured the ost-config.php file by renaming ost-sampleconfig.php to ost-config.php and setting appropriate permissions. Set up the MySQL database using HeidiSQL, creating a database named 'osTicket' with root credentials. Finalized the osTicket installation in the browser by configuring database settings and completing the installation process
</p>
<br />
