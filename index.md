# Meridian Privacy Policy

Last updated: 23 November 2026

Meridian is an always-on focus clock for Android. This policy explains what the app does with your information. In short: **Meridian has no account, no analytics, no advertising and no tracking, and the developer receives none of your data.**

## What stays on your device

Everything you set up is stored only on your device:

- Your settings, themes, layout choices, world-clock cities, alarms, countdowns, routines and focus sessions.
- Backups you choose to export, and the automatic daily backup if you turn it on. Automatic backups are written to a folder you pick; the app can read and write only that folder.
- If you tap "Use my location", the approximate location is worked out on the device and saved on the device. It is used only to calculate sunrise and sunset for sunset dimming. It is never sent anywhere.
- Diagnostic and crash history is kept locally as a JSON file you can view and export yourself. Nothing is sent automatically.

## What is sent over the internet

Meridian uses the internet in only two cases: **Weather** (off by default) and the **Time accuracy check** (only when you tap it). When Weather is on, the app contacts these services:

- **Open-Meteo** (open-meteo.com) for forecasts and to look up the coordinates of your saved city names. It receives city names and city coordinates.
- **US National Weather Service** (api.weather.gov) for official alerts, only for your home city when it is in the United States. It receives that city's coordinates.
- **Environment and Climate Change Canada** (api.weather.gc.ca) for official alerts, only for your home city when it is in Canada. It receives that city's coordinates.

If you tap "Check now" under Time accuracy in Settings, Meridian sends a standard network time (NTP) request to **time.android.com**, and to **time.cloudflare.com** if the first does not answer. It never happens automatically.

These requests include your device's IP address, as any internet request does. Weather requests also carry a generic app name. None include your name, account, device identifier or your device's own location. Each service has its own privacy policy. If Weather is off and you do not tap the time check, the app makes no network requests.

## Permissions

- **Internet:** used only for Weather and the Time accuracy check, as above.
- **Approximate location:** used only when you tap "Use my location", processed on the device. The app never uses precise location.
- **Display over other apps:** optional. Used only so the clock can reopen by itself after your device restarts. You grant it on Android's own settings page and can withdraw it at any time.
- **Run at startup:** used only if you turn on "Start on boot".
- **Battery optimisation:** the app can open Android's battery settings so you can let the clock keep running; the choice is yours and it needs no special permission.

## Backups by Android

If you have Android's own backup turned on, your system may include the app's settings in your Google backup. That is controlled by your device and Google, not by Meridian.

## Children

Meridian does not collect personal information from anyone, including children.

## Sharing and selling

Meridian does not sell, share or rent personal information, because it does not collect any.

## Changes

If this policy changes, the new version will be published here with a new date.

## Contact

Questions: open an issue at https://github.com/shobithshetty/meridian-privacy/issues
