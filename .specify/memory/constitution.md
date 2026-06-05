# BookMania Mobile Constitution

## Core Principles

### I. Cross-Platform First
Features must be designed to work seamlessly on both Android and iOS from a single shared codebase where possible. Platform-specific code should be strictly isolated and well-documented.

### II. Offline Resiliency
The app must gracefully handle spotty or disconnected network states. Core functionality should be accessible offline, with data synchronized when the connection is restored.

### III. Responsive & Native-Feeling UI
The user interface must adapt to various screen sizes. Interactions should feel native to each platform (e.g., standard navigation gestures).

## Target SDKs & Environments

- **iOS**: Minimum target iOS 15.0+
- **Android**: Minimum target Android 8.0 (API Level 26)+
- **App Stores**: All features must strictly adhere to current Apple App Store and Google Play Store review guidelines.

## Quality Gates & Review Process

- Code must pass automated linting and formatting.

## Governance

This Constitution supersedes all other project practices. All PRs and reviews must verify compliance with these mobile-first principles. Any amendments to this document require team consensus and an update to the version log.

**Version**: 1.0.0 | **Ratified**: 2026-06-05 | **Last Amended**: 2026-06-05
