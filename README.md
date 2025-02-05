# configure-ad<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Create some sample file shares with various permissions
- Step 2: Set permissions for folders
- Step 3: Attempt to access file shares as a normal user

<h2>Deployment and Configuration Steps</h2

 ![image](https://github.com/user-attachments/assets/85d2b6d1-f254-4005-bf8e-0303cd8ec4c5)
                                       

<p>

</p>
<p>
Through remote desktop we logged in as an admin user and created some files to share with an agent user login. Next, we went to the active directory users and computers tab to create an organizational unit and then granted access to Domain users. Then, we created 4 different files and granted them different levels of access priveleges. In this example we granted Doamin Users read/write priveleges in the "read access" folder.  
</p>
<br />

![image](https://github.com/user-attachments/assets/394190f0-591e-4efa-a74f-d99227af0840)


</p>
<p>
When we switched over to the agent desktop under Domain Users via remote desktop, we naviagted to the "read access" file we granted Domain Users access to. Then, we opened the file and opened up a note tab to verify that read/wtite priveleges had been granted.
</p>
