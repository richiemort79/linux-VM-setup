# linux-VM-setup
A bash script to set up Lancaster University virtual Linux installations for image analysis. 

The script adds an fstab entry for MortLab and mounts it. Customise the lines after '#create the Mortlab directory in home if it does not exist' to point it at a different /luna share.

The script installs:

gnumeric;
inkscape;
Fiji; (in your home directory)

Customise the lines after '#install useful software' to add over software form the BioLinux repos.

It adds the following toolsets to Fiji:

Cell_Patterning.ijm
Fucci_Tools.ijm

Customise the lines after '#add cell_patterning and fucci_tools toolsets' to add other macros/plugins/toolsets

Usage:

Log onto a virtual BioLinux machine at https://mylab.lancaster.ac.uk/ using your LU credentials.

Download the .zip archive and extract. Enter the 'linux-vm-setup main' directory and right click on the 'linux-VM-setup' file.

Change the permissions of 'linux-VM-setup' to 'Allow executing file as program'.

Run the script from the terminal with sudo permissions:

$ sudo ./linux-VM-setup

When prompted enter your LU password, you will also be prompted to enter the name of your home directory on the Mort Lab luna share.



