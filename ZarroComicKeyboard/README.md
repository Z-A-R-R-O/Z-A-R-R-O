# Zarro Comic Keyboard

A comic-book styled Android keyboard prototype for Samsung Galaxy and other Android devices.

## Build

The GitHub Actions workflow at `.github/workflows/build-zarro-keyboard.yml` expects a complete Gradle Android project in this directory, including:
- `settings.gradle` or `settings.gradle.kts`
- root `build.gradle` or `build.gradle.kts`
- module `app/build.gradle` or `app/build.gradle.kts`
- Android manifest and Kotlin sources

Run the workflow from **Actions → Build Zarro Comic Keyboard APK → Run workflow**. The debug APK is published as a 30-day workflow artifact.

## Important

This repository currently contains the build workflow and project instructions only. The full Android source project and artwork must be added before the workflow can produce an APK. No APK has been built or released yet.
