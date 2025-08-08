# Task-4-Setup-and-Use-a-Firewall-on-Windows-Linux
Setup and Use a Firewall on Windows, configure and test basic firewall rules to allow or block traffic.

Task 4: Setup and Use a Firewall on Windows

Objective:
Configure and test basic Windows firewall rules to allow or block network traffic using Windows Defender Firewall with Advanced Security.

Tools Used:
- Windows 10/11 with Administrator Access
- Windows Defender Firewall
- Telnet Client (for testing purposes)

Steps Followed:

1. Opened the Windows Firewall Configuration Tool:
   Accessed the firewall settings via the Control Panel and navigated to "Advanced Settings".

2. Viewed Existing Rules:
   Opened the "Inbound Rules" section to inspect current rule sets.

3. Created a Rule to Block Port 23 (Telnet):
   - Selected "Port" as the rule type.
   - Specified TCP and port 23.
   - Chose "Block the connection".
   - Applied to all profiles (Domain, Private, Public).
   - Named the rule "Block Telnet Port 23".

4. Tested the Rule:
   - Enabled Telnet Client through Windows Features.
   - Used the command `telnet localhost 23` to confirm the connection was blocked.

5. Allowed Port 22 (SSH):
   - Created another inbound rule to allow TCP port 22.
   - This simulates secure access (commonly used in Linux environments).

6. Removed the Test Rule:
   - Deleted the "Block Telnet Port 23" rule to restore original firewall configuration.

Deliverables:
- Screenshot of the custom inbound rules created.
- Screenshot of the Telnet connection attempt showing failure.
- Screenshot of the SSH allow rule (port 22).

Conclusion:
This task demonstrated the practical application of Windows Firewall for filtering network traffic based on port and protocol. It provided hands-on experience in creating, testing, and managing firewall rules, as well as understanding the impact of such rules on system accessibility and security.

Date Completed:
08/08/25

Author:
Mohommad Kaif Hattiwale
Elevate Labs Internship
Mohommad Kaif Hattiwale
Cybersecurity Intern
