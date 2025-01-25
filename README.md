This is a guide to help you utilize Root to remove all the ADs and trackers on your Android

# 1. AdAway
- Select root-based AdBlocker
- Import [AdAway.json](https://github.com/DestroyerBDT/tracKick/releases/latest/download/AdAway.json) [(*track on Obtainium*)](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22748145273%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FDestroyerBDT%2FtracKick%22%2C%22author%22%3A%22DestroyerBDT%22%2C%22name%22%3A%22tracKick%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22dontSortReleasesList%5C%22%3Afalse%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Atrue%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Atrue%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22tracKick%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Afalse%7D%22%2C%22overrideSource%22%3A%22GitHub%22%7D) | [(*view **Readable configuration***)](https://github.com/DestroyerBDT/tracKick/blob/main/AdAway/Readable%20configuration.md)
  - Hamburger menu
  - Preferences
  - Backup / restore block rules
  - Restore (*Restore your block rules from the [backup file](https://github.com/DestroyerBDT/tracKick/releases/latest/download/AdAway.json)*)
- Device-specific filtering (*enable for the device you are using it on*)
  - Search in the filter list for your device's list to block its native trackers
  - Supported devices (*uses [HaGeZi](https://github.com/hagezi/dns-blocklists) lists*)
     - [Xiaomi](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.xiaomi.txt)
     - [Oppo/Realme](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.oppo-realme.txt)
     - [Samsung](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.samsung.txt)
     - [Huawei](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.huawei.txt)
     - [Vivo](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/hosts/native.vivo.txt)
- Company-specific filtering (*enable for the company you use services of*)
  - Search in the list for a company whose service(s) you use
  - Supported companies (*uses [HaGeZi](https://github.com/hagezi/dns-blocklists) lists*)
     - [TikTok](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.tiktok.extended.txt)
     - [Amazon](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.amazon.txt)
# 2. Lucky Patcher
- Disable *Google ad services*
   - Toolbox
   - Block Ads
   - Turn off Google ad services
# 3. [Blocker](<https://f-droid.org/packages/com.merxury.blocker>)
- go to the `SDK/trackers` tab
- disable each found AD and tracker component in each app
- installing new apps
  - Go to the `search` tab
  - Search for the newly installed app
  - disable each AD & tracker component
