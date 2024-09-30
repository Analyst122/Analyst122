<h1>Hi, I'm Osman! <br/>
<h2>👨‍💻 Cybersecurity Projects:</h2>


 
  <h2>Home Lab Projects: Gaining Practical Experience in Cybersecurity:</h2>
  In today’s digital landscape, practical experience is crucial for anyone looking to excel in cybersecurity. To bolster my skills, I recently set up a home lab designed to simulate real-world scenarios. Here’s a detailed look at the projects I’ve undertaken and the lessons learned along the way.
1. Setting Up the Virtual Environment
Why VirtualBox?
I chose VirtualBox for my home lab because it’s free, user-friendly, and supports a wide range of operating systems. Setting up the lab involved creating multiple virtual machines (VMs) that simulate various roles within a network environment.

The Virtual Machines
Here’s a breakdown of the VMs I created:

Kali Linux (Attacker): A powerful penetration testing and ethical hacking distribution, equipped with a plethora of tools for security assessments.
Windows 10 (Target): A widely used operating system, ideal for testing vulnerabilities and defense mechanisms.
Ubuntu Server (Splunk): This server acts as a log collector and analysis tool, essential for monitoring network activity.
Windows Server 2022 (Active Directory): Provides user management and resource allocation, simulating a corporate environment.

Networking Configuration
I configured all four VMs to operate on the same NAT network. This setup allows them to communicate with each other while remaining isolated from my home network, providing a safe environment to conduct experiments.

2. Implementing Logging and Monitoring
Installing Sysmon
To effectively monitor activities across my virtual environment, I installed Sysmon (System Monitor) on both the Windows 10 and Windows Server 2022 machines. Sysmon enhances Windows logging capabilities by providing detailed information about process creation, network connections, and changes to file creation times.

Configuring Splunk Universal Forwarder
Next, I installed the Splunk Universal Forwarder on both Windows machines. This tool collects and forwards log data to my Ubuntu Server, where I run Splunk. The combination of Sysmon and Splunk enables comprehensive log monitoring, crucial for analyzing security events.



3. User Management in Active Directory
Creating Units, Users, and Groups
With the logging infrastructure in place, I turned to Active Directory. I created various organizational units (OUs), users, and groups to simulate an actual business environment. This step is important for managing access and permissions effectively.

Generating Event Logs
By creating different user roles and assigning permissions, I generated both successful and failed login events. This variety provides a rich dataset for analysis, reflecting the complexities of managing users in a corporate environment.


4. Performing Penetration Testing
Using Kali Linux
With the environment fully set up, I shifted my focus to penetration testing. Using Kali Linux, I executed a brute-force attack against the account of a user I created, Amr Mansour. This type of attack is common in real-world scenarios and helps illustrate potential vulnerabilities in user authentication systems.

Monitoring the Attack
While the brute-force attack was in progress, I monitored the logs generated in Splunk. The ability to see real-time logging is invaluable for understanding how attacks manifest and how to defend against them.


5. Analyzing Logs and Querying Data
Using Splunk for Log Analysis
After executing the attack, I utilized Splunk to analyze the logs collected. I wrote several queries to search for failed logon attempts across the system, focusing specifically on the attempts against Amr Mansour’s account.



Findings
The queries returned multiple entries for failed login attempts, confirming the effectiveness of my attack simulation. This analysis not only validated the setup but also provided insights into how attackers exploit weak passwords and misconfigured systems.

Conclusion
Setting up this home lab has been an incredibly enriching experience. I’ve gained hands-on knowledge of cybersecurity concepts, from user management and logging to penetration testing and log analysis. This practical approach has solidified my understanding of how to defend against and respond to cyber threats.](##https://medium.com/@osmanmusahamed/home-lab-projects-gaining-practical-experience-in-cybersecurity-b698f2913258)
  - [Vulnerability Management with Nessus]

<h2>Cybersecurity Certification</h2>

- [Google Cybersecurity](https://coursera.org/verify/professional-cert/96K3MBHCCPDH)
- [CompTIA Security+](http://verify.CompTIA.org)
- [CompTIA CySA+](http://verify.comptia.org/)
- [CompTIA Pentest+](http://verify.CompTIA.org)
- ISC2 CC
<h2> 🤳 Connect with me:</h2>


[<img align="left" alt="OsmanMusa | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]



[linkedin]: www.linkedin.com/in/osman-musa-cybersecurity-analyst

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
