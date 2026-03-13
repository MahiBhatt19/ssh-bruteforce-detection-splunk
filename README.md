# SSH Brute-Force Detection in Splunk

## Project Overview
This project simulates SSH brute-force attacks and detects them using Splunk.

## Tools Used
- Ubuntu Linux
- OpenSSH
- Splunk Enterprise

## Project Objectives
1. Simulate SSH brute-force login attempts from an attacker machine
2. Generate authentication logs with failed login attempts
3. Ingest `/var/log/auth.log` into Splunk
4. Analyze logs using SPL queries
5. Detect brute-force patterns
6. Build detection dashboards
7. Configure threshold-based alerts
8. Document findings

## Tools & Technologies
- **Operating System:** Ubuntu Linux (22.04/24.04)
- **Virtualization:** VirtualBox
- **Attack Tool:** SSH client / Hydra (TBD)
- **SIEM:** Splunk Enterprise
- **Target Service:** OpenSSH Server

## Environment Setup
- **Attacker VM:** Ubuntu (SSH client)
- **Target VM:** Ubuntu (SSH server)
- **Network:** Bridged network configuration

## Project Status
- **In Progress** - Currently setting up VMs and network configuration

## Timeline
- **Started:** 13.03.2026
