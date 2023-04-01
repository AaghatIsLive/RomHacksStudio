---
layout: page
title: Route 101
nav_exclude: true
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
| <% csv_data.each do |row| %>
| <img src="https://img.pokemondb.net/sprites/sword-shield/icon/<%= row['Mons'].downcase %>.png"> | <%= row['Mons'].split('_').map(&:capitalize).join(' ') %> | <%= row['Levels'] %> | <%= row['Rate'] %> |
| <% end %>
</details>

---
## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674
  
require 'csv'

csv_data = []
CSV.foreach('encounters.txt', headers: true, col_sep: "\t") do |row|
  csv_data << row.to_h
end

