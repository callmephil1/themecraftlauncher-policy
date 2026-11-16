# ThemeCraft Launcher Privacy Policy

Effective date: November 16, 2026

## Overview

ThemeCraft Launcher (package `io.github.themecraft`) does not collect, sell or share your personal data for advertising, analytics or profiling. It has no user accounts, no ads, no analytics and no crash-reporting SDKs. Your settings, layout and history stay on your device.

A few features need to contact an outside service to work. Each is listed below, along with exactly what is sent. This policy applies to the Android app only.

## Information the app uses

The app uses the information below. Only the items marked "Sent off device" ever leave your phone, and only for the purpose shown.

| Information | Why it is used | Where it goes |
| --- | --- | --- |
| List of installed apps | To show your apps on the home and app screens | Stays on device |
| Home layout, themes and settings | To remember how you set up the launcher | Stays on device |
| App launch history | To sort and suggest frequently used apps | Stays on device |
| Web search history | To offer your recent searches again | Stays on device |
| Approximate location (coarse, network-based) | To show local weather and sunrise/sunset times | Sent off device to Open-Meteo and sunrise-sunset.org (see Sharing) |
| Search text you type | To run a web search you start | Opened in your browser on Google Search when you submit it |
| Theme purchases | To unlock themes you have bought | Handled by Google Play Billing |

**Permissions.** The app asks for two permissions:

- **Approximate location** (`ACCESS_COARSE_LOCATION`): only for the weather and sunrise/sunset display. The app never asks for precise (GPS) location. If you deny it, everything except weather and sun times works as normal.
- **Internet** (`INTERNET`): to fetch weather and sun times, and to talk to Google Play for purchases.

## How information is stored and used

Everything the app remembers is kept in its private storage on your device. Other apps cannot read it, and the developer has no server that receives it.

- The app uses your information only to run the launcher features described above.
- Your last known approximate location and the latest forecast are cached on the device so the home screen can show them without asking again.
- The developer never sees your app list, layout, searches, launch history or location.

**Android backup.** The app allows Android's built-in backup. If you have turned on device backup, Android may include the app's settings in the backup it keeps in your own Google account. This is controlled by your device settings, not by the app, and the developer cannot access it.

## Sharing with third parties

The developer does not sell, rent or share your personal data with anyone for advertising, analytics or any other purpose. The only outside services the app talks to are listed here. Each receives only what it needs to answer the request.

| Service | What it receives | When |
| --- | --- | --- |
| [Open-Meteo](https://open-meteo.com/en/terms) | Approximate latitude and longitude, temperature unit, and your IP address (as with any internet request) | When the weather display refreshes |
| [sunrise-sunset.org](https://sunrise-sunset.org/api) | Approximate latitude and longitude, and your IP address | When sunrise/sunset times refresh |
| [Google Play Billing](https://policies.google.com/privacy) | Purchase requests for themes, handled by Google Play under your Google account | Only when you buy or restore a theme |
| [Google Search](https://policies.google.com/privacy) | The search text you submit, opened in your web browser | Only when you run a web search |

No name, email, account ID, device ID or advertising ID is sent to any of these services by the app. Their handling of the requests they receive is covered by their own privacy policies, linked above.

The developer may disclose information if required by law, but the developer holds no personal data from the app to disclose.

## Your choices and deleting your data

You control all the data the app keeps, because it lives only on your device.

- **Remove a search:** delete it from the recent searches list on the search screen.
- **Turn off location use:** revoke the location permission in Android Settings > Apps > ThemeCraft Launcher > Permissions. Weather and sun times will stop updating.
- **Delete everything:** clear the app's storage in Android Settings > Apps > ThemeCraft Launcher > Storage, or uninstall the app. This removes all settings, history and cached location.
- **Purchases:** your purchase record is kept by Google Play in your Google account, so bought themes can be restored after reinstalling.

## Children's privacy

The app is directed to users of all ages, and does not knowingly collect personal information from anyone, including children.

## Security

Weather and sun-time requests and Google Play purchases use encrypted HTTPS connections. Data stored on the device is kept in the app's private storage, protected by Android's app sandbox.

## Changes to this policy

If this policy changes, the updated version will be posted at this address with a new effective date. Significant changes will also be noted in the app's release notes.

## Contact

Questions about this policy or your data: themecraft19@gmail.com.
