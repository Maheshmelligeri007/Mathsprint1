# MathSprint Android Project

This is the MathSprint Android project packaged from the original PWA.

## Build requirements
- Java 17
- Gradle 8.7 (provided through the Gradle wrapper)
- Android SDK / Android build tools (GitHub Actions supplies these on its runner)

## GitHub Actions
The workflow at `.github/workflows/build-apk.yml` uses Java 17 and the included Gradle wrapper to build a debug APK. The resulting APK is uploaded as the `MathSprint-debug-apk` artifact.
