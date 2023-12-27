<p>
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this lab, we will outline the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Post-Install Configuration Objectives</h2>

- Configure Agents
- Configure Users
- Configure SLA's
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
In this lab, you will be doing some post-installation setup. First, you are going to configure new roles within osticket by clicking on the options Admin Panel-->Agents-->Roles. You will click on add new role and create a Supreme Admin that has been given all permissions within osTicket. Your screen should look like the image below.
</p>
<p>
<img src="https://imgur.com/28OpmGY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next, you are going to configure a new department. Click on the Departments button in the Agents tab. Each Agent is assigned to a specific department depending on their assigned role in the osTicket. You will create a department called "System Administrators" and you will assign the Supreme Admins to this department.
</p>
<p>
<img src="https://imgur.com/23t29pE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Now it is time to configure a team. Teams allow you to pull agents from different departments. An example would be that you can create a help topic that correlates with a product you produce and assign it to a team of agents that specialize in that particular product. To create a team go to Agents-->Teams. A Level I Support Team has already been made by default so you will be creating a Level II Team. 
</p>
<p>
<img src="https://imgur.com/fAmGiai.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Now that you have created a new team, you will create a new setting that will allow anyone to create tickets. Go to Admin Panel-->Settings-->User Settings to do this.
</p>
<p>
<img src="https://imgur.com/T1Uw0Yd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Now you are going to create Agents. Agents are the employees in osTicket that work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. You are going to create one agent "Jane Doe" who is in the System Administrator department and has Supreme Admin access. You will also create another Support Agent "John Doe."
</p>
<p>
<img src="https://imgur.com/YYa3WMi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
<img src="https://imgur.com/KCCDe87.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Now the next step is to create users. Users are the customers who create tickets when they are having technical issues. A user is identified with their email address. You will create a user by going to the Agent Panel-->Users-->User Directory-->Add User. You will creat two users for this lab.
</p>
<p>
<img src="https://i.imgur.com/UTsbGFZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/VStKFVa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Service Level Agreement(SLA) Plans provide a length of time that IT support is expected to take to solve a specific ticket. You are going to go to Admin Panel-->Manage-->SLA Plans to create an SLA Plan. Each SLA has a schedule and within that schedule, there's a grace period. You are going to create three SLA Plans. SEV-A is going to have a grace period of 1 hour(24/7), SEV-B is going to have a grace period of 4 hours(24/7), and SEV-C with a grace period of 8 hours(business hours).
</p>
<p>
<img src="https://imgur.com/pksSqVe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/jTyVSll.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
Help Topics help users categorize their tickets. You will create four categories (Business Critical Outage; Personal Computer Issues; Equipment Issues; and password Reset) for IT support to use when reporting an issue.
</p>
<p>
<img src="https://imgur.com/grb5GR4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/TPSbn89.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
