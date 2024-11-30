# Shared storage through NFS
**Step1**
•	Install NFS role in files and storage
•	Create folder  - properties of folder – nfs sharing – Manage NFS sharing – check share – click permission -  add ip of server 2016

**Step 2**
Go to vcenter Server  - Storage  - Right click on datacenter – storage – new datastore

![Picture27](https://github.com/gurpreet2828/VmwareProject_Images/blob/59ba6cc306d55968652b5e66ab912d89f956a1a5/Picture27.png)

**Step 3**
Select NFS  - NFS 4.1
Click Next

**Name:** enter the required name of storage

**NFS Server:** Ip address of the server OR Server Name

**NFS Share:** path of the shared folder which created on server (Example - C:\Softwares…….)

Next – select don’t use kerboes authentication – next – select host

![Picture28](https://github.com/gurpreet2828/VmwareProject_Images/blob/59ba6cc306d55968652b5e66ab912d89f956a1a5/Picture28.png)

Next – finish 

You will see nfs storage added to esxi

![Picture29](https://github.com/gurpreet2828/VmwareProject_Images/blob/59ba6cc306d55968652b5e66ab912d89f956a1a5/Picture29.png)

# Adding a shared storage through NFS to ESXI Completed



