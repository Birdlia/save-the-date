# Save the Date — South Okanagan

A small, static, phone-first wedding invitation page. It preserves the supplied card artwork and replaces the printed countdown numbers with a live days / hours / minutes / seconds countdown.

## Set the event time

Edit `event-config.js` before publishing:

```js
window.EVENT_CONFIG = {
  date: "2028-06-17",            // YYYY-MM-DD
  timeZone: "America/Vancouver", // IANA time zone
};
```

The countdown targets midnight at the start of the event date in the selected time zone. If the date or time zone is missing or invalid, the four fields show `--`.

## Publish with GitHub Pages

1. Put the contents of this folder at the root of a GitHub repository, or in the folder you choose to publish.
2. In GitHub, open **Settings → Pages** and choose **Deploy from a branch**.
3. Select the branch and folder containing `index.html` (usually `main` and `/ (root)`), then save.
4. Open the generated Pages URL on an iPhone to review the invitation.

No build step, package installation, or server is needed. The page works as a static GitHub Pages site.
