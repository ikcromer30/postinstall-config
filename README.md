<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Post-Install Configuration Objectives</h2>


- Configure Roles, Departments, And Teams
- Make Agents And Users
- Create SLA Levels
- Create Help Topics

<h2>Configuration Steps</h2>

First you will want to access the Admin Panel.
<p>

<img width="698" alt="ost admin panel" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/72e22393-c8e8-4717-bb5e-198422990014">

</p>
<p>.
From the Admin Panel, you want to click the Agents Tab. 
</p>
<br />
<img width="638" alt="OST CLICK AGENT" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/27e1b78d-a62e-4e01-9e4c-1dfd8b2e2204">

<p>

From there, the next step is to create roles. Click on the Roles Tab.
</p>
<p>
<img width="640" alt="ROLLS" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/3b43d505-8a68-4502-ae04-85c56eee9445">

</p>
<br />

Once in the Roles section, select "Add New Role" . 
<p>
</p>
<img width="710" alt="OST ADD NEW ROLE" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/6e7e6047-c8af-43ec-a13f-ce5fcd273f5d">

<p>

</p>
Create a "Supreme Admin" role. Enable all Tickets, Tasks, And Knowledgebase in the Permissions Tab
<br />
<img width="599" alt="ost enable permissions" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/d62b3f89-d4f9-47d1-89ba-7f2b42091033">

Next We Create A Department. Click on the departments tab.
</p>
<p>
<img width="641" alt="OST DEPARTMENTS TAB" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/d67d4e9e-1680-400c-b01b-544ac8bf30e7">
</p>
<p>
Click "add New Departments, and create your departments. 
</p>
<p>
<img width="628" alt="ost add new department" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/74746a87-51bd-4d98-b795-4ffaf0b6f518">
</p>
<p>
<img width="626" alt="ost create system admin dept" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/e7d02d82-90af-4642-81a1-aaea1d50b9ee">
</p>
<p>
Now that the departments are made, we will start making teams. Click on the Teams Tab.
</p>
<p>
<img width="623" alt="OST Create teams" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/e27e594b-4e7b-4376-bfb9-64690ff7ea34">
</p>
<p>
Select "Add New Teams"
</p>
<p>
<img width="634" alt="ost add team" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/6d9c332f-3577-4d39-be0b-eefb10f027f6">
</p>
<p>
Once a team has been created, you want to delegate members to the team. Select Members and choose from the agents already created.
</p>
<p>

  **Side note, as the admin and creator of this instance of osTicket, you are the only user so far**
</p>
<p>
We then want to go to the settings tab, and enable Registration for user logins in order to create tickets.  
</p>
<p>
<img width="482" alt="ost settings" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/18b18fe1-1d48-4473-bb95-bf39f175b575">
</p>
<p>
<img width="617" alt="OST settings reg enable" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/6a9bbb0f-348b-464b-94dd-356b536aaaca">
</p>
<p>
We can now create agents. Click on the Agents tab. Select "Add New Agent". Create Your Agents, make sure to set password as well as change their status and settings.
</p>
<p>
<img width="628" alt="ost add new agent" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/c70915e1-03f3-4703-b1d8-7fd4c37575d4">
</p>
<p>

<img width="614" alt="Screenshot 2024-01-25 112504" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/365e5dc8-c6a7-480a-b03d-b424daf61541">
</p>
<p>
<img width="595" alt="Screenshot 2024-01-25 113000" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/d0fe9374-f9c8-4d4f-9094-2c62ed637e82">

</p>
<p>
Moving on, we now create our SLA teirs. Click the Manage Tab.
</p>
<p>
<img width="595" alt="ost MANAGE" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/b19742c6-65f6-4d01-b75b-5d61db9cd6e4">

</p>
<p>
Select the SLA tab.
</p>
<p>
<img width="599" alt="OST SLA TAB" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/db36783c-2239-4389-9edd-734357c7085b">

</p>
<p>
Select "Add New SLA Plan" And create your SLA teirs.
</p>
<p>
<img width="603" alt="ost ADD NEW SLA PLAN" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/3fdded2f-aa0f-426e-ada9-7be664227560">
</p>
<p>
<img width="578" alt="Screenshot 2024-01-25 113636" src="https://github.com/nickbannenberg/post-install-config/assets/157658949/afbc87b8-567d-4601-a6ea-4c48bbf0eae9">
</p>
<p>
The final step is to create help topics. From the manage tab, click Help Topics. 
</p>
<p>
<img width="437" alt="ost click help topic" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/19af17c9-028a-46ad-b782-2beac74c1e1d">

</p>
<p>
Select "Add Help Topics" .
</p>
<p>
<img width="605" alt="ost add new help topic" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/c675ea2d-bb7a-46f7-a096-23ef675a7b11">

</p>
<p>
Create your help topics. A quick google search can give you common help topic suggestions.
</p>
<p>
<img width="604" alt="ost help topics" src="https://github.com/ikcromer30/postinstall-config/assets/157658949/6c1cd128-1eab-40a5-87d6-2a262d5cddc4">
</p>
<p>

You have now successfully set up your osTicket System for Users, End Users , and Admins.
