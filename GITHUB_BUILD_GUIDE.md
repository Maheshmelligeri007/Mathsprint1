# MathSprint — corrected GitHub APK build

This project includes a Gradle wrapper and a GitHub Actions workflow for building a debug APK without Android Studio on your phone.

## Important
Upload the **contents of this project** to the root of your GitHub repository. In particular, make sure these paths exist:

- `gradlew`
- `gradlew.bat`
- `gradle/wrapper/gradle-wrapper.jar`
- `gradle/wrapper/gradle-wrapper.properties`
- `.github/workflows/build-apk.yml`
- `app/`
- `settings.gradle`
- `build.gradle`

## Build from GitHub

1. Open the repository's **Actions** tab.
2. Select **Build MathSprint APK**.
3. Tap **Run workflow**.
4. Wait for the run to finish with a green check.
5. Open the successful run.
6. Under **Artifacts**, download `MathSprint-debug-apk`.
7. Extract the artifact and install the `.apk` on your Android phone.

The workflow uses Java 17 and Gradle 8.7, matching the Android Gradle Plugin 8.6.1 used by this project.
