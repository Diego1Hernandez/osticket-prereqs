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

- Installation Files 

<h2>Installation Steps</h2>

- Create Virtual Machine in Azure
- Install/Enable IIS in Windows With CGI
- Download and install PHP Manager for IIS
- Download and install the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8
- Download and install VC_redist.x86.exe.
- Download and install MySQL 5.5.62

<h2>Installation Steps</h2>
<p>
<img src="https://i.imgur.com/RPoVYi2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First step is creating our Windows 10 virtual machine(VM) on Azure. THis can be done on Azure by opeinging Virtual Machines->Create->Windows 10/create username and password->Review->Create. 
</p>
<br />

<p>
<img src="https://i.imgur.com/eyelds7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Remote Desktop Connection then connect to your virtual machine by typing it's ip address into Remote Desktop Connection. Use the credentials you created for the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/tlDjrht.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the VM, right-click the windows menu->Run=>Control
</p>
<br />

<p>
<img src="https://i.imgur.com/Ei0U4Jd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
->Programs->
</p>
<br />

<p>
<img src="https://i.imgur.com/yJu56Ra.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Turn Windows features on or of-> Internet Information Services->World Wide Web->Application Development features->CGI
</p>
<br />

<p>
<img src="https://i.imgur.com/L0lHN84.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Activating CGI allows us to host a webpage on our own network. Test this by typing 127.0.0.1 into google.com in your VM. The webpage that loads up should look like the screenshot above.
</p>
<br />

<p>
<img src="https://i.imgur.com/M4Sr5aK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, download/install VC_Redlist. Here is the link 
</p>
<br />

<p>
<img src="https://i.imgur.com/lXoJo2x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/5MLCxwJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download/install MSQL Server from here . Name the server osTicket and enter your root password and press enter to create a server for your osTicket to use.
</p>
<br />

<p>
<img src="<img src="https://i.imgur.com/bV668o5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>.
<img src="https://i.imgur.com/bV668o5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/bV668o5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Activating CGI allows us to host a webpage on our own network. Test this by typing 127.0.0.1 into google.com in your VM. 
</p>
<br />
