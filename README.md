# Muslim-App

An online Quran app with surah browsing, caching and location features.

## Highlights

- **Online mode** — surah list and pages fetched over the network.
- **Local mode** — a bundled JSON copy of the Quran for offline reading.
- Local SQLite caching for faster repeat access.
- Pull-to-refresh and Google Maps integration.

## Tech Stack

| Concern | Choice |
|---|---|
| UI | Flutter, Material |
| Networking | `http` |
| Persistence | `sqflite`, `path` |
| UX | `pull_to_refresh` |
| Maps | `google_maps_flutter` |

## Project Structure

```
lib/
- `local_json_quran_app`
- `online_quran_app`
- `main.dart`
```

## Getting Started

### Prerequisites

- Flutter `>= 3.16` (Dart `>= 3.2`)

### Run

```bash
git clone https://github.com/developer-rahim/Muslim-App.git
cd Muslim-App
flutter pub get
flutter run
```

### Test

```bash
flutter test
flutter analyze
```

## Notes

Two implementations sit side by side — `local_json_quran_app` and `online_quran_app` — so you can compare offline and network-backed data sources.

## License

Released under the MIT License.
