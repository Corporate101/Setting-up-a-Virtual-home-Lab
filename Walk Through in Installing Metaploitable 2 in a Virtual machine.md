
<h2>Download Metasploitable</h2>
<a href="https://sourceforge.net/projects/metasploitable/files/latest/download">Click here</a> to download the Metasploitable 2 VM. The file you download will be approximately 800 MB in size and will come in a zip format.

Extract the Zip File:
After downloading, extract the contents of the zip file. You should see several files including a .vmdk file which is crucial for setting up the VM.

<img src= >

Open VirtualBox:
Launch VirtualBox on your computer. If you haven't installed VirtualBox, you need to do so before proceeding.

Create a New Virtual Machine:
Click on "New" to start the VM creation wizard. 
Name the VM something descriptive like "Metasploitable2". 
Choose the operating system type as "Linux" and the version as "Ubuntu" since Metasploitable 2 is based on Ubuntu.



Set Memory Allocation:
Allocate memory to the VM. 512MB is often recommended, but you can adjust based on your system's capabilities and needs.


Use Existing Hard Disk:
Instead of creating a new virtual hard disk, select the option "Use an existing virtual hard disk file." 
Navigate to the folder where you extracted the Metasploitable files and select the .vmdk file.



Configure the Network:
Ensure that your network settings are configured appropriately. It's recommended to use NAT or Host-only network settings to keep the VM isolated from public networks, as Metasploitable should never be exposed to untrusted networks.

Start the VM:
Click on "Start" to boot the VM. After booting, you'll be prompted to log in. The default username and password for Metasploitable 2 are both msfadmin.


Verify Installation:
Once logged in, you can verify the setup by running commands like ifconfig to see the IP address assigned to Metasploitable, which you can use for further penetration testing practices.

This should give you a working Metasploitable 2 environment in VirtualBox for security testing purposes. Remember, this VM is intentionally vulnerable, so be cautious with its network configuration to avoid security risks.

