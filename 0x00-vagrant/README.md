## Setting up Zero Day Environment

### Creating a New Directory and Adding a README

1.**Navigate to the Zero Day Repository**: First, navigate to the 'zero_day' repository on your local machine.
2.**Create a New Directory**: Inside the 'zero_day' repository, create a new directpry called '0x00-vagrant'.
3.**Add a README.md File**: Enter the newly created directory and add a README.md file

### SSH into Ubuntu VM and Retrieve System Information

1.**SSH into Ubuntu VM**: Use the 'ssh' command to connect to your Ubuntu VM. Replace '<username>' with yoour username and '<ip_address>' with the IP address of your VM.

  ssh <username>@<ip_address>

2.**Run the 'uname' Command**: Once connected to the VM, run the 'uname' command without any options to rerieve system information
3.**Record the Output**: Take note of the output of the 'uname' command. This information will be used to answer the question
