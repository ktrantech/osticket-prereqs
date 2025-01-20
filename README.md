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

- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Log into the VM with Remote Desktop
- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Open IIS as an Admin
- Register PHP from within IIS
- Reload IIS
- Install osTicket v1.15.8

<h2>Installation Steps</h2>

Step 1. Create an Azure Virtual Machine Windows 10, 4 vCPUs


![image](https://github.com/user-attachments/assets/e16081fa-860e-44a6-88a9-d3d71b0fa8ef)


- Name: osticket-vm

- Username: labuser

- Password: osTicketPassword1!          



<h2>Step 2. Log into the VM with Remote Desktop</h2>

![osticket2 login](https://github.com/user-attachments/assets/1529c408-7957-41c3-aa93-874ecb4c76d0)


- Copy your osTicket Virtual Machines Public IP Address

<h2>Step 3. Navigate to your Microsoft Remote Desktop Application</h2>


![Screenshot 2025-01-20 at 9 52 11 AM](https://github.com/user-attachments/assets/bf904f3c-b5e0-43f0-a168-1130a1f26de8)


- Select the "+" button to add a New PC
- Paste your Virtual Machine Public IP Address in the PC Name box


<h2>Step 4. Paste your Virtual Machine Public IP Address in the PC Name box</h2>


![Screenshot 2025-01-20 at 9 54 01 AM](https://github.com/user-attachments/assets/48afdff0-338b-448a-9855-5a3f25ea4e78)


- In the Friendly Name box type in osticket
- Click "Add to add osTicket VM


  
<h2>Step. 5 Connect to the osTicket VM and login using credentials from above</h2>

  ![image](https://github.com/user-attachments/assets/a6a480e1-dc56-4510-bf51-727c5e9d9f96)

  - Sometimes Azure will make you reset the password before signing in
  - To do this click on osticket VM in Azure
  - Under the Help tab click Reset Password
  - Connect to osTicket VM after Password has been reset

<h2>Step. 6 Within the VM (osticket-vm) download the osTicket Installation File</h2>

![image](https://github.com/user-attachments/assets/359e60b1-a5b5-453c-9502-fac54ab9b02a)

- [osTicket Installation File](https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0)
- I will use the files in this folder to install osTicket and some of the dependencies 


<h2>Step. 7 Extract osTicket Installation File & put file on desktop</h2>


https://github.com/user-attachments/assets/7a0aace6-610b-4dd7-a239-57999de126da

- Watch the Instructional Video above

  
<h2>Step. 8 Install/ Enable IIS in Windows WITH CGI</h2>


https://github.com/user-attachments/assets/80f370bf-9108-4cd6-a193-3347d0e5481b

- Watch the Instructional Video above


<h2>Step. 9 Install PHP Manager & Rewrite Module for IIS </h2>



https://github.com/user-attachments/assets/71d5d47c-e795-4a88-8381-4226656b5a0a


- PHP is a backend web server langauage that osTicket runs off of
- We are required to install PHP in order for osTicket to function
- It is a requirment that we install Rewrite Module to use osTicket
- Watch the Instructional Video above





Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
