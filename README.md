##  ⚠️ Patch still in WIP !
**We are working alone without contributor, so its can take a longer time!**


Note : 
Unlike ReVanced patches, this patch only support patch YouTube and YouTube Music. Don't ask for other apps such as : Spotify,Reddit,Twitter,etc !

## Patch list : 

### [ `com.google.android.youtube`](https://play.google.com/store/apps/details?id=com.google.android.youtube)
<details>

| Patch | Description | Supported Version |
|:--------:|:--------------:|:-----------------:|
| `buffer-fix` | Spoof YouTube client version and package name to fix video playback buffer issue. | all |
| `remove-ads` | Remove advertisement from Video and Shorts. | all |
| `remove-general-ads` | Remove advertisement banner on homepage. | all |
| `microg-support` | Ability to login Google account with Vanced microG. Required when build non-root variant. | all |
| `allow-nomicrog` | Allow YouTube Vanced to run without GMS or Vanced microG with no login function. | all |
| `pip` | Play videos in Picture-in-Pictures mode | all |
| `bg-playback` | Playback videos in background mode | all |
| `vanced-settings` | Vanced settings. | all |
| `disable-pip-shorts` | Disable Picture-in-Pictures in Shorts. (Experiment flag) | all |
| `branding-vanced` | Applies YouTube Vanced icon and splash background. | all |
| `vanced-name` | Change branding names to YouTube Vanced. | all |
| `package-name` | Change package name to com.vanced.android.youtube (Warning : non-root only) | all |
| `ryd` | Return YouTube dislikes integration. | all |
| `sponsorblock` | SponsorBlock integration. | all |
| `video-download` | Download videos and audio from YouTube Vanced with NewPipe bulit-in integration. | all |
| `seekbar-shorts` | Seekbar in Shorts (Experiment) | all |
| `remove-offline-download` | Remove bulit-in stock YouTube "Downloaded video" feature from Library menu. | all | 
| `videoquality` | Enable old video quality layout. | all |
| `black-theme` | Applies black theme. | all |
| `monettheme`| Applies Material You theme (Android 12+), minSDK version also change to 31. | all |
| `old-layout` | Spoof YouTube version to 17.28.34 to restore old layout. | all |
| `optimize` | Optimize apk after patching complete. | all |


</details>

### [ `com.google.android.apps.youtube.music`](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music)
<details>

| Patch | Description | Supported version |
|:--------:|:--------------:|:-----------------:|
| `remove-ads` | Remove advertisement from YT Music. | all |
| `remove-premium` | Remove buy YouTube Premium banner. | all |
| `branding-logo` | Change original YouTube Music logo, header and splash to YouTube Music Vanced. | all | 
| `branding-name` | Change app name to YouTube Music Vanced. | all |
| `package-name` | Change package name to com.vanced.android.apps.youtube.music (Warning : non-root only) | all |
| `bg-playback` | Play music in background. | all |
| `vanced-settings` | YT Music Vanced settings | all |
| `disable-cast` | Disable cast button | all |
| `microg-support` | Ability to login Google account with Vanced microG. Required when build non-root variant. | all | 
</details>


Limitions between ReVanced Extended and this patches : 

❌ Features worse more than [ReVanced Extended](https://t.me/revanced_extended)

❌ No Import/export settings function

❌ No "Force VP9 codec" function

❌ No custom branding icon & name & custom package name

❌ Ad-block might not work well

❌ ~~No brightness & volume swipe gesture~~

✅ allow-nomicrog patch : Allow to run YouTube Vanced without Vanced microG (non-root variant) with no login function (Like old Vanced <16.xx.xx)

✅ video-download patch : Built-in video & audio downloader inside patch (NewPipe integration)

✅ Stability 

✅ Compatible with Unisoc processor devices

✅ Actually is a specific Vanced patch (not ReVanced anymore)

Branding icon & name will build as YouTube Vanced icon & name. If you build non-root variant, package name will change to : com.vanced.android.youtube.

There is no options like custom branding icon & name to prevent someone else build YouTube Vanced as ReVanced branding name & icon.
