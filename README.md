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
![image](https://github.com/user-attachments/assets/031870a2-8a47-47e2-948c-05c07a8bf08e)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/557b6bad-bde9-44f0-806d-f3ed0ded972d)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/3129c6d9-7fe1-456b-947b-8bd9963a7bf8)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/37767cdc-ebbf-4f4c-918b-e8dc8d73a967)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/9b8608eb-7e8e-4f59-8a79-3bf716f82d1d)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
