# ticket-simulation

Ticket ID: HD-001  

Issue:
User reports they are unable to log in and receive an "account locked" message.

Environment:
- Windows 10
- Domain-joined desktop

Troubleshooting Steps:
1. Verified account status in Active Directory
2. Confirmed account was locked due to multiple failed attempts
3. Unlocked account
4. Reset password
5. Verified login with user

Resolution:
Account unlocked and password reset successfully.

Impact:
Single user, unable to work

Notes:
Advised user to update saved credentials on mobile device.



Ticket ID: HD-002  

Issue:
User reports no internet access while connected via Ethernet.

Environment:
- Windows 11
- Wired connection

Troubleshooting Steps:
1. Verified physical cable connection
2. Ran `ipconfig /all`
3. Identified APIPA address
4. Released and renewed IP address
5. Restarted network adapter

Resolution:
DHCP lease successfully obtained after adapter reset.

Impact:
Single user

Notes:
Would escalate if DHCP issue persisted.



Ticket ID: HD-002  

Issue:
User reports no internet access while connected via Ethernet.

Environment:
- Windows 11
- Wired connection

Troubleshooting Steps:
1. Verified physical cable connection
2. Ran `ipconfig /all`
3. Identified APIPA address
4. Released and renewed IP address
5. Restarted network adapter

Resolution:
DHCP lease successfully obtained after adapter reset.

Impact:
Single user

Notes:
Would escalate if DHCP issue persisted.



Ticket ID: HD-003  

Issue:
Outlook not receiving new emails.

Environment:
- Windows 10
- Outlook 365

Troubleshooting Steps:
1. Verified internet connectivity
2. Checked Outlook was not in offline mode
3. Restarted Outlook
4. Repaired Outlook profile

Resolution:
Mailbox began syncing after profile repair.

Impact:
Single user

Notes:
User confirmed email flow restored.



Ticket ID: HD-004  

Issue:
User unable to print; printer shows offline.

Environment:
- Network printer
- Windows 10

Troubleshooting Steps:
1. Verified printer powered on
2. Checked network connectivity
3. Cleared print queue
4. Restarted Print Spooler service

Resolution:
Printer returned online and printed test page.

Impact:
Single user



Ticket ID: HD-005  

Issue:
User reports computer is running slowly.

Environment:
- Windows 10
- Laptop

Troubleshooting Steps:
1. Checked Task Manager for high resource usage
2. Identified multiple startup applications
3. Disabled unnecessary startup items
4. Checked disk space

Resolution:
System performance improved after reducing startup load.

Impact:
Single user

Notes:
Recommended periodic reboots.
