---
layout: default
title: VPN Setup Guide
collection: operations
order: 1
---

# VPN Setup Guide

## Overview

This guide will help you set up VPN access to connect to Earnest's internal network securely.

## Prerequisites

- Company-issued laptop or approved personal device
- Valid Earnest email account
- Two-factor authentication enabled

## Setup Instructions

### Step 1: Download VPN Client

1. Download the VPN client for your operating system:
   - **macOS**: [Download link]
   - **Windows**: [Download link]
   - **Linux**: [Download link]

### Step 2: Install the Client

#### macOS
```bash
# Installation commands
```

#### Windows
1. Run the installer
2. Follow the setup wizard
3. Restart if prompted

#### Linux
```bash
# Installation commands
```

### Step 3: Configuration

1. Launch the VPN client
2. Click "Add New Connection"
3. Enter the following details:
   - **Server Address**: vpn.earnest.com
   - **Connection Name**: Earnest VPN
   - **Authentication Type**: Certificate + Password

### Step 4: Obtain Certificates

1. Go to [internal certificate portal]
2. Log in with your Earnest credentials
3. Request a VPN certificate
4. Download and install the certificate

### Step 5: First Connection

1. Open the VPN client
2. Select "Earnest VPN"
3. Enter your credentials:
   - Username: your.email@earnest.com
   - Password: Your AD password
4. Enter your 2FA code when prompted
5. Click "Connect"

## Troubleshooting

### Connection Issues

**Problem**: Cannot connect to VPN
- Check internet connection
- Verify credentials
- Ensure 2FA is working
- Contact IT support

**Problem**: Slow connection
- Try different server endpoint
- Check local network speed
- Report persistent issues to IT

### Certificate Issues

**Problem**: Certificate expired
- Request new certificate from portal
- Remove old certificate
- Install new certificate

## Security Best Practices

1. **Never share VPN credentials**
2. **Always disconnect when not in use**
3. **Keep VPN client updated**
4. **Report suspicious activity immediately**

## Support

For VPN issues, contact IT support:
- Email: it-support@earnest.com
- Slack: #it-help
- Phone: ext. 1234

## Additional Resources

- [Network Security Policy](/operations/security-policy)
- [Remote Work Guidelines](/people/remote-work)
- [IT FAQ](/operations/it-faq)