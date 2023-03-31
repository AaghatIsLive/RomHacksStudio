---
title: Download
layout: page
nav_order: 2
---

# Download Pokemon Emerald Crest

Thank you for choosing Pokemon Emerald Crest! You can download the latest version of the game below.

{% assign defaultVersion = "v1.0.8.1" %}

## Download 
{: .d-inline-block }

{% if defaultVersion == "v1.0.8.1" %}
Recommended
{: .label .label-green }
{% endif %}

{% if defaultVersion == "v1.0.8" %}
Major Update
{: .label .label-blue }
{% endif %}

{% if defaultVersion == "v1.0.7.1" %}
Bug Fix
{: .label .label-yellow }
{% endif %}

{% if defaultVersion == "v1.0.7" %}
Major Update
{: .label .label-blue }
{% endif %}

<a id="download-button" href="https://ko-fi.com/api/file-upload/ac19cd89-3abb-4c8f-926a-5553413447f5/download?transactionId=2d6f01d1-e733-4529-aeb7-d4136ecf0320" class="btn">Pokemon Emerald Crest {{ defaultVersion }} UPS Patch</a>

{% assign versions = "v1.0.8.1, v1.0.8, v1.0.7.1, v1.0.7" | split: ", " %}

{% for version in versions %}
{% assign versionName = version %}

{% if version == defaultVersion %}
{% assign versionName = versionName | append: " (Recommended)" %}
{% endif %}

{% case version %}
{% when "v1.0.8.1" %}
{% assign label = "label-green" %}
{% assign type = "Recommended" %}
{% when "v1.0.8" %}
{% assign label = "label-blue" %}
{% assign type = "Major Update" %}
{% when "v1.0.7.1" %}
{% assign label = "label-yellow" %}
{% assign type = "Bug Fix" %}
{% when "v1.0.7" %}
{% assign label = "label-blue" %}
{% assign type = "Major Update" %}
{% endcase %}

- [{{ versionName }}]({{ "https://ko-fi.com/api/file-upload/" | append: version | append: "/download?transactionId=" | append: version }}){: .btn .btn-small }<span class="label {{ label }}">{{ type }}</span>
{% endfor %}

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 
