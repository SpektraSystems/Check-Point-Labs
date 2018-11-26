# Check-Point-Labs

# Accessing Hands-on Labs Check Point CCSE/CCSA

# Overview
This lab guide will help you in getting started on accessing the hands-on lab infrastructure for
Checkpoint CCSA/CCSE Lab. 

# Contents 
* Checkpoint CCSE/CCSA Certification: Accessing Hands-on Labs
1. [Registration for the Labs](#Registration-for-the-labs)
* [Lab Overview](#lab-overview)
* [Prerequisites](#Prerequisites)
* [Time estimate](#Time-estimate)
* [Exercise 1: Register for the Lab](#Exercise1-op1)
* [Exercise 2: Access the CCSE/CCSA Host Lab Server and VMs](#Exercise2)
* [Exercise 3: Start VMs using Hyper-V](#Exercise3)
* [Exercise 4: Start,Stop,Restart the Lab Server](#Exercise4)
<a name="Registration-for-the-labs"></a>
# 1. Registration for the Labs 
<a name="lab-overview"></a>
# Lab Overview:
There’re two ways you could register for the labs., One is when an instructor provides you a signup
link with voucher, second when you receive an exclusive invite. Please follow steps based on the registration details
provided to you.
<a name="Prerequisites"></a>
# Prerequisites:
* You should have received a lab registration URL from your instructor OR
* You should have received an exclusive invite for the lab signup
* Modern Web Browser and Microsoft Windows Remote Desktop. RDP is included by default in Windows, If you're using Apple Mac, Please download RDP from App Store: https://itunes.apple.com/us/app/microsoft-remote-desktop-10/id1295203466?mt=12
<a name="Time-estimate"></a>
# Time Estimate
 2 Minutes
 <a name="Exercise1-op1"></a>
 # Exercise 1-Option-1: Register for Lab using signup link.
 1. **Launch** a modern web browser(Edge,Chrome,Firefox etc.) and open the lab registration
portal. **URL** should be provided to you by your instructor. Please note that you may also be required to have an activation or voucher code depending upon your labs arrangement. Please consult with your instructor. 
2. **Enter** the required details and click on **Submit**
 ![](images/image1.png)
3. Once registration is completed, **Click on Launch Lab** WHEN you’re ready to start the lab.
Note that the lab environment provisioning will start as soon as you click on Launch Lab. So
you should do this only once you’re ready.
 ![](images/image2.png)
4. This will start provisioning the lab environment. Note that this can take around 10-20 minutes for
the lab environment provisioning to finish. You can close this web browser if you wish to,
you’d get another email with lab details once provisioning is completed. 
 ![](images/image3.png)
5. Once provisioning is completed, you’d find following details on lab details page and the
email.
 * Azure Login Username Password: This is just to look at azure infrastructure (Read access).
 * CCSE/CCSA Host DNS Name: You’d use this to take RDP of the Host Machine.
 * CCSE/CCSA Host Credentials: Username and password for the host to take remote desktop. 
![](images/image4.png)
6. At any point, if you close the lab details web browser, you can always click on Launch lab during the
lab duration and this will open up web page with lab details.
<a name="Exercise1-op2"></a>
## Register via Custom Invite 
1. You’d have received an automated invite to launch the Lab. Click on Launch Lab, Once you’re
ready to start the lab.
![](images/image5.png)

2. This will open up a web page, **Click on Launch Lab** again WHEN you’re ready to start the lab.
Note that the lab environment provisioning will start as soon as you click on Launch Lab.
![](images/image2.png)

3. This will start provisioning the lab environment. Note that this can take around to 15 - 20 minutes for the
lab environment provisioning to finish. You can close this web browser if you wish to, you’d get
another email with lab details once provisioning is completed. 
4. Once provisioning is completed, you’d find following details on lab details page and the
email.
 * Azure Login Username Password: This is just to look at azure infrastructure (Read access).
 * CCSE/CCSA Host DNS Name: You’d use this to take RDP of the Host Machine.
 * CCSE/CCSA Host Credentials: Username and password for the host. 
 ![](images/image4.png)
5. At any point, if you miss the lab details, you can always click on **Launch lab** during the lab duration and this will open up web page with lab details. 
<a name="Exercise2"></a>
# Exercise 2: Access the CCSE/CCSA Host Lab Server and VMs

**In this exercise, you will take remote of the CCSE/CCSA Lab Server** 
1. Copy the CCSE/CCSA Host DNS Name from lab details webpage/email
2. Launch Microsoft RDP Client, by searching for remote desktop in Start Menu or entering mstsc
in run/command prompt.
3. Enter the DNS name in computer field copied from lab details.
![](images/image6.png)

4. Click on **More Choices** if you get a prompt with your local username.
![](images/image7.png)
5. Enter the Host VM credentails(**Admin/Chkp!234**) 
6. Check the option for Don’t ask me again for connection and Click on **Yes** if prompt as shown
below:
![](images/image8.png)
7.  Once you’re inside the server, You can launch **Hyper-V Manager** available on task bar to
connect to CCSA VMs. 
 ![](images/image09.png)

8. You’d see list of all VMs in Hyper-V Manager. You can connect to a VM by right clicking on it
and saying connect. Accept the default resolution option if asked. 
![](images/image100.png)
<a name="Exercise3"></a>

# Exercise 3: Start Check Point Lab VMs using Hyper-V Manager
**In this exercise, you will use Hyper-V Manager to start VMs**
1. Once you’re inside the server, You can launch **Hyper-V Manager** available on task bar to
connect to CCSA VMs. 
 ![](images/image09.png)
2. You’d see list of all VMs in **Hyper-V Manager**. You can start the VM by just clicking on it and
select Start option on the right pane of the window.
![](images/image12.png)
3. This will start the VM
![](images/image13.png)

> Note: Please start the VMs Router and A-LDAP before you start any other VMs
<a name="Exercise4"></a>
# Exercise 4: Start,Stop,Restart the Lab Server. 

1. If by mistake, you end up shutting down the host lab server itself, you can start this by
following below instructions.
2. Click on the launch lab link from the emails again. This will open up your lab details page.
3. Click on Virtual Machines, As specified in below link. 
 ![](images/image14.png)
4. You can use toolbar items to start/restart/stop the server. 
 ![](images/image15.png)
 
 > Please note that these operation might take 5 to 10 minutes to complete. Please wait for few minutes before trying to take remote access of the server. 
 
 
 # Contact for Support
 
 Please reach out to your instructor for any support. If you've any lab environment related issues or questions, you/your instructor can reach via email on cloudlabs-support@spektrasystems.com


