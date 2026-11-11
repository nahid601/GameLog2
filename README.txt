GAME LOG - Android + Windows

The easy way (no installs on your computer):
 1. Make a free account at github.com and create a new repository.
 2. Upload everything in this folder (keep the folder names, and the hidden .github folder).
 3. Open the repository's "Actions" tab. The build starts by itself (or press "Run workflow").
 4. When it finishes (a few minutes), open the run and download:
      GameLog-Android-APK        -> app-debug.apk   (share and install on any Android phone)
      GameLog-Windows-Installer  -> Game Log Setup 1.0.0.exe (install on Windows)

The manual way:
 Android: open the "android" folder in Android Studio, then Build > Build APK(s).
 Windows: install Node.js, open a terminal in the "windows" folder, run:
            npm install
            npm run dist
          The installer appears in windows/dist.

Game covers: in the app, tap "Turn on game covers" and paste a free key from rawg.io/apidocs.
Edit the app: change index.html in android/app/src/main/assets and windows (keep both the same).
