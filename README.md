# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/manikandan26052004/ARP-Attack-and-Network-Sniffing/assets/121999845/83b6a08c-34ba-4f1b-8f73-9bd59861b188)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/manikandan26052004/ARP-Attack-and-Network-Sniffing/assets/121999845/ce630157-cffe-419d-af72-060ac3c4afae)


 dsniff:



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/manikandan26052004/ARP-Attack-and-Network-Sniffing/assets/121999845/a7e6e111-e692-485b-aec2-83a4a8896ca0)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/manikandan26052004/ARP-Attack-and-Network-Sniffing/assets/121999845/20a374ff-9211-451e-bd62-668827ecc69e)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/manikandan26052004/ARP-Attack-and-Network-Sniffing/assets/121999845/4336abd3-0507-4d00-aec2-653d78de7f24)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
