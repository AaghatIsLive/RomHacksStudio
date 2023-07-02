---
title: Home
layout: home
nav_order: 1
permalink: /
---

# **Pokemon Emerald Crest**

Thank you for choosing Pokemon Emerald Crest! You can download the latest version of the game below.

## **Download**
{: .d-inline-block }

New Release 
{: .label .label-green }

{: .d-inline-block }

Bug Fix
{: .label .label-yellow }

[Pokemon Emerald Crest v1.0.8.5 UPS Patch](https://ko-fi.com/api/file-upload/ea9c675b-04d6-4b67-a84b-9d27db3f564f/download?transactionId=65997c01-4f04-4858-a53f-df0362f15b51){: .btn }
```
What's New!

🔸Spotlight Events
🔸Fixed Black Screen Issue while fighting Some Gym Leaders 
🔸Fixed game corner prices for EXP Candys
🔸Added more Wild Bosses (DNS)
🔸Fixed Some Follower Sprites
🔸Fixed several other bugs 
🔸And a lot of minor improvements
```

{: .warning }
> It's an `Early release` so there might be some bugs and issues, please report them in our [discord server]

## **v1.9.0**
{: .d-inline-block }

27.78% complete
{: .label .label-red }

<html>
<head>
  <style>
    .progress-bar {
      width: 250px;
      height: 10px;
      background-color: #f0f0f0;
      border-radius: 10px;
      position: relative;
      overflow: hidden;
      box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.1);
      visibility: hidden; /* Initially hide the progress bar */
      opacity: 0; /* Initially set opacity to 0 */
      transition: opacity 0.5s ease-in-out;
    }

    .progress {
      height: 100%;
      background-color: #4caf50;
      width: 0%;
      border-radius: 10px;
      position: absolute;
      top: 0;
      left: 0;
      animation: progressAnimation 2s ease-in-out forwards;
    }

    @keyframes progressAnimation {
      0% {
        width: 0%;
      }
      100% {
        width: 27.78%;
      }
    }
  </style>
  <script>
    window.addEventListener('scroll', function() {
      var progressBar = document.querySelector('.progress-bar');
      var progressRect = progressBar.getBoundingClientRect();
      var windowHeight = window.innerHeight || document.documentElement.clientHeight;

      if (progressRect.top < windowHeight && progressRect.bottom >= 0) {
        progressBar.style.visibility = 'visible';
        progressBar.style.opacity = '1';
      }
    });
  </script>
</head>
<body>
  <div class="progress-bar">
    <div class="progress"></div>
  </div>
</body>
</html>

### Previous Releases

- [v1.0.8.4](https://ko-fi.com/api/file-upload/9cd230b8-ea42-4a27-8305-d744baf9ac35/download?transactionId=d254967d-8f99-44eb-890b-8860e0fde9ac)
{: .d-inline-block }

Bug Fix
{: .label .label-yellow }

- [v1.0.8.3](https://ko-fi.com/api/file-upload/ec54840b-a723-4647-afcb-1e35e9478b55/download?transactionId=9fd41810-c49d-42f6-aaa2-7c144cdc9e65)
{: .d-inline-block }

Bug Fix
{: .label .label-yellow }

- [v1.0.8](https://ko-fi.com/api/file-upload/3d2db367-d8da-447b-a225-409d7e801697/download?transactionId=a802d6a5-1a04-483c-a2bd-7f72ee6f2daf)
{: .d-inline-block }

Major Update
{: .label .label-blue }


[see full changelog](https://aaghatislive.github.io/RomHacksStudio/changelog.html)

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://mgba.io/downloads.html) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://aaghatislive.github.io/RomHacksStudio/HowToPatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('aaghatislive', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Support me',
    'floating-chat.donateButton.background-color': '#794bc4',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>

<!DOCTYPE html>
<html>
<head>
  <style>
    .switch {
      position: relative;
      display: inline-block;
      width: 60px;
      height: 34px;
    }
    
    .switch input {
      opacity: 0;
      width: 0;
      height: 0;
    }
    
    .slider {
      position: absolute;
      cursor: pointer;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: #ccc;
      transition: .4s;
      border-radius: 34px;
    }
    
    .slider:before {
      position: absolute;
      content: "";
      height: 26px;
      width: 26px;
      left: 4px;
      bottom: 4px;
      background-color: white;
      transition: .4s;
      border-radius: 50%;
    }
    
    input:checked + .slider {
      background-color: #2ecc71;
    }
    
    input:checked + .slider:before {
      transform: translateX(26px);
    }
    
    .slider.round {
      border-radius: 34px;
    }
    
    .slider.round:before {
      border-radius: 50%;
    }
  </style>
</head>
<body>  
  <label class="switch">
    <input type="checkbox" class="js-toggle-dark-mode">
    <span class="slider round"></span>
  </label>
  
  <script>
    const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

    toggleDarkMode.addEventListener('change', function() {
      if (this.checked) {
        // Dark mode is enabled
        document.body.classList.add('dark-mode');
        toggleDarkMode.textContent = 'Return to the light side';
      } else {
        // Dark mode is disabled
        document.body.classList.remove('dark-mode');
        toggleDarkMode.textContent = 'Preview dark color scheme';
      }
    });
  </script>
</body>
</html>

