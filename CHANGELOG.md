# 🚚 Load Tracker – Changelog

## v1.3.0 – 2025-08-03
- Vehicle capacity now manually set via Setup page
- Vehicle capacity is persisted per vehicle
- Default capacity logic applies only if no value is entered
- Fixed issue where switching vehicles reset to default capacity
- Setup page: Fire Suppression and Jack inputs disabled
- Capacity is no longer affected by accessories like rod rack or jack
- Added log email export with:
  - Fuel level (4/8, 80L of 160L)
  - Tray and Rod Rack item separation
  - Total weight, tray weight, rack weight
- Fixed bug where rack items were not saved or displayed
- Rack/tray indicators now included in exported logs
- Fixed incorrect calculation where weight was subtracted instead of added
- Capacity used now shown as a whole number percentage
- Vehicle capacity input now replaces placeholder zero cleanly on focus

## v1.2.1 – 2025-07-29
- Fuel gauge added to dashboard
- Fuel affects usable vehicle capacity
- Fuel level persists and is included in logs

## v1.2.0 – 2025-07-20
- Product table supports trial items (shown with *)
- Fixed bug with screen zoom when re-entering app
- iPad Safari export button issue resolved
- Rod rack product logic split into second table
- Product weights reduced by 10% for recycling mode

## v1.1.0 – 2025-07-10
- Major UI rework for dashboard layout
- Responsive layout adjustments for portrait mode
- Added backup + restore feature (JSON file)
- Dynamic load indicator bar and car image overlays

## v1.0.0 – 2025-06-20
- Initial public release
- Full offline support (PWA)
- Vehicle setup, product tracking, and logs
- LocalStorage persistence
- Basic export by email
