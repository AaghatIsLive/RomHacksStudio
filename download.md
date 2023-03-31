---
title: Download
layout: page
nav_order: 2
---

# Download Pokemon Emerald Crest

Thank you for choosing Pokemon Emerald Crest! You can download the latest version of the game below.

{% assign default_version = "v1.0.8.1" %}

## Download 
{: .d-inline-block }

{% if page.version == default_version %}
Recommended
{: .label .label-blue }
{% else %}
{% assign version_number = page.version | remove: 'v' %}
Version {{ version_number }}
{: .label .label-blue }
{% endif %}

{% assign download_link = "https://ko-fi.com/api/file-upload/" %}
{% assign download_transaction = "?transactionId=" %}

{% case page.version %}
{% when "v1.0.8.1" %}
New Release 
{: .label .label-green }

{% when "v1.0.7.1" %}
Bug Fix
{: .label .label-yellow }

{% when "v1.0.7" %}
Major Update
{: .label .label-blue }
{% endcase %}

<a id="download-button" href="{{ download_link }}{{ page[page.version] }}{{ download_transaction }}{{ page[page.version+"_transaction"] }}" class="btn">{{ page[page.version+"_name"] }}</a>

{% if page.version != default_version %}
<a href="#download-button">Back to download</a>
{% endif %}

{: .warning }
> It's an `Early release` so there might be some bugs and issues, please report them in our [discord server]

### Previous Releases

- [v1.0.8](https://example.com/download?version=v1.0.8)
    Major Update
    {: .label .label-blue }

- [v1.0.7.1](https://example.com/download?version=v1.0.7.1)
    Bug Fix
    {: .label .label-yellow }

- [v1.0.7](https://example.com/download?version=v1.0.7)
    Major Update
    {: .label .label-blue }

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 
