---
layout: default
is_contact: true
title: "./tmagham/contact"
---

## Contact

<i class="far fa-envelope"></i> Email: [tmagham[at]outlook.com](mailto:tmagham@outlook.com)

<i class="far fa-envelope"></i> Email: [tmagham[at]pm.me](mailto:tmagham@pm.me)

### Social

{% for entry in site.social %}
<a href="{{ entry.url }}" target="_blank"><i class="{{ entry.icon }}"></i> {{ entry.name }}</a>
{% endfor %}

### Academic

{% for entry in site.academic %}
<a href="{{ entry.url }}" target="_blank"><i class="{{ entry.icon }}"></i> {{ entry.name }}</a>
{% endfor %}
