---
layout: default
title: Hidden Berkeley
---

# Berkeley Beyond the Bears

Berkeley has plenty of useful places and services that are easy to miss if you only know the main campus. This guide collects a few of them in one spot, but hours and access rules change, so always check the official link before you go.

<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
