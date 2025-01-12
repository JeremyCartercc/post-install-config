<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments and Teams 
- Allow anyone to create tickets
- Configure Agents(workers) and Users(customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
  <h2>1. Configure Roles, Departments and Teams</h2>

  ![image](https://github.com/user-attachments/assets/90f5ff1f-ecc5-4674-8741-dffed7c4d0ff)

</p>
<p>
Login to the osTicket admin page with this link "https://docs.google.com/document/d/1EemwcNJBrCkZMARXThUriy74IH9ewwZSm-mHf4wvUWg/edit?tab=t.0". Click admin panel, Agents, roles, Add New Role then type in Supreme admin. Give them permissions for everything, click Add role. Now for departments click Departments, add new department, name it SysAdmin and click create department. For teams, go to Team, add new team, name it Online Banking and create Team.
</p>
<br />

<p>
  <h2>2. Allow anyone to create tickets</h2>
  
![image](https://github.com/user-attachments/assets/ab8c3be5-3e62-4079-9810-f621abb383c5)

</p>
<p>
Go to settings and then users, make sure Require registration and login to create tickets is unchecked.
</p>
<br />

<p>
  <h2>3. Configure Agents and Users</h2>
  
![image](https://github.com/user-attachments/assets/33afbc3b-b953-4207-b2e3-ab433f7fb1cc)

</p>
<p>
Go Agents then Add New Agent, put in who you want, press set password, uncheck "send the agent a password reset email" and set the password. Click Access and put her in SysAdmin department and her role as Supreme Admin. 
</p>
<br />

<p>
  <h2>2. Allow anyone to create tickets</h2>
  
![image](https://github.com/user-attachments/assets/ab8c3be5-3e62-4079-9810-f621abb383c5)

</p>
<p>
Go to settings and then users, make sure Require registration and login to create tickets is unchecked.
</p>
<br />

<p>
  <h2>2. Allow anyone to create tickets</h2>
  
![image](https://github.com/user-attachments/assets/ab8c3be5-3e62-4079-9810-f621abb383c5)

</p>
<p>
Go to settings and then users, make sure Require registration and login to create tickets is unchecked.
</p>
<br />
