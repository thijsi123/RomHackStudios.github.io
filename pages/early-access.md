---
title: Early Access
layout: page
nav_exclude: true
image: /pages/v1.0.8.7.EA.png
---
# **Pokemon Emerald Crest**

Thank you for choosing Pokemon Emerald Crest! You can download the `Early Access` version of the game below.

<p align="center">
<img src="https://media.discordapp.net/attachments/1101397974313074708/1127584844751315004/Adobe_Express_20230709_1829050_1.png" />
</p>

## **Download**
{: .d-inline-block }

Early Access 
{: .label .label-yellow }

[Early Access v1.0.8.7](){: .btn .btn-purple .mr-2 }
```
What's New!
- Fixed Exp Share breaking in options menu
- Fixed Flickering move text in double battles
- Added Exp multiplayer in options menu
```

{: .warning }
> It's an `Early Access` version so there might be some bugs and issues, please report them in our [discord server]

## **v1.9.0**
{: .d-inline-block }

33.33% complete
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
        width: 33.33%;
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

## Installation Instructions

To play Pokemon Emerald Crest, you will need to have a Game Boy Advance emulator installed on your device. We recommend using [Mgba](https://mgba.io/downloads.html) for Windows, Linux, and Mac, or [My Boy!](https://play.google.com/store/apps/details?id=com.fastemulator.gba) for Android devices.

Once you have downloaded the emulator, follow these steps in [How To Patch](https://romhackstudios.github.io/pages/howtopatch.html) to play Pokemon Emerald Crest

## Support

If you encounter any issues or have questions about Pokemon Emerald Crest, please contact us through our [discord server].

[discord server]: https://discord.gg/aaghat-s-server-965900074532081674 

<script src='https://storage.ko-fi.com/cdn/scripts/overlay-widget.js'></script>
<script>
  kofiWidgetOverlay.draw('aaghatislive', {
    'type': 'floating-chat',
    'floating-chat.donateButton.text': 'Support Us',
    'floating-chat.donateButton.background-color': '#ff5f5f',
    'floating-chat.donateButton.text-color': '#fff'
  });
</script>
