# Royal Gambit

Royal Gambit is a polished Flutter chess game built for Android. It includes a premium mobile chess experience with custom board themes, animated piece movement, AI opponent modes, local two-player mode, timers, sound effects, tutorials, match history, and persistent settings.

## Features

- Play vs Computer and 2-player local mode
- Easy, Medium, and Hard difficulty selection
- Theme-based chess boards and SVG piece sets
- Wood, Green, and Black visual themes
- Timer and no-timer match options
- Legal chess move validation using the `chess` package
- Check, checkmate, stalemate, draw, castling, en passant, and promotion support
- Pawn promotion selection for Queen, Rook, Bishop, or Knight
- Smooth animated piece movement
- Capture popup with sound and animation
- Checkmate/game-over popup with match result
- Match history screen with move list and captured pieces
- Learn Chess section with visual movement demonstrations
- Persistent settings using `shared_preferences`
- Custom app logo and launcher icon

## Screens

- Splash Screen
- Main Menu
- Match Setup
- Chess Board
- Learn Chess
- Settings
- Match History
- Game Over Popup

## Tech Stack

- Flutter
- Dart
- Provider
- chess
- flutter_svg
- audioplayers
- shared_preferences
- animations
- google_fonts
- flutter_launcher_icons

## Project Structure

```text
lib/
  main.dart
  models/
  screens/
  services/
  widgets/

assets/
  audio/
  fonts/
  images/
  matchsetup/
  pieces/
  ui/
```

## Getting Started

Install dependencies:

```bash
flutter pub get
```

Run on a connected Android device:

```bash
flutter run
```

Run on a specific device:

```bash
flutter run -d DEVICE_ID
```

## Build APK

Create a release APK:

```bash
flutter build apk --release
```

The APK will be generated at:

```text
build/app/outputs/flutter-apk/app-release.apk
```

## App Icon

The app icon is configured with `flutter_launcher_icons`.

To regenerate launcher icons:

```bash
flutter pub run flutter_launcher_icons
```

## Notes

- This project is optimized for Android portrait gameplay.
- Release APK files are not committed to GitHub.
- Build output folders such as `build/`, `.dart_tool/`, and generated Android build files are ignored through `.gitignore`.

## Author

Developed by Shahrukh Khan.
