# Ubuntu Server Standard Template

**Server Enhancement Layer**: Adds essential server tools and security to the raw foundation.

## Overview

This template builds upon the server-raw foundation to create a production-ready server with enhanced networking, security, and administrative tools. Perfect for general-purpose server deployments.

## Security & Access Control

### Firewall Protection
- **UFW (Uncomplicated Firewall)**: User-friendly firewall management.
- **fail2ban**: Intrusion prevention against brute-force attacks.

### Authentication & Secrets
- `sshpass` - Non-interactive SSH password authentication.
- `libsecret-tools` - Secure credential storage and retrieval.
- `gnome-keyring` - Secret management service.

## Network Administration

### Network Tools
- `ethtool` - Network device configuration (Wake-on-LAN, etc.).
- `net-tools` - Classic networking utilities (ifconfig, netstat).
- `curl` - HTTP/HTTPS data transfer tool.

### Network Diagnostics
- `traceroute` - Network path tracing and latency analysis.
- `whois` - Domain and IP address information lookup.

## System Administration

### File System & Permissions
- `acl` - Advanced file system permissions (Access Control Lists).
- `tree` - Directory structure visualization.

### System Utilities
- `uuid` - UUID generation and manipulation.

### Backup & Recovery
- `restic` - Modern, efficient, and secure backup solution.

## System Maintenance
- **Hostname Configuration**: Sets unique server hostname.
- **Package Cleanup**: Removes unnecessary packages.
- **Machine-ID Reset**: Ensures unique system identity.
- **System Cleanup**: Removes temporary files and configurations.

## Dependencies
- **Builds On**: `10-proxmox-ubuntu-server-raw`.
- **Used By**: Production servers requiring enhanced tools.

#
### Created by:

1. Luciano Sampaio.
