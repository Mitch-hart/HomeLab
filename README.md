# Home Lab Environment

Welcome to my home lab environment! This page serves as a documentation hub for my personal home lab setup. Feel free to explore the hardware, software, and configurations that make up my lab.

## Table of Contents

- [Introduction](#introduction)
- [Hardware](#hardware)
- [Network Topology](#network-topology)
- [Virtualization](#virtualization)
- [Services and Applications](#services-and-applications)
- [Configuration Scripts](#configuration-scripts)
- [Troubleshooting](#troubleshooting)
- [Resources](#resources)

## Introduction

In this section, I'll provide a brief overview of my home lab, its purpose, and what I aim to achieve with it.

Need to complete this section.

## Network & Servers

Here's a list of the  components that form the backbone of my home lab:
- **Host:** Asus Laptop, 24GB RAM, 256GB SSD, GTX 1060. Hostname: UKLHOST01, OS: Proxmox 8.0.3.
- **Domain Controller:** Virtual, 2GB RAM, 40GB Storage. Hostname: UKDC01, OS: Windows 2022 Eval. 
- **Web Server:** **TO DO** Consideration
- **Network Switch:** Ubiquiti UniFi USW Flex Mini 5-Port Layer 2 Gigabit Switch
- **Security Gateway:** Ubiquiti UniFi Security Gateway Router
- **Software Firewall:** pfSense Version TBC
- **Storage Array:** Onboard storage via Laptop Host. Exploring NAS options 

## Network Topology

Proposed environment below. Need to add data flow with IPs and key legend.

![alt text](https://github.com/Mitch-hart/HomeLab/blob/main/Network%20Design%20V2.png?raw=true)"Title")

## Virtualization

- **Hypervisor:** Proxmox Virtual Environment 8.0.3
- **VM Templates:** Mention any pre-configured virtual machine templates I've created.

## Services and Applications

List the services, applications, and tools im running in my home lab. Include a brief description of each:
- **Domain Controller:** BadBlood to populate https://github.com/davidprowe/BadBlood. Also look at BloodHound for attack paths.
- **DNS Server:** Domain Controller will host DNS for Server LAN. Router will handle DNS for Home PC.
- **Web Server:** **TO DO** Find vulnerable web server images
- **Metasploitable Server:** **TO READ** https://docs.rapid7.com/metasploit/metasploitable-2/
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
