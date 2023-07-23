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
That will open the Virtual Machine creation page. Here you will select the subscription you created at creating your Azure account. Creating a new VM will automatically create a new resource group. If you already have an RG created, you can select to put your created  You can then give the machine a name and region, as well as an operation system image: <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/e88f1da7-8da7-4492-8d9c-db51bc51f8cc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scrolling down the page, we can select the VM size, the amount of the virtual CPUs, and the ram the VM will possess. Due to this being a free subscription with credits, we are limited to a maximum of 4 vcpus that can be running at once. We can then create an admin account complete with a username and password. Don't forget to check the box under licensing. We can then click Networking by scrolling back up to the top to make sure the VM has internet connectivity when we have finished configuring the basics:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/33775d84-f566-4f86-b75a-6ed9cec7346e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Opening this tab will automatically create a Virtual Network, Subnet, and Public IP. This is noted by the "new" in the parentheses of each category. Once confirmed that the network is all setup, we can then click on the blue box at the bottom of the page that says "Review + create":  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/3fd3b855-09a9-4be7-b7fb-981c87f6d2f6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Clicking the button will run a quick validation to ensure that the VM can run properly. A prompt stating that the Validation was succeeded will show on top of the page. On this page, we'll see the cost the VM will incur per hour as well as a list summary of the VM you configured. We can then click "Create" in the blue box at the bottom of the page to confirm everything and start the deployment of the VM:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/c4364901-22f3-4407-95ea-5498678a20b0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Let the deployment commence (it may take some time) The screen will change when the deployment is complete:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/936191b2-a125-4234-a4e7-c35a80fb77cf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/0fac1a84-3a80-4787-9432-0609b78a253d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
It is now time to connect to your freshly deployed Virtual Machine. To start, click on "Go to recourse to grab the public IP address. This is needed to connect to the VM using  Remote Desktop Connection:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/3933f558-2185-4b74-960a-69857b76ffe7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now let's connect to our VM using Remote Desktop Connection. Start by simply searching for "Remote Desktop" using the search bar in the taskbar and open the first app that comes up:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/a72d062a-9ca4-4e46-8e8f-4acf9d8e36f0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
When the app launches, you can type the Public IP address in the computer column. Click "Connect" to initiate the connection to the VM:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/0c8fd7b0-8a00-4abb-9923-abe5f481c429" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Initiating the connection will bring up a Microsoft Security window asking you to enter the credentials for the machine you're trying to connect to in the form of a username and password. We're not connecting using my credentials because we set it to something different when we created the VM. So we will click on "More choices" and then "Use a different account":  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/74f18f0c-99e6-4309-8cd2-3f948d534721" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This will clear out the Username field allowing us to type in the credentials we created when setting up the VM. Type them in and click "OK" to continue:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/6c737a0d-5823-43f9-a346-a9b0ee713d89" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Continuing will bring up one final warning prompt. Under the certificate name box, you should see the name that you set your VM to. In our case, it's VM1. This is good as this indicates we connected to the VM we intended to connect. Hit "yes" at the bottom of that window to connect to the VM:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/0ad94d8c-0cec-41e8-9a51-604e93e791c8" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Congratulations! You have successfully created and connected to your Azure Virtual Machine:  <br/>
<img src="https://github.com/tsiensesvendomingos/creating-vms-in-azure/assets/138411730/7a862af3-e309-44b8-8a87-37a383c598f3" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
