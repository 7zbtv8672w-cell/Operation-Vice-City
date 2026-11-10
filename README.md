# Operation Vice City V9

Upload these files to the root of your existing GitHub Pages repository, replacing the V8 versions.

## V9 additions
- Animated Vice City opening screen
- Original synthesized startup and launch sound effects (optional)
- Staged cinematic go-live sequence
- V9 Upgrades department with Home Assistant / WiZ / Xbox integration setup references
- Updated service-worker cache version

## Update your existing GitHub Pages site
Replace `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, and `README.md` in the repository root. Commit directly to `main`. GitHub Pages will redeploy automatically.

## Integration limitations
This version does not directly control WiZ or Xbox devices. Home Assistant must be separately installed and configured, and supported device integrations and permissions must be checked. Do not put Home Assistant tokens in this static app.
