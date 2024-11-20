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

- Step 1: Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Step 2: Log into the VM with Remote Desktop
- Step 3: Download osTicket Installation Files to VM
- Step 4: Install / Enable IIS in Windows WITH CGI
- Step 5: Install PHP Manager for IIS
- Step 6: Install the Rewrite Module
- Step 7: Create the directory C:\PHP
- Step 8: Install PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder
- Step 9: Install VC_redist.x86.exe
- Step 10: 


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/7E93uXW.png" height="80%" width="80%" alt=""/>
</p>
<p>
Step 1: Create an Azure Virtual Machine Windows 10, 4 vCPUs  
</p>

<p>
<img src="https://i.imgur.com/dlnWxf3.png" height="80%" width="80%" alt=""/>
</p>
<p>
Step 2: Log into the VM with Remote Desktop 
</p>

<p>
<img src="https://i.imgur.com/7E93uXW.png" height="80%" width="80%" alt=""/>
</p>
<p>
<h3> Step 3: Download osTicket Installation Files to VM </h3> 

We will use the files in this folder to install osTicket and some of the dependencies.   
</p>

<p>
<img src="https://i.imgur.com/UBjKqdS.png" height="80%" width="80%" alt=""/>
</p>
<p>
<h3>Step 4: Install / Enable IIS in Windows WITH CGI </h3> 

1. Go to start menu
2. Type in Control Panel
3. Click Uninstall Programs
4. Click Turn Windows Features On and Off
5. Tick Internet Information Services > World Wide Web Services > Application Development Features > CGI
6. Click OK

You can now enter 'http://127.0.0.1/' and it should return a splash screen for IIS. 
</p>

<p>
<img src="https://i.imgur.com/Fggqsfc.png" height="80%" width="80%" alt=""/>
</p>
<p>
<h3>Step 5: Step 5: Install PHP Manager for IIS</h3>

From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)  
</p>
<p>
<img src="https://i.imgur.com/XFUaltz.png" height="80%" width="80%" alt="Log into Remote Desktop"/>
</p>

<p>
<h3>Step 6: Install the Rewrite Module</h3>
</p>
<p>
<img src="https://i.imgur.com/RwacG67.png" height="80%" width="80%" alt="Log into Remote Desktop"/>
</p>

<p>
<h3>Step 7: Create the directory C:\PHP</h3>

1. Right-click the manila folder on the taskbar
2. Choose File Explorer
3. Click the chevron for This PC
4. Click Windows (C:)
5. Right-click and choose New Folder
6. Rename the folder PHP  
</p>
<p>
<img src="https://i.imgur.com/DkY0y1h.png" height="80%" width="80%" alt="Log into Remote Desktop"/>
</p>

<p>
<h3>Step 8: Install PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder</h3>
</p>
<p>
<img src="https://i.imgur.com/b9hlgqC.png" height="80%" width="80%" alt="Log into Remote Desktop"/>
</p>
