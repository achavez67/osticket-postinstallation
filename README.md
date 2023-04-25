<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-installation</h1>
This tutorial outlines the post-installation process of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

-osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

For this project, I created a virtual machine via Microsoft Azure using Windows 10 as the operating system. There are a handful of requirements to install in order for osTicket to function properly.

<p>
<img src="https://i.imgur.com/mdu44fs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before we install osTicket, we must install and enable IIS in windows with CGI. We can achieve this by going to the windows search bar and type "Control Panel". Then we will go to Programs->Programs and Features->Turn Windows features on or off. We will find IIS and enable it, expand it, expand Application Development Features, and enable CGI. 

</p>
<br />
<p>
<img src="https://i.imgur.com/rkHcmpx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We must download the files in the image above and listed on the "prerequisites". We follow the instructions of each file to install the programs succesfully.
</p>
<br />
