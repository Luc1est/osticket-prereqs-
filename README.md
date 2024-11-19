<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS (internet information services) in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI
-  install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
- install the Rewrite Module (rewrite_amd64_en-US.msi)
- Create the directory C:\PHP-
- From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 into the “C:\PHP” folder- 
<h2>Installation Steps</h2> 

![image](https://github.com/user-attachments/assets/3a43b1ec-ba27-438f-b586-4567a2589a8a)

I used Azure cloud to create a virtual machine, after creating and Logging into my virtual machine on Windows 10 i Start to install OS Ticket
</p>
<br />


![image](https://github.com/user-attachments/assets/67970022-0c2d-4dba-97b5-f0772530530c)

i enabled IIS and CGI, a dependent that OS ticket needs found within world wide web services


![image](https://github.com/user-attachments/assets/ba50e594-2892-4f6f-8c12-7de787d7a5d4)

i installed PHP manager for IIS, this is essential for OS Ticket to Run

 ![image](https://github.com/user-attachments/assets/0e537dd5-f348-45b6-969a-8df8e5b701b3)

Next i instlled Microsoft visual C+ Redistributable 


![image](https://github.com/user-attachments/assets/d4bce304-5c86-48a3-8f79-3fc1ed80b43b)

Lastly i installed my SQL, this is a database where all the data will be stored and organized. user accounts, ticketeing info etc...



