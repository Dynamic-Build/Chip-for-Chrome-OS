# Chip for Chrome OS
The Chip Browser for the Chrome Operating System! The minimum version for it to work is Chrome OS 63 and will work on any version above Chrome OS 63. The Chip Browser uses the Revor Engine and it's virtual processor to run it. Since an advanced browser needs advanced hardware, How about you do the math!

> Coming soon to Chrome OS 64 and 65!

<a target="_blank" href="https://chrome.google.com/webstore/detail/edggnmnajhcbhlnpjnogkjpghaikidaa">![Try it now in CWS](https://raw.github.com/GoogleChrome/chrome-app-samples/master/tryitnowbutton.png "Click here to install Chip for Chrome OS from the Chrome Web Store")</a>

# The browser itself

The app's main window contains a `<webview>` that is sized to fit most of it
(via the `width` and `height` attributes). The location bar is used to
update its `src` attribute.

`<webview>` is the preferred way for the app to load web content into the app itself. It
runs in a separate process and has its own storage, ensuring the security and
reliability of your computer.

## Resources

* [Webview](http://developer.chrome.com/apps/app_external.html#webview)
* [Permissions](http://developer.chrome.com/apps/manifest.html#permissions)

## Screenshot

![screenshot](https://raw.githubusercontent.com/Dynamic-Build/Chip-for-Chrome-OS/master/assets/screenshot_1280_800.png)
