# MY FITNESS — Premium Fitness

This is a self-contained MY FITNESS build based on the supplied black/gold reference UI.

## Included
- One-time profile setup: name, age, height, weight, gender, goal, level
- Premium black/gold UI with stable bottom navigation
- Exercise Library with 40 exercises and muscle filters/search
- Target Muscle browser
- Exercise detail/demo screen
- Monday–Sunday workout plans and difficulty selector
- Personal Trainer session with device speech synthesis
- Automatic motivation behavior (no separate Motivation Mode switch)
- Camera posture-tracker preview using device camera permission
- Indian balanced meal template and starting energy estimate
- Progress dashboard
- Profile, settings, premium theme choices
- Recommendation section
- LocalStorage persistence
- Offline-friendly PWA files
- Android WebView project
- GitHub Actions workflow to build a debug APK in the cloud

## Build APK without a PC
1. Put this project in a GitHub repository.
2. Open **Actions → Build MY FITNESS APK → Run workflow**.
3. Download the `MY-FITNESS-debug-apk` artifact.

## Important
The posture tracker here is a camera preview, not production-grade pose estimation/rep counting. The voice coach uses the device/browser speech engine. Production AI/pose models and a backend can be added later.
