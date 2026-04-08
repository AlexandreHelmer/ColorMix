ColorMix is a small subtractive color-mixing tool (paint-like mixing).

You provide N named input colors and their proportions; the app computes the resulting mixed color and suggests a name for it.

# Build

## Android (debug APK)

Requires: Cordova + Android SDK. From the project root:

```bash
export ANDROID_HOME=/opt/android-sdk/
cd ColorMix
cordova build android
mv platforms/android/app/build/outputs/apk/debug/app-debug.apk ../ColorMix.apk
```
