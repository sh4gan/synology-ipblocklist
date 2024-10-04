# Synology IP Block List
This is the repository for storing IP addresses of bots which could attack your NAS server like Synology, TrueNAS, QNAP etc.

![alt text](https://www.lenharthsystems.com/wp-content/uploads/2017/12/sliders-synology.jpg)

If you’re looking to get reduce amount of warnings belong to bots keeping trying to login on your server feel free to used my list which you could add in bulk to your NAS firewall. 

## Installing
To add IP addresses to banlist you need to download deny-ip-list and upload it to synology nas security black-list.
1. Download deny-ip-list
2. Login to your DSM and open settings.
3. Go to Network Center > Security > Auto Block.
4. Click Allow/Block List.
5. On the Block List tab, select "Import IP address list" from the Create drop-down menu.
6. Import a text file containing the IP addresses to add and enter an expiration time. 
7. Click OK to import.
8. Click Close to finish.


## Tips
1. You may choose to overwrite existing IP addresses from both allow/block lists. If this option is not selected, duplicate IP addresses will be skipped.
2. If the file you selected follows the correct format, IP addresses will be listed.
