TryHackMe - Nmap Room

Room : TryHackMe - Nmap  ,  https://tryhackme.com/room/furthernmap

Summery : In this room , we learned how to use Nmap tool to scan open ports on a target system.

Tools Used : 
-Nmap : A powerful network scanning tool used for discovering open ports, services, and vulnerabilities.

Steps:
1.First we learned whats nmap used for? 
2.Then we improve our knowledge about the rule and instruction.
3.It had some questions and test to test my knowledge about Namp.

Now we start work with Nmap:
1.nmap -sV -T4 <TARGET_IP>  -> we use this instruction to scan the target to find which ports are open.
       -sV: Detects service versions.
       -T4: Increases the speed of the scan (faster).
  nmap -sV -p 22,80 <TARGET_IP>  ->  get more informaiton.

nmap --script vuln <TARGET_IP>  ->  A list of potential vulnerabilities based on the service versions.
gobuster dir -u http://<TARGET_IP> -w /path/to/wordlist.txt  ->  This revealed additional hidden directories or files.

We work on Nmap with other instruction had but this instructions are more important and useful.

Flag:
For security things i dont't add the flag but you can fallow the link to get more information.

Takeaways:
Nmap is a must-know tool for security testing.
Discovering open ports and identifying service versions is key to finding vulnerabilities.

Refrences:
-Nmap Room _ TryHackMe
-Watching video in YouTube
