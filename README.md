
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

- 4 VCPUs to improve performance and responsiveness in case of concurrent use and large influx of requests and database queries.
- 16GiB RAM

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

1. Establish a Remote Desktop Connection with VM-osTicket using credentials created in Azure Portal. 
<p>
<img src="https://i.imgur.com/NuNazQS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
2. Install and configure IIS. 
</p>
I opened VM-osTicket and enabled IIS with CGI using the following steps: 
</p>
open the Control Panel -> click Programs -> click "turn windows features on or off"
</p>
Locate "Internet Information Services", enable it and expand it, -> expand "World Wide Web Services" -> expand "Application Development Features", find CGI and enable it, then clicked ok. 
<p>
<p>
  <p>
    <p>
<img src="https://i.imgur.com/szxP0CF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<br />
<p>
  - Verify IIS installation and configuration by intering local host IP (127.0.0.1) in the address bar. 
 <p>
<img src="https://i.imgur.com/pvHSKv1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
3. Download and install PHP Manager for IIS
<p>
   - download link (https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view?usp=share_link)
<p>
4. Download and install rewrite module 
<p>
<p>
  - dowload link (https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=share_link)
</p>

5. Download and install PHP
   - download link (https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=share_link)
<p>
  - create folder in C drive and name it PHP (C:\\PHP)

  <p></p>
- Extract PHP files to C:\\PHP
<p>
  <p>
<img src="https://i.imgur.com/PMi9rbx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

6. Download and Install MySql database
   <p></p>
   - download link (https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=share_link ) 
   <p>
   - Create root password
<p>
<img src="https://i.imgur.com/0e5Wdzs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
   </p>
</p>

7. Download and install VC++ redistributable
   <p></p>
   - download link (https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=share_link) 
<br />

<p>
8. Open IIS as Admin
  <p>
    <p>
  - Register PHP from within IIS 
      <p>
  <p>
<img src="https://i.imgur.com/lyOH8L3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    </p>
  </p>

9. Download oSticket
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
