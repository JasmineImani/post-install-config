<p align="center">
<img src="https://imgur.com/LOa2j35.png" alt="kali logo"/>
</p>

<h1>Kali Linux - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of Kali Linux.<br />


<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox (Virtual Machines/Computer)
- Kali Linux

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/bdKEndO.png" height="80%" width="80%" alt="Update Steps"/>
</p>
<p>
Update the operating system and applications
  
1. In the command line window, type sudo apt update, and then press Enter. Type your password if prompted, and then press Enter.
2. A list of the downloaded update packages is displayed.
3. Type sudo apt full-upgrade, and then press Enter.
4. The window displays several pieces of information.

      All new and upgraded packages

      The size of the additional archives that apt must download to complete the upgrade

      The net hard disk space required
5. The window displays the question, “Do you want to continue?” Type y, and then press Enter.
6.  The window displays the progress of the system upgrade. This process could take several minutes.
7.  The window displays the question, “Restart services during package upgrades without asking?” Use your arrow keys to select Yes, and then press Enter.
8.   All package updates should be complete.
</p>
<br />

<p>
<img src="https://imgur.com/WvUPxFw.png" height="80%" width="80%" alt="PasswordChange Steps"/>
</p>
<p>
Change the default user password using the command line

1. To open the command line, press Ctrl+Alt+T or click the Terminal Emulator icon on the taskbar.
2. The command line is displayed.
3. Type passwd, and then press Enter. When prompted to provide your current password, type kali, and then press Enter.
4.  Create a new password and make it strong. Ensure it has at least 12 characters and includes uppercase and lowercase letters as well as numbers and symbols. Type 125Js#e1dXA& or a similar password, and then press Enter. Retype the password when prompted, and then press Enter.
</p>
<br />

<p>
<img src="https://imgur.com/YJ1vxIx.png" height="80%" width="80%" alt="UserAdd Steps"/>
</p>
<p>
Add a new user using the command line

1. In the command line window, type sudo useradd test, and then press Enter. Type your password when prompted, and then press Enter.
2. Now you’ll set a password for the new user. Type sudo passwd test, and then press Enter. Type your password when prompted, and then press Enter.
3. Type the new password for test when prompted, and then press Enter. Retype the password when prompted, and then press Enter.
</p>
<br />
