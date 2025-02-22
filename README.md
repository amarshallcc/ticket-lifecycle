<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
What Happens?

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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
What Happens?

The Help Desk Agent (John) reviews the ticket’s properties:
Priority (How urgent is this?)
Department (Who should handle it?)
SLA (Service Level Agreement) (How quickly does it need to be resolved?)
Assigned To (Who is responsible?)
Adjustments are made based on the severity of the issue:
Example: A critical outage (Sev-A) is reassigned to the Online Banking Department and must be resolved within 1 hour (24/7 SLA).
If necessary, the Admin may intervene to reassign tickets or escalate visibility.
Purpose:

Ensures the right team is working on the right issue.
Uses SLAs to enforce timely resolution based on urgency.
Email notifications keep users updated whenever changes occur.
<p>

---

3. Working the Issue
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
What Happens?

The assigned agent begins troubleshooting:
Jane works on the Online Banking outage ticket.
John fixes the CFO’s laptop issue.
Agents follow structured steps:
Reproduce the issue (confirm the problem).
Investigate and diagnose (analyze logs, test fixes).
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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
What Happens?

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
