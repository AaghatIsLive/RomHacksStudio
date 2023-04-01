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

<% File.foreach("encounters.txt") do |line| %>
  <% key, value = line.chomp.split(': ') %>
  <% case key %>
  <% when "Encounter rate" %>
  <%   @encounter_rate = value.to_i %>
  <% when "Species" %>
  <%   @species = [] %>
  <% when "Species".."Max level" %>
  <%   @species << value %>
  <% when "Max level" %>
  <%   puts @species %>
  <% end %>
<% end %>

</details>
