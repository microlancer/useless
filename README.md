# Useless Framework
Useless is a multi-platform (iOS, Android, Desktop, Web) framework for developing extremely simple applications

Existing frameworks are very powerful, but they have many downsides.

| Framework | Problems |
|------|-----|
| ReactNative | Requires a "bridge" and doesn't work natively with the OS, making it slower. It also doesn't work well on the web. |
| Flutter | Uses the device GPU and renders everything from scratch, losing a lot of the native component efficiency. It's a waste of battery life for basic apps that don't need 60 fps performance. |
| Ionic Cordova / Capacitor | Uses a WebView which is being deprecated by iOS/Android, and already has major issues with cross-site cookie handling. WebView also has very poor performance. |

Useless is different from the above "single codebase" frameworks in that Useless apps compile to Swift for iOS, Java for Android, and HTML/JS/CSS for Web. That is, it uses the code that works the most efficiently for each individual platform.

The trade-off or downside of Useless is that only a very specific subset of functionality is available. Useless is only good for the most basic, brain-dead application you can imagine. All Useless applications have:

* A menu from a hamburger button
* A screen per menu item
* A screen can be text, form, or a list of items

That's pretty much it. No fancy widgets. No 60 fps animations. No "WebView" nonsense. No bridges or canvases. Just multiple platforms from a single codebase.
