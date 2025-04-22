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


![image](https://github.com/user-attachments/assets/069933d6-d1a0-494a-b6a7-6ec3e7c82222)![image](https://github.com/user-attachments/assets/b59fb9ca-91a5-4198-89a3-2994234d85dc)
![image](https://github.com/user-attachments/assets/0aecb1a4-dd7b-44ae-9b77-ebd58cfd13db)![image](https://github.com/user-attachments/assets/fbfdf2ca-20b5-4ac6-af04-21425248726f)


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


![image](https://github.com/user-attachments/assets/fcb084d9-2f9a-4b3d-830b-1beba0806d8d)![image](https://github.com/user-attachments/assets/c65f63e0-dec3-4710-914a-d5552fdcedfe)
![image](https://github.com/user-attachments/assets/87a1feaa-9a62-4f4d-985f-415d3a39123d)![image](https://github.com/user-attachments/assets/f1b62017-3f66-457d-8d90-cefaca356173)

Ticket 2: Adobe Upgrade for Accounting Department
End-User Action

Reported that Adobe in the Accounting Department is broken and needs an upgrade.

Help Desk Agent (John)

Reviewed the ticket and saw the following:

Priority: Sev-B

Department: Support

SLA: 4 hours, 24/7

Ticket Progress

John handled the upgrade and got Adobe back up and running.

Resolution

Issue was resolved by John, and the ticket was successfully closed.


![image](https://github.com/user-attachments/assets/745d60de-69b0-451b-8668-60b925db817e)![image](https://github.com/user-attachments/assets/5896d3b5-105b-49a9-b4d2-38af5e0c7c7a)
![image](https://github.com/user-attachments/assets/eb1087e5-243e-4ae4-ac2a-5cf8715bcfb6)![image](https://github.com/user-attachments/assets/eb4b293b-3fc4-4ae8-a08b-2e8032f84fed)

Ticket 3: CFO’s Laptop Won’t Turn On
End-User Action

Reported that the CFO’s laptop isn’t powering on.

Help Desk Agent (John)

Checked the ticket and noted:

Priority: Sev-B

Department: Support

SLA: 4 hours, 24/7

Ticket Progress

John troubleshot the issue and got the laptop working again.

Resolution

Problem was fully resolved by John and the ticket was closed.

