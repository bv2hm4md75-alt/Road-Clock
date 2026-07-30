# Beta 2 RC3 Release Notes

## Route state
- Bumped saved-state storage version to prevent stale RC2 destinations from restoring.
- Added New Route and Clear Saved Route controls.
- Edit Route now selects the existing destination for immediate replacement.

## Map control
- Any genuine map gesture disables automatic follow.
- Manual exploration remains active until Resume is tapped.
- Camera updates are blocked while manual exploration is active.

## Shutdown recommendations
- Added a hard 11-second search ceiling.
- Added stale-request protection when routes change.
- Failed searches now resolve with a clear retry message.
