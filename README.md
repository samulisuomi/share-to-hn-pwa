# Share to HN (PWA)

A super simple PWA ([progressive web application](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)) that adds a sharing option for [Hacker News](https://news.ycombinator.com/) to the sharing menu in your Android device.

![Demonstration of how the sharing UX looks like on Chrome for Android](https://user-images.githubusercontent.com/3490745/189866298-62ebab14-06b4-4a72-b649-ebc42398a1f2.png)

In other words, it's a handy mobile alternative for the [official HN bookmarklet](https://news.ycombinator.com/bookmarklet.html) for us who often browse HN on their phone. That bookmarklet doesn't work in all mobile browsers, at least not in Chrome for Android.

⚠️ The PWA utilizes the experimental `share_target` attribute in the [manifest](https://developer.mozilla.org/en-US/docs/Web/Manifest), which as of September 2022 is only supported by Chrome and Edge. Check the up-to-date browser support info at [caniuse.com](https://caniuse.com/mdn-html_manifest_share_target).

## Development

Prerequisites:

1. ```
   npm install -g serve
   ```
2. Install Prettier to your editor or shell

Run:

```
serve .
```
