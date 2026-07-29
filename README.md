# Road Clock Beta 1

Road Clock Beta 1 is a major performance and reliability overhaul for private driver testing.

## Major changes

### Navigation smoothness
- 60 FPS visual vehicle updates
- Camera rendering capped at 30 FPS to reduce main-thread load
- Accuracy-aware short-range position prediction
- GPS outlier rejection
- Heading derived from movement when the phone does not provide it
- Heading-aware route snapping
- Automatic rerouting after repeated route deviation
- Dynamic camera look-ahead and zoom

### Reliability
- Saved route and HOS state restore after accidental app closure
- Network timeouts and backup routing/geocoding services
- Wake-lock support during active navigation
- Global error recovery messages
- Route calculation status
- GPS quality and system health indicator
- Network-first service worker with offline app-shell fallback

### Stops and HOS
- TomTom commercial stop search when a key is available
- OpenStreetMap/Overpass route-aligned fallback
- Unverified parking is clearly labeled
- HOS elapsed time is calculated from real timestamps
- Low-drive-time warning
- Destination-local ETA

### AI Co-Driver
- Voice, typed, and one-tap commands
- ETA, clocks, shutdown, legal reach, next turn, speed, and GPS quality
- Fresh speech-recognition session per request
- Spoken answers where supported

### Jesse demo mode
1. Calculate any route.
2. Tap **RUN JESSE DEMO DRIVE**.
3. Road Clock simulates highway movement.
4. Tap again to stop.

## Important testing note

This is a private beta release candidate, not a certified ELD or commercial truck-routing system. Drivers must independently verify HOS compliance, vehicle restrictions, parking availability, and navigation instructions.

## Deployment

Upload the five core files in this ZIP to the GitHub repository once. Netlify should publish automatically.
