### Firefox/Tor Safari-Like Configuration

This is only working for `Firefox 104` or below. Firefox View broke it.

It will still probably work for latest versions of Tor Browser because they will never add Firefox View.

### macOS Installation

Copy `chrome` and `configuration` folers into your Firefox/Tor Profile Directory

To find your Firefox/Tor Profile Directory you can:

1. Go to `about:support` in Firefox/Tor.
2. Application Basics > Profile Directory > Open Directory.
3. Copy folders mentioned above into the profile folder. (usually has `-release` at the end).
4. If you are using Firefox 69+:
	1. Go to `about:config` in Firefox.
	2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
5. Restart Firefox.
6. Done!


### Credits

* [AdamXweb/WhiteSurFirefoxThemeMacOS](https://github.com/AdamXweb/WhiteSurFirefoxThemeMacOS) for the entire base. I just changed some color values and fixed it for Tor Browser.

