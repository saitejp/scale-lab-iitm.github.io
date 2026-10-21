---
title: People
nav:
  order: 2
  tooltip: Meet the SCALe Group
---

# {% include icon.html icon="fa-solid fa-users" %}People

{% include section.html %}

## Principal investigator

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

{% include section.html %}

## Students and researchers

{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

Interested in joining? See the [contact page]({{ "contact" | relative_url }}).
