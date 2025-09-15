# Twitch Ads in Safari
This repo aims to keep track of various adblock solutions for Twitch.tv in Safari. Solutions apply to both iOS/iPadOS and macOS unless otherwise stated. Forked from [pixeltris/TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions).

**Don't combine Twitch specific ad blockers.**
## Recommendations
Currently in Safari, Userscripts are the best working solution to tackle ads in Twitch. Userscripts are small Javascript files you can run on websites.

## Script
- vaft - [userscript(permalink)](https://github.com/stevenya97/TwitchAdsSafari/blob/8fd54137db9b228319af4c5259a0b660bf9b27f9/vaft.user.js)
  - Uses a lower resolution stream during ads.
- video-swap-new - [userscript(permalink)](https://github.com/stevenya97/TwitchAdsSafari/blob/8fd54137db9b228319af4c5259a0b660bf9b27f9/video-swap-new.user.js)
  - The same as video-swap-new but attempts to get a clean stream faster (may suffer from more freezing / playback issues).

## Applying a script
- Install a userscript manager from the App Store.
  - Free - [Userscript](https://apps.apple.com/us/app/userscripts/id1463298887)(by [Quoid](https://github.com/quoid/userscripts))
  - Paid - [Tampermonkey](https://apps.apple.com/us/app-bundle/tampermonkey-bundle/id1780757125?mt=12)($2.99 for the app bundle. Contains both Safari and legacy Safari versions. Individual extensions are also available.)
- Viewing one of the userscript files should prompt the given script to be added (assuming you have a userscript manager installed). Otherwise, import it manually.

## Troubleshooting
- Make sure that only one solution/script is enabled at a time. Solutions often conflict with one another trying to manipulate the same underlying video stream served to you.
