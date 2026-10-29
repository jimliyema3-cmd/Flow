# MusicFlow Android app

A starter Android music player built with Kotlin and the Android SDK.

## Included
- Dark, modern MusicFlow interface
- Reads music files on the device after permission is granted
- Search by song title or artist
- Play/pause, previous, next, and automatic next-track playback
- GitHub Actions workflow that builds a debug APK and uploads it as an artifact

## Build an APK on your phone using GitHub
1. Download and extract `MusicFlow-project.zip`.
2. Create a GitHub repository and upload the *contents* of the extracted folder (including the hidden `.github` folder).
3. Open the repository's **Actions** tab.
4. Choose **Build MusicFlow APK** and tap **Run workflow** if it hasn't started automatically.
5. Open the completed run, find **Artifacts**, and download **MusicFlow-debug-apk**.
6. Extract the artifact ZIP; install `app-debug.apk` on your phone. Android may ask you to allow installs from that source.

## Notes
- This is a first working version, not a Play Store release.
- The APK is unsigned for Play Store release (Android debug-signed for local installation).
- The app plays audio files available through Android MediaStore. Streaming services and online accounts are not included.
