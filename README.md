#### :warning: With the introduction of [Chrome Memory Saver](https://blog.google/products/chrome/new-chrome-features-to-save-battery-and-make-browsing-smoother/) this extension is somewhat redundant and I decided to archive it.

## Unload Tabs - Chromium Extension

This is a minimal extension for Chromium browsers using Manist v3. I created it because I wanted an extension to reduce my browser RAM usage. I didn't want to install an extension that would auto-update and bring all sorts of shenanigans (spam, monitoring, ads, etc.). So, I created this extension and decided to share it in case someone is looking for something similar.

### Installation

**This extension is for developers and people who can understand its code as all settings are embedded in the first lines of the `background.js` file.**

Download the code and unzip it.

Adjust the values for `discardAfterMinutes` and `doNotDiscard` in the `background.js` file. 

Type chrome://extensions in your browser (or go to Settings->Extensions) and enable Developer Mode.

Then click Load Unpacked and point to the folder where you stored the code.

You may also set `log` or `debug` true in the `background.js` file to see what the extension is doing. To get the console log after installation, click Details->Service Worker. You can also go to chrome://discards to see the tabs that have been discarded/unloaded.
