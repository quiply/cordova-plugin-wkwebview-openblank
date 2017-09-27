### Cordova Plugin WKWebView OpenBlank

##### Only for iOS
For security reasons, WKWebViews doesn't allow `window.open('https://google.com', '_blank')` to open. If it did it will take over the WKWebView. This plugin catches the request of `window.open+_blank` and sends the url to Safari.
