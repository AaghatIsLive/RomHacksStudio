---
layout: page
title: Route 101
nav_exclude: true
---

# Route 101

**This grassy path running between Littleroot Town and Oldale Town is perfect for doing fieldwork.**

Route 101 is a route in southwestern Hoenn, connecting Littleroot Town and Oldale Town.

---

{% capture file_content %}
{% include_relative encounters.txt %}
{% endcapture %}

{% assign rows = file_content | strip | newline_to_br | remove: '<br />' | split: '<br>' %}

## Wild Encounters

### Grass <img src="https://cdn.discordapp.com/attachments/1069560427312332843/1091325360534212618/RSE_Grass.png">

<details open markdown="block">

| Image  | Pokemon | Levels | Rate |
|:-------|:------- |:-------|:-----|
{% for row in rows %}
| {% for cell in row %}{{ cell }} | {% endfor %}
{% endfor %}

</details>

---

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674
