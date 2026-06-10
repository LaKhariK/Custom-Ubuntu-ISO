# 🐧 Custom Ubuntu ISO Automation

Enterprise Ubuntu workstation deployment solution designed to automate provisioning, security configuration, and centralized management for virtual workstation environments.

## Overview

This project automates the deployment and configuration of a pre-configured Ubuntu virtual machine environment designed to serve as an alternative workspace when primary systems or applications become unavailable.

The solution enables users to quickly access a secure, ready-to-use Ubuntu environment with enterprise tools, security controls, and management configurations already installed. By eliminating manual setup and repetitive configuration tasks, the deployment process becomes faster, more consistent, and easier to scale.

## Features

* Automated Ubuntu workstation provisioning
* System updates and package installation
* Active Directory domain integration
* Device enrollment into centralized management platforms
* VPN and endpoint security software deployment
* Browser policy management and enterprise enrollment
* TPM-based disk encryption configuration
* Automated boot security configuration with Dracut
* Kernel package installation and system preparation
* Standardized workstation deployment workflows

## Objectives

* Reduce deployment and configuration time
* Improve consistency across workstation environments
* Strengthen endpoint security through TPM integration
* Support centralized device management
* Automate repetitive IT administration tasks
* Enhance deployment scalability and reliability

## Technologies Used

```python
technologies = [
    "Bash Scripting",
    "Ubuntu Linux",
    "TPM2 Tools",
    "Dracut",
    "Active Directory / Realmd",
    "SSSD",
    "Ubuntu Landscape",
    "Chrome Enterprise Policies",
    "APT",
    "DPKG"
]
```

## System Architecture

The deployment workflow automates workstation preparation by:

1. Configuring operating system packages and dependencies
2. Enrolling devices into enterprise management platforms
3. Integrating systems with Active Directory
4. Applying browser and security policies
5. Configuring TPM-based disk encryption
6. Establishing secure boot configurations
7. Preparing the environment for immediate user access

## Impact

* Reduced manual provisioning effort through automation
* Improved deployment consistency across systems
* Enhanced security through automated configuration controls
* Increased operational efficiency for IT support teams
* Supported scalable enterprise workstation deployment

## Security Notice

For public release, all company-specific information including domains, enrollment tokens, internal URLs, deployment identifiers, and configuration details have been removed or replaced with placeholders.

This repository is intended to demonstrate deployment automation concepts, enterprise Linux administration practices, and security-focused workstation provisioning techniques.
