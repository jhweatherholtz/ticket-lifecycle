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


THERE WILL BE TWO SEPERATE PAGES; ADMIN PANEL, USER PAGE.

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

MAKE SURE TO DELETE MAINTENANCE DEPARTMENT AS WELL


<p>

![Screenshot 2024-11-14 121815](https://github.com/user-attachments/assets/b05d3c04-19e2-4547-83d6-bc254c978d59)

</p>
<p>

As an end-user, create the following ticket
entire mobile/online banking system is down

</p>
<br />

<p>

![Screenshot 2024-11-14 122539](https://github.com/user-attachments/assets/66cdbcdd-d575-4c8c-9c7b-ca94b4ab927c)

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket

Sev-A (1 hour, 24/7)

Online Banking Department

Attempt to observe the ticket again as “john”. Can you view or change?

Work the ticket to completion as jane
</p>
<br />

<p>

![Screenshot 2024-11-14 122806](https://github.com/user-attachments/assets/e32d4773-8d5b-45f5-8761-f06ddf9d506e)

</p>
<p>

As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

</p>
<br />
</p>
<br />

<p>

![Screenshot 2024-11-14 122939](https://github.com/user-attachments/assets/e5c6cb79-20f7-4993-8066-c06038fbcced)

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties

Priority

Department
	
SLA
	
Assigned To

Set Properties to the ticket

Sev-B (4 hours, 24/7)

Support

Work the ticket to completion as john

</p>
<br />

<p>

![Screenshot 2024-11-14 123201](https://github.com/user-attachments/assets/28027bc4-41c9-40f4-97da-8549bcceae8f)

</p>
<p>

  As an end-user, create the following ticket
CFO’s laptop will no longer turn on

</p>
<br />
</p>
<br />

<p>

![Screenshot 2024-11-14 123318](https://github.com/user-attachments/assets/789b35b8-8a13-4347-8528-a74d6bfd70a9)

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties
	
 Priority
	
 Department
	
 SLA
	
 Assigned To

Set Properties to the ticket

Sev-B (4 hours, 24/7)

Support

</p>
<br />

ADDITIONAL THINGS THAT CAN BE OBSERVED:

Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
Switch to admin panel and assign yourself View-access to Sys Admins
Switch to agent panel and observe the escalated ticket
Observe that you can no longer make changes to it

Solve all of the tickets
Explain in most ticketing systems (probably this one too) there is an email capability so every time you update the ticket, the user gets a copy and they can respond

Explain ticket intake IRL:
Sometimes tickets get created via phone, chat app, email, web form, or maybe even you run into someone in your hall or they roll up on you at your desk.
A lot of the time people will randomize you and try to get you to fix stuff on the spot. It’s fine to fix things on the spot, but generally speaking, you want to create tickets for EVERYTHING you do. (metrics are important)

Finishing up and additional practice
Obviously there is much more to this product that covered here
Encourage the use and exploration of the email feature
Do this lab a few more times, enough times where you’re able to implement it with this simple checklist. This will build your intuition.
Talk about Technical skill pillar
Re-touch on technical ability and re-doing the lab several
