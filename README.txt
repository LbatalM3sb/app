BUILD THE APK (5 minutes, free)
1. Install Android Studio (developer.android.com/studio) on a PC.
2. File > Open > select this PrankGame folder. Wait for Gradle sync.
3. Build > Build Bundle(s)/APK(s) > Build APK(s).
4. APK appears in app/build/outputs/apk/debug/app-debug.apk
5. Send it to your bro's phone and install (he must allow "install unknown apps").

Change the loading time: edit D=15000 (milliseconds) in app/src/main/assets/index.html
Add/change error messages: edit the "errs" list in the same file.

NO ANDROID STUDIO? BUILD ON GITHUB (free, browser only)
1. Create a free account at github.com and make a New repository.
2. Upload ALL files from this folder (including the hidden .github folder) to it.
3. Open the Actions tab > "Build APK" > wait ~5 min until green.
4. Click the finished run > Artifacts > download FireStrike-APK (a zip containing app-debug.apk).
