# USB/IP download page

The one-page site at **https://kruchone.github.io/usbip/**. It detects the visitor's platform (Android, Windows x64/ARM64,
Linux, macOS, iOS) and links the right download from the latest release of
[usbip-windows](https://github.com/kruchone/usbip-windows) or [usbip-android](https://github.com/kruchone/usbip-android).

Release info is read live from the GitHub API, so new releases show up without editing the page. `FALLBACK` in
`index.html` covers the API being unreachable; update it occasionally.
