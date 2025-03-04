
This is a general how-to for working within the Linux terminal. 

**Objective:** Getting more comfortable with utilizing the command line without the GUI (Graphical User Interface)

**Setting up the Environment**

**VirtualBox Download**
	Download a virtual environment that is able to host virtual machines. We are going to be using VirtualBox, however there are plenty of other programs out there.
	**Download Link**: https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html?source=:ow:o:p:nav:mmddyyVirtualBoxHero&intcmp=:ow:o:p:nav:mmddyyVirtualBoxHero
		This download link above gives us the option to install on Windows, Mac, or Linux. Choose whichever one is the base OS of your system and download/run the installer. 

**VM Image**
	We are going to be installing the latest version of RHEL 9.5. 
		**Download Link:** https://developers.redhat.com/products/rhel/overview (Requires RHEL Account)
			Download is going to look something like this: rhel-9.5-x86_64-boot.iso
		If all is good with the download let's move on. 

**Creating Virtual Machine**
	1. Open VirtualBox
	2. Hit the "New" button on the top bar
	3. Enter the following Parameters
		1. **Name:** RedHat 
		2. **Folder:** C:\Users\yourpc\VMs
		3. **ISO Image**: rhel-9.5-x86_64-boot.iso
		4. **Type:** Linux
		5. **Version:** Red Hat 9.X
		6.  **Base Memory:** 4096MB
		7. **Processors:** 2
		8. **Create Virtual Hard Disk Now:** 40.00 GB
	Once all settings have been configured, let's try to boot up the virtual machine.  