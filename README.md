# Nmap Scanning Project

## Objective

The Nmap scanning project was designed to provide hands-on experience in network scanning and reconnaissance using Nmap, a powerful open-source network scanning tool. The primary goal was to configure a virtual environment with multiple operating systems and perform various network scans to identify active hosts and gather detailed information about their configurations and services. This lab aimed to enhance understanding of network security assessment techniques and familiarize participants with effective scanning methodologies.

### Skills Learned

- In-depth knowledge of Nmap functionalities and command-line options.
- Hands-on experience in configuring virtual machines for practical cybersecurity labs.
- Ability to identify active hosts and assess network services using diverse scanning techniques.
- Proficiency in utilizing Nmap Scripting Engine (NSE) for advanced scanning tasks.
- Enhanced troubleshooting and analytical skills in interpreting scan results.

### Tools Used

- Nmap: For network discovery and security auditing.
- Kali Linux: A penetration testing distribution used as the main attack machine.
- CentOS 7: A Linux distribution used as a target host.
- Windows Server 2019: Another target host to practice scanning techniques.
- Virtualization Software: Such as VirtualBox or VMware for creating isolated environments.

## Steps

### 1. Setup Virtual Machines:

- Created three VMs: - Host 1: Kali Linux (PenTest VM)
- Host 2: CentOS 7 (Target Host)
- Host 3: Windows Server 2019 (Target Host)


- Configured the Kali VM following the installation instructions provided in the previous lab.


### 2. Network Configuration:

- Ensured all hosts were configured on the NAT Network (LAB-NAT-NET) to facilitate communication between VMs.


### 3. Running Nmap Scans:

- Utilized the file output switch to save scan results using the command: nmap -oN  .
- Conducted initial discovery scans to identify active hosts on the network.
- Experimented with various Nmap scans, including TCP connect scans, SYN scans, and service version detection.


### 4. Using NSE Scripts:

- Implemented Nmap Scripting Engine (NSE) scripts to gather more detailed information about the services running on the target hosts.


### 5. Documentation and Review:

- Documented findings from each scan, detailing the information gathered about each host, including open ports and running services.


### 6. Lab Conclusion:

- After completing the lab exercises, deleted the virtual machines to maintain a clean environment for future labs.
- Reflected on the experiences gained during the lab, reinforcing knowledge of network scanning processes.

Screenshots

Ref 1: Nmap Scan Results
Nmap Scan Results
Description: Example of the output generated from an Nmap scan on the Kali VM, showcasing identified active hosts and their associated services.

Ref 2: VM Network Configuration
VM Network Configuration
Description: Screenshot of the network settings for the virtual machines, confirming they are all configured on the same NAT network.

## Conclusion

This lab significantly enhanced my practical skills in network scanning and cybersecurity assessment. The hands-on experience with Nmap not only solidified my understanding of scanning techniques but also prepared me for real-world applications in cybersecurity roles.
