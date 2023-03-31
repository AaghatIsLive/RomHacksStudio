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

<a href="#" id="download-btn" class="btn">Pokemon Emerald Crest v1.0.8.1 UPS Patch</a>

{: .warning }
> It's an `Early release` so there might be some bugs and issues, please report them in our [discord server]

### Previous Releases

- [v1.0.8](#) Major Update {: .label .label-blue .version-link }
- [v1.0.7.1](#) Bug Fix {: .label .label-yellow .version-link }
- [v1.0.7](#) Major Update {: .label .label-blue .version-link }

<script>
  const downloadBtn = document.querySelector("#download-btn");
  const versionLinks = document.querySelectorAll(".version-link");
  const downloadLinks = [
    "https://ko-fi.com/api/file-upload/ac19cd89-3abb-4c8f-926a-5553413447f5/download?transactionId=2d6f01d1-e733-4529-aeb7-d4136ecf0320",
    "https://ko-fi.com/api/file-upload/cbf173cb-3653-4d8d-a54a-32ac4119bc75/download?transactionId=0cf84642-cd5d-43e0-8330-a197d986be27",
    "https://ko-fi.com/api/file-upload/efb7ebe6-c4d3-4d10-9e97-9940b6ca2d23/download?transactionId=0bfa4228-d4a2-4598-b3e7-6c3ec6d3c9b5",
    "https://ko-fi.com/api/file-upload/ac19cd89-3abb-4c8f-926a-5553413447f5/download?transactionId=2d6f01d1-e733-4529-aeb7-d4136ecf0320"
  ];
  const versionTexts = [
    "Pokemon Emerald Crest v1.0.8.1 UPS Patch",
    "Pokemon Emerald Crest v1.0.7.1 Bug Fix",
    "Pokemon Emerald Crest v1.0.7 Major Update",
    "Pokemon Emerald Crest v1.0.6 Initial Release"
  ];

  versionLinks.forEach((link, index) => {
    link.addEventListener("click", event => {
      event.preventDefault();
      downloadBtn.href = downloadLinks[index];
      downloadBtn.innerText = versionTexts[index];
      window.location.hash = "download-btn";
    });
  });
</script>

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://vba-m.com/) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 
