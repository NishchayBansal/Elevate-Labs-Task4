# Elevate-Labs-Task4

_Task 4 : Setup and Use a Firewall on Windows/Linux
1.Opened firewall configuration tool (Windows Firewall).
2.Listed down the current firewall rules (inbound and outbound).
3.Added a rule to **block inbound traffic** on a **specific port** (e.g., 23 for Telnet)._
![image](https://github.com/user-attachments/assets/4942caa3-4770-459d-a34d-c0b85fcbb7f3)

_4.Tested the rule by attempting to connect to that port locally or remotely.
_ ![image](https://github.com/user-attachments/assets/2913758c-b31b-40d3-b0fd-4c9735378fe8)

**5.Add rule to allow SSH (port 22) if on Linux. N/A
6.Removed the test block rule to restore original state.**
![image](https://github.com/user-attachments/assets/f45da8a7-238a-49d0-aca8-4966b1301dfc)

**7.Documented commands or GUI steps used.**
_GUI steps used:-_
Windows Defender Firewall with Advanced Security> Inbound Rules> New Rule…> Rule Type> Protocol and Ports (Port selection eg. 23) > Action (Block the Connection)> Profile (Domain/ Private/ Public) > Name> 

_Commands used-_
 Used command- telnet <ip address> 23 to check if port is working or not.
If it is working then shows blank, otherwise shows NotFound.

**8.Summarize how firewall filters traffic.**
It examines the data packets and compares them against predefined security rules.

There are various security rules such as:
1. source and destination IP addresses,
2. port number,
3. protocol,
4. Type of Network our computer system is using,
5. Action (if it allows or blocks)
Based on the match, the firewall decides whether to allow the packet to pass through, or to block or discard it. 

