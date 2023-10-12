# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## ALGORITHM:

1) Install kali linux either in partition or virtual box or in live mode

2) Investigate on the various categories of tools as follows:

3) Open terminal and try execute some kali linux commands


## METHODS:

### ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a

#### OUTPUT:

![e1](https://github.com/Vishwarathinam/ARP-Attack-and-Network-Sniffing/assets/95266350/c659deb0-9c6e-4c9a-8587-2e8e40bbf375)




### From kali linux issue the command : sudo arpspoof -i eth0 -t <target system> <gateway>

#### OUTPUT:

![e2](https://github.com/Vishwarathinam/ARP-Attack-and-Network-Sniffing/assets/95266350/37ef8a6b-e3b0-4f91-aa3c-f11fec2f5d3e)




### dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

![e3](https://github.com/Vishwarathinam/ARP-Attack-and-Network-Sniffing/assets/95266350/b18b322a-1787-43db-b674-d57d02d9fcb3)



### In Kali issue the following commands:  sudo dsnifff

#### OUTPUT:

![e4](https://github.com/Vishwarathinam/ARP-Attack-and-Network-Sniffing/assets/95266350/cd5b98ff-f5cc-4950-a26e-eb5f2ae35971)



### Invoke the wireshark and examine the various menus and controls of the tool:

![e5](https://github.com/Vishwarathinam/ARP-Attack-and-Network-Sniffing/assets/95266350/2c09b40e-ec42-4e7a-8099-5b2df60cc3ef)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
