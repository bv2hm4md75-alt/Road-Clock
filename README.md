# Road Clock Alpha 4

## What changed

- Edge-to-edge map layout for installed iPhone use
- No default Nashville-to-Indianapolis route
- Opens at the driver's current GPS location
- Start Route is contained inside the bottom sheet and no longer overlaps status text
- Smoother Leaflet rendering without the CSS map tilt that caused glitches
- Route line remains visible during live tracking
- Cleaner route-planning state
- Start Route stays disabled until a route is calculated
- Improved service-worker updating to reduce stale cached versions

## Upload to GitHub

Replace these files at the top level of your repository:

- index.html
- manifest.json
- service-worker.js
- netlify.toml
- README.md

Upload the individual files, not the ZIP.

## Full-screen iPhone use

Safari itself always shows browser controls. For the edge-to-edge version:

1. Open the Netlify site in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Launch Road Clock from the new Home Screen icon.

## Alpha limitations

- This is not an ELD or approved commercial routing system.
- Routing currently uses a public passenger-car routing service.
- Speed limits remain unavailable until a reliable provider is connected.
- iOS may pause web GPS when Road Clock is backgrounded or the phone locks.
