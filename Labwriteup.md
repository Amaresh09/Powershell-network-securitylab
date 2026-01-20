# Lab – PowerShell in Network and Security Operations

## Objective
The objective of this lab was to understand how PowerShell can be used to
perform security-relevant administrative tasks such as file searching,
host discovery, and port scanning in a controlled environment.

## Environment
- Windows 10 Virtual Machine (PowerShell run as Administrator)
- Ubuntu Linux Virtual Machine
- Isolated lab network

## Task 1: File Content Searching
PowerShell was used to search through user directories to identify files
containing specific keywords. This demonstrates how administrators and
security analysts can locate sensitive data and audit file contents.

## Task 2: Ping Sweep (Host Discovery)
A PowerShell script was created to perform a ping sweep across a subnet
to identify active and inactive hosts. This technique is useful for both
network administration and security monitoring.

## Task 3: Script Execution Policy
The Windows execution policy was reviewed and adjusted to allow locally
created scripts to run. This highlights the importance of balancing
usability with security controls.

## Task 4: Port Scanning
A PowerShell script was developed to test connectivity to a range of ports
on a Linux system using Test-NetConnection. This helps identify accessible
services and understand network exposure.

## Security Takeaways
- Sensitive files should not be stored in plaintext
- Host discovery activity can be detected through network monitoring
- Port exposure should be minimized using firewalls and segmentation
- PowerShell activity should be logged and monitored in enterprise systems

## Conclusion
This lab strengthened understanding of PowerShell as a powerful tool for
both system administration and security analysis when used responsibly.

## Disclaimer
This lab was conducted in an authorized academic environment.
No real-world systems were targeted.
