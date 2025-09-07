---
layout: default
title: Operations
---

# Operations Documentation

IT resources, tools, and operational procedures for Earnest.

## Documentation

{% for doc in site.operations %}
### [{{ doc.title }}]({{ doc.url | relative_url }})
{% endfor %}

## Quick Links

- [VPN Setup](/operations/vpn-setup)
- [IT Resources](/operations/it-resources)
- [Security Protocols](/operations/security)
- [Office Information](/operations/office)
- [Tools & Software](/operations/tools)