# Build the APK with GitHub Actions

Upload the CONTENTS of this folder to the root of your GitHub repository.
Do not put the Flutter project inside `.github/workflows`.

The repository root must show at least:

- `android/`
- `lib/`
- `pubspec.yaml`
- `.github/workflows/build-apk.yml`

Then open GitHub > Actions > Build Android APK > Run workflow.
When the job succeeds, download the artifact named `secure-document-vault-debug-apk`.
It contains `app-debug.apk`.
