
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

Internet Information Services (IIS)

    -CGI
  
    -Common HTTP Features
  
    -IIS Management Console
PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)

Rewrite Module (rewrite_amd64_en-US.msi)

PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip)

Visual C++ Redistributable (VC_redist.x86.exe)

MySQL 5.5.62 (mysql-5.5.62-win32.msi)

HeidiSQL

<h2>Installation Steps</h2>

<p>
<img width="468" alt="Screen Shot 2024-07-04 at 1 47 31 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/1bf84327-0832-476d-8285-c3eccdc5f923"


</p>
<p>
Create and log onto a virtual machine in Micorsoft Azure, then open control panel, enabled internet information Services, CGI and common http features. IIS is the webserver that OSticket will be running on. 
</p>
<br />

<p>
<img width="369" alt="Screen Shot 2024-07-04 at 1 44 28 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/888554f6-f11f-460d-adba-ce50ffde36d9">

</p>
<p>
Download and install all of the prerequisite files needed to run the ticketing software.
</p>
<br />

<p>
<img width="651" alt="Screen Shot 2024-07-04 at 2 00 09 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/9c68bdbd-0f11-425c-9e88-cc9a11dc9e9a">

</p>
<p>
Create a PHP directory within the C: Drive, and extract contents of PHP 7.3.8 into it. 
</p>
<br />
<img width="1070" alt="Screen Shot 2024-07-04 at 2 16 14 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/ab883fa7-206e-443f-8a6f-866523dd6285">
</p>
</p>
<br />
Open IIS as an admin and registered PHP within IIS. 
<br />
</p>
</p>

<img width="846" alt="image" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/7f43fb1a-b37a-4471-a1c2-d37adec58a9a">
</p>
</p>

Copy contents of OS ticket "Upload" file into the www.root folder within C: Drive. This is the web server's main folder. Rename the file to "osTicket".



![l](https://github.com/Bpeduru/osticket-prereqs/assets/171273980/7381f72d-819b-4a0c-8287-92aa26e7d16e)


Go back to Internet Information Services --> PHP manager --> Enable or Disable an extension, and enable required extensions


<img width="1080" alt="Screen Shot 2024-07-04 at 2 48 43 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/aa5a4aff-edf1-40cd-9ca3-1e417d2432ae">


Change name of ost-sampleconfig.php to ost-config.php, then change the permissions so that any user has full control. This is because the OSticket installer is going to manipulate this file, and we do not know which user it's going to use to do that. 


<img width="944" alt="Screen Shot 2024-07-04 at 2 33 23 PM" src="https://github.com/Bpeduru/osticket-prereqs/assets/171273980/ffa337f5-5563-44cb-a87d-55297de2c9ce">

open HeidiSQL and create a new connection to the MySQL Server. Also create a new database called OSticket. 

Finish installing OsTicket on the browser. I created credentials and entered the credentials for the MySQl Database. After the installation was successful, go back and deleted the setup folder within C:\inetpub\wwwroot\osTicket to cleanup. 

