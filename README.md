# post-install-config<p align="center">
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
Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 


End Users osTicket URL:
http://localhost/osTicket 


Acknowledge Agent Panel vs Admin Panel


Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
* Supreme Admin


Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
* SysAdmins


Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
* Online Banking


Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
* Registration Required: Require registration and login to create tickets 


Configure Agents (workers)
Admin Panel -> Agents -> Add New
* Jane (Dept: SysAdmins)
* John (Dept: Support)


Configure Users (customers)
Agent Panel -> Users -> Add New
* Karen
* Ken


Configure SLA
Admin Panel -> Manage -> SLA
* Sev-A (Grace Period: 1 hour, Schedule: 24/7)
* Sev-B (Grace Period: 4 hours, Schedule: 24/7)
* Sev-C (Grace Period: 8 hours, Business Hours)


Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
* Business Critical Outage
* Personal Computer Issues
* Equipment Request
* Password Reset
* Other

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
