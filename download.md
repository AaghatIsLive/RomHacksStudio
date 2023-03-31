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

{% capture current_download_url %}https://ko-fi.com/api/file-upload/ac19cd89-3abb-4c8f-926a-5553413447f5/download?transactionId=2d6f01d1-e733-4529-aeb7-d4136ecf0320{% endcapture %}

{% capture current_version %}v1.0.8.1{% endcapture %}

{% capture current_label %}Early Release{% endcapture %}

[Pokemon Emerald Crest {{ current_version }} UPS Patch]({{ current_download_url }}){: .btn }

{% if previous_versions %}
### Previous Releases

{% assign default_version = previous_versions.first[0] %}
{% for version in previous_versions %}
{% capture download_url %}{{ version[1] }}{% endcapture %}
{% capture label %}{{ version[2] }}{% endcapture %}
{% assign version_number = version[0] %}
{% if version_number == default_version %}
{% capture version_label %}(Recommended){% endcapture %}
{% else %}
{% capture version_label %}{% endcapture %}
{% endif %}
- [{{ version_number }}]({{ download_url }}) {{ version_label }}
    {% if label == 'Major Update' %}
    {: .label .label-blue }
    {% elsif label == 'Bug Fix' %}
    {: .label .label-yellow }
    {% endif %}
{% endfor %}
{% endif %}

{: .warning }
> It's an `{{ current_label }}` so there might be some bugs and issues, please report them in our [discord server].

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest.

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674
