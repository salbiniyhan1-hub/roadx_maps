ROADX MAPS 3D — ANDROID PWA

FILES
- index.html: app
- manifest.webmanifest: install/home-screen metadata
- sw.js: app-shell caching (does not download map tiles for offline use)
- icon-192.png and icon-512.png: app icons
- icon.svg: scalable icon

IMPORTANT: To use GPS and install as an app, host ALL these files at the same folder on an HTTPS website. Opening index.html from Downloads/file:// will not reliably allow location or PWA installation.

QUICK HOSTING OPTION (GitHub Pages)
1. Create/sign in to GitHub and make a new public repository, e.g. roadx-maps.
2. Upload all files in this folder to the repository root (not the ZIP itself).
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch; choose main and /(root), then Save.
5. Wait for the published HTTPS URL. Open that URL in Chrome on Android.
6. Tap the GPS button and allow location permission. Also ensure Android Location is on.
7. In Chrome, tap ⋮ > Install app (or Add to Home screen). If an Install button appears in RoadX, you can use that too.

LOCATION TROUBLESHOOTING
- Must be the HTTPS website, not a local file preview.
- Chrome site settings > Location > Allow.
- Android Settings > Location: on; allow Chrome location access.
- Try outdoors or near a window; wait a little for GPS fix.
- If denied previously, reset the site's location permission and reload.

LIMITS
- Online maps, search and routing need internet.
- Public OpenStreetMap/Nominatim/OSRM services can rate-limit or be unavailable.
- No live traffic, and this is not an official emergency navigation product. Follow road signs and use a safe phone mount.
