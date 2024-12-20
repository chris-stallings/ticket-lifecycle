<p align="center">
<img width="699" alt="Screenshot 2024-11-07 at 11 36 30 AM" src="https://github.com/user-attachments/assets/fbae847c-af51-430e-988c-eb6324dac850">
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2> -->

<!-- - ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com) -->

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
<p><a href="http://localhost/osTicket/">http://localhost/osTicket</a> Admin/Analyst login page</p>
<p><a href="http://localhost/osTicket/">http://localhost/osTicket/</a> End user osTicket page</p>
<br />

<p>
<img width="1710" alt="Screenshot 2024-11-11 at 6 24 25 PM" src="https://github.com/user-attachments/assets/110b91ab-33fa-4879-bf72-dea2c733c565">

</p>
<p>
First we will go to the end user home page. From here we will create a new ticket. 
</p>
<br />

<p>
<img width="1710" alt="Screenshot 2024-11-14 at 5 01 59 PM" src="https://github.com/user-attachments/assets/77960ccd-609b-496e-934b-5d899fb475e8">
</p>
<p>
Create a help ticket with the following information:</p>
</p>

- E-Mail Address: karen@email.com
- Full Name: Karen
- Help Topic: Report a Problem
- Issue Summary: My employees are reporting that users are no longer able to access their online banking portal. The ones who are occasionally access it, cannot log in. 
<br />

<p>
<img width="1710" alt="Screenshot 2024-11-14 at 5 15 33 PM" src="https://github.com/user-attachments/assets/b6cdeaf8-e026-4f54-9deb-f54e4ea0318d">
</p>
<p>
Next log into the administrator page using the agent accound John
</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-15 at 5 15 33 PM" src="https://github.com/user-attachments/assets/e364e44f-d45b-46c4-bc98-9eb22ff5a540">
</p>
<p>Once logged in as John. Click on the ticket we made as user Karen.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-15 at 5 18 48 PM" src="https://github.com/user-attachments/assets/ab389ad7-3bf7-45b5-bd9d-3156b3b7a206">
</p>
<p>From this screen we will observe a few key details of the ticket. Take note of the following:
</p>

- Priority
- Department
- SLA
- Assigned To
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 3 41 31 PM" src="https://github.com/user-attachments/assets/524297bc-de90-40f5-a9c0-58c651ac0bf9">
</p>

- Set the SLA Plan to Sev-A
- Assign the ticket to the Online Banking Team
- Change Help Topic to Report A Problem/Business Critical Issue


<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 3 48 29 PM" src="https://github.com/user-attachments/assets/af19b14f-061f-4c57-8fea-9457c5367567">
</p>
<p>Now work the ticket as the agent Jane. </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 3 51 04 PM" src="https://github.com/user-attachments/assets/6255c687-1c04-4009-9910-47e4ab23f557">
</p>
<p>Assign the ticket to Jane.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 3 54 49 PM" src="https://github.com/user-attachments/assets/219db27a-1af1-45ea-b284-f08173734db9">
</p>
<p>Post a commentof what you plan to do to work the ticket. "I believe the problem is the recent update. Update was tested sufficiently however I will look into it and roll back if necessary."</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 3 59 45 PM" src="https://github.com/user-attachments/assets/a7c5edb4-1527-4a93-8c6e-c49900187698">
</p>
<p>After "testing the update" the update was the problem. Submit another note explaining this. </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 02 33 PM" src="https://github.com/user-attachments/assets/bcc1ebde-8495-4b31-809a-29adcaaf110b">
</p>
<p>Now that the problem is resolved close the ticket. </p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 10 39 PM" src="https://github.com/user-attachments/assets/21c22bc2-00a5-462c-8ba1-bb7793105399">
</p>
<p>Create a new help ticket. This time we will use the end user Ken. Create the ticket with the following information.</p>

- Help Topic: General Inquiry/Other
- accounting department needs adobe upgrade, broken
- It looks like many people in the accounting department can't use their adobe software.

<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 19 51 PM" src="https://github.com/user-attachments/assets/b293f844-42d6-4ece-b93c-9e566e60f473">
</p>
<p>Log back in as agent John. Observe the ticket we just created.</p>

- Set SLA to Sev-C
- Assign ticket to John.

<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 28 13 PM" src="https://github.com/user-attachments/assets/9e63e071-aeef-4b78-b99e-396095891b32">
</p>
<p>Observe that the updates were made to the ticket. Then proceed to work the ticket to completion as John.</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 35 30 PM" src="https://github.com/user-attachments/assets/43a10aec-0061-44a1-98a2-c0002c463f83">

</p>
<p>Add the note : "Customer states only 2 people in accounting department unable to open and use adobe reader. Customer testing restart and will call back after lunch."</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 38 06 PM" src="https://github.com/user-attachments/assets/7c566aa7-e55a-4a49-b55c-87758ae17a78">
</p>
<p>Once customer calls back add the note: "Customer states restart fixed issue. Closing out ticket."</p>
<br />
<p>
  <img width="1710" alt="Screenshot 2024-11-16 at 4 41 17 PM" src="https://github.com/user-attachments/assets/8bccf182-f38f-4f6d-a80e-3edf445810cf">
</p>
<p>Close ticket as resolved.</p>
<br />
