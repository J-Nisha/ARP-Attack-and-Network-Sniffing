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
<img width="639" height="384" alt="image" src="https://github.com/user-attachments/assets/42fce08d-f488-4db9-a322-e5c96a7bc2f8" />



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="658" height="577" alt="image" src="https://github.com/user-attachments/assets/a31fd689-9104-48dd-aa5e-39446d8c63ed" />





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="613" height="269" alt="image" src="https://github.com/user-attachments/assets/bc1e87dd-d433-4f2d-8eea-60a857c7cafd" />




Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="745" height="574" alt="image" src="https://github.com/user-attachments/assets/2f306ace-ca92-48b1-84df-39b0399e33b6" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
