# OSTicket-Post-Instal-Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

# Environments and Technologies Used
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop
Internet Information Services (IIS)

# Operating Systems Used
Windows 10 (21H2)

# Post-Install Configuration Objectives
Configure Roles
Configure Departments
Configure Teams
Configure Agents
Configure Users
Configure SLA
Configure Help Topics


# Configuration Steps

Configure Roles:

Admin Panel -> Agents -> Roles.

Supreme Admin:

![image](https://github.com/user-attachments/assets/2e97061e-639e-4c1e-9abb-61c76ce3326e)

![image](https://github.com/user-attachments/assets/b6e76b24-37bc-4484-8de7-aba9442e79a9)

![image](https://github.com/user-attachments/assets/d5f37ab8-a6f2-4b99-8f12-9cd046c4770c)

![image](https://github.com/user-attachments/assets/3edcdc01-ca5f-48cc-a9d1-78f6f4bff0fe)

![image](https://github.com/user-attachments/assets/2872946e-48cf-4252-adb3-42476f90975a)


# Configure Departments

Admin Panel -> Agents -> Departments.

System Administrators:

![image](https://github.com/user-attachments/assets/6d6f5cfb-3853-458c-b748-3da023883913)

![image](https://github.com/user-attachments/assets/fa233786-f1cb-42bd-92ad-7898b7a312f4)



# Configure Teams


Admin Panel -> Agents -> Teams.

Level II Support:

![image](https://github.com/user-attachments/assets/00de7573-59ba-4ba0-8f2f-bd44fb282b94)


# Allow anyone to create ticket


Admin Panel -> Settings -> User Settings.

Make sure "Require registration and login to create tickets" is not selected:

![image](https://github.com/user-attachments/assets/e18801fb-5c55-4d29-bc38-d27651942e63)


# Configure Agents (workers)


Admin Panel -> Agents -> Add New.

Jane Doe:

![image](https://github.com/user-attachments/assets/5eb33b3e-8003-4c43-a804-5e67bf6d6505)

John Doe:

![image](https://github.com/user-attachments/assets/03df7bdb-261c-4b3f-9e85-dbb7aef07b6e)

![image](https://github.com/user-attachments/assets/180ee081-433e-482e-9451-2e4797f0182c)


# Configure Users (customers)

Admin Panel -> Users -> Add New.

Ken User:

![image](https://github.com/user-attachments/assets/7bfdaf49-1bd3-43e1-8af8-377a5e08ec08)

Repeat the same above for Karen User.


# Configure SLA


Admin Panel -> Manage -> SLA.

Sev-A (1 hour, 24/7).

Sev-B (4 hours, 24/7).

Sev-C (8 hours, business hours):

![image](https://github.com/user-attachments/assets/55de049f-be0c-4e2c-825b-3a7587e3595f)

![image](https://github.com/user-attachments/assets/fd67824a-2c15-4562-97b0-9c1cc7cce935)

![image](https://github.com/user-attachments/assets/02d37531-915d-4d0c-bc96-1c3198d7d17b)


# Configure Help Topics

Admin Panel -> Manage -> Help Topics.

Business Critical Outage.

Personal Computer Issues.

Equipment Request.

Password Reset.

![image](https://github.com/user-attachments/assets/9a3825b0-7041-4041-8523-6f996131c328)

![image](https://github.com/user-attachments/assets/e21cb1b7-c8f5-430c-b4e9-07dd42899756)

![image](https://github.com/user-attachments/assets/887b3a56-a2aa-42f8-9079-769b58a74b1c)

![image](https://github.com/user-attachments/assets/2b511325-2757-40f6-b1a3-25afa938522f)

Now our osTicket is fully configured, whew! I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets to ipmrove your skills.

This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.



