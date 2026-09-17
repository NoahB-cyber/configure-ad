ACTIVE DIRECTORY USING MICROSOFT AZURE VIRTUAL MACHINES (VMs) 


SOFTWARE USED

- DOMAIN CONTROLLER (DC) : Windows 11 Pro
- CLIENT VM : Windows 10


WHAT DC LOOKS LIKE :

&nbsp;
&nbsp;

<img width="1066" height="605" alt="Screenshot 2026-09-02 5 12 42 PM" src="https://github.com/user-attachments/assets/12e0d66b-f7bf-41d2-ac36-8fe7b3bf18e4" />
<p
<p
<bg 
  
The image above is the server manager page. This is the first thing to show up when opening the Domain Controller, and where all the magic happens. Configurations to DNS, adding users and servers, monitoring/managing, adding Active Directory Domain services (or AD DS) for remote and local servers, as well as various other "QuickTool Access" abilities. 

&nbsp;
&nbsp;
&nbsp;


<img width="1061" height="602" alt="Screenshot 2026-09-02 5 27 15 PM" src="https://github.com/user-attachments/assets/a72dce6d-2e5c-40d6-b1c2-8b0c7d7e379e" />

This image above is what "users and computers" looks like from an admins perspective.

&nbsp;
&nbsp;
&nbsp;

<img width="1056" height="597" alt="Screenshot 2026-09-02 5 26 27 PM" src="https://github.com/user-attachments/assets/4fcd4091-1d6d-4a4a-a906-4a32d8d9bd39" />


The image above displays the "file explorer" tab, after configurations, here is where your AD hub will be. From here you can access users and computers, AD admin center, etc.

&nbsp;

A common use for this as a help desk technician is to reset passwords, which would be in the tab shown below

&nbsp;

<img width="1063" height="599" alt="Screenshot 2026-09-02 5 29 38 PM" src="https://github.com/user-attachments/assets/e66028c0-8352-4873-8e4f-dc9e5d6830cc" />

&nbsp;
&nbsp;
&nbsp;

-In the course careers DC-1 and Client-1 Labs, we configured the DNS of Client-1 to point to DC-1's private IP Address through powershell

&nbsp;

-Configured "employees", auto generated with random letters as names through WireShark and PowerShell.

&nbsp;

-Logging into Client-1 as one of the "employees", intentionally locking them out by constant login attempts with incorrect passwords.

&nbsp;

-Logging into DC-1 as an admin user to  unlock the "employees" account.

&nbsp;

-Adding permissions to "employees" and assigning to groups with certain read/write/viewer only accesses


