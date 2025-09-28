# Firewall-Setup
Firewall Setup: Configure and test basic firewall rules on Windows using Windows Firewall with Advanced Security. Includes blocking Telnet (port 23), verifying with PowerShell, and documenting results with screenshots
# Firewall Setup and Usage

This repository contains the work for **Setup and Use a Firewall on Windows/Linux**.  
The objective is to configure and test basic firewall rules to allow or block traffic.

## Contents
- `screenshots/` → Firewall configuration and testing screenshots
- `README.md` → Steps performed and summary
- `commands.txt` (optional) → Commands used for testing (PowerShell)

## Objective
- Block inbound Telnet traffic on port 23
- Test the rule using PowerShell `Test-NetConnection`
- (Optional) Allow SSH on port 22 for secure remote access
- Remove test block rule to restore original state
