# CI

This repository uses GitHub Actions and GitLab CI.

## GitHub Actions

- Workflow: `.github/workflows/ci.yml`
- Runs: `flutter pub get`, `flutter analyze`, `flutter test`

## GitLab CI

- Pipeline: `.gitlab-ci.yml`
- Image: `cirrusci/flutter:stable`
- Runs: `flutter pub get`, `flutter analyze`, `flutter test`
