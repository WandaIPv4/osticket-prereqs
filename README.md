<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Web Server: Install/Enable IIS with CGI 
- PHP Manager 
- Rewrite Module
- Microsoft Visual C
- Database Server: MySQL 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Web Server 
Go to start menu > control panel > programs > turn window features on or off > check off internet information services.
Also install World Wide Services > Application Development Features > Check off CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install PHP Manager from website.
Install Rewrite Module from website. 
Then creaate directory on C drive called PHP
unzip PHP 7.3.8 and extract files into PHP folder
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Microsoft Visual C++ 
Install MySQL make sure to select typical set up & standard configuration. 
Open IIS as an Admin and Register PHP from within IIS and Reload IIS
Install osTicket v1.15.8 by unzipping file. 
Once everything is extracted, open the osTicket file and copy the upload folder into “c:\inetpub\wwwroot” 
Make sure to rename upload to "osTicket" and reload IIS 

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
In IIS, go to sites > Default > osTicket and double click PHP manager to enable or disable an extension. 
You can check the osTicket website to confirm its working properly. Go to sites > default web site > os ticket and 
click Browse on the right side of window.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename: ost-config.php > From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
Assign permissions: ost-config.php
Continue Setting up osTicket in the browser (click Continue)
Install HeidiSQL and continue setting up osTicket in the browser

</p>
<br />

