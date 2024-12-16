# Hands-On Nmap Scanning Project: Network Reconnaissance and Security Assessment

## Objective
This project aimed to provide hands-on experience with network scanning using Nmap, a powerful open-source tool crucial for network reconnaissance and security assessment. By configuring a virtual environment with multiple operating systems, I sought to identify active hosts and gather detailed information about their configurations and services.

## Skills Learned
- In-depth understanding of Nmap functionalities and command-line options.
- Experience in setting up virtual machines for practical cybersecurity labs.
- Ability to identify active hosts using various scanning techniques, including:
  - TCP Connect Scans
  - SYN Scans
  - Service Version Detection
- Proficiency in using the Nmap Scripting Engine (NSE) for advanced analysis.
- Enhanced skills in troubleshooting and analyzing scan results.

## Tools Used
- **Nmap**: For network discovery and security auditing.
- **Kali Linux**: Utilized as the primary attack machine due to its extensive penetration testing tools.
- **CentOS 7 & Windows Server 2019**: Configured as target hosts for diverse scanning techniques.
- **Virtualization Software (VirtualBox/VMware)**: Created isolated environments to ensure safe testing.

## Steps

1. **Setup Virtual Machines**
   - Configured three VMs:
     - Host 1: Kali Linux (PenTest VM)
     - Host 2: CentOS 7 (Target Host)
     - Host 3: Windows Server 2019 (Target Host)

2. **Network Configuration**
   - All hosts were configured on the NAT Network (LAB-NAT-NET) to facilitate communication.

3. **Running Nmap Scans**
   - Utilized the file output switch to save scans:
     ```bash
     nmap -oN scan_results.txt <target_ip>
     ```
   - Conducted initial discovery scans to identify active hosts.
   - Experimented with various scan types:
     - TCP Connect Scans
     - SYN Scans
     - Service Version Detection

4. **Using NSE Scripts**
   - Implemented NSE scripts such as `http-enum` to gather detailed information about web services running on target hosts.

5. **Documentation and Review**
   - Documented findings including open ports and running services, analyzing the implications for security posture.

## Conclusion
This lab significantly enhanced my practical skills in network scanning and cybersecurity assessments. The hands-on experience with Nmap solidified my understanding of scanning techniques and prepared me for real-world applications in cybersecurity roles. Moving forward, I plan to explore more advanced scanning methods and automate my scanning processes using scripting.
