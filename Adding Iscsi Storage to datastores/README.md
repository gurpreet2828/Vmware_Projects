# Adding Iscsi Storage to datastores

**Step 1**
Go to vcenter Server  - Storage  - Right click on datacenter – storage – new datastore

1. Select VMFS
2. Enter the Datastore Name
3. Select host from drop down

![Picture25](https://github.com/gurpreet2828/VmwareProject_Images/blob/9e669bdc38dbd4258492375683c1204a105f3621/Picture25.png)

**Step 2**

Select name or LUN – Next -Select VMFS-6 – NEXT (default setting in partition configuration) – Next – Complete
<br>You will see all the storage in datacenter</br>

![Picture26](https://github.com/gurpreet2828/VmwareProject_Images/blob/9e669bdc38dbd4258492375683c1204a105f3621/Picture26.png)

***Also you can check going to esxi server***
1.	Go to esxi host – right click on vm server 2016  -edit options – add harddisk – select new raw disk you will find shared disk here
2.	Create shared storage in esxi host – new datastore  in storage – create vmfs – select storage created in server 2016
3.	Now go to the vm machine (win 10) – right click on – go edit setting – add harddisk – new harddisk  - select shared storage (created in server 2016) by browsing.
4.	Go to computer or disk management in VM you will find the storage

## Completed: Adding Iscsi Storage to datastores



