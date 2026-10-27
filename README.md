# SideHustle

A coursework Android project (Java) for browsing and managing part-time job listings. Screens include splash, login/signup, home, search, featured jobs, job detail, favorites and a profile with personal details, experience and skills fragments.

This repository is a snapshot of a course project; no claim is made here about authorship beyond its use as a learning exercise.

## Setup

1. Open the project in Android Studio and let Gradle sync.
2. The login flow uses Firebase / Google sign-in. `google-services.json` is intentionally **not** included (it is git-ignored). Create your own Firebase project, register the app package `com.example.sidehustle`, and place the downloaded `google-services.json` in `app/` before building.
3. Run on an emulator or device (`./gradlew assembleDebug`).
