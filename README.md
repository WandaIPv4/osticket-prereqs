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
Install Web Server (IIS - Internet Information Services)
</p> Go to start menu > control panel > programs > turn window features on or off > check off internet information services.</p>
Also install World Wide Services > Application Development Features > Check off CGI (now FastCGI)
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p> Install PHP Manager from website.
</p> Install Rewrite Module from website. 
</p> Then creaate directory on C drive called PHP
</p> Unzip PHP 7.3.8 and extract files into PHP folder
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p> Install Microsoft Visual C++ 
</p> Install MySQL make sure to select typical set up & standard configuration. 
</p> Open IIS as an Admin and Register PHP from within IIS and Reload IIS
</p> Install osTicket v1.15.8 by unzipping file. 
</p> Once everything is extracted, open the osTicket file and copy the upload folder into “c:\inetpub\wwwroot” 
</p> Make sure to rename upload to "osTicket" and reload IIS </p> 
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
</p> In IIS, go to sites > Default > osTicket and double click PHP manager to enable or disable an extension. 
</p> You can check the osTicket website to confirm its working properly. Go to sites > default web site > os ticket and 
</p> click Browse on the right side of window.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename: ost-config.php > From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p> Assign permissions: ost-config.php
</p> Continue Setting up osTicket in the browser (click Continue)
</p> Install HeidiSQL and continue setting up osTicket in the browser

</p>
<br />

