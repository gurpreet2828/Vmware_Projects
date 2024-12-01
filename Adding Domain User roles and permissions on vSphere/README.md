# Adding Domain User roles and permissions on vSphere

**Step1 :** Create users in Active Directory Domain Controller

***Note: I created 3 users for testing purpose and assigning the different roles to esxi***

Assigning the role according to your requirements

**Step 2:** Go to ESXI Host  - Manage – Security and Users – Roles

![Picture30](https://github.com/gurpreet2828/VmwareProject_Images/blob/8458bca441b99047bef2b78d58ab03c2e9e49efb/Picture30.png)

Adding a user and assigned the required role to user

**Step 3:** Go to Esxi – Host – Actions  - Permission – Add User

Enter the user which you created in Domain Controller and give permission from drop down

***I gave the read-only permission to user***

![Picture31](https://github.com/gurpreet2828/VmwareProject_Images/blob/f7a4d8741b7acaae3f21792e084125f9aa58e377/Picture31.png)

After creating the user you will find as bellow

![Picture32](https://github.com/gurpreet2828/VmwareProject_Images/blob/f7a4d8741b7acaae3f21792e084125f9aa58e377/Picture32.png)

**Step 4:** Now you can access the ESXI host with user which you created in esxi

Login with gurpreet@cloudinfotech.ca

And password which you assigned in domain controller

Login to ESXI with user as shown below

![Picture33](https://github.com/gurpreet2828/VmwareProject_Images/blob/1002490f0f4f4c6c2debc301efce46f5d4577735/Picture33.png)

After login you will see the following screen as user login

![Picture34](https://github.com/gurpreet2828/VmwareProject_Images/blob/1002490f0f4f4c6c2debc301efce46f5d4577735/Picture34.png)

## Adding of User and giving perminssion completed 


