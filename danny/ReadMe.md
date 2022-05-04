This is Danilexy_hak

OUR FIRST ASSIGNMENT
So, we were told to connect our system to a network that has other devices connected to that network and then scan all the devices on that network.

To get started, we have to connect to the network and then know our device IP address 
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/ifconfig.png)

After knowing my device IP address, i then proceeded to know the gateway of the network i'm connected to.
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/port-scanning.png)

Finally, i scanned all the devices on the network to know the available open ports that could be exploited.
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/Screenshot%20from%202022-04-28%2020-32-52.png)





OUR SECOND ASSIGNMENT
Next up, we captured packets from a network connection i.e we were able to listen to different packets that were communicating while network communication was ongoing.

To get started, we started our wireshark application(a network protocol analyzer)
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/Screenshot%20from%202022-04-28%2020-46-17.png)

Secondly, we proceeded to establish a connection with www.Facebook.com 
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/Screenshot%20from%202022-04-28%2020-48-38.png)

Thirdly, we then  captured packets from the network connection to Facebook.com
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/wireshark.png)

Lastly, we followed the HTTPS protocol stream to listen to some of the conversations that was held in the process of establishing connection
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/tcp%20stream.png)





OUR THIRD ASSIGNMENT
DEAUTHENTICATION USING THE AIRCRACK SUITE IN KALI LINUX

TO start with, we typed iwconfig in the terminal and look for your wireless card (and change the default mode to monitor.
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/deauth1.jpg)

Now run iwconfig again to verify that our interface’s name has changed and that it is indeed in Monitor mode.
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/deauth2.png)

Then,we visualize all Access Points and clients around us and choosing a target
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/deauth3.png)

Once we have located our target AP we will take note of the MAC address (bssid) and the channel it is broadcasting on.
![alt text](https://github.com/danilexy/ProblemSets-1/blob/main/danny/pictures/deauth5.png)


