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

<a href="https://www.mediafire.com/file/tgxpvmgwhhyj8c4/PokemonEmeraldCrestv1.0.8.1.zip/file" class="btn" id="download-button">Pokemon Emerald Crest v1.0.8.1 UPS Patch</a>

{: .warning }
> It's an `Early release` so there might be some bugs and issues, please report them in our [discord server]

### Previous Releases

- [v1.0.8](javascript:void(0);){: .release-link }
{: .d-inline-block }

Major Update
{: .label .label-blue }

- [v1.0.7.1](javascript:void(0);){: .release-link }
{: .d-inline-block }

Bug Fix
{: .label .label-yellow }
- [v1.0.7](javascript:void(0);){: .release-link }
{: .d-inline-block }

Major Update
{: .label .label-blue }

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

<script>
  var downloadButton = document.getElementById('download-button');
  var releaseLinks = document.querySelectorAll('.release-link');
  var defaultVersion = 'v1.0.8.1'; // Change this to the version you want to set as default
  for (var i = 0; i < releaseLinks.length; i++) {
    releaseLinks[i].addEventListener('click', function(event) {
      event.preventDefault();
      downloadButton.href = event.target.href;
      downloadButton.innerText = event.target.innerText + ' UPS Patch'; // Change the text of the download button to match the selected version
      window.location.href = '#download-button'; // Take the user back to the download button
    });
  }
  downloadButton.innerText = 'Pokemon Emerald Crest ' + defaultVersion + ' UPS Patch'; // Set the initial text of the download button to the default version
</script>

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 
