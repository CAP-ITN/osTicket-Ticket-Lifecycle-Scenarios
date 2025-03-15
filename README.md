# osTicket-Ticket-Lifecycle-Scenarios
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket-Lifecycle</h1> An insight on the typical lifecycle of tickets.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Links/Notes</h2>

SLA Format
Sev-A (1 hour, Schedule: 24/7)
Sev-B (4 hours, Schedule: 24/7)
Sev-C (8 hours, Business Hours)


Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

NOTE: These links above will not work unless you are within the network environment created.


<h2>Ticket LifeCycle 1</h2>


![osTicketLIfeCycle3](https://github.com/user-attachments/assets/78e1c5aa-9dac-49a3-b3eb-432c1b5414ad)

<p>
</p>
<p>
The end-user (Billy.Ray) submits a critical ticket reporting that the entire mobile and online banking system is down. Help Desk Agent Rick reviews the ticket, noting that priority, department, SLA, and assignment are initially unassigned. Rick updates the ticket to Sev-A priority (1-hour response, 24/7 support), assigns it to the Online Banking Department as he does not have permissions for this critical outage.
<br />

<p>

![osTicketLifeCycle5](https://github.com/user-attachments/assets/316d6e9a-f9ee-4649-8cf7-9c2375642516)

</p>
<p>
After investigating the issue, (Online Banking Department) Bob determined that a recent update to the banking system caused the outage. To resolve the issue, Bob rolled back the update, which immediately restored online and mobile banking services. The software vendor was notified about the faulty update, and with systems back to normal, the incident was marked as resolved, ensuring uninterrupted service for customers.
</p>
<br />


<h2>Ticket LifeCycle 2</h2>
<p>

![osTicketLifeCycle6](https://github.com/user-attachments/assets/036afdc2-557f-4339-b3d2-b379bd960af0)

</p>
<p>
An end-user (Fernando) submits a ticket requesting an Adobe upgrade for the Accounting Department, as the current version is broken. Help Desk Agent Rick reviews the ticket, notes that priority, department, SLA, and assignment are unassigned, and then updates it to Sev-B under the Support department. After investigating, Rick discovered that only two employees in the Accounting Department were affected, rather than the entire department. Based on this, he downgraded the SLA to Sev-C to reflect the lower urgency. He then performed a computer reset on both affected machines, which successfully restored access to Adobe, resolving the issue before closing the ticket.
</p>
<br />

<h2>Ticket LifeCycle 3</h2>
<p>
  
![osTicketLifeCycle7](https://github.com/user-attachments/assets/f6fd625f-cdb8-4f2c-9fe4-6f081f662eec)

</p>
<p>
An end-user (Billy Ray) submits a ticket reporting that the CFO’s laptop will not turn on. Help Desk Agent Rick reviews the ticket, assigns it a Sev-B priority under the Support department, and begins troubleshooting. After diagnosing a faulty power adapter, Rick replaces it with a new one, verifies the laptop is functioning properly, and closes the ticket.
</p>
<br />
