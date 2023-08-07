<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation</h1>


This tutorial demonstrates the post-configuration setup of the osTicket system.<br />
<p>We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first, we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case, since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.</p>

<img src="https://i.imgur.com/7ngAavb.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>

</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.
</p>
<br />

<p>
<img src="https://i.imgur.com/7socgJE.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example, you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example, we will create a Level II Support Team.
</p>
<br />

<p>
<img src="https://i.imgur.com/mrOkzVt.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

<p>
<img src="https://i.imgur.com/fMli4ut.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we are going to create Agents.Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their departments. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are assigned in the Agents tab.<p>
 
<p>
<img src="https://i.imgur.com/5PyyBcr.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.


<p>
<img src="https://i.imgur.com/8vdgbwe.png://" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
