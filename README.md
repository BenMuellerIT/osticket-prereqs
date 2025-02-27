<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/8foq0WltNKI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a virtual machine in Azure
- Install/Enable Internet Information services (IIS) in windows with Common Gateway Interface (CGI) 
- Install PHP Manager for IIS
- Install Rewrite Modual
- Create Directory C:\PHP
- Install VC_redist.x896.exe
- Install MySQL
- Register PHP
- Install osTicket
- Enable Disabled Extensions
- Assign Permissions
- Create osTicket Database

<h2>Installation Steps</h2>

<p>
<blockquote class="imgur-embed-pub" lang="en" data-id="a/MnZyWfp" data-context="false" ><a href="//imgur.com/a/MnZyWfp"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
</p>
<p>
In order to install a webserver on the virtual machine I first had to enable some application development features. Such as a Common Gateway Interface
</p>
<br />

<p>
<blockquote class="imgur-embed-pub" lang="en" data-id="a/BeJR9kr" data-context="false" ><a href="//imgur.com/a/BeJR9kr"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
</p>
<p>
Registering the PHP from within IIS makes the webserver aware of the location of our PHP folder that was created
</p>
<br />

<p>
<blockquote class="imgur-embed-pub" lang="en" data-id="a/dnTEWlo" data-context="false" ><a href="//imgur.com/a/dnTEWlo"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
</p>
<p>
Now that osTicket is installed we can create tickets as users and manage tickes as employees and admins.
</p>
<br />
