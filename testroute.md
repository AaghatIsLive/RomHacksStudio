---
layout: page
title: Route 101
---
# Route 101

**This grassy path running between Littleroot Town and Oldale Town is perfect for doing fieldwork.**

Route 101 is a route in southwestern Hoenn, connecting Littleroot Town and Oldale Town.

---

## Wild Encounters

### Grass <img src="https://cdn.discordapp.com/attachments/1069560427312332843/1091325360534212618/RSE_Grass.png">

<details open markdown="block">

| Image                                                                                      | Pokemon             | Levels | Rate|
|:-------------------------------------------------------------------------------------------|:--------------------|:-------|:----|

<% File.readlines("encounters.txt").each do |line| %>
  <% data = line.split(/\s+/) %>
  <% if data[0] == "gRoute101" && data[1] == "land_mons" %>
    | <img src="https://img.pokemondb.net/sprites/sword-shield/icon/<%= data[3].downcase %>.png"> | <%= data[2].sub(/^SPECIES_/, '') %> | <%= data[4] %> | <%= data[5] %> |
  <% end %>
<% end %>

</details>

---

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674
