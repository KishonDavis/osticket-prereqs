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

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Mircosoft Azure Account
- Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)

<h2>Installation Steps</h2>

1. {Create A Resource Group}

Log into Microsoft Aure https://portal.azure.com, navigate the resoucre group tab, and then create a resource group.


![image](https://github.com/user-attachments/assets/23ef5175-4ead-4a26-aee6-2b707602c5fc)


2. {Create a Virtual Machine}

Navigate the virtual machine tab, and begin creating your machine. While creating your machine, make sure your region matches the region of your resource group and add it to the resource group created previously.
  
![image](https://github.com/user-attachments/assets/a26d4514-b511-4c2a-a416-dee58923ccfb)

Your virtual machine settings should look like this with atleast 2 vcpus for the size. 

![image](https://github.com/user-attachments/assets/c445aff0-bdde-4dca-8579-2ef1b5a79229)

Confirm the licensing of your VM, and create.

![image](https://github.com/user-attachments/assets/b9d4f422-7437-4028-b523-9708cfba50ad)

3. {Access Virtual Machine}

Using Remote Desktop, log into the VM using the credentials used when creating your VM and adding its Public IP Address in the "Computer" space.

![image](https://github.com/user-attachments/assets/616ab797-4a3b-48f3-84d5-cf37466daab0)

![image](https://github.com/user-attachments/assets/2bcc832a-10ac-43bf-abfa-a8676aa9b953)

![image](https://github.com/user-attachments/assets/25175f7f-8aba-4f67-85a9-9ef03d0659e4)

4. {Downloading & Preparing Installation}

Within your VM, download the osticket.zip files

![image](https://github.com/user-attachments/assets/f35b8d22-6eda-4d11-8c7c-fd6039a83ccb)


