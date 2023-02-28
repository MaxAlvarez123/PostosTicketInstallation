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

- Configure a Agent(worker)
- Configure Role
- Configure a Department
- Configure a Team
- Configure SLA 
- Configure User(Customer)
- Comfigure Help topic

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/LbEr3JN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/Et9nuba.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/3sFP8aJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Agents are defind as given access to the help desk with the intent to resolve tickets fast

- To create a Agent make sure your are in the admin Admin panel

- And go to Agents -> Add new Agent

- From there you able to put in any information about the agent give access and permission and assign them to a team. 
</p>
<br />

<p>
<img src="https://i.imgur.com/PWfQTWd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- In osTicket a role are the permissions granted to Agents per Department that they have access to.

- To configrue a role go to Admin Panel -> Agents -> Role
</p>
<br />

<p>
<img src="https://i.imgur.com/T2FJxZ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/WF4Tmcc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Departments are where the tickets are routed through.

- To configure go departments got to admin panel -> Agents -> Departments 

</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/sXG9MHo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/kgkjWuf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- In osTicket Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.

- To configure teams got to Admin Panel -> Agents -> Teams -> Add New Team

</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/PrQnpjC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- SLA or Service Level Agreement is to provide a length of time in which the help desk Administrator expects tickets to be closed.

- To configure SLA go to Admin Panel -> Manage -> SLA -> Add New SLA Plan 

</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/GmSDSKR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Users are ticket owners of the ticket in Help Desk aka the customer

- To create new users go to the Agent Panel -> Users -> Add Users
 
</p>
<br />

<br />

<p>
<img src="https://i.imgur.com/p0XJprd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/kLoxiyg.pngg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Help Topics will determine what Department the ticket is routed to which will determine which Agents have access to the ticket. The Help Topic also can determine other configurations of the ticket, such as the ticket’s SLA (or Service Level Agreement) and priority of a ticket, i.e. Emergency to Low.

- To create a Help Topic go to Admin Panel -> Mange -> Help Topic -> Add New Help Topic

- And those are all of the basic feature to get ur ticketing system up and running. 

</p>
<br />
