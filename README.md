Iodine network manager helper
Script to prepare iodine-based networking.

Features:
* Replace local dns with providers dns (reduce latency)
* Set up routers (specific routers to dns, default gateway to tunnel)
* Use network manager settings to get information
* check interface status before changing anything

iodine-nm-helper depends on network-manager networking and will not work
without nm-managed network.

Script use /etc/iodine-nm-helper.conf with following options:
* IODINE_SERVIER - domain name to connect via
* IODINE_PASS - password for iodine connection
* MTU - mtu size (not mandatory)
* REMOTE - remote IP

  
