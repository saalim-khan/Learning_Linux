# Learning_Linux
# the topic we are going to cover
# 1.Raid - 1/5
1. RAID (Redundant Array of Independent Disks)<br>
RAID is a data storage virtualization technology that combines multiple physical disks into one logical unit to improve performance, redundancy, or both. Common levels include:<br>

RAID 0: Striped data for performance (no redundancy).<br>
RAID 1: Mirrored data for redundancy.<br>
RAID 5: Striped with parity for fault tolerance.<br>
1. RAID (1/5)<br>
What to Learn: Concepts of RAID levels (0, 1, 5, 10), software RAID setup.<br>
Resources:<br>
Video Tutorials: RAID Basics on YouTube.<br>
Practical Guides: DigitalOcean RAID Setup Guide.<br>
Labs: Set up RAID with mdadm in a VM or cloud server.<br>
# 2.os hardening - 1/5
OS Hardening.<br>
Enhancing the security of an operating system by:<br>

Disabling unnecessary services.<br>
Setting secure configurations (firewalls, SELinux).<br>
Applying patches and updates.<br>

 OS Hardening (1/5)<br>
What to Learn: Disabling unnecessary services, secure configurations, SELinux/AppArmor.<br>
Resources:<br>
Books: "Practical Linux Security Cookbook" by Tajinder Kalsi.<br>
Course: Linux Server Hardening on Udemy.<br>
Tools: Learn chkconfig, iptables, and tools like Lynis.<br>
# 3.os patching - 1/5
3. OS Patching
The process of applying updates to fix security vulnerabilities, <br>
improve stability, or add features.<br>
Includes kernel updates and software patches.<br>

3. OS Patching (1/5)
What to Learn: Patch management tools like yum, dnf, apt.<br>
Resources:<br>
Documentation: Red Hat or Ubuntu official docs.<br>
Tutorials: Linux Patch Management Basics.<br>
Practice: Set up a test Linux system and apply patches manually.<br>

# 4.RHN satellite/Suse manager - 0/5
4. RHN Satellite/SUSE Manager<br>
Centralized systems management tools for Red Hat and SUSE Linux environments.<br>

RHN Satellite: For patching, provisioning, and configuration.<br>
SUSE Manager: Similar functionality for SUSE systems.<br>

4. RHN Satellite/SUSE Manager <br>
What to Learn: Centralized management of RHEL/SUSE systems, automated patching.
Resources:<br>
Official Docs: Red Hat Satellite Documentation.<br>
SUSE Training: SUSE Manager.<br>
Labs: Use trial versions to practice.<br>

# 5.Linux Rescue/single user issues - 2/5
5. Linux Rescue/Single User Issues<br>
Accessing the system in rescue or single-user mode to troubleshoot boot issues or reset root passwords.<br>

Linux Rescue/Single User Issues (2/5)<br>
What to Learn: Boot in rescue mode, recover from GRUB issues.<br>
Resources:<br>
Tutorials: GRUB Bootloader Rescue Guide.<br>
Labs: Use a virtual machine to simulate boot issues and practice rescue.<br>
# 6.hostname change - 5
Hostname Change
Modifying a server’s identifier (hostname) using tools like hostnamectl or by editing configuration files.

6. Hostname Change (5/5)
What to Learn: hostnamectl, hostname command.
Resources:
Quick Tutorials: How to Change Hostname.
Practice: Try in a VM environment.

# 7.filesystem related question - 4/5
# 8.nfs
# 9.ftp/sftp - 3/5
# 10ip addition / route additation, how to make it permanent - 4/5
# 11Nic bonding - 3/5
# 12lvm - 4/5
# 13multipath
# 14iscsiadm ..
# 15NAS/SAN
# 16apache - 1 /5
# 17OS cluster - 1/5
# 18DNS - 1 /5
# 19port of different services ssh/ syslog/ftp/ etc
# 20vmware basics
# 21Openshift
################################3


