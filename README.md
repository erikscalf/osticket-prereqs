<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/WRr7XhbUlJg?si=oAGJCPO8T0LA7D6I)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

- Download osTicket
- Enable ISS
- Enable CGI
- Install PHP Manager
- Create the directory C:\PHP
- Exract all PHP files into C:\PHP


![osticket](https://github.com/user-attachments/assets/a292d859-9e46-4650-a7f4-a347a967d047)


- Install VC Redistributable file
- Install MySQL


![phpmysql](https://github.com/user-attachments/assets/ae62281c-d96b-42e8-8429-c398a7c64c79)

- Run IIS as admin
- Register PHP from IIS
- Reload IIS

![iisreload](https://github.com/user-attachments/assets/b90a0831-317d-4702-bff3-704f64f2856a)

- Unzip osTicket files
- Move 'upload' folder to 'c\inetpub\wwwroot'
- Rename 'upload' folder to 'osTicket'

![ost](https://github.com/user-attachments/assets/bca87e59-c262-4354-b500-cceab96f895e)

- Restart IIS Manager
- Browse to osTicket site within IIS Manager

![browsetoosticket](https://github.com/user-attachments/assets/82eaeff6-6b69-4aad-8fdc-2962d81fdf98)

- Rename 'ost-sampleconfig.php' to 'ost-config.php
- Remove all inherited permisions from 'ost-config.php'

![renamefile](https://github.com/user-attachments/assets/74eb136c-9b97-4da0-aef2-9242aff01747)





















<br />
