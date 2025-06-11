
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Building a Help Desk Ticketing System: From Server Setup to Ticket Resolution with osTicket</h1>
In this project, I installed and configured osTicket, an open-source help desk system, on a virtual machine hosted in Microsoft Azure. I used Remote Desktop to manage the VM, set up IIS as the web server, and walked through the entire lifecycle of ticket management within osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure: Virtual Machines
- Remote Desktop: To access the VM
- IIS: Web server setup for osTicket
- Windows 10 Pro: Operating system on the VM

<h2>Prerequisites</h2>
To ensure a smooth installation of osTicket, I first installed the necessary prerequisites:

- MySQL: As the database for osTicket.
- HeidiSQL: For managing the osTicket database.
- PHP & PHP Manager: To handle the server-side scripting.
- VC Redist & URL Rewrite: Dependencies for running PHP on IIS.

<h2>Installation Steps</h2>

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 8 49 19 PM" src="https://github.com/user-attachments/assets/1b86d9cc-fe39-461e-b4a5-2ce827a540fc">
</p>
<p>
Create a Windows 10 Pro Virtual Machine in Azure and use Remote Desktop to access it.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 05 02 PM" src="https://github.com/user-attachments/assets/10d671e1-4885-4f3c-9e87-9ea9fd908d04">
</p>
<p>
Prepare Windows 10 as a Web Server by installing and enabling IIS, along with the required application features and the IIS Management Console.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 09 01 PM" src="https://github.com/user-attachments/assets/337f9312-cea4-4806-85ba-a6fa965a8363">
</p>
<p>
Install PHP Manager, VC Redist, Rewrite Module, and PHP.

Install MySQL and set it up for database management with HeidiSQL.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 22 05 PM" src="https://github.com/user-attachments/assets/4d7a1f9c-5a61-43ae-b203-572b8e93347a">
</p>
<p>
Download and extract the osTicket files, place them in the IIS root directory, and configure it as a website.

Test to ensure osTicket is running properly through IIS.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 24 19 PM" src="https://github.com/user-attachments/assets/b9413205-a3be-44de-83e7-5c1b884f1826">
</p>
<p>
Enable necessary PHP extensions and assign proper file permissions for security and functionality.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 38 08 PM" src="https://github.com/user-attachments/assets/62988fbe-4f9c-4c87-afd8-e2640aa92aae">
</p>
<p>
Register osTicket, connected it to SQL, and completed the setup process.
</p>
<br />

<h2>Post-Installation Configuration:</h2>
<p>
After the installation, configure osTicket to function as an efficient help desk system:
</p>

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 49 48 PM" src="https://github.com/user-attachments/assets/4de83a5f-85a9-4367-a98c-8536678f6148">
</p>
<p>
Create roles for administrators and agents and set up teams for different support levels (e.g., Level 1 and Level 2).
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 9 56 51 PM" src="https://github.com/user-attachments/assets/4ca95f30-b2ba-4bfe-afa1-5da939803a24">
</p>
<p>
Add support agents and end-users who would be interacting with the ticket system.
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 10 07 53 PM" src="https://github.com/user-attachments/assets/1dde7b62-c099-4e95-8397-afe8e163814f">
</p>
<p>
Establish SLAs (Service Level Agreements):

Define response times for various ticket priorities, such as a 1-hour response for critical issues (Sev-A).
</p>
<br />

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 10 16 24 PM" src="https://github.com/user-attachments/assets/701f672c-2348-494e-9f62-eef1b55e38ff">
</p>
<p>
Set up help topics to categorize user requests, like "Password Resets" or "Equipment Requests."
</p>
<br />

<h2>Managing the Ticket Lifecycle:</h2>

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 10 23 22 PM" src="https://github.com/user-attachments/assets/7da77515-0a2e-425b-8fd3-9e7aa4804e9b">
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

<p>
<img width="2056" alt="Screenshot 2024-10-16 at 10 37 12 PM" src="https://github.com/user-attachments/assets/d3733d73-49a5-44ff-96aa-6210b5884f37">
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
