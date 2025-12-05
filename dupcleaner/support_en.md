# DupCleaner Support
Last updated: 2025-12-06

## About the App
- iPad app that scans user-selected folders to find duplicate files and lets you safely isolate/clean them.
- All scanning, hashing, and history stay on-device (App Group). No data is sent to servers.

## How to get help
- **GitHub Issues**: Please open an Issue in this repository.
- Include when possible for faster resolution:
  - Device/OS version, app version (Settings > App Info)
  - Folder/volume type selected (local, external, network, etc.)
  - Scan options you used (auto-select on/off, etc.)
  - Repro steps, screenshots, or logs if available

## FAQ
- **Data storage/transfer**: File metadata and hashes are stored locally in an App Group database and are not uploaded.
- **Folder access**: Access is limited to folders/volumes you pick via the file picker, using security-scoped bookmarks. No hidden access to other paths.
- **Crashlytics**: Collects crash reports only; no analytics/ads/IDFA. The “Crashlytics test crash” button is optional.
- **Sync**: No iCloud/server sync. Each device works independently.
- **Data deletion**: Deleting the app removes local data. To revoke folder access, remove the folder selection in the picker and restart the app.

## Links
- Privacy Policy (English): [privacy_policy_en.md](privacy_policy_en.md)
- 개인정보 처리방침(한국어): [privacy_policy_ko.md](privacy_policy_ko.md)
- Support (한국어): [support_ko.md](support_ko.md)
