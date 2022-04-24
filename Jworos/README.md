# 1.
## Problem 1;

Sent icmp packets (Ping) to these sites using terminal, and retrieved their static IP addresses;

### Google.com - 216.58.223.238

#### Facebook.com - 102.132.101.35
#### Amazon.com - 176.32.103.205
#### Herokuapp.com - 54.160.84.228
Scanned the ports of the sites using the Zenmap standalone app, and connected successfully to all the ports using terminal.

Ports on Google.com

21/Ftp - Open 25/Smtp - Open 80/Http - Open 443/ Https - Open 587/Submission - Open

Ports on Facebook.com

21/Ftp - Open 25/Smtp - Open 80/Http - Open 443/ Https - Open 587/Submission - Open 843/Unknown - Closed 5222/Xmpp-client - Closed

Ports on Amazon.com

Amazon came up with 3 IP addresses after scanning:

176.32.103.205
205.251.242.103
54.239.28.85 - this IP came up with 13 filtered ports
21/Ftp - Open 25/Smtp - Open 80/Http - Open 443/ Https - Open 587/Submission - Open

Ports on Herokuapp.com Amazon came up with 3 IP addresses after scanning:

54.160.84.228
52.200.177.141
21/Ftp - Open 25/Smtp - Open 80/Http - Open 443/ Https - Open 587/Submission - Open

Tested all open ports, also tested the closed port from Facebook.com, but that didn’t connect.

Created a new Git Repo, cloned it using terminal, edited the README.md file in VSCODE, and commited the edit using terminal after saving on VsCode.

To upload the photos, after commiting the changes to the document to github, i edited the file on Git, then dragged and dropped the photo on the editor to upload it.
<img width="1148" alt="Screenshot 2022-04-12 at 20 18 57" src="https://user-images.githubusercontent.com/85462184/163120594-6cea4625-d3d2-4c68-a95d-b87240547cf3.png">
<img width="592" alt="Screenshot 2022-04-12 at 21 03 14" src="https://user-images.githubusercontent.com/85462184/163120801-1a57f54e-4af8-4295-91a8-579f2d932b30.png">
<img width="579" alt="Screenshot 2022-04-12 at 20 52 10" src="https://user-images.githubusercontent.com/85462184/163120844-a784b499-2a5f-486d-bab0-bae950ad53a9.png">



## Problem 2

For this problem, I connected my phone to my computer using Xender, then I scanned the IP address from Xender connecting my Pc and Phone using Zenmap app.

Before scanning, I sent packets to the IP (172.20.10.1) using the ping command

After scanning, I got the following open ports;

21 - Ftp
53 - Domain 
6789 - Ibm-db2-admin
62078 - iPhone-sync

I was able to connect to these ports successfully using Netcat on terminal.
<img width="1440" alt="Screenshot 2022-04-12 at 21 09 15" src="https://user-images.githubusercontent.com/85462184/163120417-f3f81ce9-d3ec-43d1-b98c-a5f6cfe2808e.png">
<img width="586" alt="Screenshot 2022-04-12 at 21 05 41" src="https://user-images.githubusercontent.com/85462184/163120466-7654a8c4-6560-489f-9280-7c0809678a02.png">

## Problem 3

First i downloaded iSH app on my iOS device, and Termux app on my android device, i opened a port on my Android device via Termux and connected to the open port using iSH app on the iOS device, everything worked smoothly, i was able to send messages back and forth.
![IMG_1006](https://user-images.githubusercontent.com/85462184/164911487-1e5ae824-3d84-41cf-a83a-f48a485124d0.PNG)
![Screenshot_2022-04-22-18-14-16-760_com termux](https://user-images.githubusercontent.com/85462184/164911616-03d3fe19-4d10-4bf1-9986-a4e2a4ae36d1.jpg)

On my Mac Pc, i had issues using the Netcat command, initially, i used "nc" command when trying to open a port, but after some research, i found the correct command to use, which was "ncat".

Afer getting the command right, everything worked perfectly.
![IMG_1093](https://user-images.githubusercontent.com/85462184/164911424-81025bb4-d67c-4172-bbdc-136ce080670c.PNG)


<img width="1047" alt="Screenshot 2022-04-23 at 15 30 52 1" src="https://user-images.githubusercontent.com/85462184/164911381-6b09e561-d7e1-42c4-902e-ce15395c3557.png">
