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
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/uQFItX9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
log into osTicket using the following URL: http://localhost/osTicket/scp/login.php
</p>
<br />

<p>
<img src="https://i.imgur.com/jYfwWDD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles: 
Admin Panel -> Agents -> Roles

Add new "Supreme Admin" Role & give them permission to do anything
</p>
<br />

<p>
<img src="https://i.imgur.com/n4uiWfg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments:
Admin Panel -> Agents -> Departments

Add "System Administrators" Department
</p>
<br />

<p>
<img src="https://i.imgur.com/uqJ1o8j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams:
Admin Panel -> Agents -> Teams

Create Level I Support

Create Level II Support
</p>
<br />

<p>
<img src="https://i.imgur.com/fLGlW88.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets:
Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets 
</p>
<br />

<p>
<img src="https://i.imgur.com/Nmt8cTN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New

Create "Jane Doe" assign to System Administrators & make a Supreme Admin

Create "John Doe" assign to Support Department & give All Access
</p>
<br />

<p>
<img src="https://i.imgur.com/j2gIRkX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New

Create "Karen" & Create "Ken"
</p>
<br />

<p>
<img src="https://i.imgur.com/sNeyXSq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA:
Admin Panel -> Manage -> SLA

Sev-A (1 hour, 24/7)

Sev-B (4 hours, 24/7)

Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/zE1067b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics:
Admin Panel -> Manage -> Help Topics

Business Critical Outage

Personal Computer Issues

Equipment Request

Password Reset
</p>
<br />
