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

- Web Server: Install/Enable IIS with CGI 
- PHP Manager 
- Rewrite Module
- Microsoft Visual C
- Database Server: MySQL 

<h2>Installation Steps</h2>

<p>
<img width="300" alt="Image 2 - The results after Web Server is Installed" src="https://github.com/user-attachments/assets/023b597d-cbec-4acd-b70a-e5f48761321f" />

<img width="500" alt="Image 1 - Install Web Server" src="https://github.com/user-attachments/assets/55e68abe-9fc8-4197-809b-b3f717bdeb7e" />
</p>
<p> 1. Install Web Server (IIS - Internet Information Services)
</p>   - Press Windows + R to open Run dialog and type optionalfeatures and press enter to open the "Windows Features" dialog.
</p>   - Scroll down and find Internet Information Services (IIS) and check the box next to it. 
</p>   - Expand to customize which IIS features to install and click ok to begin installation process
<p>       * World Wide Services > Application Development Features > Enable CGI (FastCGI)
</p>
<br />

<img width="350" alt="Screenshot 2025-04-16 at 8 14 35 PM" src="https://github.com/user-attachments/assets/c07e6bd5-d3d5-4941-a5c5-714fd8fdea93" />
<img width="350" alt="Image 4 - Create PHP folder in C drive" src="https://github.com/user-attachments/assets/f309d54a-eb5c-4577-b978-c48dc24bfcb2" />
</p>
<img width="350" alt="Image 5 - Extract PHP files to PHP folder in C drive" src="https://github.com/user-attachments/assets/b1cbcfaf-194d-4165-baf8-da05335fcf94" />

</p>
<p>
</p> 2. Install PHP Manager from Microsoft website or reliable source
</p> 3. Install Rewrite Module from Microsoft website or reliable source
</p> 4. Creaate directory on C drive called PHP
</p> 5. Unzip PHP 7.3.8 and extract files into PHP folder
</p>
<br />

<p>
</p>
<img width="491" alt="Image 6 - Install Microsoft Visual C++" src="https://github.com/user-attachments/assets/ba4f5104-09a0-452f-8a0e-60e7521c146f" />
<img width="340" alt="Image 7 - Run IIS as an admin" src="https://github.com/user-attachments/assets/67799200-86d0-43d2-9ba4-5e1b2c1b4866" />
<img width="476" alt="Image 8 - Register PHP " src="https://github.com/user-attachments/assets/e7f15354-e961-4a9b-ba31-7389100669e4" />
<p>



https://github.com/user-attachments/assets/f88de36b-48f8-4fd8-a320-37005fc9ab5c


</p> 6. Install Microsoft Visual C++ from Microsoft page and choose the latest version 
</p> 7. Install MySQL and make sure to select typical set up & standard configuration. 
</p> 8. Open IIS as an Admin and Register PHP from within IIS and Reload IIS
<p>

</p><img width="400" alt="Image 10 - Install osTicket by extracting file" src="https://github.com/user-attachments/assets/ca59c5b8-3906-4fc4-aeca-ef880e1d3bfa" />

<img width="350" alt="Image 11 - Open osTicket file and copy the upload folder into wwwroot" src="https://github.com/user-attachments/assets/42afebe4-9a9f-427b-bbba-1c2d3c0a01ce" />
<img width="400" alt="Image 12 - Rename upload to  osTicket" src="https://github.com/user-attachments/assets/8859ef8e-3ec6-4950-847c-04926b277e12" />



</p> 9. Install osTicket v1.15.8 by unzipping file. 
</p> 10. Once everything is extracted, open the osTicket file and copy the upload folder into “c:\inetpub\wwwroot” 
</p> 11. Make sure to rename upload to "osTicket" and reload IIS </p> 
</p>
<p>


https://github.com/user-attachments/assets/0dbdca40-6dc9-4c12-82f8-c48586ad5485

<img width="1435" alt="Image 15 - Enable and disable difference" src="https://github.com/user-attachments/assets/908a0a16-30ef-469f-bd17-4e6a9ae34369" />


</p>
</p> 12. In IIS, go to sites > Default > osTicket and double click PHP manager to enable or disable an extension. 
</p> 13. You can check the osTicket website to confirm everything is working properly by refreshing the webpage
</p    
</p>
<br />
<p>


https://github.com/user-attachments/assets/82fad14f-65f3-4a87-bbe0-7b1a25f2cc30


<img width="400" alt="Image 17 - Download Heidi SQL " src="https://github.com/user-attachments/assets/370346c1-2f4b-41b2-ba5d-995b9a76f10d" />

<img width="400" alt="Image 17 - Set Up Database in HeidiSQL" src="https://github.com/user-attachments/assets/c5a670e4-aa19-4329-bde7-a1f6f483a148" />
<img width="40" alt="Image 18 - Completed Set UP" src="https://github.com/user-attachments/assets/9cedc6dc-08fd-46f8-ae68-f08d37fc09cb" />
<img width="450" alt="Image 19 Set up Part 2" src="https://github.com/user-attachments/assets/74deb176-672f-43bb-a3f2-9674face8a5b" />

</p>
<p> 14. Rename: ost-config.php > From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php to C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p> 15. Assign permissions: ost-config.php
</p> 16. Continue Setting up osTicket in the browser (click Continue)
</p> 17. Install HeidiSQL and continue setting up osTicket in the browser

</p>
<br />

