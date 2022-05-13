### REGISTRY
##### I pressed Windows key + R. In the run box, I typed regedit, and press enter.
##### I Pasted the path in the address bar: Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run.
##### Right click on run and create new string value Edit the name to what you want and modify the value data to program path ypu want to run on boot
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/Screenshot%20(4).png)
##### I opened command prompt administrative and I pasted the path of the app on it.
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/Screenshot%20(9).png)
##### I restarted my device and the modified app popped up immediately
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/Screenshot%20(10).png)



### NMAP PORT
Nmap 192.168.43.176

Nmap -sV 192.168.43.176

##### arp -a to scan hosts up 
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/p1.png)
##### Nmap -sV 192.168.43.28 to identify our target 
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/p2.png)
##### Nmap -sV 192.168.43.28 to confirm the host up
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/p4.png)



### Enable promiscious mode on all interface in wireshark
##### To turn on promiscuous mode, click on the CAPTURE
##### Then click OPTION
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/Screenshot%20from%202022-05-09%2020-09-00.png)
##### Now select it from the options
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/Screenshot%20from%202022-05-09%2020-10-35.png)


### Arpspoof
##### Directing the traffic to my network

##### Lauch the attack with - sudo arpspoof- -i wlan0 -t 192.168.43.223 -r 192.168.43.1 
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/arpspoof.png)
##### How to identify your target - sudo nmap 192.168.43.0-255
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/arpspoof1.png)


### (http)Facebook.com sniffing with wireshark
##### Open wireshark and double click on wlan0 to view all logs
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/wireshark.png)
##### You see something like this after double clicking on WLAN0
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/wiresharksniffing.png)
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/wiresharksniffing1.png)
##### go to your browser and type facebook.com, make sure you wireshark is still sniffing
##### now search http on wireshark
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/wiresharkhttpresponse.png)


### Deauth Attack
##### A wireless Adapter is required to perform this attack
##### The wireless adapter as to be in monitor mode to perform this attack
##### Open your terminal and type IWCONFIG and select your adapter, normally in WLAN0
##### To put the adapter in monitor mode we'll need to run the aircrack command "airmon-ng"
##### Now we have to kill any process that might interfere our attack. Run "airmon-ng check kill" to kill the process.
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/b1.png)
##### Type "sudo airodump-ng wlan0mon" to view all networks nearby
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/b2.png)
##### Now type sudo airodump --bssid (targets bssid) --channel (targets channel) wlan0mon
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/b3.png)
##### Now let's deauth our target. Type "sudo aireplay-ng --deauth 1000 -a (targets bssid) wlan0mon
##### ![ait text](https://github.com/mitchell-d-coder/ProblemSets/blob/main/Mitchell/Picture/b5.png)



5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
