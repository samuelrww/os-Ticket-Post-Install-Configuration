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

- Active Azure subscription
- Vritual machine
- OSTicket

<h2>Installation Steps</h2>

<p>
</p>
<p>
First step is to open the virtual machine using Remote desktop. Then proceed to sign in using the public IP address assigned to your Remote Desktop.
</p>
<img src="https://i.imgur.com/Pti1af6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
</p>
<p>
Then proceed to enable IIS using control panel>uninstall program>turn windows features on/off.
</p>
<img src="https://i.imgur.com/zQLTCU1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
  Proceed to Install all applications listed in google drive.
  </p>
<br />

<p>
</p>
<p>
a.) Once webplatform is installed open application then Add and install MYSQL 5.5
  Name: root
  Password: Password1
 b.)add all simple versions of x86 PHP up until 7.3.
 c.)Fix any failures if applicable using drive link to reinstall/uninstall.
</p>
<p>
  <img src="https://i.imgur.com/b0mf6Mk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  </p>
<br />




<p>
a.)Install OS ticket from drive then proceed to extract and copy the "upload" folder into c:\inetpub\wwwroot
 b.) within c:\inetpub\wwwroot Rename upload to "osTicket"
</p>
<p>
  <img src="https://i.imgur.com/GplZqcg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />




<p>
  a.)Open and Reload IIS by stoppping and starting the server.
  b.) navigate to sites>default>osticket Then enable extensions by double clicking php manager.
  C.)enable php_imap.dll> php_intll.dll>php_opcache.dll
</p>
<p>
<img src="https://i.imgur.com/WaANcqn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
a.)Then proceed to locate the file C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php and rename to C:\inetpub\wwwroot\osTicket\include\ost-config.php.
  b.) Assign permissions to the config file by right clicking and going to security. Then you will click the advanced option, then disable all inheratince. 
  c.)You will then create a new principal for everyone to have full access and editing rights.
</p>

<p>
<img src="https://i.imgur.com/03ObsqN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />



<p>
a.)Set up your information using the .80 website located in the IIS application to the right of the window.
  b.)Download and install Heidi SQL and create a new session. Username:Root Password: Password1
  C.)Connect to session  and create a database called  "osTicket"
</p>
<p>
<img src="https://i.imgur.com/VYjup00.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will now install files from the browser!
  You have now completed installation.
</p>
<br />
