# Road Clock Alpha 10.5

## Arrow and camera tracking

- Adds short-range dead-reckoning prediction between GPS updates
- Predicts forward motion from live speed and heading
- Snaps predicted position back to the route when appropriate
- Uses faster catch-up interpolation to reduce arrow lag
- Smooths heading without making the arrow trail far behind
- Camera follows the predicted, smoothed position
- Geolocation requests now use zero cached age

## AI Co-Driver stability

- AI opens as a compact voice overlay instead of a full-screen panel
- Speech recognition is created only when the microphone is tapped
- Each question uses a fresh recognition session
- Eight-second timeout prevents frozen microphone sessions
- Spoken answers remain enabled
- Typed AI remains available as a fallback

## Upload

Replace the five repository files with the files inside this ZIP.
