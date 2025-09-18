---
layout: page
title: Publications
permalink: /publications/
nav: true
nav_order: 4
---

⭐ **Note:** Selected publications are highlighted first, followed by the complete list of other publications.  

## Selected Publications
---

{% bibliography --query @*[selected=true] --group_by year --group_order descending %}

## Other Publications
---

{% bibliography --query @*[selected!=true] --group_by year --group_order descending %}

---

<p style="text-align:center; margin-top:2rem;">
  <a href="#top">↑ Back to top</a>
</p>
