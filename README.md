# Alfred Workflow: Youtube Music Controls for Chrome

An Alfred workflow for controlling Youtube Music playback in an open Youtube Music tab in Chrome.

I built this workflow out of necessity as Google Play music will be retired shortly. I listen to music most of the day at work and this helps immensely. While this workflow was created using Alfred 4, it should also work with Alfred 2 & 3.

The workflow uses the following keywords to control playback in an open Google Play tab:

* `ym`: Play/Pause
* `ym prev`: Previous Song
* `ym next`: Next Song
* `ym+`: Thumbs Up Song
* `ym-`: Thumbs Down Song
* `ym quit`: Close Youtube Music Tab
* `ym search <search term>`: Search Youtube Music

![Alfred Workflow Screenshot](screenshot.jpg)

## Requirements

By default, executing JavaScript through AppleScript is turned off in Chrome. To turn it on, from the menu bar, go to *View > Developer > Allow JavaScript from Apple Events*.

For more information: [https://support.google.com/chrome/?p=applescript](https://support.google.com/chrome/?p=applescript)

![Chrome Enable Applescript](chrome-enable-applescript.jpg)
