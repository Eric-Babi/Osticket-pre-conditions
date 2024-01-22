
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

- Set-up and deploy compute resources in Microsoft Azure
- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS, Install Rewrite Module, download PHP and install C++ redistributable. 
- Install and set-up MySQL server
- Install and set-up HeidiSql as database client
- Register PHP from within IIS
- Install and configure osTicket
- Clean up / Test

<h2>Installation Steps</h2>

1. Establish a Remote Desktop Connection with VM using credentials created in Azure Portal. 
<p>
<img src="https://i.imgur.com/NuNazQS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
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
