# app-min-update-version

The Famedly Flutter app requests the static json in this repository on each app start and compares the minimal version number with the current installed version. If the current installed version is older than the minimal version in this json, it displays a warning dialog to the user. With this strategy we force users to update to new versions.

### Get the currently available versions

Android: https://play.google.com/store/apps/details?id=com.famedly.talk

iOS: https://apps.apple.com/de/app/famedly/id1459847644

⚠️ IMPORTANT
Make sure to include the version for all 3 platforms in the following format:
```
{
    "android": "X.Y.Z",
    "ios": "X.Y.Z",
    "web": "X.Y.Z"
}
```
