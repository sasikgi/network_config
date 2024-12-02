This Bash script is designed to assist with network configuration on Linux systems by allowing users to set a static IP address, subnet mask, and gateway for a specific network interface. The script prompts the user for the necessary network configuration details and applies the settings to the system.

#Features:
User-friendly interface for entering network configuration settings.
Updates the network configuration file /etc/network/interfaces with the provided details.
Restarts the networking service to apply the changes effectively.

#Instructions:
Run the script as root: sudo ./network_config_script.sh.
Follow the prompts to enter the interface name, IP address, subnet mask, and gateway.
The script will update the network configuration and restart the networking service.

#Usage Example:
sudo ./network_config_script.sh

#Note:
Ensure that you have the necessary permissions to modify network settings.
Test the script in a safe environment before applying it to production systems.
