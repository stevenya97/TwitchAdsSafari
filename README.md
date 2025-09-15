# Twitch Ads in Safari
This repo aims to keep track of various adblock solutions for Twitch.tv in Safari. Solutions apply to both iOS/iPadOS and macOS unless otherwise stated. Forked from [pixeltris/TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions).

**Don't combine Twitch specific ad blockers.**
## Recommendations
Currently in Safari, Userscripts are the best working solution to tackle ads in Twitch. Userscripts are small Javascript files you can run in your browser.

## Script
*As of 06/27/25, updated versions of the scripts from [pixeltris/TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions) are not working in the `Userscripts` extension by Quoid. The versions below are the latest working versions of those scripts. If you are using `Tampermonkey` and want the latest updated scripts, follow [pixeltris/TwitchAdSolutions](https://github.com/pixeltris/TwitchAdSolutions)

- `vaft` - [userscript(permalink)](https://raw.githubusercontent.com/stevenya97/TwitchAdsSafari/8fd54137db9b228319af4c5259a0b660bf9b27f9/vaft.user.js)
  - Uses a lower resolution stream(typically <360p) during ads. Swaps back to full quality(if user selected) after ads are over.
- `video-swap-new` - [userscript(permalink)](https://raw.githubusercontent.com/stevenya97/TwitchAdsSafari/0e01efe06415a56c827049a4d45bdf9895fb1251/video-swap-new.user.js)
  - The same as video-swap-new but attempts to get a clean stream faster (may suffer from more freezing / playback issues).

## Applying a script
- Install a userscript manager from the App Store.
  - Free - [Userscripts](https://apps.apple.com/us/app/userscripts/id1463298887)(by [Quoid](https://github.com/quoid/userscripts))
  - Paid - [Tampermonkey](https://apps.apple.com/us/app-bundle/tampermonkey-bundle/id1780757125?mt=12)($2.99 for the app bundle. Contains both Safari and legacy Safari versions. Individual extensions are also available.)
- Viewing one of the userscript files should prompt the given script to be added (assuming you have a userscript manager installed). Otherwise, import it manually.

## Troubleshooting
- Make sure that only one solution/script is enabled at a time. Solutions often conflict with one another trying to manipulate the same underlying video stream served to you.

## Contributing
Feel free to make a pull request or create a new issue here discussing any new or updated solutions.
