# Help Desk Ticketing System Project
![Image](https://github.com/user-attachments/assets/b3e90221-0ffc-4739-a381-6021e2aace5f)

Overview:
This project simulates a real-world IT Help Desk environment using ServiceNow/Jira, showcasing ticket lifecycle management, troubleshooting, and communication skills.

Key Components:
- Created and resolved 15+ realistic tickets.
- Issues included login failures, VPN issues, DNS problems, Outlook failures, and hardware malfunctions.
- Documented each ticket with steps, findings, root cause, and resolution.
- Demonstrated customer service communication and SLA-aware responses.
  
Skills Demonstrated:
- Ticketing systems (ServiceNow)
- Troubleshooting Windows/macOS issues - Customer service & communication
- Documentation and escalation workflow


# Process of demo of Help Desk Ticketing System


<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/be745039-ddda-4b3f-bb9b-1a98f329ba7b" />

Here we see me logged in to  the ServiceNow  ticketing system where I have already created 15 enteries with different issues assigned to me as the Help Desk Tech now lets create 5 more tickets.



<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4b15f0d8-376a-49e4-b353-685c80907af4" />
First things first , is you want to look over to the top right corner of the page and find the New button that will direct you to a the Indcident new record page to create a new page.


So on this page you will fill out the incident new record and we will go though this step by step.

1.Fill out caller field with name of caller.

2.Choose the category that the caller was calling about.

3.Fill Short description of what the issue that the caller was calling in about.

4.Fill description section with detailed decription of what the issue is.

5.Choose the the channel which is just how they got in contact with the  IT team

6.Choose the impact level and Urgenery of the issues to create the Priority of the Ticket.

7.Final choose the IT Tech that will be assigned to it which is me of course.


<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/404542ec-3fe9-4e8b-906a-f47cdd76d3dd" />

 8. Submit the ticket and it will load onto the ticket dashboard and as you see below the ticket has been add to  the indicents page.

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/70fa8fae-0d1e-4054-b041-fc8f90255024" />


# Now let's Resolve some tickets (Documenting troubleshooting steps, findings, resolutions, and escalation paths following ITIL standards.)


Ticket 1: Password Reset Request

Process and workflow

1️⃣ Intake & Identity Verification

Open incident in ServiceNow.

Verify user identity (Employee ID, Manager verification, or MFA confirmation).

Confirm username and domain.

2️⃣ Investigation

Check Active Directory (AD) account status.

Confirm account is not locked or disabled.

Review password policy requirements.

3️⃣ Resolution

Reset password in Active Directory.

Select "User must change password at next logon".

Provide temporary password securely.

4️⃣ Validation

User logs in successfully.

Confirm access to email, VPN, and internal systems.

✅ Closure Notes

Identity verified. Password reset in AD. User successfully authenticated and confirmed access. Ticket resolved.



 Ticket 2: New User Onboarding

Process and workflow

1️⃣ Intake

Review onboarding request form.

Confirm manager approval.

Verify department and job role.

2️⃣ Account Creation

Create AD user account.

Assign naming convention.

Generate corporate email address.

Add to department security groups.

3️⃣ Provisioning

Assign Microsoft 365 license.

Enable mailbox.

Add to distribution lists.

Configure shared drive access.

4️⃣ Device Setup

Image laptop.

Join to domain.

Apply security policies.

Assign asset tag.

5️⃣ Validation

Send welcome email with login instructions.

Confirm successful first login.

✅ Closure Notes

AD account created. M365 license assigned. Security groups applied. Device configured and issued. User onboarded successfully.



Ticket 3: Printer Not Responding

Process and workflow
1️⃣ Intake

Confirm printer name and location.

Determine if issue affects one user or multiple.

2️⃣ Investigation

Ping printer IP address.

Check print queue on print server.

Verify Print Spooler service status.

3️⃣ Troubleshooting

Restart Print Spooler service.

Clear stuck print jobs.

Verify network connection.

Reinstall printer drivers if necessary.

4️⃣ Resolution

Re-add printer via IP or server path.

Print test page.

✅ Closure Notes

Cleared print queue and restarted spooler service. Printer reinstalled. Test page printed successfully.

Ticket 4: Outlook Not Syncing (Desktop)

Process and workflow

1️⃣ Intake

Confirm Outlook version and OS.

Identify sync issue (missing emails, delayed send/receive).

2️⃣ Investigation

Verify internet connectivity.

Check Microsoft 365 service health.

Launch Outlook in Safe Mode.

3️⃣ Troubleshooting

Disable add-ins.

Clear OST file.

Recreate Outlook profile.

4️⃣ Resolution

Reauthenticate account.

Rebuild mail profile.

5️⃣ Validation

Send/receive test email.

Confirm folders sync properly.

✅ Closure Notes 

Outlook profile rebuilt. Mailbox re-synced successfully. Test email confirmed. Issue resolved.

Ticket 5: Wi-Fi Connection Dropping

Category: Network Connectivity
Priority: Medium–High

Process and workflow

1️⃣ Intake

Confirm device type and physical location.

Identify SSID and frequency of disconnects.

2️⃣ Investigation

Run ipconfig /all

Check signal strength.

Verify DHCP lease.

3️⃣ Troubleshooting

Forget and reconnect to network.

Update wireless drivers.

Disable power-saving mode on adapter.

4️⃣ Network Validation

Check access point status.

Verify no network congestion.

5️⃣ Resolution

Renew IP lease.

Reassign access point if needed.

✅ Closure Notes 

Wireless driver updated. DHCP lease renewed. Stable connection confirmed after monitoring.

Ticket 6: Account Locked Out


Process and workflow 
1️⃣ Intake

Confirm username and lockout time.

2️⃣ Investigation

Check AD lockout status.

Review failed login attempts.

Identify login source (VPN, mobile device, mapped drive).

3️⃣ Troubleshooting

Confirm recent password changes.

Remove cached credentials.

4️⃣ Resolution

Unlock account in AD.

Reset password if required.

5️⃣ Prevention

Update saved credentials on mobile/email apps.

✅ Closure Notes 

Account unlocked. Root cause identified as outdated mobile credentials. User updated saved password. Issue resolved.




Ticket 7: Shared Folder Access Denied

Process and workflow
1️⃣ Intake

Confirm shared folder path.

Capture exact error message.

2️⃣ Investigation

Check AD security group membership.

Review NTFS and Share permissions.

3️⃣ Troubleshooting

Run gpupdate /force

Log user off/on.

Remap network drive.

4️⃣ Resolution

Add user to appropriate security group.

Apply least-privilege principle.

5️⃣ Validation

Confirm read/write access.

✅ Closure Notes

User added to Finance_Share security group. Permissions validated. Access confirmed.

