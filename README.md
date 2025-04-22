# Ticket-lifecycle
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


![image](https://github.com/user-attachments/assets/e13cd765-7110-40b0-a6a2-e04fd9639a62)![image](https://github.com/user-attachments/assets/c84139c4-a41e-4d47-8478-8be044e6833a)
![image](https://github.com/user-attachments/assets/20f53e9f-0326-4bba-94f0-b9b898fcea79)![image](https://github.com/user-attachments/assets/95f2674a-b2da-4c61-8d80-0d97f2489c69)




1. Log In and Get Familiar

- Admin/Analyst Login: http://localhost/osTicket/scp/login.php

- End-User Portal: http://localhost/osTicket

2. Admin Tasks

- Make SysAdmins a Top-Level Department

- Go into the SysAdmins department settings and convert it into a top-level one (no parent)

- Delete Maintenance Department

- Completely remove the Maintenance department (don’t archive it—delete it for good)

3. End-User Action – Submit a Ticket

- Log in as an end-user and create a ticket

- Example Issue: “Entire mobile/online banking system is down.”

4. Agent Action (John – Help Desk)

- After the user submits the ticket, log in as john (Help Desk Agent)

- Take a look at the ticket and note the following details:

- Priority

- Department

- SLA (Service Level Agreement)

- Assigned To

- Set the ticket properties:

- Priority: Sev-A (1 hour response, 24/7)

- Department: Online Banking Department

5. Try Re-Accessing the Ticket (Still as John)

- After setting those properties, try to go back into the ticket and see if you can view or make changes to it again

6. Resolve the Ticket (as Jane)

- Log in as jane, pick up the ticket, and fully resolve it—close it out properly

