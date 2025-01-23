<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- macOS 

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Log into the VM with Remote Desktop
- Navigate to your Microsoft Remote Desktop Application
- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS
- Install the Rewrite Module
- Open IIS as an Admin
- Register PHP from within IIS
- Reload IIS
- Install VC Redist & MySQL
- Enable Extensions & Assign Permissions
- HeidiSQL Setup
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


- In the Friendly Name box type in osTicket
- Click "Add to add osTicket VM


  
<h2>Step. 5 Connect to the osTicket VM and log in using credentials from above</h2>

  ![image](https://github.com/user-attachments/assets/a6a480e1-dc56-4510-bf51-727c5e9d9f96)

  - Sometimes Azure will make you reset the password before signing in
  - To do this click on osTicket VM in Azure
  - Under the Help tab click Reset Password
  - Connect to osTicket VM after the Password has been reset

<h2>Step. 6 Within the VM (osTicket-vm) download the osTicket Installation File</h2>

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


- PHP is a backend web server language that osTicket runs off of
- We are required to install PHP for osTicket to function
- It is a requirement that we install Rewrite Module to use osTicket as well
- Watch the Instructional Video above


<h2>Step. 10 Create the PHP Directory folder</h2>

![Create directory php](https://github.com/user-attachments/assets/6c44296b-5b90-4fbf-9479-e36518025afb)

- Click on the yellow folder on your VM taskbar
- Find Windows(C:) and click on it
- Create a PHP folder within Windows(C:)
- Please see the photo diagram above

<h2>Step. 11 Install VC Redist & MySQL</h2>


https://github.com/user-attachments/assets/ee941f64-4603-49d9-9db1-6d81b0e17688

- Watch the Instructional Video above
- Once MySQL 5.5.62 Server is done configuring.  Click Finish


<h2>Step. 12 Open IIS as an Admin & Register for PHP from within</h2>


https://github.com/user-attachments/assets/701a90c7-fd87-474d-a830-ef90448e93aa

- Watch the Instructional Video above
  

<h2>Step. 13 Enable Extensions & Assign Permissions</h2>



https://github.com/user-attachments/assets/cee179dd-56c1-4545-8a49-6a1d3341677e


- Watch the Instructional Video above
- Name your Help Desk name whatever you want
- Type an email address
- Fill out Admin User information (make sure to use a different email from above)
- Install HeidiSQL in your osTicket installation file folder you downloaded at the start
- HeidiSQL is an application that allows us to make a connection with our database


<h2>Step. 14 HeidiSQL Setup</h2>

<img width="663" alt="Screenshot 2025-01-20 at 7 36 11 PM" src="https://github.com/user-attachments/assets/d6651276-9e8c-4afc-aab1-a5c8783609b8" />

- Once HeidiSQL is installed
- Type in root for user and password for your credentials from earlier


https://github.com/user-attachments/assets/5e5394d3-e085-4f5e-867b-fa4128ed4b4a

- Watch the Instructional Video above
- Then go to your Database Settings in HeidiSQL
- Fill out Database settings just like the diagram below then click "Install Now"

![Screenshot 2025-01-20 at 7 53 58 PM](https://github.com/user-attachments/assets/d9ff4eb0-d924-430f-8a09-39ec98b9ef68)


<h2>Step. 15 Congratulations, hopefully it is installed with no errors!
</h2>


![Screenshot 2025-01-20 at 7 58 18 PM](https://github.com/user-attachments/assets/eca87329-602f-4c1b-873c-ca1734ef44ba)

- You should see a congratulations page like the one above


https://github.com/user-attachments/assets/11368310-2b72-47f2-9faf-a177443d1102

- Watch the Instructional Video above




