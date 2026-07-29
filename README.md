# Road Clock Beta 2 RC1

## Navigation stabilization
- Route matching occurs only when a real GPS sample arrives, not every animation frame.
- Tight accuracy-aware road snapping replaces the previous oversized snap radius.
- Route progress is monotonic to prevent snapping backward.
- Vehicle, heading, and camera each use separate smoothing.
- Prediction is capped to prevent the arrow from lunging ahead.
- Camera look-ahead and zoom respond gradually to speed.
- UI calculations are throttled so map rendering gets priority.
- GPS outlier rejection and off-route confirmation are stricter.

## Test first
Use a familiar route with a passenger observing. This remains a private beta and is not a certified ELD or guaranteed truck-routing product.
