
<h2>Download Metasploitable</h2>
<a href="https://sourceforge.net/projects/metasploitable/files/latest/download">Click here</a> to download the Metasploitable 2 VM. The file you download will be approximately 800 MB in size and will come in a zip format.

<h2>Extract the Zip File</h2>
After downloading, extract the contents of the zip file. You should see several files including a .vmdk file which is crucial for setting up the VM.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/Extract%20file.jpg">

<h2>Open VirtualBox</h2>
Launch VirtualBox on your computer. If you haven't installed VirtualBox,I have created a guide on Setting up a home lab <a href="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Walk%20Through%20for%20creating%20Windows%20Virtual%20machine.md">here</a>

<h2>Create a New Virtual Machine</h2>
Click on "New" to start the VM creation wizard. 
Name the VM something descriptive like "Metasploitable2". 
Choose the operating system type as "Linux" and the version as "Ubuntu" since Metasploitable 2 is based on Ubuntu.

<img src=https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/New.jpg>


<h2>Set Memory Allocation</h2>
Allocate memory to the VM. 512MB is often recommended, but you can adjust based on your system's capabilities and needs.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/Allocate%20memory.png">

<h2>Use Existing Hard Disk</h2>
Instead of creating a new virtual hard disk, select the option "Use an existing virtual hard disk file." 
Navigate to the folder where you extracted the Metasploitable files and select the .vmdk file.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/Existing%20HDD.png">

<h2>Configure the Network</h2>
Ensure that your network settings are configured appropriately. It's recommended to use NAT or Host-only network settings to keep the VM isolated from public networks, as Metasploitable should never be exposed to untrusted networks.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/VM-Network.jpg">

<h2>Start the VM</h2>
Click on "Start" to boot the VM. After booting, you'll be prompted to log in. The default username and password for Metasploitable 2 are both msfadmin.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/Start%20MTSP.png">

<h2>Verify Installation</h2>
Once logged in, you can verify the setup by running commands like ifconfig to see the IP address assigned to Metasploitable, which you can use for further penetration testing practices.

<img src="https://github.com/Corporate101/Setting-up-a-Virtual-home-Lab/blob/main/Folder/Ifconfig%20MTSP.png">

This should give you a working Metasploitable 2 environment in VirtualBox for security testing purposes. Remember, this VM is intentionally vulnerable, so be cautious with its network configuration to avoid security risks.

