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

<h1></h1>
<br \>
<br \>

- Install VC Redistributable file
- Install MySQL


![phpmysql](https://github.com/user-attachments/assets/ae62281c-d96b-42e8-8429-c398a7c64c79)

<h1></h1>
<br \>
<br \>

- Run IIS as admin
- Register PHP from IIS
- Reload IIS

![iisreload](https://github.com/user-attachments/assets/b90a0831-317d-4702-bff3-704f64f2856a)

<h1></h1>
<br \>
<br \>

- Unzip osTicket files
- Move 'upload' folder to 'c\inetpub\wwwroot'
- Rename 'upload' folder to 'osTicket'

![ost](https://github.com/user-attachments/assets/bca87e59-c262-4354-b500-cceab96f895e)

<h1></h1>
<br \>
<br \>

- Restart IIS Manager
- Browse to osTicket site within IIS Manager

![browsetoosticket](https://github.com/user-attachments/assets/82eaeff6-6b69-4aad-8fdc-2962d81fdf98)

<h1></h1>
<br \>
<br \>

- Enable Extensions within PHP Manager
- Enable: php_imap.dll
- Enable: php_intl.dll
- Enable: php_opcache.dll

![phpenableext](https://github.com/user-attachments/assets/bafbaacf-5a2f-4116-8635-0bcc80066566)

<h1></h1>
<br \>
<br \>

- Rename 'ost-sampleconfig.php' to 'ost-config.php
- Remove all inherited permisions from 'ost-config.php'

![renamefile](https://github.com/user-attachments/assets/74eb136c-9b97-4da0-aef2-9242aff01747)

<h1></h1>
<br \>
<br \>

- Add new permission
- Select a principal
- Choose 'Everyone'
- Choose 'Full Control'

![permissions](https://github.com/user-attachments/assets/54348155-32ce-4c4d-be62-4de5f14087e8)


















<br />
