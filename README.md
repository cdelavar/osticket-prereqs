<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This is a step-by-step guide on the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- IIS (Internet Information Services) with CGI
- PHP Manager and URL Rewrite Module
- PHP and Visual C++ Redistributable for Visual Studio 2015-2019
- MySQL Server 
- osTicket
- Heidi SQL

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/4O9BxFh.png" height="80%" width="80%" alt="Control Panel"/>
</p>
<p>
Navigate to Control Panel - Programs - Turn Windows features on or off
</p>
<br />

<p>
<img src="https://imgur.com/6FGWbiA.png" height="80%" width="80%" alt="IIS"/>
</p>
<p>
Check the box for Internet Information Services
</p>
<br />

<p>
<img src="https://imgur.com/UGvDLXo.png" height="80%" width="80%" alt="CGI"/>
</p>
<p>
Click the drop down menu for World Wide Web Services <br />
   - Click the drop down menu for Application Development Features <br />
   - Check the box for CGI, then click ok <br />
   CGI lets us install PHP manager, which we need on our computer because osTicket runs on PHP <br />
</p>
<br />

<p>
<img src="https://imgur.com/VguOjw8.png" height="80%" width="80%" alt="IIS Up and Running"/>
</p>
<p>
If loaded and working, you'll see Internet Information Services webpage running on local host 127.0.0.1
</p>
<br />

<p>
<img src="https://imgur.com/VyUG59G.png" height="80%" width="80%" alt="Download PHP Manager"/>
</p>
<p>
Download and install PHP Manager for IIS - version 1.5.0 from the iis.net website
</p>
<br />

<p>
<img src="https://imgur.com/G8VRq8i.png" height="80%" width="80%" alt="Download URL Rewrite Module"/>
</p>
<p>
Download the URL Rewrite Module for IIS 
<br /> 
osTicket config file needs this to process URL's
</p>
<br />

<p>
<img src="https://imgur.com/w4BiHfy.png" height="80%" width="80%" alt="PHP Directory"/>
</p>
<p>
Create a directory for PHP on the local hard drive C:\PHP
</p>
<br />

<p>
<img src="https://imgur.com/hnZ0j5v.png" height="80%" width="80%" alt="Download PHP and VC"/>
</p>
<p>
Download and install PHP and the Visual C++ Redistributable for Visual Studio 2015-2019
</p>
<br />

<p>
<img src="https://imgur.com/mquDFnG.png" height="80%" width="80%" alt="Download MySQL"/>
</p>
<p>
Download and install MySQL Server - (mysql-installer-community-8.0.32.0.msi)
</p>
<br />

<p>
<img src="https://imgur.com/9keJ1ub.png" height="80%" width="80%" alt="IIS Admin"/>
</p>
<p>
Click the windows icon, type in IIS and run as administrator with Internet Information Services Manager
<br />
  -click on PHP Manager
</p>
<br />

<p>
<img src="https://imgur.com/bg0lhHj.png" height="80%" width="80%" alt="Register PHP"/>
</p>
<p>
Click on Register new PHP version, and navigate to C:\PHP\php-cgi.exe in order to register
</p>
<br />

<p>
<img src="https://imgur.com/1JnpcrU.png" height="80%" width="80%" alt="osTicket Folder"/>
</p>
<p>
Copy the upload folder and copy to the C:\inetpub\wwwroot folder, then rename the folder to osTicket
</p>
<br />

<p>
<img src="https://imgur.com/4KN7GPQ.png" height="80%" width="80%" alt="Enable Extensions"/>
</p>
<p>
Lorem ipsum
</p>
<br />



