# Road Clock Alpha 9.1 Fixed

- Smoother interpolated camera follow
- Map dragging pauses follow until Resume is tapped
- GPS is matched to the route before calculating progress
- Next-turn distance is measured along the route
- Named shutdown stops are scored by route position and off-route distance
- Stops more than roughly three miles off route are rejected

This remains a browser alpha using public routing and OpenStreetMap data.


## Fix

Corrected a JavaScript syntax error that prevented the map, GPS, and controls from starting.
