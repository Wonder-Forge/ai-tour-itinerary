# Microsoft AI Tour Houston 2026 Itinerary

A mobile-friendly single-page itinerary app for Microsoft AI Tour Houston 2026.

The app is designed to be hosted with GitHub Pages and opened from a phone browser. It highlights the current schedule item during the conference, shows a countdown before the conference starts, shows an ended state after the itinerary is complete, supports dark mode through the device/browser preference, and includes expandable alternates for selected sessions.

## Features

- Single `index.html` static app.
- Mobile-friendly layout.
- Device/browser dark mode support.
- Houston/CDT time-aware current-session indicator.
- Countdown before the conference starts, including seconds.
- Ended-state card after the conference ends.
- Expandable alternates and fallbacks under relevant sessions.
- Booth windows separated from the main itinerary.
- Venue button for George R. Brown Convention Center in Google Maps.
- Embedded app icon for browser/PWA-style use.

## GitHub Pages setup

1. Open the repository settings.
2. Go to **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/root**.
5. Save.

After GitHub Pages finishes publishing, open the site URL in Safari or Chrome. On iPhone, use **Share -> Add to Home Screen** for app-like access.

## Notes

This is a lightweight static itinerary app. It does not require a build step, package manager, server runtime, or external JavaScript libraries.

The schedule data is embedded directly in `index.html`.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
