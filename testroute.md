---
layout: page
title: Route 101
---
require 'csv'

# Open the file and read its contents
file_contents = File.read('/path/to/your/file.txt')

# Convert the file contents into a hash
data = {}
file_contents.split(/\n/).each do |line|
  key, value = line.split(':')
  data[key.strip.to_sym] = value.strip if key && value
end

# Load the data into the table
species = []
CSV.parse(data[:Species], headers: true, col_sep: ':') do |row|
  species << row.to_h
end

# Render the table using the loaded data

# Route 101

**This grassy path running between Littleroot Town and Oldale Town is perfect for doing fieldwork.**

Route 101 is a route in southwestern Hoenn, connecting Littleroot Town and Oldale Town.

---

## Wild Encounters

### Grass <img src="https://cdn.discordapp.com/attachments/1069560427312332843/1091325360534212618/RSE_Grass.png">

<details open markdown="block">

| Image                                                                                      | Pokemon             | Levels | Rate|
|:-------------------------------------------------------------------------------------------|:--------------------|:-------|:----|
<% species.each do |s| %>
| <img src="https://img.pokemondb.net/sprites/sword-shield/icon/<%= s['Species'] %>.png"> | <%= s['Species'].sub('SPECIES_', '') %> | <%= s['Min level'] %>-<%= s['Max level'] %> | <%= data['Encounter rate'] %> |
<% end %>
</details>
---
## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674
