# Chip for Chrome OS
The Chip Browser for the Chrome Operating System!

<a target="_blank" href="https://chrome.google.com/webstore/detail/edggnmnajhcbhlnpjnogkjpghaikidaa">![Try it now in CWS](https://raw.github.com/GoogleChrome/chrome-app-samples/master/tryitnowbutton.png "Click here to install Chip for Chrome OS from the Chrome Web Store")</a>

# The browser itself

The app's main window contains a `<webview>` that is sized to fit most of it
(via the `width` and `height` attributes). The location bar is used to
update its `src` attribute.

`<webview>` is the preferred way for you to load web content into your app. It
runs in a separate process and has its own storage, ensuring the security and
reliability of your application.

## Resources

* [Permissions](http://developer.chrome.com/apps/manifest.html#permissions)

## Screenshot

![screenshot](Chip-for-Chrome-OS/assets/screenshot_1280_800.png)
