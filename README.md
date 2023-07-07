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
- Ticket Creating Permissions
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="80%" height="80%" alt="Agents   roles update roles" src="https://github.com/davidrosa01/post-install-config/assets/119774564/f9bf42e4-5f3b-440a-bdd9-a19daeb4f4ea">
</p>
<p>

1. Configure Roles
    - Access the Admin Panel:
      - Log in to the ticketing system with your admin credentials
      - Locate and access the Admin Panel section of the system
    - Navigate to Agents and Roles:
        - In the Admin Panel, find the "Agents" section
        - Look for the option or tab labeled "Roles"
    - Configure a Role that your organization needs:
        - Within the Roles section, create a new role
        - Name the role what you desire
    - Adjust Role Permissions:
       - Review the available permissions or privileges that can be assigned to the role you created
       - Enable or disable specific permissions based on the desired level of access and functionality for the role
    - Save and Apply Changes

</p>

<br />

<p>
<img width="80%" height="80%" alt="Add new departmentss" src="https://github.com/davidrosa01/post-install-config/assets/119774564/ac157577-83a4-4fb9-95f3-de6242c2481b">
</p>

<p>

2. Configure Departments
    - Navigate to Agents and Departments:
       - Within the Admin Panel, find the "Agents" section
       - Look for the option or tab labeled "Departments"
    - Configure the Department:
       - In the Departments section, create a new department with a name
    - Adjust Department Members:
       - Assign or remove agents from the department based on their roles and responsibilities
    - Save and Apply Changes
      
</p>

<br />

<p>
<img width="80%" height="80%" alt="agents   add new team" src="https://github.com/davidrosa01/post-install-config/assets/119774564/bfff16fc-9734-44f3-b209-1d9a74553770">
</p>
<p>

3. Configure Teams
    - Navigate to Agents and Teams:
       - Within the Admin Panel, find the "Agents" section
       - Look for the option or tab labeled "Teams"
    - Configure the Team:
       - In the Teams section, search for the existing teams or create new teams if necessary
       - Assign or remove agents from the team based on their roles and responsibilities
    - Save and Apply Changes
   
</p>

<br />

<p>
<img width="80%" height="80%" alt="registration required" src="https://github.com/davidrosa01/post-install-config/assets/119774564/7db02b80-d407-4d66-b3da-84de3c9b8d46">
</p>

<p>

4. Allow anyone to create tickets:
    - Navigate to Settings:
       - Within the Admin Panel, find the "Settings"
       - Look for the option or tab labeled "User Settings"
    - Adjust Registration Requirement:
       - In the User Settings section, locate the "Registration Required" setting and uncheck the box.
       - This will remove the requirement for users to register and login before creating tickets.
      - Save and Apply Changes
</p>
<br />

<p>
<img width="80%" height="80%"  alt="Add New Agent" src="https://github.com/davidrosa01/post-install-config/assets/119774564/250705f8-4e18-4068-930c-184ae0bc93a4">
</p>
<p>

5. Configure Agents (workers)
    - Navigate to Agents:
       - Within the Admin Panel, find the "Agents" section
    - Add New Agent:
       - Click on the "Add New Agent"
    - Fill in Agent Details:
       - Enter the necessary details for the new agent, such as their name, email address, and username.
       - Optionally, set a password for the agent or configure a password reset process.
    - Assign Roles and Permissions:
       - Specify the role or roles for the new agent
       - Assign the appropriate permissions or access levels based on the agent's responsibilities and requirements
    - Save and Apply Changes

</p>
<br />

<p>
<img width="80%" height="80%"  alt="Users" src="https://github.com/davidrosa01/post-install-config/assets/119774564/9af511f7-9e7f-40d3-ba00-a066ceb1f44f">
</p>
<p>

6. Configure Users (customers)
    - Access the Agent Panel:
       - Log in to the ticketing system using your agent credentials
    - Navigate to Users:
       - Within the Agent Panel, find the "Users" section
       - Look for the option or tab labeled "User Directory"
    - Add New User:
       - In the User Directory section, locate the option to add a new user
       - Click on the "Add User" to start adding a new user
    - Fill in User Details:
       - Enter the necessary details for the new user, such as their name, email address and phone number
    - Save and Apply Changes

</p>
<br />

<p>
<img width="80%" height="80%" alt="sla " src="https://github.com/davidrosa01/post-install-config/assets/119774564/b3de97c7-e50d-4334-b72d-c0f3bf835115">
</p>
<p>

7. Configure SLA:
    - Locate and access the Admin Panel section of the system
    - Navigate to SLA Management:
       - Within the Admin Panel, find the "Manage" section
       - Look for the option or tab labeled "SLA" or "Service Level Agreements"
    - Configure SLAs:
       - In the SLA Management section, you will see a list of existing SLAs or the option to create new ones
       - Review the available SLAs and their settings
    - Create or Edit SLAs:
      - If you need to create a new SLA, click on the "Add New SLA Plan" button to start the creation process.
      - If you want to edit an existing SLA, select the desired SLA from the list
    - Set SLA Parameters:
      - Within the SLA creation or editing interface, you can define various parameters, such as response time, resolution time, priority levels, escalation rules, and notifications
      - Customize these parameters based on your organization's service level targets and requirements
    - Save and Apply Changes

</p>
<br />

<p>
<img width="80%" height="80%"  alt="help topic" src="https://github.com/davidrosa01/post-install-config/assets/119774564/bb51484a-03dd-4fce-8f4e-7b654892a238">
</p>
<p>

8. Configure Help Topics:
    - Navigate to Help Topics Management:
       - Within the Admin Panel, find the "Manage" section
       - Look for the option or tab labeled "Help Topics"
    - Manage Help Topics:
       - In the Help Topics Management section, you will see a list of existing help topics or the option to create new ones
       - Review the available help topics and their settings
    - Create a New Help Topic:
       - To create a new help topic, click on the "Add New Help Topic" button to start the creation process.
       - Provide a title and description for the help topic
    - Edit Existing Help Topics:
      - If you want to edit an existing help topic, select the desired topic from the list
    - Customize Help Topic Details:
        - Within the help topic creation or editing interface, you can customize the details such as the title, description, content, tags, category, and visibility settings.
        - Add relevant information and format the content as needed
    - Save and Apply Changes
      
</p>
<br />
