# Operation Vice City — Ultimate Edition V10.1

A cross-platform, installable Progressive Web App (PWA) for the GTA VI launch plan.

## Deploy / update on GitHub Pages
Upload and commit all files in this package to the root of your existing GitHub Pages repository, replacing the previous V10 files. Keep the repository's existing Pages deployment configuration. Wait for the Pages deployment to finish, then open the published HTTPS URL.

## Install on iPhone
1. Open the published URL in Safari.
2. Tap Share.
3. Choose Add to Home Screen.
4. Enable Open as Web App if shown, then tap Add.

## Install on Android
1. Open the published URL in Chrome.
2. Tap Install app if Chrome offers it (or ⋮ → Add to Home screen).
3. Confirm Install / Add.

The PNG 192×192 and 512×512 icons are included for Android installation; the Apple touch icon is included for iOS.

## Included
- Dashboard, mission checklist, editable launch schedule, inventory, setup checks
- Original generated synth ambience and sound cues
- Spotify / Apple Music playlist link handoff
- Exploration tracker and personal intelligence notebook
- Editable countdown (default 19 November 2026, 00:00 UK)
- Local persistence, JSON backup/restore, offline app shell
- Responsive mobile and desktop layouts

## Important: each person's data
By default, each installation stores its own tasks, inventory, notes and preferences in that person's browser/device. Your mates can each use their own copy independently. Data does not automatically sync between people or devices. A shared crew board / cloud sync would require a backend and user accounts, which is a separate upgrade.

## Capability notes
- Xbox, TV, WiZ lighting, fridge temperature and controller battery status are manual checks, not live-connected diagnostics.
- Licensed music is not streamed by this app; playlist links open the selected music provider.
- The app must be served over HTTPS (GitHub Pages provides HTTPS) for installation and offline service-worker support.
