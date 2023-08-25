<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
Intake:
<p>
  
![image](https://github.com/michaelpeters2/ticket-lifecycle/assets/141062110/ec121d7e-7164-4b0e-9138-c9224d9f696f)
</p>
<p>
Enter http://localhost/osTicket/ into a new browser and begin to create your first three tickets.

  - Email: Karen@osticket.com
  - Name: Karen Karen
  - Help Topic: Business Critical Outage 
  - Fill in Summary and Details

Create new ticket
  - Email: Ken@osticket.com
  - Name: Ken Ken
  - Help Topic: Personal Computer Issues
  - Fill in Summary and Details

Create new ticket
  - Email: Karen@osticket.com
  - Name: Karen Karen
  - Help Topic: General Inquiry
  - Fill in Summary and Details
</p>
<br />
Log out of osTicket and log back in as a Help Desk Professional (Jane.Doe)
  - Username: jane.doe
  - Password: Password1

Assignment and Communication
<p>
  
![image](https://github.com/michaelpeters2/ticket-lifecycle/assets/141062110/f20a2780-f26a-4d3b-8348-0eb1c87d08f0)

</p>
<p>
Begin to update Karen's first ticket submission as Jane the admin.
  
  - Update Priority: Emergency
  - Details: Business Impacting Event
  - Assign ticket to yourself (Jane).
  - Update Department: System Administrators
  - Update SLA Plan: Sev-A -> Business Impacting Event
</p>

  ![image](https://github.com/michaelpeters2/ticket-lifecycle/assets/141062110/2312d758-6c53-4be3-89cd-34ec64944214)

</p>
Send your response to let Karen know you are collaborating with other IT members to fix the issue.

Then, update Karen letting her know you have resolved the issue.

![image](https://github.com/michaelpeters2/ticket-lifecycle/assets/141062110/ada7f38d-0432-4001-95d3-890a9ca9363a)

</p>
<br />
Moving on to Ken's ticket:

  - Priority: High
  - SLA Plan: Sev-B
  - Assigned To: John Doe
  - Respond to Ken

![image](https://github.com/michaelpeters2/ticket-lifecycle/assets/141062110/da85b873-d24f-4fa4-876f-8fb2c90ec732)

