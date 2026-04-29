---
layout: default
is_contact: true
title: "./tmagham/contact"
---

## Contact

<i class="far fa-envelope"></i> Email: [tmagham[at]outlook.com](mailto:tmagham@outlook.com)

<i class="far fa-envelope"></i> Email: [tmagham[at]proton.me](mailto:tmagham@proton.me)

### Social

{% for entry in site.social %}
<a href="{{ entry.url }}" target="_blank"><i class="{{ entry.icon }}"></i> {{ entry.name }}</a>
{% endfor %}