7. Filesystem (4/5)
What to Learn: Filesystem types, mounting, troubleshooting.
Resources:
Book: "Linux Filesystem Hierarchy" by T. Mack.
Tutorials: Linux Filesystems.
Labs: Practice creating/extending filesystems using mkfs and resize2fs.
8. NFS
What to Learn: Configure and manage NFS shares.
Resources:
Tutorials: Setting Up NFS Server and Client.
Labs: Practice setting up an NFS share in a test environment.
9. FTP/SFTP (3/5)
What to Learn: Set up FTP/SFTP, secure file transfers.
Resources:
Tutorials: FTP and SFTP Setup.
Labs: Use vsftpd or sftp in a VM.
10. IP Addition/Route Addition (4/5)
What to Learn: IP configuration, persistent routes.
Resources:
Tutorials: Networking Commands in Linux.
Labs: Practice using nmcli and ifcfg files.
11. NIC Bonding (3/5)
What to Learn: Combine multiple network interfaces.
Resources:
Tutorials: NIC Bonding Configuration.
Practice: Set up in a VM.
12. Multipath
What to Learn: Multipath I/O concepts, multipath.conf.
Resources:
Tutorials: Setting Up Multipath.
Labs: Use a virtualized SAN/NAS setup.
13. iSCSIadm
What to Learn: Set up iSCSI initiator/target.
Resources:
Tutorials: iSCSI Setup.
Labs: Use a VM to practice connecting to an iSCSI target.
14. NAS/SAN
What to Learn: Configure NAS/SAN storage.
Resources:
Tutorials: NAS and SAN Basics.
Labs: Use free-tier cloud storage for practice.
15. Apache (1/5)
What to Learn: Set up and secure Apache web server.
Resources:
Tutorials: Setting Up Apache.
Labs: Practice setting up Apache on a VM.
16. OS Cluster (1/5)
What to Learn: High-availability clusters.
Resources:
Tutorials: Linux Clustering Basics.
Labs: Practice using Pacemaker/Corosync.
17. DNS (1/5)
What to Learn: Set up DNS server, resolve records.
Resources:
Tutorials: Linux DNS Server Setup.
Labs: Practice setting up BIND on a VM.
18. Ports of Services
What to Learn: Ports of SSH, Syslog, FTP, etc.
Resources:
Reference: IANA Service Port Numbers.
Practice: Use nmap to scan services.
19. VMware Basics
What to Learn: Virtual machine management.
Resources:
Tutorials: VMware’s official learning portal.
Practice: Use VMware Workstation/Player.
20. OpenShift
What to Learn: Basics of Kubernetes/OpenShift.
Resources:
Tutorials: OpenShift Interactive Labs.
Courses: Red Hat OpenShift Certification.
######################################################################

 
7. Filesystem
Managing storage systems in Linux, including partitioning, mounting, and troubleshooting filesystem errors. Common filesystems include ext4, xfs, and btrfs.

8. NFS (Network File System)
A protocol that allows file sharing between Linux systems over a network.

9. FTP/SFTP
FTP: Transfers files between systems.
SFTP: Secure file transfer over SSH.
10. IP Addition/Route Addition
Configuring network interfaces and routes to enable connectivity. Persistent configurations ensure changes remain after a reboot.

11. NIC Bonding
Combining multiple network interfaces for redundancy or increased throughput.

12. Multipath
A technique to provide multiple data paths between servers and storage for fault tolerance and load balancing.

13. iSCSIadm
A tool for managing iSCSI connections, allowing Linux to connect to remote storage devices.

14. NAS/SAN
NAS (Network-Attached Storage): File-level storage accessible over a network.
SAN (Storage Area Network): Block-level storage for high performance and scalability.
15. Apache
A popular open-source web server used to host websites and applications.

16. OS Cluster
Combining multiple servers into a cluster to ensure high availability and fault tolerance. Tools like Pacemaker are commonly used.

17. DNS (Domain Name System)
Resolves domain names to IP addresses, enabling systems to locate each other on the internet or private networks.

18. Ports of Services
Standard port numbers used by services:

SSH (22), FTP (21), Syslog (514), etc.
19. VMware Basics
Using VMware software for creating and managing virtual machines. Key concepts include ESXi, vSphere, and virtual networking.

20. OpenShift
A container orchestration platform based on Kubernetes, used to deploy and manage containerized applications.
