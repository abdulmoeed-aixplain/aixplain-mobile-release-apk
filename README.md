# aiXplain — Android test builds

Sideloaded test builds of the aiXplain app (production environment). The app
reads [`latest.json`](latest.json) when it opens and offers each new build.

## Install

1. On the phone, open the
   [latest release](https://github.com/abdulmoeed-aixplain/aixplain-mobile-release-apk/releases/latest) and download the
   `.apk`.
2. Open the downloaded file. If Android asks, allow your browser to install
   unknown apps.
3. After that, tap **Update** when the app offers a new build, then open the
   downloaded file.

**Have a build older than 7?** It was signed with a different key, so
Android won't install over it. Uninstall it first, then install this one.

## Files

- `latest.json` — the newest build; the app's update check reads it.
- [`RELEASES.md`](RELEASES.md) — every published build, newest first.
