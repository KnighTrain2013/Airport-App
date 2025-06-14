# Airport Navigator App (Flutter)

A cross-platform app for navigating major airports, tracking flights, and finding airport facilities.

## Features

- Interactive hybrid airport maps (OpenStreetMap + official terminal overlays)
- Indoor navigation with blue-dot (device GPS or user pin)
- Display TSA, lounges, gates, restrooms, etc.
- Search for and track flights (Aviationstack API)
- Push notifications for flight status/updates (via Firebase)
- Save user preferences and flights (local and cloud sync)

## Tech Stack

- **Flutter** (cross-platform)
- **Firebase** (auth, Firestore, cloud messaging)
- **Aviationstack** (flight data)
- **OpenStreetMap** (outdoor maps)
- **Official airport SVG maps** (indoor overlays)
- **geolocator** (device GPS)
- **flutter_map** (OpenStreetMap integration)
- **flutter_svg** (SVG overlays)
- **provider** (state management)
- **Hive** (local storage)

## Getting Started

1. Clone this repository.
2. Add your Aviationstack and Firebase config.
3. Run `flutter pub get`.
4. Launch on iOS/Android/emulator.

## Next Steps

- Add more airport SVG overlays in `assets/maps/`.
- Polish onboarding & notifications.
- Expand indoor navigation accuracy.
