# Rainlit for Android

The Android app for [Rainlit](https://rainlit.app). Each release here has one file,
`Rainlit.apk`, and is tagged with the app's version (`v1.3.2` is Rainlit 1.3.2).

Rainlit is invite-only, so you'll need an account to sign in.

## Installing

- **Straight from the site:** open [rainlit.app/android](https://rainlit.app/android)
  on your phone, open the file, and allow your browser to install apps when asked.
- **With [Obtainium](https://github.com/ImranR98/Obtainium):** add
  `https://github.com/coldsignals/rainlit-android` and it'll keep Rainlit up to date.

New versions install over the old one; there's no need to uninstall first (that
would sign you out).

Works on Android 7 and up, without Google services (GrapheneOS included).

## Notifications while Rainlit is closed

Install [ntfy](https://ntfy.sh/docs/subscribe/phone/) too (free, no account). Rainlit
finds it and connects by itself. On Obtainium, add
`https://github.com/binwiederhier/ntfy-android` and pick the **fdroid-release** APK.

## Xiaomi, Redmi and Poco phones

They close apps in the background, even during calls. In Settings → Apps → Manage
apps → Rainlit, set **Battery saver** to **No restrictions** and turn on **Autostart**.
