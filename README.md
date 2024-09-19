<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/3652e401-f273-40da-ad28-1aa31b1392e0" height="50%" width="50%"/>
</p>
<p>
Log in to osTicket with your admin credentials and navigate to the Admin Panel.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/9029255f-bdbc-41f4-b0ae-6937f559f8b9" height="50%" width="50%"/>
</p>
<p>
We are now going to add an Admin role. Click on Agents->Roles->"Add New Role". For this example, we will name it Supreme Admin.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/cb027677-57a9-45a5-b590-3c10c4503183" height="50%" width="50%"/>
</p>
<p>
We are going to give Surpeme Admin permission to do everything.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/56638296-1d22-4036-96ae-447a42ba1782" height="50%" width="50%"/>
</p>
<p>
Let's create a new Department. Move over to the Departments tab next to the Roles tab you were just in. Select "Add New Department". For this example, we will name it "System Administrators". Leave options default for now.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0c09ed4c-fae3-49a0-adf2-1fe0d2a8cdbe" height="50%" width="50%"/>
</p>
<p>
Now we will make a new team. A team is a way to pull select agents from different departments to work on a task, among other things. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/4bdf2f5e-a953-441b-9a8c-bb8b8a5b943b" height="50%" width="50%"/>
</p>
<p>
Let's create some new agents. Go to Agents->Agents->"Add New Agent".  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/00ac1743-b9c9-4b99-b1e1-97cafece4ce1" height="50%" width="50%"/>
</p>
<p>
Next, assign them to their specified Department and team as well as their Permissions.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/31dd969b-08d9-4cb9-8a9f-1ab0e455a7e6" height="50%" width="50%"/>
</p>
<p>
Navigate to the Agent Panel now by clicking on it in the top right corner. We are going to create Users, these are the people that are making the ticket requests. Click Users->"Add New User"
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/7c3cbfeb-11d0-4439-a0e9-23c827f74352" height="50%" width="50%"/>
</p>
<p>
We will create SLA's now. Go back to Admin Panel and go to Manage->SLA. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f0061251-e88a-4927-bf6e-dbc8bd64b901" height="50%" width="50%"/>
</p>
<p>
Create 3 different SLA's with different severity levels. SEV-A has a 1 hour grace period on a 24/7 basis, SEV-B has a 4 hour grace period on a 24/7 basis and SEV-C has a 8 hour grace period on a Monday-Friday 8am-5pm basis. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f54793a9-90a6-43fc-8b93-00121efc7572" height="50%" width="50%"/>
</p>
<p>
Let's create some Help Topics. Go to Mange->Help Topics->Add New Help Topic. We added a several common issues such as "Password Reset" and Equipment Request" . 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f54793a9-90a6-43fc-8b93-00121efc7572" height="50%" width="50%"/>
</p>
<p>
Let's create some Help Topics. Go to Mange->Help Topics->Add New Help Topic. We added a several common issues such as "Password Reset" and Equipment Request". We have now configured everything we need. Go to the next lab to see some ticket lifecycle examples.
</p>
<br />

























