# HA and DRS

<br>**HA**: High Availability</br>
<br>**DRS**: Distributed Resource Scheduler</br>

### Cluster
VMware, a cluster is a group of physical servers, or hosts, that share resources and work together under one IP address. The cluster manages the resources of all the hosts within it

**Step 1: Create a cluster**

<br>Right click on datacentre- cluster – create a new cluster</br>
<br>Right click on cluster – setting</br>

As shown in bellow picture

![Picture14](https://github.com/gurpreet2828/VmwareProject_Images/blob/2d3e04b1e2c764aad9652eff04e575eec1a84992/Picture14.png)

**Step 2:** Click on vSphere Availability – Edit – check on (put all setting default)

![Picture15](https://github.com/gurpreet2828/VmwareProject_Images/blob/2d3e04b1e2c764aad9652eff04e575eec1a84992/Picture15.png)

**Step 3:**
Generally I have two host running ESXI01 and ESXI02

In ESXI02 only 1 VM is running as shown in following picture

![Picture16](https://github.com/gurpreet2828/VmwareProject_Images/blob/2d3e04b1e2c764aad9652eff04e575eec1a84992/Picture16.png)

In ESXI01 4 VM's are runnning as shown in following picture

![Picture17](https://github.com/gurpreet2828/VmwareProject_Images/blob/172c1f796608a0aca8ccb06c558a808df8d073b6/Picture17.png)

**Step 4**
Now I am going to shutdown the ESXI02 host and you will see all the VM in esxi02 moved to ESXI01

After some time you will see WIN7-VM1 ruuning in ESXI02 moved to the ESXI01 as shown bellow

![Picture18](https://github.com/gurpreet2828/VmwareProject_Images/blob/9870a491d816853f10f6142111f035976871cb3d/Picture18.png)


## HA and DRS completed 





