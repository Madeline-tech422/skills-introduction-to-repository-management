Case: Pigs Rule

Executive Summary: Gained intel about the Hacktivists throughout the globe who plan to launch a hacking campaign against your country. Required to sniff the ongoing incoming traffic, indentify the malicious traffic.

Then, I was required to create a custom snort rule to alert for malicious traffic. I was also required to capture a tcpdump and then required to save it and monitor the traffic and then send it to snorby to see the flag.

Finding: 

Process

Finding details: 

Cat README

Description:

A process that gave the commands to edit, send, and filter traffic

This command was discovered by using ls to see if the README file was in the directory then using the cat command to show the contents of the file

Finding:

Process

Finding Details:

Nano

Description:


Edits rules so you can add or delete, or change the rules

This process appeared when I used nono /etc/snort/rules/local.rules to get into and add the rule to detect malicious traffic and alert for it

Methodology: 

Tools and techniques used:

- Sudo: lets me run root commands
- Nano: create, view, and edit text files directly from the terminal
- Snort: analyzes traffic, detects attacks, alerts logs of events, and blocks malicious traffic in real time
- Snorby: used to visualize alerts
- Ls: lists the contents of a directory
- -r: reads the output.pcap file
- Cat: shows the contents of a file

Investigation Process: 
1. I started by capturing the tcpdump
2. Next, I saved the dump as an output.pcap file
3. Then, I read the output.pcap file
4. Next, I used ls to make sure the README file was in the directory
5. Then, I used the README directory to get the rules I would need to edit the rules, monitor traffic and send the traffic to snorby
6. Next, I created a rule to capture the malicious traffic
7. Then, I monitored the traffic
8. Next, I sent the monitored traffic to snorby
9. Lastly, I found the flag for the challenge in snorby

Reccomendations: 
1. Enable SIEM integration to visualize alerts or patterns
2. Enable Firewall and log monitoring by controlling acess and detecting threats
