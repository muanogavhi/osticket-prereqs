
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Mastering osTicket : A Comprehensive Guide to setup, Configure and Ticket Management</h1>
In this project, i Deployed osTicket, an open-source help desk system, on an Azure virtual machine. Configured IIS, installed osTicket, and managed ticket lifecycle (creation, assignment, response, resolution). Demonstrated skills in Azure, VM management, web server configuration, and help desk ticketing system implementation.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop 
- Internet information ServicesIIS (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Prerequisites</h2>

- MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- HeidiSQL
- PHP 7.3.8
- PHP ManagerForlls_V1.5.0.msi
- VC Redist.x86.exe
- Rewrite Module (rewite_amd64_en-US.msi)

<h2>Installation Steps</h2>


![image](https://github.com/user-attachments/assets/f7eb7fd0-41d5-49ce-a1e3-71590210f148)


<p>
Create a Windows 10 Pro Virtual Machine in Azure and use Remote Desktop to access it.
</p>
<br />


![image](https://github.com/user-attachments/assets/335c96db-e920-4196-8a65-a8562267a9a6)

</p>
<p>
Prepare Windows 10 as a Web Server by installing and enabling IIS, along with the required application features and the IIS Management Console.
</p>
<br />


![image](https://github.com/user-attachments/assets/b91655ea-0bda-4480-ab1b-a0e30f468320)


<p>
Install PHP Manager, VC Redist, Rewrite Module, and PHP.

Install MySQL and set it up for database management with HeidiSQL.
</p>
<br />


![image](https://github.com/user-attachments/assets/75418ae1-54bc-4557-8f61-f878410929ef)


<p>
Download and extract the osTicket files, place them in the IIS root directory, and configure it as a website.

Test to ensure osTicket is running properly through IIS.
</p>
<br />


![image](https://github.com/user-attachments/assets/ba28b34b-7522-48da-98b5-6662e15372f8)

<p>
Enable necessary PHP extensions and assign proper file permissions for security and functionality.
</p>
<br />


![image](https://github.com/user-attachments/assets/574b4aee-19c4-4948-9bb9-d0351cf7c916)


</p>
<p>
Register osTicket, connected it to SQL, and completed the setup process.
</p>
<br />

<h2>Post-Installation Configuration:</h2>
<p>
After the installation, configure osTicket to function as an efficient help desk system:
</p>


![image](https://github.com/user-attachments/assets/1eaa02dd-dfe1-487e-8090-5440c5437f8f)

</p>
<p>
Create roles for administrators and agents and set up teams for different support levels (e.g., Level 1 and Level 2).
</p>
<br />


![image](https://github.com/user-attachments/assets/f0b8692a-e010-417b-8400-b24ef6f392f0)

</p>
<p>
Add support agents and end-users who would be interacting with the ticket system.
</p>
<br />


![image](https://github.com/user-attachments/assets/3e311e29-5e35-45c0-bf3f-a48f48be2553)

</p>
<p>
Establish SLAs (Service Level Agreements):

Define response times for various ticket priorities, such as a 1-hour response for critical issues (Sev-A).
</p>
<br />


![image](https://github.com/user-attachments/assets/e11ead53-0533-4f0a-9a72-0315403af66a)

</p>
<p>
Set up help topics to categorize user requests, like "Password Resets" or "Equipment Requests."
</p>
<br />

<h2>Managing the Ticket Lifecycle:</h2>


![image](https://github.com/user-attachments/assets/ac2823f0-1b87-452b-ba1f-bc37a6193e79)

</p>
<p>
Ticket Creation: Users or agents submit tickets via the help desk.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 10 27 43 PM" src="https://github.com/user-attachments/assets/b3d0f38f-0951-4b9b-bf50-439088cce8c2">
</p>
<p>
Ticket Assignment: Tickets are supposed to be assigned based on priority and category. Sometimes the end user will not label their tickets correctly, and it is up to the help desk support to fix them so we can address the issue appropriately.
</p>
<br />

![image](https://github.com/user-attachments/assets/0230c953-d1d3-4b35-a1e0-b0a1dbfc1352)


</p>
<p>
Resolution and Closure: Agents resolve the issues, communicate with users, and close tickets once verified.
</p>
<br />

<h2>Conclusion:</h2>

<p>
This project gave me hands-on experience with setting up and managing a help desk system, demonstrating my ability to configure both the backend and operational side of IT ticket management and get familiar with a ticketing system environment as both an administrator and help desk support agent.
</p>
<br />
