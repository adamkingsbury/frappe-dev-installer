# frappe-dev-installer
A script to spin up a frappe development environment. I intended this to be used inside a Linux Mint 19 VM

## How to use
1. Download or copy the contents of the frappe-dev-installer file to your local environment (inside the VM where you want to set up the dev environment).
1. Set the file to be executable "chmod +x frappe-dev-installer"
1. If needed, add in any additional app installs required in the placeholder in the file.
1. Run the installer by calling: "./frappe-dev-installer"
1. Restart the virtual machine to ensure you pick up full security permissions

## Running the dev environment
To gracefully start up the development environment:
1. Open a terminal window and make sure you are in your home directory
2. run the quickstart application by calling: "./quickstart"
3. The script will start up the docker servers and start frappe in development mode. Do not close the window while you are developing (you can hide or minimise it)


## Stopping the development environment
To gracefully stop the development environment:
1. Go to/reopen the terminal window running the frappe server.
1. Press "ctrl-c" to stop the frappe services
1. Call "./quickstop" to gracefully shutdown the docker servers
