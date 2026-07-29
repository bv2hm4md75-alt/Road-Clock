# Road Clock Alpha 10.2

## Fixed

- Prevents the MapLibre error: `Style is not done loading`
- Route drawing now waits for `load` or `style.load`
- Route layers are safely recreated after light/dark theme changes
- Default clocks are now:
  - Drive: 10:00
  - Duty: 15:00
  - Cycle: 70:00
- Route calculation waits for the vector map before drawing

## Upload

Replace the five repository files with the five individual files inside this ZIP.
