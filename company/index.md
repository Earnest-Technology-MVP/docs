---
layout: default
title: Company
---

# Company Documentation

Welcome to the Company documentation section. Here you'll find information about Earnest's mission, values, history, and organizational structure.

## Key Documents

{% for doc in site.company %}
### [{{ doc.title }}]({{ doc.url | relative_url }})
{{ doc.description }}
{% endfor %}

## Quick Links

- [Mission & Values](/company/mission-values)
- [Company History](/company/history)
- [Organizational Structure](/company/org-structure)
- [Business Strategy](/company/strategy)
- [Board & Investors](/company/board-investors)

## Need to Add Documentation?

To add new company documentation:
1. Create a new `.md` file in the `_company` folder
2. Add appropriate front matter (layout, title, order)
3. Submit a pull request for review