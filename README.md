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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/uvVj6OS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step to installing osticket is to make a, VM (virtual machine). It is good practice to test new software in a virtual machine so you don't tamper or harm  the host operating system. This will in turn, create a virtual network and all of it's resources. Azure is a great resource to utilize if you want to get some experience with VM's, as it is free to use for thirty day's. 
</p>
<br />

<p>
<img src="https://i.imgur.com/muWptGT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Next, we will install\enable IIS with CGI. IIS allows your computer to serve up websites, because osticket runs out of a website. CGI lets you installl PHP manager, which is a back-end prorgamming language, and osticket runs off of PHP. There are a bunch of prerequisite software that will need to be installed to make osticket operate better. some being: PHP manager, Rewrite Module, PHP 7.3.8, VC_redist, and MySQL. MySQL is one of the more important softwear to download, because you will need to create credentials that will be used later on in the lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/XtrwNpJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 After, you will need to download\register PHP. This register a new version of PHP manager. Following that, you will need to download osticket, and extract and copy the "upload" folder to c:\inetpub\wwwroot folder. This is a special forld, which is the webservers main folder. Rename the "upload ticket" to "osticket", reload IIS, click browse *:80. You will then see that some of the extentions are not enabled, and that you don't necessarily need them. In our case we will need them.
</p>
<br />

<p>
<img src="https://i.imgur.com/RaFOyxU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In conclusion, we will set the permissions so that everyone can do anything that want to the file. Next, we will continue to setup osticket in the browser, such as, username, password. This is now where MySQL, and the credentials we made, will come in handy. We install Heidi SQL, this will allow us to connect to the MySQL database, and then set up a database. The remainder of the lab is just signing into the admins accout to make sure it is active.
</p> 
<br />

