<p align="center">

<h1>Creating your First Virtual Machine in Azure</h1>
This tutorial outlines the steps required to create your first virtual machine in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Creat a free subscription in Microsoft Azure by visiting https://azure.microsoft.com/en-ca/pricing/purchase-options/azure-account/ and click "Try Azure for free"
- Step 2: Sign in with a email address you own or create a new one 
- Step 3: Once the account is created or you have signed in with your email, to access the portal visit this link: https://portal.azure.com/
- Step 4: Create a resource group by clicking resource group under the Azure services in the portal home page or searching resource groups in the search bar in the middle of the page
- Step 5: Once inside the Resource manager, you will click on the "+Create" at the top left of the page
- Step 6: Add a resource group name and region that will not change throughout this tutorial
- Step 7: Click on review + create and create once again at the bottom of the page (it will be blue)
- Step 8: Search VM in the Azure search bar and click Virtual Machines
- Step 9: You will click on the "+Create" at the top left of the page and choose virtual machine
- Step 10: Choose the Resource group we created previously under the Resource group section
- Step 11: Choose a name for your virtual machine and have the same region from step 6
- Step 12: On the Image section you want to choose Windows 10 Pro, version 22H2 - x64 Gen 2 ( It may also be named Windows 10 Enterprise, version 22H2 - x64 Gen2), If you cannot find it, click on see all images at the bottom
- Step 13 (optional): After clicking "see all images" you will click on "select" under "Windows 10" and choose Windows 10 Enterprise, version 22H2 - x64 Gen2
- Step 14: Under the "Size" section choose an option with 2 vcpus with 8 GIB memory. If you do not see that option, click on "see all sizes"
- Step 15 (optional): After clicking "see all sizes" click on the D-Series v3 drop down and select the first option and click select at the botton left of the page
- Step 16: Under "Administration account" create a username and password that you will remember
- Step 17: Tick the box under "Licensing" and click on "Next:Disk:" click again to : Next: Networking"
- Step 18: On the Networking page, click on "Edit virtual network" under the "Virtual Network" section
- Step 19: Change the name and click save at the bottom left
- Step 20: Click "Review + Create" at the bottom of the page and "Create" again
- Step 21: You will be led to a page where it says "Deployment is in progress", wait until it says "Your deployment is complete"
- Step 22: Search VM again in the search bar and click virtual machines
Step 23: Congratulations! You will see your very first virtual machine with its status/size/ IP Address

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/duowaer-lang/Storage-Account-Creation/blob/main/Resource%20Step%202.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1
 : Search Resource Groups and click on create at the top left of the page ( It will have a + sign) in Microsoft Azure
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Storage-Account-Creation/blob/main/Resource%20Step%203.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2
 : Make sure to add a name to your resource group and to choose the appropriate region
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Storage-Account-Creation/blob/main/Resource%20Step%204.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5
 : Be sure to use the resource group you created in step 1 on the resource group option below subscription

  Step 6
 : Add a unique name to the storage account

Step 7 
: Click on review + create and create once again
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Storage-Account-Creation/blob/main/Resource%20Step%209.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 9
 : Check if your storage account is in the right resource group in the resource group column
</p>
<br />
