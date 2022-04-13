# 1.
Problem 1;

Sent icmp packets (Ping) to these sites using terminal, and retrieved their static IP addresses;

Google.com - 216.58.223.238
Facebook.com - 102.132.101.35
Amazon.com - 176.32.103.205
herokuapp.com - 54.160.84.228
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

Problem 2

For this problem, I connected my phone to my computer using Xender, then I scanned the IP address from Xender connecting my Pc and Phone using Zenmap app.

Before scanning, I sent packets to the IP (172.20.10.1) using the ping command

After scanning, I got the following open ports;

21 - Ftp
53 - Domain 
6789 - Ibm-db2-admin
62078 - iPhone-sync

I was able to connect to these ports successfully using Netcat on terminal.