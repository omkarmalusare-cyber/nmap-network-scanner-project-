# nmap-network-scanner-project-

 🟢 Section 1 — Show Nmap is Installed
 "First let me confirm Nmap is installed on my 
Kali Linux system. As you can see I am running 
Nmap version 7.94 — the latest stable version.

Nmap stands for Network Mapper and it allows us 
to discover hosts, open ports, running services, 
and even the operating system of a target machine."

🟢 Section 2 — Connect VPN and Show Target IP
"I am using a TryHackMe lab machine as my target. 
This is completely legal and ethical — it is a 
controlled environment designed specifically for 
practicing cybersecurity skills.

My target machine IP is 10.10.253.52.
Let me first verify it is online using a ping."


🟢 Section 3 — Basic Port Scan

"This is the most basic Nmap scan. It scans the 
top 1000 most common ports and tells us which 
ones are open.

As you can see in the results — we have found 
1000 open ports. Let me explain each one:

Port 21 is FTP — File Transfer Protocol.
This is used to transfer files but it is 
unencrypted which makes it a security risk.

Port 22 is SSH — Secure Shell.
This is used for secure remote login.

Port 80 is HTTP — this means there is a 
web server running on this machine.

This is already very useful information for 
a penetration tester!"


🟢 Section 4 — Service Version Scan
"Now I am going to use the -sV flag which stands 
for service version detection. This tells us not 
just WHAT services are running but WHICH VERSION 
they are running.

This is critical because older versions of services 
often have known vulnerabilities that attackers 
can exploit."

🟢 Section 5 — OS Detection 
"Now let me try OS detection using the -O flag. 
This uses network fingerprinting techniques to 
guess what operating system the target is running.

As you can see Nmap detected that the target 
is running.

This information helps a penetration tester 
understand what types of attacks might be 
effective against this specific system."

🟢 Section 6 — Aggressive Scan
"Now for the most powerful scan — the aggressive 
scan using the -A flag. This combines service 
version detection, OS detection, script scanning, 
and traceroute all in one command.
This is what a real penetration tester would 
run during the reconnaissance phase of an 
engagement.
Let me walk you through the output...
This is exactly the kind of information that 
appears in a real penetration testing report!"

