<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Teams and Departments
- Configure Agents
- Configure SLA
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/OfwXNrY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure roles, go to: Admin Panel > Agents > Roles. Add role. Name it and enable all ticket permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/poOcW2j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Agents > Departments, Name the department and select a manager. Click "Creat Dept".
</p>
<br />

<p>
<img src="https://i.imgur.com/6uIWQwR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
go to Admin Panel -> Agents -> Teams. Select "Add team". Name it "Level II Support" and add member by clicking on "Members" tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/bV13rN3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel -> Agents and click "Add new agent". Create name and email. Press the set password button. Deselect the "Send the agent a password reset" box and create a password. Deselect the "require password change" box and press "set". Click on "Access" tab and select "System Administrators". Also select the department you created. In extended access below, select the department you created and add "support" department as well. Next, click on "teams" tab and select the team you created. Click "Create".
</p>
<br />

<p>
<img src="https://i.imgur.com/4jLUdib.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add another agent with limited permissions. To create users, go to Agent Panel > Users > and click on "Add user". Create name, email and password. Click "Add User".
</p>
<br />

<p>
<img src="https://i.imgur.com/4jLUdib.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add another agent with limited permissions. To create users, go to Agent Panel > Users > and click on "Add user". Create name, email and password. Click "Add User".
</p>
<br />

<p>
<img src="https://i.imgur.com/JcOl07P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Manage > SLA and click "add new SLA plan". Place these settings for Sev-A: (1 hour, 24/7). Sev-B will be (4 hours, 24/7) and Sev-C will be (8 hours, Monday - Friday).
</p>
<br />

<p>
<img src="https://i.imgur.com/SXXyokb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Manage > Help Topics and click "Add help topic". Title the first one "Critical Outage", the second "Computer Issues", and lastly "Password Reset". Log into the user portal of osTicket at: http://localhost/osTicket/. Use a user you created to create tickets.
</p>
<br />
