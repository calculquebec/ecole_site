---
layout: base
---

# Témoignages

{% for testimony in site.data.temoignages %}

<blockquote class="">
    {{ testimony.quote }}
</blockquote>
– {{ testimony.person }}
{% endfor %}
