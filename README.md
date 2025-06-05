<h1>Unlocking-a-users-account</h1>


<h2>Description</h2>
The aim of this task is to unlock a users account after it has been disabled.


<h2>Utilities Used</h2>

- <b>Virtualbox</b>
- <b>virtual machines</b>
- <b>Windows ISO</b>

<h2>Environments Used </h2>

- <b>Windows 10 server OS</b>
- <b>Windows 10 OS</b>



<h2>Program walk-through:</h2>

When I attempted to log into Patty's account on a separate VM, the following message was displayed.

<img src="https://i.imgur.com/UPuRxjA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

The first step I took was to open the Windows Server 10 operating system, where Active Directory is installed, so I could access and modify Patty’s account settings.

<img src="https://i.imgur.com/h7h8ovi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Next, I navigated to the folder containing the user account I wanted to unlock, selected the account, and proceeded to unlock it.

<img src="https://i.imgur.com/wpX7ZWY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Next time I attempt to log in, I should be able to access the account without any issues.

