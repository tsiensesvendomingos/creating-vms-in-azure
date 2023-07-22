<h1>Creating Virtural Machines in Microsoft Azure</h1>


<h2>Description</h2>
A Microsoft Azure account is required for everything covered in this Portfolio. This can be obtained by signing up for a free Microsoft Azure Account. A debit or credit card will be required for signup. As of the creation of this page, Azure offers $200 worth of credits to use for a big library of tools that Azure has to offer. These credits are able to create and run the virtual machines we used in the portfolio to simulate the projects we conducted.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Creation walk-through:</h2>

<p align="center">
Start by heading to Azure by browsing to portal.azure.com. Once there, search for Virtual Machines. Under services, select Virtual Machines: <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/eab0fa46-0188-4c1c-97dc-f987ae93fdb7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To create the VM, click on Create in the middle of the page. That should show a drop-down menu. Click then on "Azure virtual machine":  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/294636af-d457-4643-b883-2b76f7779939" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
That will open the Virtual Machine creation page. Here you will select the subscription you created at creating your Azure account. Creating a new VM will automatically create a new resource group. If you already have a RG created, you can select to put your created  You can then give the machine a name and region, as well as an operation system image: <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/e88f1da7-8da7-4492-8d9c-db51bc51f8cc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scrolling down the page, we can select the VM size, the amount of the virtual CPUs, and the ram the VM will possess. Due to this being a free subscription with credits, we are limited to a maximum of 4 vcpus that can be running at once. We can then create an admin account complete with a username and password. Don't forget to check the box under licensing. We can then check Networking to make sure the VM has internet connectivity.:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/33775d84-f566-4f86-b75a-6ed9cec7346e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
