# Pockets Infinity
**Version:** `0.1.0-alpha`

Pockets Infinity gives players of the game [Destiny](http://destinythegame.com/) enhanced access to the items on their Guardians and the Vault. Its basically Batman's utility belt for your Guardian, all your items in one place.

Since version `0.1.0-alpha` is _pre-release_, Pockets Infinity only dipslays information in the console, press `Ctr + Shift + J` on Windows or `Cmd + Opt + J` on Mac to bring up the console.

## Requirements
- [Bungie Platform Developer API-Key](https://www.bungie.net/en/User/API)
- [Chrome Desktop Web Browser](https://www.google.com/intl/en/chrome/browser/desktop/index.html)

## Getting Started
[Download a .zip](https://github.com/blainefricks/pockets-infinity/zipball/master) or clone the repo: `git clone https://github.com/blainefricks/pockets-infinity.git`.

Install dependencies: `bower install` or see the [Wiki](https://github.com/blainefricks/pockets-infinity/wiki/dependencies) for a list of dependencies.

Save your [API-Key](https://www.bungie.net/en/User/API) in the `app/scripts/apiKey.js` file:
```javascript
var apiKey = 'ENTER_YOUR_API_KEY_HERE';
```

Enable [Chrome Extensions Developer Mode](https://developer.chrome.com/extensions/faq#faq-dev-01) and point it to the `app/` folder.

Once you have installed the Chrome Extension, sign into [Bunge.net](http://bungie.net) and then press the Pockets Infinity icon or options page to launch. Press `Ctr + Shift + J` on Windows or `Cmd + Opt + J` on Mac to view the Console and see your Destiny data that Pockets Infinity fetches.

## Reporting Bugs
Have a bug to report? First search through the [open](https://github.com/blainefricks/pockets-infinity/issues?q=is%3Aopen+is%3Aissue) and [closed](https://github.com/blainefricks/pockets-infinity/issues?q=is%3Aissue+is%3Aclosed) issues before submitting your bug. If your problem has not been submitted, please open a new issue and include the version of Pockets Infinity you are using.

## License
Code released under [the MIT license](http://choosealicense.com/licenses/mit/).
