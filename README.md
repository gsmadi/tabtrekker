#TabTrekker
[![Codacy Badge](https://api.codacy.com/project/badge/grade/558c8d1d8ddc419fa5fa501558288155)](https://www.codacy.com/app/gowong/tabtrekker)

Explore the world one tab at a time.
TabTrekker is a Firefox addon that replaces the new tab page.

##Development
1. Install npm
1. Install jpm `npm install jpm --global`
1. Start Firefox with a separate dev profile using: `jpm run --profile=~/firefox-dev/profiles/dev` *(Note: replace ~ with the absolute path to your home directory)*
1. Install [Extension Auto-Installer](https://addons.mozilla.org/en-US/firefox/addon/autoinstaller/).
1. (Optional) Install [Locale Switcher](https://addons.mozilla.org/en-US/firefox/addon/locale-switcher/).
1. (Optional) Install any [language packs](https://addons.mozilla.org/en-US/firefox/language-tools/) that you want to test.
1. Automatically build and install the addon when files change: `jpm watchpost --post-url http://localhost:8888/`
1. Deploy Parse API using `parse deploy TabTrekkerDev`

##Translations
[Help translate TabTrekker!](https://gowong.oneskyapp.com/collaboration/project?id=47644)

## Compatibility
Firefox 39+ is supported.
