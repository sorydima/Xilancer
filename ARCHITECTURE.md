# Architecture

## Overview

Xilancer is a Flutter application with platform-specific runners for Android,
iOS, and web.

## Application Layers

- UI: Flutter views and widgets
- View Models: UI state + orchestration
- Services: API, auth, payments, and integration logic
- Data Models: response and domain models

## Data Flow

- Views call view models
- View models delegate to services
- Services communicate with network/data layers
- Results flow back to view models and UI

## Key Directories

- `lib/` app source and UI
- `assets/` images, icons, audio, and animations
- `android/`, `ios/`, `web/` platform projects
