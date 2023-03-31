---
title: Download
layout: page
nav_order: 2
---

# Download Pokemon Emerald Crest

Thank you for choosing Pokemon Emerald Crest! You can download the latest version of the game below.

## Download 
{: .d-inline-block }

New Release 
{: .label .label-green }

{: .d-inline-block }

Bug Fix
{: .label .label-yellow }

{% assign default_version = "v1.0.8.1" %}

{% assign versions = site.data.versions | sort: 'date' | reverse %}

{% assign selected_version = default_version %}

{% if page.version %}
  {% assign selected_version = page.version %}
{% endif %}

{% for version in versions %}
  {% if version.version == selected_version %}
    {% assign download_url = version.download_url %}
    {% assign version_label = version.label %}
    {% break %}
  {% endif %}
{% endfor %}

{% if selected_version == default_version %}
  {% assign version_label = "Recommended" %}
{% endif %}

{% assign download_button = "[Pokemon Emerald Crest " | append: selected_version | append: " UPS Patch](" | append: download_url | append: "){: .btn }" %}

{{ download_button }}

## Previous Releases

{% for version in versions %}
  {% if version.version != default_version %}
    {% assign label_color = "blue" %}
    {% if version.bug_fix %}
      {% assign label_color = "yellow" %}
    {% endif %}
    {% if version.version == selected_version %}
      {% assign label_color = "green" %}
    {% endif %}
    {% assign version_label = version.label %}
    {% assign download_button = "[Pokemon Emerald Crest " | append: version.version | append: " UPS Patch](" | append: version.download_url | append: "){: .btn }" %}
    {% if version.version == selected_version %}
      {% assign version_label = version_label | append: " (Selected)" %}
    {% endif %}
    {% assign version_label = version_label | prepend: "- " | append: " {: .label .label-" | append: label_color | append: " }\n" %}
    {{ version_label }}
    {{ download_button }}
  {% endif %}
{% endfor %}

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 
