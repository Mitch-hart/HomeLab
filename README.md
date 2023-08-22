# Home Lab Environment

Welcome to my home lab environment! This page serves as a documentation hub for my personal home lab setup. Feel free to explore the hardware, software, and configurations that make up my lab.



## Table of Contents

- [Introduction](#introduction)
- [Network and Servers](#network-and-servers)
- [Network Diagram](#network-diagram)
- [Virtualization](#virtualization)
- [Services and Applications](#services-and-applications)
- [Configuration Scripts](#configuration-scripts)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)

## Introduction

In this repository, I document my journey through cyber security and penetration testing:

**Real-World Attack Simulations:** Understanding the power of penetration testing as I replicate authentic attack vectors. Understand vulnerabilities and the importance of proactive defense.

**Vulnerability Exploration:** Delve into vulnerabilities, from software bugs to misconfigurations. Grasp their potential impact on security posture.

**Toolbox Exploration:** Discover industry-standard tools and frameworks. Gain insights into their usage, effectiveness, and how they bolster security.

**Defense Strategies:** It's not just about attacks; robust defense matters. Explore the implementation of firewalls, intrusion detection systems, and more.

**Shared Knowledge:** Find invaluable resources, courses, and reading materials that fuel my growth in cyber security.

**Malware Analysis:** With a controlled environment, I dissect and analyze malicious software to understand its behavior, origins, and potential impact.

## Network and Servers

Here's a list of the  components that form the backbone of my home lab:
- **Host:** Asus Laptop, 24GB RAM, 256GB SSD, GTX 1060. Hostname: UKLHOST01, OS: Proxmox 8.0.3.
- **Domain Controller:** Virtual, 2GB RAM, 40GB Storage. Hostname: UKDC01, OS: Windows 2022 Eval.
- **Workstatation:** Windows 10 Workstation.
- **ParrotOS PC:** This will be used to conduct the testing.
- **Network Switch:** Ubiquiti UniFi USW Flex Mini 5-Port Layer 2 Gigabit Switch. Virtual switch via Laptop Host.
- **Security Gateway:** Ubiquiti UniFi Security Gateway Router.
- **Firewall:** pfSense 2.7.0
- **Storage Array:** Onboard storage via Laptop Host. Exploring NAS options.
- **Malware Analysis:** remnux

## Network Diagram

Proposed environment below. Need to add data flow with IPs and key legend.

![alt text](https://github.com/Mitch-hart/HomeLab/blob/main/HomeLab%20v3.png)"Title")

## Virtualization

- **Hypervisor:** Proxmox Virtual Environment 8.0.3
- **VM Templates:** Mention any pre-configured virtual machine templates I've created or used.

## Services and Applications

- **Domain Controller:** BadBlood to populate https://github.com/davidprowe/BadBlood. Also look at BloodHound for attack paths.
- **DNS Server:** Domain Controller will host DNS for Server LAN. Router will handle DNS for Home PC.
- **Web Server:** **TO DO** Find vulnerable web server images
- **Metasploitable Server 2:** https://docs.rapid7.com/metasploit/metasploitable-2/
- **Metasploitable Server 3:** https://github.com/rapid7/metasploitable3
- **Database Server:** **TO DO** Find vulnerable database images
- **Monitoring Tools:** Possibilities: SNORT, Zeek, Suricata, The Elastic Stack, SecurityOnion

## Configuration Scripts

If I've created any automation scripts or configuration files to set up my lab environment, provide links or snippets here:

- **Provisioning Script:** Link to provisioning script
- **Network Configuration:** Link to network configuration files

## Troubleshooting

Document common issues I've encountered and their solutions. This can help others who might face similar challenges:

- **Issue 1:** Description of the issue and solution
- **Issue 2:** Description of the issue and solution


## Resources

Provide links to external resources, guides, or tutorials that have helped me set up and maintain my home lab:
- [AD population](https://github.com/davidprowe/BadBlood)
- [Home Lab Inspiration](https://www.notra-sec.com/blog/my-home-lab-setup)
- [Network Monitoring Tool](https://zeek.org/)
- [John Hammond Virtual Environment](https://www.youtube.com/watch?v=pKtDQtsubio)
- [VulnHub](https://www.vulnhub.com/entry/vulnerable-pentesting-lab-environment-1,737/)
- https://www.vulnhub.com/lab/
- https://kb.help.rapid7.com/docs/setting-up-a-penetration-testing-lab
- https://github.com/AutomatedLab/AutomatedLab
- https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/evaluation-lab-expanded-os-support-amp-atomic-red-team/ba-p/2993927
- https://simulandlabs.com/README.html
- https://github.com/mandiant/Azure_Workshop
- https://securityonionsolutions.com/
- https://www.accidentalrebel.com/building-my-virtual-cybersecurity-home-lab.html
- https://remnux.org/
- https://www.ariefprabowo.com/en/malware-analysis-en/personal-notes-building-a-malware-analysis-lab-environment/
