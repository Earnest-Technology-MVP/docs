---
layout: default
title: Engineering
---

# Engineering Documentation

Technical documentation for Earnest's engineering team.

## Documentation

{% for doc in site.engineering %}
### [{{ doc.title }}]({{ doc.url | relative_url }})
{% endfor %}

## Quick Links

- [System Architecture](/engineering/architecture)
- [API Documentation](/engineering/api-docs)
- [Development Standards](/engineering/dev-standards)
- [Security Guidelines](/engineering/security)
- [CI/CD Pipeline](/engineering/cicd)