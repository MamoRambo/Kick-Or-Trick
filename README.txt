KICK OR TRICK - Android APK project
====================================
1. Make a free account on github.com, then create a new repository (any name, Public or Private).
2. Upload EVERYTHING from this unzipped folder to it (Add file > Upload files; drag in all files and folders,
   including the hidden ".github" folder). If ".github" doesn't upload, use Add file > Create new file, type
   .github/workflows/build-apk.yml as the name, and paste in the contents of build-apk.yml (included next to this file).
3. Open the repository's "Actions" tab. A run called "Build APK" starts by itself (takes about 3-5 minutes).
   If it doesn't start, click "Build APK" > "Run workflow".
4. When it shows a green check, open the run and download the "KickOrTrick-apk" file under Artifacts.
   Unzip it to get app-debug.apk.
5. Copy app-debug.apk to your phone, open it, and allow "install from this source" when Android asks.

To change the app later, edit app/src/main/assets/www/index.html and upload again to get a new APK.
