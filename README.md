# post-install-config
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
- Configure Agents
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps</h2>

- Configuring Roles would be our first step and here are the steps to follow.
   In our Admin panel,  Select Agents tab => Roles => Add New Roles
   Name would be :Supreme Admin
   Select Permissions tab and check every box under the "Tickets", "Tasks" and "Knowledgebase" section
   Select Add Role
   Create the role Supreme Admin, and give it  accessbility befitting the role: Complete Control.
   
   <p align="center">
   <a href="https://imgur.com/KMN1XIc"><img src="https://i.imgur.com/KMN1XIc.png" title="source: imgur.com" /></a>
   <a href="https://imgur.com/wHg5NVv"><img src="https://i.imgur.com/wHg5NVv.png" title="source: imgur.com" /></a>
   </p>
   
- Configuring Departments is the next step.
  Make sure you are in admin panel (check top right to see which panel you are in)
  Select the Agents tab => Department => Add New Department, 
  The name should be System Administrators.
  Then select create Department.
  
  <p align="center">
  <a href="https://imgur.com/7rsjTRp"><img src="https://i.imgur.com/7rsjTRp.png" title="source: imgur.com" /></a>
  <a href="https://imgur.com/itU05Qe"><img src="https://i.imgur.com/itU05Qe.png" title="source: imgur.com" /></a>
  </p>
      
- Following up is Configuring Teams.
   Stay in admin panel (check top right to see which panel you are in, used to hearing this huh? lol)
   Select the Agents tab => Teams => Add New Team
   Name: Level II Support
   Go to the members tab and then select yourself in "Select Agent" dropdown menu
   Select create team.
   
  <p align="center">
  <a href="https://imgur.com/HQKtJCA"><img src="https://i.imgur.com/HQKtJCA.png" title="source: imgur.com" /></a>
  </p>
     
- Allow anyone to create tickets.
   Make sure that you are in the admin panel (you know where to check).
   Select the settings => User Settings
   Make sure box is unchecked:
   Registration Required: Require registration and login to create tickets

- Configure Agents is next
   Make sure you are in admin panel (check top right to see which panel you are in)
   Select the Agents tab => Add New Agents  
   Create and define the roles of agents Jane and John Doe. 
   
   For e.g. Name: Jane Doe.
   
            Email : jane.doe@osticket.com.
            Username: jane.doe.
   
   Click set password and uncheck box that says "send the agent a password reset email".
   
               👉Set your password to anything you like.
               👉uncheck box that says "require password change at next login.
               👉Select set.
               
   These agents will be responding to ticket requests from clients Ken and Karen.
   
<p align="center">
<a href="https://imgur.com/HB3o9EK"><img src="https://i.imgur.com/HB3o9EK.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/FX94epU"><img src="https://i.imgur.com/FX94epU.png" title="source: imgur.com" /></a> 
<a href="https://imgur.com/HQKtJCA"><img src="https://i.imgur.com/HQKtJCA.png" title="source: imgur.com" /></a>
</p>
   
- Configure SLA
      Steps: Admin Panel => Manage => SLA => Add New SLA Plan 
             
      👉Sev-A (1 hour, 24/7) Name: SEV-A, Grace Period: 1 hr, Schedule dropdown menu: 24/7, Select Add Plan.
      👉Sev-B (4 hours, 24/7) Name: SEV-B, Grace Period: 4 hrs, Schedule dropdown menu: 24/7, Select Add Plan.
      👉Sev-C (8 hours, business hours) Name: SEV-C, Grace Period: 8 hrs, Schedule dropdown menu: business hours,
      
     Select Add Plan

   <p align="center">
   <a href="https://imgur.com/i1Kwla6"><img src="https://i.imgur.com/i1Kwla6.png" title="source: imgur.com" /></a>
   </p>

- Configure Help Topics

   Make sure you are in admin panel (Always remeber the rule of Admin club: ALWAYS CHECK if you are still in admin club).
   Select Manage tab => Help Topics => Add New Help Topics
   
      👉Business Critical Outage
      👉Personal Computer Issues
      👉Equipment Request
      👉Password Reset
    
   <p align="center">
   <a href="https://imgur.com/aW1lp1I"><img src="https://i.imgur.com/aW1lp1I.png" title="source: imgur.com" /></a>
   <a href="https://imgur.com/JHaQjJv"><img src="https://i.imgur.com/JHaQjJv.png" title="source: imgur.com" /></a>
   <a href="https://imgur.com/QYhzczP"><img src="https://i.imgur.com/QYhzczP.png" title="source: imgur.com" /></a>
   </p>
   
   Select Add Topic for each topic, and just like the image for the Business Critical Outage, make 4  the mentioned help topics.
   
  🎆 CONGRATULATIONS!!!! 🎆 You're all done with Post Install Configuration for osTicket! 🏅
  
  .....
  ..........
  ............... for now ⚠️
  
</p>
<br />
