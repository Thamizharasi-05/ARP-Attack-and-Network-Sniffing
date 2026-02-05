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

<img width="654" height="336" alt="Screenshot 2026-02-05 134830" src="https://github.com/user-attachments/assets/b3f74237-f9ca-45fd-b0cd-928748cd471d" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="731" height="370" alt="image" src="https://github.com/user-attachments/assets/1e5a7455-b988-42e3-8aee-4a18ba3cc610" />

## dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="803" height="344" alt="image" src="https://github.com/user-attachments/assets/6a646726-a9b5-4c79-8cdf-1d0c3adb8c68" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="255" height="83" alt="image" src="https://github.com/user-attachments/assets/c401b2e5-f367-43f4-8218-70f61706f758" />

Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1690" height="945" alt="Screenshot 2026-02-05 141354" src="https://github.com/user-attachments/assets/0a74a4b2-9274-4c85-be23-81dadb511f03" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
