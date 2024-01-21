
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Preconditions and Installation</h1>
This tutorial spells out the preconditions and installation procedures of Osticket, an open-source help desk ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Virtual Machines in Microsoft Azure Environment
- Windows Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Processing Capacity </h2>

- 2 VCPUs to improve performance and responsiveness in case of concurrent use and large influx of requests and database queries. 

<h2>List of Prerequisites</h2>

- Enable IIS to host website osTicket
- Install MySQL server which will be used by Ostickets to store application data such as configurations, users and ticket details. 
- Installing/configuring osTicket
- Enabled osTicket to fetch/process email
- Create database for osTicket

<h2>Installation Steps</h2>

1. Create a tenant and subscription in Microsoft Azure
2. Create a Resource Group
3. Create and deploy a virtual machine
<p>
<img src="https://i.imgur.com/pZ5M0bB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Install and configure IIS, a native web server for Windows where Osticket will be hosted. 
  - Ensure common http features and Common Gateway Interface (CGI) are turned on 
  - Verify IIS installation and configuration by intering local host IP (127.0.0.1) in the address bar. 
  <p>
<img src="https://i.imgur.com/pZ5M0bB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />

<p>
<img src="https://i.imgur.com/hxGUMyi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here i'm installing a server for our future database for osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/Nn11Jxp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now i'm installing/configuring osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/wy9yJOQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I've enabled osTicket to fetch & process email.
</p>
<br />

<p>
<img src="https://i.imgur.com/PKaBUNZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket database has been created!
</p>
<br />

<p>
<img src="https://i.imgur.com/fPRGNNx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
osTicket installation is now complete!
</p>
<br />
