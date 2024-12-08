<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Microsoft Windows with CGI
- Install PHP Manager
- Installing MySQL database
- Install osTicket v.1.15.8
- Downloading and Installing HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/2NX4OpP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Internet Information Services (IIS) Web Server was installed to host applications and websites. IIS provides support for Web and FTP servers, along with support for ASP.NET web sites, dynamic content such as Classic ASP (web application framework) and CGI (Common Gateway Interface), and local and remote management. For this installation, it aided in installing osTicket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/qfV8w2Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installing PHP Manager for IIS file (PHPManagerForIIS_v1.5.0.MSI).
</p>
<br />

<p>
<img src="https://i.imgur.com/hrGjOVs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Installing MySQL 5.5.62, which is a database that osTicket uses to store all of its data in, such as user accounts, ticketing information, etc., on the backend.  
</p>
<br />

<p>
<img src="https://i.imgur.com/ZTcbhmt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Running IIS as an Administrator. This is to register PHP from within IIS. This is making the web server aware of the existence of PHP on the computer, so that the computer knows where it is located.  
</p>
<br />

<p>
<img src="https://i.imgur.com/k9sFQYE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
By opening up osTicket from IIS, by clicking on browse*.80(http) from the "manage folder" section of IIS, you can now open up osTicket, where you can do many solutions for help desk, IT solutions, and cybersecurity. The osTicket software uses PHP as a programming language and uses a MySQL database to store pertinent information.
</p>
<br />

<p>
<img src="https://i.imgur.com/mERUgWP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
HeidiSQL was installed to allow an adminsitrator to login into the MySQL database backend for osTicket, for it to function properly.   
</p>
<br />






