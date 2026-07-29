# Road Clock Alpha 10.4

## Improved navigation tracking

- GPS fixes update a target rather than moving the arrow instantly
- The arrow is animated continuously between GPS updates
- Position is snapped to the route when close enough
- Heading changes are smoothed to reduce wobble
- The camera follows the smoothed arrow at a 62-degree pitch
- Camera motion runs continuously rather than restarting a new ease animation on every GPS update

## ETA

- ETA still uses the destination's local time zone
- Only the arrival time is displayed, such as `9:18 AM`
- Time-zone abbreviations are no longer shown in the compact trip panel

## Voice AI Co-Driver

- Push-to-talk microphone button
- Spoken questions are transcribed into the AI Co-Driver
- Answers are read aloud with speech synthesis
- Graceful fallback when browser speech recognition is unavailable

Voice recognition and speech playback depend on browser permissions and device support.
