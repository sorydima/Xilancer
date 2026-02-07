# Contributing to Xilancer

Thanks for taking the time to contribute.

## Quick Start

1. Fork the repo and create your branch from `main`.
2. Install Flutter (stable channel).
3. Run:
   - `flutter pub get`
   - `flutter analyze`
   - `flutter test`

## Development Setup

### Prerequisites

- Flutter SDK (stable)
- Android Studio (Android SDK + emulator)
- Xcode (for iOS builds on macOS)
- Git

### Environment

- `flutter doctor -v`
- `flutter pub get`

### Run

- Android: `flutter run -d android`
- iOS (macOS only): `flutter run -d ios`
- Web: `flutter run -d chrome`

### Build

- Android APK: `flutter build apk`
- iOS: `flutter build ios`
- Web: `flutter build web`

## Project Structure

- `lib/` Flutter app source
- `assets/` static assets
- `android/`, `ios/`, `web/` platform projects

## Code Style

- Use `dart format` where appropriate.
- Avoid unnecessary churn and keep diffs minimal.

## Commit Guidelines

- Keep commits focused and descriptive.
- Prefer imperative commit messages (e.g., "Fix login validation").
- If enabled, use Conventional Commits format.

## Pull Requests

- Explain the problem and the solution.
- Include screenshots or recordings for UI changes.
- Update docs when behavior changes.
- Ensure CI passes.
