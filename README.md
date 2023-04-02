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

<h3>Step 1: Open osTicket and Log In

  - Log in to osTicket using the credentials you made during the installation tutorial
  - Make sure you are in the Admin panel (check the top-right of the screen to see which panel you are in)
	- If it says "Agent," you are in the Admin panel
- Select the Agent tab > Roles > Add New Role
	- Name: Supreme Admin
	- Select Permissions tab and check every box under the "Tickets," "Tasks," and "Knowledgebase" sections
- Select Add Role

<p>
<img src="https://i.imgur.com/BzkPqCs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  <h3>Step 2: Configure Departments</h3>

- Ensure you are still in the Admin panel
- Select the Agent tab > Departments > Add New Department 
- Name: System Administrators
- Select Create Department 

<p>
<img src="https://i.imgur.com/o3kwRqw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 3: Configure Teams
</h3>

- Select the Agent tab > Teams > Add New Team
	- Name: Level II Support 
- Go to the Members tab and select yourself in "Select Agent" dropdown menu
- Select Create Team	
	
<p>
<img src="https://i.imgur.com/Tm9JdI8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


<h3>Step 4: Allow Anyone to Create Tickets</h3>

- Select Settings > User Settings
- Make sure the following box is unchecked: 
- Registration Required: Require registration and login to create tickets 	

<p>
<img src="https://i.imgur.com/itXbB6R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

h3>Step 5: Configure Agents</h3>

- Select the Agent tab > Add New Agents
	- Name: Sam Doe
	- Email : sam.doe(@)osticket.com
	- Username: sam.doe
	- Click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"
		- Set your password to anything you like
		- Uncheck the box that says "Require Password Change at Next Login"
		- Se- Select the Access tab 
	- Under Primary Department: 
		- Select the Department dropdown menu > System Administrators
		- Select the Role dropdown menu > Supreme Admin
	- Extended Accesss 
		- Select Department > Support > Add > Supreme Admin
- Select Team tab
	- Select Team dropdown menu > Level II Support
	 - Select Add > Select Create	
	 -  Create another agent and replace "Sam with John".
	- Follow the same steps as above, except make some changes to the Primary Department
		- Select the Department dropdown menu > Support
		- Select the Role dropdown menu > View Only
	- Extended Accesss next Select Department > Support > Save Changes
		

<p>
<img src="https://i.imgur.com/vPPYraV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 6: Configure Users
</h3>

<p align="center">
<img src="https://i.imgur.com/UUqCK1d.png" height="80%" width="80%" alt="Azure Free Account"/>		
	
- Select the Users tab to create a user
	- Email Address: Karen(@)osticket.com
	- Full Name: Karen Karen
	- Select Add User
	-	
 - Select the User tab again to create another user
	- Email Address: Ken(@)osticket.com
	- Full Name: Ken Ken
	- Select Add User

<p>
<img src="https://i.imgur.com/f4WiGoU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/inNvYa8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/CwpcELn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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


