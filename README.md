# Post-Install-Configuration
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

- Configure Departments
- Configure Agent (worker)
- Configure Roles
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/TMJll19.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Departments were configured through the Agents tab under the Admin Panel. Departments are used to route tickets in help desk. The Deparments may be private or public and they can be assigned to 1 or more agents and managers. 
</p>
<br />

<p>
<img src="https://i.imgur.com/uR0FRaL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents were configured and given access to the help desk with the intent to respond and resolve tickets. When adding an Agent to the help desk, they can be be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/oR3MF2t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments. Roles are configured in the Agents tab under the Admin Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/SRD6aI6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans or Service Level Agreements. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed. SLA Plans can be created by going to the Manage tab under the Admin Panel and clicking "Add New SLA Plans." 


</p>
<br />
