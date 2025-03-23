<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This Project outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Agent and Admin panel
- Roles and Departments
- Teams
- Agents and Users
- SLA and Help Topics

<h2>Configuration Steps</h2>

<h4>Agent and Admin panel:</h4>

<p>
<img src="https://i.imgur.com/aqwY2zo.jpeg" height="50%" width="50%" alt="Agent Panel"/>
<img src="https://i.imgur.com/5XIyIiP.jpeg" height="50%" width="50%" alt="Admin Panel"/>
</p>
<p>
First, you need to login to osticket as either a agent or as the admin. Depending on which one you are the dashboard will look at different. As agent the dashboard will consists of the users, tasks, and tickets. Any tickets that you are currently working on or have completed will show as well as any tasks that need to be done. For the admin this will look like emails, settings, agents, and manage. Here you will be able to do a number of things such as set permissions, assign agents to certain deparments, and create/look at different tasks.   
</p>
<br />

<h4>Roles and Departments:</h4>

<p>
<img src="https://i.imgur.com/WpZ1SFI.jpeg" height="50%" width="50%" alt="New Roles"/>
</p>
<p>
  We are going to add a new role called the Supreme admin. As the admin you want to go to agent section, select the category role and type in the name of the new role then save it so that way it will now be added. 
</p>
<br />

<p>
  <img src="https://i.imgur.com/Eu21X4z.jpeg" height="50%" width="50%" alt="New Department"/>
  <img src="https://i.imgur.com/UwJi5y7.jpeg" height="50%" width="50%" alt="New Department"/>
</p>
<p>
  Here we created a new department called Sysadmin. To create this you will need to go over to to agents the go to departments and fill out all of the information. You can also setup different things like the SLA,type, and status as well.    
</p>
<br />

<h4>Teams:</h4>

<p>
<img src="https://i.imgur.com/HNuRsPF.jpeg" height="50%" width="50%" alt="New Teams"/>
<img src="https://i.imgur.com/Akkk9Oc.jpeg" height="50%" width="50%" alt="New Teams"/>
</p>
<p>
A new team was created above so you can assign certain tickets to a specific team if that needed to take place. So, we created a new team by just going over to the agents section and going to teams. Once there you can fill out the information and save it. 
</p>
<br />

<h4>Agents and Users:</h4>

<p>
  <img src="https://i.imgur.com/VEVDPGW.jpeg" height="50%" width="50%" alt=" New Agents"/>
</p>
<p>
  By creating a new agent, we can assign tickets to them and set different settings/status for them. To do this you will need to go to the agents section and press create a new agent. Fill out the info and different settings you want to add and save it. 
</p>
<br />

<p>
   <img src="https://i.imgur.com/fu4VlVE.jpeg" height="50%" width="50%" alt="New Users"/>
   <img src="https://i.imgur.com/OkdqFjm.jpeg" height="50%" width="50%" alt="New Users"/>
</p>
<p>
To add a new user, as an agent go over to the users section and select add new user. You can create multiple new users and add internal notes to them if needed. 
</p>
<br />

<h4>SLA and Help Topics:</h4>

<p>
  <img src="https://i.imgur.com/dwTGm7c.jpeg" height="50%" width="50%" alt="New SLA"/>
  <img src="https://i.imgur.com/ZP2LMXT.jpeg" height="50%" width="50%" alt="New SLA"/>
  <img src="https://i.imgur.com/w8yEXIo.jpeg" height="50%" width="50%" alt="New SLA"/>
</p>
<p>
  A SLA( service level agreement) is a agreement or contract between a IT provider and client on what is going to be done. Depending on the impact, a priority will be set. To Create a SLA as the admin you will need to go to manage and then to the SLA sectiona. Select create new SLA, after that we wil set the grace hours and the schedule. The schedule can be 24/7 or within business hours aas well. Create three new SLAs and save them. 
</p>
<br />

<p>
   <img src="https://i.imgur.com/C77XSAL.jpeg" height="50%" width="50%" alt="New Help Topics"/> 
  <img src="https://i.imgur.com/AM5lH2c.png" height="30%" width="50%" alt="New Help Topics"/>
</p>
<p>
  A help topic helps users select the problem that is occuring so that the agents have an idea of what is going on. Above you'll see different examples of that. We created these by going to manage and selecting help topics. When creating a new help topic, you will need to set the status, priority, type, and deparment. When finished press save and it will be created. 
</p>
<br />
