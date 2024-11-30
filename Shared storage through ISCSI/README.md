# Shared storage through ISCSI

**Step 1: First create a shared storage in server 2016 and connect through esxi host and shared with computer (client)**

1.	Create server 2016 or any other version
2.	Install iscsi and server for nfs in files and storage

Follow the following steps as shown in image

![Picture19](https://github.com/gurpreet2828/VmwareProject_Images/blob/9799f5483aa8909e9648c04734f8d650402195fb/Picture19.png)

3.	Go to files and storage – Iscsi – create new iscsi VD – automatically calculate the storage – choose fixed – enter name – add  - choose ipaddress(enter esxi ip)  - next – click add – select (enter a value for the selected type) – Choose IPAddress (Enter ESXI IP)
4.	Go to vCenterServer – Select Esxi-Configure- in storage – go to storage adaptor

![Picture20](https://github.com/gurpreet2828/VmwareProject_Images/blob/9799f5483aa8909e9648c04734f8d650402195fb/Picture20.png)

5. Add software iscsi – Next – Complete
![Picture21](
