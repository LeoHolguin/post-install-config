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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="710" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/0dcda947-91ba-4cf5-a9ea-e505b8e9085a">
<img width="572" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/0e3af839-361a-49a9-85c0-7f19bef3c25b">
<img width="708" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/4adbe4d7-6e14-4196-94ea-9f999f1cbe5c">



</p>
<p>
Now that we are in the ticketing system we are going to set up our environment to simulate a real one. First, we are going to configure roles which are the permissions granted to Agents per department that they have access to. Once we login into the osTicket website we are going to head over to the admin panel, agents, and roles. This role is going to be name supreme adimn because we are going to give it every permissions that there is. Since tickets are routed through departments now we are going to configure one. Just by clicking on departments  we can add a new Department called system administrators don't worry about the SLAs just yet we can leave them on default for now.
</p>
<br />

<p>
<img width="720" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/dbaea95d-9cae-4bcb-ad2e-1f31b812cd95">
<img width="704" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/618a1486-b089-4754-b58e-5b9e1071f1e3">
<img width="715" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/96b8461e-58f4-4770-926f-7a0aa9864792">
<img width="718" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/fe5ae5a0-6a61-40ab-abb4-87740f369620">



</p>
<p>
Next, we are going to congifure teams which allows us to pull Agnets from departments and organize them. Head over to the teams tab and add a new teamn called Level II Support. Now we are to to check off a box where we allow anyone to create tickets, on the admin panel go to settings, users settings and check off  require registration and login to create tickets. We are next creating agents which are the people who responds and resolves the tickets. Lets head over to agents and create a new agent and for this example its going to be Jane Doe. We are going to be givnig them admin access and assigning them the the new team we made earlier. We are going to create another agent name John Doe and give him similar permissions.
</p>
<br />

<p>
<img width="484" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/dcc46521-7e04-4706-976e-d5748b7e8c98">
<img width="722" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/c838dca6-7939-4add-a39c-9cd7af5521b0">


</p>
<p>
Then we are going to create users which are basically the customers and they can create accounts and tickets when ever they have a technical problem. Click on agent panel, users, and add a new agent. For this lab We are going to add Karen as one of our users and also another person call Ken.
</p>
<br />
<p>
<img width="730" alt="image" src="https://github.com/LeoHolguin/post-install-config/assets/138087728/e58742ae-7faa-461e-8c9f-49537a647f25">



</p>
<p>
We are going to configure SLA Plans because this provides a length of time in which a ticket expects to be closed. Now we are going back to the admin panel, manage, and on SLA. We are going create three plans of SLA first one Ill walk you through it. Click on add SLA the name should be severity-b with a 4 hour grace peroid which gives us 4 hours to solve that ticket. 
</p>
<br />
