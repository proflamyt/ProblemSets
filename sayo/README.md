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
