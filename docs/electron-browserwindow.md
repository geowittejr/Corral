

Access the DOM From Web Page not Main Process
https://stackoverflow.com/questions/50494872/how-do-i-access-the-dom-elements-in-electron


Tabbed Browser Interface
-The difference between a BrowserWindow and Webview is that the Webview has Node integration turned off
by default. That way untrusted content from the internet can be embedded.
-According to this post:
https://stackoverflow.com/questions/37602759/what-is-the-difference-between-browserwindow-and-webview-tag-in-electron-and-w

It appears that I will want to create a page using a BrowserWindow that has an html page containing multiple tabs, with each tab containing a separate WebView component.

Here's an example project that does just that:
https://github.com/brrd/electron-tabs

Here's another:
https://blog.jscrambler.com/building-a-web-browser-using-electron/