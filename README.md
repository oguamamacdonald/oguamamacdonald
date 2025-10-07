<h1>Hi, I'm Mac! <br/><a href="https://www.linkedin.com/in/macdonald-oguama/">Network & Server Engineer</a>, <a href="https://www.linkedin.com/in/macdonald-oguama/">Cloud Engineer</a>, & <a href="https://www.linkedin.com/in/macdonald-oguama/">Cybersecurity Professional</a>.</h1>

<h2> 🖧 Computer Networking:</h2>

- <b>Enterprise Network Routing & Redundancy Implementation</b>
  - [Configured EIGRP as the dynamic routing protocol to automatically learn and advertise networks across all routers.](https://github.com/oguamamacdonald)
  - [Implemented HSRP on two routers to provide a virtual default gateway for end-users, ensuring high availability.](https://github.com/oguamamacdonald)
  - [Configured inter-VLAN routing using a router-on-a-stick to enable communication between different departmental VLANs.](https://github.com/oguamamacdonald)
  - [Verified connectivity and path redundancy using continuous pings and show ip route commands.](https://github.com/oguamamacdonald)
- <b>Secure Campus Network with VLANs and Access Control</b>
  - [Configured a VTP server to centrally manage VLANs (VLAN 10 - "Donald", VLAN 20 - "Mercy") across multiple switches.](https://github.com/oguamamacdonald)
  - [Implemented 802.1Q trunking on inter-switch links to carry multiple VLAN traffic.](https://github.com/oguamamacdonald)
  - [Assigned access ports to specific VLANs and hardened them using Port Security, restricting access by MAC address.](https://github.com/oguamamacdonald)
  - [Created and applied Extended ACLs to filter traffic based on source/destination IP and protocol, preventing unauthorized access between subnets.](https://github.com/oguamamacdonald) 
- <b>WAN Connectivity & DHCP Services Deployment</b>
  - [Configured a Frame Relay WAN cloud to connect a central HQ router to two remote branch routers using point-to-point subinterfaces and DLCI mappings.](https://github.com/oguamamacdonald)
  - [Implemented PPP with PAP authentication on a serial link between two routers to ensure a secure point-to-point connection.](https://github.com/oguamamacdonald)
  - [Set up a DHCP server on a router to dynamically assign IP addresses to end devices in multiple subnets](https://github.com/oguamamacdonald)
  - [Configured IP Helper Address to relay DHCP requests across different subnets from a central server](https://github.com/oguamamacdonald)
- <b>Network Address Translation (NAT) for Internet Access</b>
  - [Configured Static NAT for a specific internal server to be accessible from the public network.](https://github.com/oguamamacdonald)
  - [Implemented Dynamic NAT with a pool of public addresses for general internal user internet access.](https://github.com/oguamamacdonald)
  - [Used Access Control Lists to define which private addresses were permitted to be translated](https://github.com/oguamamacdonald)
    

<h2> 🪟 Microsoft Server:</h2>

- <b>Enterprise Active Directory Domain Services Deployment</b>
  - [Promoted a Windows Server to a Domain Controller, establishing a new forest and root domain.](https://github.com/oguamamacdonald)
  - [Configured forest and domain functional levels for backward compatibility.](https://github.com/oguamamacdonald)
  - [Created and managed user accounts, security groups, and organizational units to structure the IT environment.](https://github.com/oguamamacdonald)
  - [Implemented granular account policies, including logon hour restrictions and account expiration for security compliance.](https://github.com/oguamamacdonald)
  - [Joined client computers to the domain, centralizing authentication and management.](https://github.com/oguamamacdonald)
- <b>Centralized Policy and Software Management via Group Policy</b>
  - [Created and linked Group Policy Objects (GPOs) at the domain level.](https://github.com/oguamamacdonald)
  - [Deployed third-party software applications (.MSI packages) to domain users and computers, eliminating the need for manual installation.](https://github.com/oguamamacdonald)
  - [Enforced corporate security policies and desktop configurations, including mandated wallpapers and system settings.](https://github.com/oguamamacdonald)
  - [Utilized security filtering to apply specific GPOs to targeted user groups and enforced policies to ensure inheritance.](https://github.com/oguamamacdonald)
- <b>Automated Network Management with DHCP & File Services</b>
  - [Installed and configured the DHCP Server role, creating a scope to automatically assign IP addresses to client machines.](https://github.com/oguamamacdonald)
  - [Integrated DHCP with DNS and set a default gateway for seamless client network integration.](https://github.com/oguamamacdonald)
  - [Implemented and managed a file server using File Server Resource Manager (FSRM).](https://github.com/oguamamacdonald)
  - [Created network shares with customized permissions and applied storage quotas to limit folder sizes and prevent disk space abuse.](https://github.com/oguamamacdonald)
  - [Configured file screens to block specific file types (e.g., executables, video files) from being stored on network drives.](https://github.com/oguamamacdonald)
- <b>System Deployment & Update Infrastructure</b>
  - [Deployed Windows Deployment Services (WDS) to enable network-based installation of Windows operating systems.](https://github.com/oguamamacdonald)
  - [Added boot and install images to WDS and configured multicast transmissions for simultaneous deployment to multiple clients.](https://github.com/oguamamacdonald)
  - [Installed and configured Windows Server Update Services (WSUS) to manage and distribute Microsoft product updates.](https://github.com/oguamamacdonald)
  - [Synchronized update approvals and configured client computers to receive updates from the internal WSUS server.](https://github.com/oguamamacdonald)
- <b>Data Security, Redundancy, and Backup Strategy</b>
  - [Implemented BitLocker Drive Encryption on data volumes to protect against data theft from lost or stolen hardware.](https://github.com/oguamamacdonald)
  - [Created and managed various disk volumes, including Mirrored Volumes (RAID-1) for data redundancy.](https://github.com/oguamamacdonald)
  - [Configured scheduled and one-time backup jobs using Windows Server Backup to secure critical server data to external and network locations.](https://github.com/oguamamacdonald)




<h2> 🐧 Linux Server:</h2>

- <b>Secure Server Hardening with Firewalld</b>
  - [Installed and enabled firewalld, disabling the legacy iptables service.](https://github.com/oguamamacdonald)
  - [Configured active firewall zones (e.g., public, internal) and set default policies.](https://github.com/oguamamacdonald)
  - [Opened specific ports for essential services (SSH) and added pre-defined services (e.g., http, https) to the firewall rules.](https://github.com/oguamamacdonald)
  - [Implemented rich rules to allow access from specific source IP subnets for administrative purposes.](https://github.com/oguamamacdonald)
  - [Managed runtime and permanent rules, ensuring configurations persisted across reboots.](https://github.com/oguamamacdonald)
- <b>Remote Administration via OpenSSH Server</b>
  - [Installed and configured the openssh-server package.](https://github.com/oguamamacdonald)
  - [Started and enabled the sshd service to ensure it launches at boot](https://github.com/oguamamacdonald)
  - [Verified the service was listening on the correct port using systemctl status](https://github.com/oguamamacdonald)
  - [Successfully established remote SSH connections from client machines, confirming secure access.](https://github.com/oguamamacdonald)
- <b>System Management & Automation Scripts</b>
  - [Wrote shell scripts incorporating variables, user input (read), and arithmetic operations](https://github.com/oguamamacdonald)
  - [Created scripts to perform calculations with precision using tools like bc.](https://github.com/oguamamacdonald)
  - [Developed scripts for file management and text processing using commands like grep with regular expressions to filter and analyze log files or data.](https://github.com/oguamamacdonald)
- <b>Package Management & Software Deployment</b>
  - [Utilized yum to update the system, list repositories, and install software packages (e.g., GNOME desktop, OpenSSH).](https://github.com/oguamamacdonald)
  - [Managed system subscriptions for RHEL-based systems to access official software channels.](https://github.com/oguamamacdonald)
  - [Used rpm for lower-level package installation and verification.](https://github.com/oguamamacdonald)
- <b>Filesystem and User Management</b>
  - [Created, archived (gzip), and extracted file archives using tar.](https://github.com/oguamamacdonald)
  - [Managed file and directory permissions using chmod for user, group, and owner access levels.](https://github.com/oguamamacdonald)
  - [Created and managed user accounts and groups.](https://github.com/oguamamacdonald)
  - [Implemented hard and soft links for efficient filesystem navigation and file management.](https://github.com/oguamamacdonald)
    

<h2> ☁️ Cloud Computing:</h2>

- <b>Identity & Access Management with Azure AD and RBAC</b>
  - [Created and configured Azure AD users and groups, implementing dynamic membership rules based on user attributes (e.g., Department, Job Title)](https://github.com/oguamamacdonald)
  - [Activated and assigned Azure AD Premium P2 licenses to enable advanced group features.](https://github.com/oguamamacdonald)
  - [Created a custom RBAC role named "Support Request Contributor" with specific permissions to create support tickets and view resource groups.](https://github.com/oguamamacdonald)
  - [Assigned the custom role at the management group scope, demonstrating granular access control beyond the subscription level.](https://github.com/oguamamacdonald)
- <b>Governance & Compliance via Azure Policy</b>
  - [Assigned the built-in "Require a tag and its value on resources" policy to a resource group, effectively blocking the creation of any resources that did not have the required Role: Infra tag.](https://github.com/oguamamacdonald)
  - [Implemented a remediation strategy by assigning the "Inherit a tag from the resource group if missing" policy. This automatically applied the correct tag to existing non-compliant resources and new deployments, ensuring consistency.](https://github.com/oguamamacdonald)
- <b>Automated Resource Deployment & Management</b>
  - [Deployed Azure managed disks using ARM templates via the Azure Portal, understanding and modifying template parameters.](https://github.com/oguamamacdonald)
  - [Utilized Azure PowerShell within Cloud Shell to create resource groups and managed disks, and performed configuration changes (e.g., resizing disks, changing SKUs from Standard HDD to Premium SSD).](https://github.com/oguamamacdonald)
  - [Executed equivalent tasks using Azure CLI in a Bash environment, demonstrating flexibility across different administrative tools.](https://github.com/oguamamacdonald)
- <b>Secure Virtual Networking & DNS Configuration</b>
  - [Designed and implemented a virtual network (10.40.0.0/20) with multiple subnets for workload segmentation.](https://github.com/oguamamacdonald)
  - [Deployed VMs into different subnets and configured static private and public IP addresses (Standard SKU).](https://github.com/oguamamacdonald)
  - [Created and associated a Network Security Group (NSG) with rules to securely allow RDP traffic to VMs.](https://github.com/oguamamacdonald)
  - [Configured Azure Private DNS zones (contoso.org) for internal name resolution and Azure Public DNS zones for external name resolution, mapping records to VM public IPs.](https://github.com/oguamamacdonald)
- <b>Hybrid Network Architecture with VNet Peering</b>
  - [Provisioned a multi-region lab environment with three virtual networks.](https://github.com/oguamamacdonald)
  - [Established local VNet peering between networks in the same region and global VNet peering between networks in different regions.](https://github.com/oguamamacdonald)
  - [Thoroughly tested intersite connectivity using PowerShell's Test-NetConnection, validating the successful implementation of the network topology.](https://github.com/oguamamacdonald)
    
- <b>EC2 Instance & Elastic Block Store (EBS) Lifecycle Management</b>
  - [Launched Amazon EC2 instances, selecting appropriate instance types and creating new key pairs for secure SSH access.](https://github.com/oguamamacdonald)
  - [Understood the financial impact of resource management by terminating instances to stop billing.](https://github.com/oguamamacdonald)
  - [Created EBS volumes within the same Availability Zone as target EC2 instances and attached them to provide additional storage.](https://github.com/oguamamacdonald)
  - [Initialized and formatted attached EBS volumes using Disk Management (for Windows) to make them available for use by the operating system.](https://github.com/oguamamacdonald)
- <b>Cloud Monitoring & Dashboard Creation with CloudWatch</b>
  - [Created CloudWatch Alarms to monitor billing metrics and specific resource health, enabling proactive issue detection.](https://github.com/oguamamacdonald)
  - [Built custom CloudWatch Dashboards, adding widgets to visualize metrics and usage statistics across resources.](https://github.com/oguamamacdonald)
  - [Enabled and configured Live Data on dashboards for real-time monitoring of system metrics.](https://github.com/oguamamacdonald)
  - [Shared dashboards publicly by generating the necessary URL and confirming the permissions policy.](https://github.com/oguamamacdonald)
- <b>Centralized Operations with AWS Systems Manager</b>
  - [Configured Explorer to aggregate operational data across AWS accounts and regions.](https://github.com/oguamamacdonald)
  - [Set up a Resource Data Sync to funnel data from various sources into a central location for Explorer.](https://github.com/oguamamacdonald)
  - [Leveraged Systems Manager capabilities for automated management and configuration of EC2 instances.](https://github.com/oguamamacdonald)
- <b>Backup & Recovery Strategy with AWS Backup</b>
  - [Created a Backup Plan to define automated backup schedules and retention policies.](https://github.com/oguamamacdonald)
  - [Assigned AWS resources (e.g., EBS volumes) to the backup plan for consistent protection.](https://github.com/oguamamacdonald)
  - [Performed on-demand backups for specific recovery points outside of the scheduled plan.](https://github.com/oguamamacdonald)
  - [Successfully tested the recovery process by restoring a backup to a new resource, validating the integrity of the backup strategy.](https://github.com/oguamamacdonald)
- <b>Relational Database Deployment with Amazon RDS</b>
  - [Provisioned an Amazon RDS instance using the Easy Create option for rapid deployment.](https://github.com/oguamamacdonald)
  - [Selected Microsoft SQL Server as the database engine, utilizing the Free Tier for cost-effective learning and development.](https://github.com/oguamamacdonald)

<h2>🛡️ Cybersecurity</h2>

- <b>Network Vulnerability & Traffic Analysis</b>
  - [Performed comprehensive network reconnaissance using Nmap for host discovery and service enumeration.](https://github.com/oguamamacdonald)
  - [Conducted stealthy port scanning via proxy servers using Scanless to assess external footprint.](https://github.com/oguamamacdonald)
  - [Captured and deeply analyzed network packets using Wireshark and Tcpdump to identify malicious traffic patterns, unusual protocols, and potential data exfiltration attempts.](https://github.com/oguamamacdonald)
  - [Monitored active network connections and routing tables using Netstat and Route for baseline establishment and anomaly detection.](https://github.com/oguamamacdonald)
- <b>Web Application Penetration Testing</b>
  - [Intercepted, inspected, and modified HTTP/S traffic using Burp Suite to test application logic and session management.](https://github.com/oguamamacdonald)
  - [Manually identified and exploited SQL Injection and Cross-Site Scripting (XSS) vulnerabilities to demonstrate potential data breach risks.](https://github.com/oguamamacdonald)
  - [Tested for Cross-Site Request Forgery (CSRF) and Directory Traversal vulnerabilities to ensure proper access controls.](https://github.com/oguamamacdonald)
  - [Utilized Gobuster for brute-forcing hidden directories and APIs, and Wpscan for conducting security assessments of WordPress installations.](https://github.com/oguamamacdonald)
- <b>Active Directory & System Exploitation</b>
  - [Conducted credential harvesting attacks using Site Cloning and Responder to capture NTLM hashes on the network.](https://github.com/oguamamacdonald)
  - [Performed brute-force attacks using Hydra to test password policy strength.](https://github.com/oguamamacdonald)
  - [Utilized the Metasploit Framework to exploit vulnerabilities, gain initial access, and pivot through networks.](https://github.com/oguamamacdonald)
  - [Generated custom payloads with Msfvenom to bypass antivirus solutions.](https://github.com/oguamamacdonald)
  - [Demonstrated post-exploitation techniques, including extracting password hashes from memory using Mimikatz.](https://github.com/oguamamacdonald)
- <b>Proactive Threat Intelligence Gathering</b>
  - [Used theHarvester and Recon-ng to gather exposed employee emails, subdomains, and host information associated with target domains.](https://github.com/oguamamacdonald)
  - [Performed comprehensive DNS enumeration with Dnsenum, Nslookup, and Dig to map out target infrastructure and identify potentially misconfigured records.](https://github.com/oguamamacdonald)
- <b>Vulnerability Management & Compliance</b>
  - [Leveraged Nessus to perform automated vulnerability scans, generating detailed reports on system misconfigurations and unpatched software.](https://github.com/oguamamacdonald)
  - [Applied knowledge of the OWASP Top 10 to prioritize critical web application risks for remediation.](https://github.com/oguamamacdonald)
    
- <b>Password Security & Integrity Auditing</b>
  - [Utilized Hashcat and John the Ripper to perform password cracking and audit password policy effectiveness.](https://github.com/oguamamacdonald)
  - [Verified file integrity and detected unauthorized modifications by generating and comparing checksums.](https://github.com/oguamamacdonald)


<h2>📜 Certifications</h2>

- [CISCO Certified Network Associate](https://www.credly.com/badges/99afe69f-61ad-4fef-894f-bdda55646853)
- [CompTIA Security+ ce Certification](https://www.credly.com/badges/5de19307-dbf0-4780-88e7-9363b6417bf3)
- [Microsoft Certified: Azure Administrator Associate](https://www.credly.com/badges/f151ddda-e678-46de-9a9a-48e4ef7b35a6)
- [IT Specialist - Networking](https://www.credly.com/badges/b0ba004c-f6c9-41a2-b4a7-d0667f44788f)
- [Google Cybersecurity](https://coursera.org/share/ae9ed34d46313825c2d8182831910cf6)
  

<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="oguamamacdonald | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]



[linkedin]: https://www.linkedin.com/in/macdonald-oguama


