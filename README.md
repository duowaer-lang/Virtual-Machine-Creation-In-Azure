<p align="center">

<h1>Creating your First Virtual Machine in Azure</h1>
This tutorial outlines the steps required to create your first virtual machine in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

<h2>Configuration Steps</h2>

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

<h2>Setting up Azure</h2>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/Step%201.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1: Creat a free subscription in Microsoft Azure by visiting https://azure.microsoft.com/en-ca/pricing/purchase-options/azure-account/ and click "Try Azure for free"
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%202.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 2: Sign in with a email address you own or create a new one 
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%203.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 3: Once the account is created or you have signed in with your email, to access the portal visit this link: https://portal.azure.com/
</p>
<br />

<h2>Create Resource Group</h2>
<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%204.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 4: Create a resource group by clicking resource group under the Azure services in the portal home page or searching resource groups in the search bar in the middle of the page
</p>
<br />

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%205.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 5: Once inside the Resource manager, you will click on the "+Create" at the top left of the page
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%206.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 6: Add a resource group name and region that will not change throughout this tutorial
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%207.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 7: Click on review + create and create once again at the bottom of the page (it will be blue)
</p>

<h2>Create A Virtual Machine</h2>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/Step%208.png?raw=true " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 8: Search VM in the Azure search bar and click Virtual Machines
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%209.png?raw=true " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 9: You will click on the "+Create" at the top left of the page and choose virtual machine
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2010.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 10: Choose the Resource group we created previously under the Resource group section
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2011.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 11: Choose a name for your virtual machine and have the same region from step 6
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2012.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 12: On the Image section you want to choose Windows 10 Pro, version 22H2 - x64 Gen 2 ( It may also be named Windows 10 Enterprise, version 22H2 - x64 Gen2), If you cannot find it, click on see all images at the bottom
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2013.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 13 (optional): After clicking "see all images" you will click on "select" under "Windows 10" and choose Windows 10 Enterprise, version 22H2 - x64 Gen2
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2014.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 14: Under the "Size" section choose an option with 2 vcpus with 8 GIB memory. If you do not see that option, click on "see all sizes"
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2015.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 15 (optional): After clicking "see all sizes" click on the D-Series v3 drop down and select the first option and click select at the botton left of the page

</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2016.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 16: Under "Administration account" create a username and password that you will remember
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2017.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 17: Tick the box under "Licensing" and click on "Next:Disk:" click again to : Next: Networking"
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2018.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 18: On the Networking page, click on "Edit virtual network" under the "Virtual Network" section
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2019.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 19: Change the name and click save at the bottom left
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2020.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 20: Click "Review + Create" at the bottom of the page and "Create" again
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2021.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 21: You will be led to a page where it says "Deployment is in progress", wait until it says "Your deployment is complete"
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2022.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 22: Search VM again in the search bar and click virtual machines
</p>

<p>
<img src="https://github.com/duowaer-lang/Virtual-Machine-Creation-In-Azure/blob/main/step%2023.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 23: Congratulations! You will see your very first virtual machine with its status/size/ IP Addres
</p>





