# Project 2: Firewall Configuration and System Hardening

[![Project](https://img.shields.io/badge/Project-2-blue?style=for-the-badge)](https://img.shields.io)
[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![Focus](https://img.shields.io/badge/Focus-System%20Hardening-darkgreen?style=for-the-badge)](https://img.shields.io)

## Summary
This project demonstrates practical endpoint hardening on Windows using firewall rules and baseline security controls. The focus was to reduce unnecessary network exposure and enforce safer configuration defaults.

## Objective
- Configure Windows Defender Firewall securely
- Allow only required services
- Block risky or unnecessary ports
- Verify policy enforcement using GUI and command-line checks
- Record implementation evidence

## Folder Contents
```text
2_Firewall Configuration & System Hardening/
|- README.md
|- Report/
|- Screenshots/
```

## Hardening Activities Performed
- Enabled firewall profiles for Domain, Private, and Public networks
- Created allow rules for essential ports (22, 80, 443)
- Blocked unnecessary ports (for example 21 and 23)
- Reviewed Defender-related security settings
- Disabled guest access and checked update posture
- Validated applied rules through system tools

## Tools and Environment
- Windows Defender Firewall with Advanced Security
- Command Prompt / PowerShell
- Netsh-based verification

## Security Impact
Applying restrictive inbound rules and removing legacy exposure points improves endpoint resilience, limits unauthorized access paths, and supports defense-in-depth.

## Deliverables
- Firewall configuration screenshots
- Verification evidence
- Written report in Report folder
