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

1. Intake (Creating and Logging the Issue)

<p>
  
![image](https://github.com/user-attachments/assets/601a944e-1584-4fad-9fce-8fe29627cd0e)

![image](https://github.com/user-attachments/assets/f58f01ba-869a-4f89-bac8-40c091ce2ac4)

</p>

An end-user (customer or employee) reports an issue by submitting a ticket.
The ticket includes a description of the problem, such as:
“The entire mobile/online banking system is down.”
“CFO’s laptop will no longer turn on.”
The system logs important details: timestamp, requester, initial department, and priority.
Purpose:

Ensures that all issues are formally documented rather than handled informally.
Allows IT teams to track, prioritize, and distribute workload efficiently.

---

</p>
2. Assignment and Communication
<br />
<p>
  
![image](https://github.com/user-attachments/assets/3480e424-540f-4635-af8a-3f3d2917cee5)

</p>

The Help Desk Agent (John) reviews the ticket’s properties:
Priority (How urgent is this?)
Department (Who should handle it?)
SLA (Service Level Agreement) (How quickly does it need to be resolved?)
Assigned To (Who is responsible?)
Adjustments are made based on the severity of the issue:
Example: A critical outage (Sev-A) is reassigned to the Online Banking Department and must be resolved within 1 hour (24/7 SLA).

![image](https://github.com/user-attachments/assets/35db62a1-10a7-4b3e-9ff5-b0f9e9794228)

If necessary, the Admin may intervene to reassign tickets or escalate visibility.
Purpose:

Ensures the right team is working on the right issue.
Uses SLAs to enforce timely resolution based on urgency.
Email notifications keep users updated whenever changes occur.
<p>
  
![image](https://github.com/user-attachments/assets/a3417a35-fd9f-4a9b-89c2-36e68763225b)

---

3. Working the Issue
<p>
  
![image](https://github.com/user-attachments/assets/e6edf668-7ae8-43c4-9e84-18056b61e9c2)

</p>

![image](https://github.com/user-attachments/assets/3bb7963f-e662-4382-aee0-9940d7461b48)

The assigned agent begins troubleshooting:
Jane works on the Online Banking outage ticket.
John fixes the CFO’s laptop issue.
Agents follow structured steps:
Reproduce the issue (confirm the problem).
Investigate and diagnose (analyze logs, test fixes).

![image](https://github.com/user-attachments/assets/07fb64ed-1464-4f9c-a105-4ef1261e2f78)

Communicate with the end-user (provide updates).
As work progresses, ticket updates generate automatic emails, allowing users to track status and provide feedback.
Purpose:

Ensures a structured approach to troubleshooting.
Encourages proper documentation of actions taken.
Keeps the end-user informed without requiring follow-ups.
<p>

---

4. Resolution and Closing the Ticket
<p>
  
![image](https://github.com/user-attachments/assets/2357936b-cac7-476f-aefc-e126a03e1185)

</p>
<p>

Once the problem is resolved, the agent marks the ticket as completed and documents the solution.
The end-user is notified, confirming the issue has been fixed.
If additional work is needed, the ticket can be reopened.

Final steps:
Deleting unnecessary departments 
Granting admin permissions to access restricted tickets.
Reviewing the system to ensure everything is functioning properly.

Purpose:

Provides a clear record of completed work (useful for reports and future troubleshooting).
Ensures that only authorized users can change resolved tickets (prevents tampering).
Reinforces the importance of ticketing metrics in IT support.

</p>
<br />

---
