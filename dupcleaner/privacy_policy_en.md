# DupCleaner Privacy Policy
Last updated: 2025-12-06

## 1. Data We Collect
- **Crash/diagnostic data**: Firebase Crashlytics collects non-identifying crash logs (stack traces, device model, OS version, anonymized session/instance IDs).
- **On-device app data**: Scan configurations, security-scoped bookmarks for folders you select, file metadata/hashes, scan history, and isolation decisions are stored locally.

## 2. How We Use the Data
- Perform duplicate detection and show results on your device.
- Improve stability and investigate crashes (Crashlytics).

## 3. Storage and Transmission
- On-device data (bookmarks, hashes, history) stays in the App Group container and is not transmitted to servers or iCloud.
- Crash logs may be sent to and stored on Firebase Crashlytics servers (via HTTPS).

## 4. Third Parties and Ads
- No ads, IDFA, or profiling.
- No analytics/tracking SDKs besides Crashlytics.

## 5. Permissions and Scope
- **Folder access**: Limited to folders/volumes you explicitly pick via the system file picker, managed through security-scoped bookmarks.
- No hidden access to other paths; no iCloud/remote sync.

## 6. Sync/Backup
- Cloud sync is not provided. Each device keeps its own data. System/device backups are managed by the OS.

## 7. Data Retention and Deletion
- On-device data remains until you delete it or uninstall the app.
- Deleting the app removes local data. To revoke folder access, deselect the folder in the picker and restart the app.
- To stop crash collection, uninstalling the app stops Crashlytics.

## 8. Security
- Local data is protected by the App Group sandbox.
- Crashlytics network communication uses HTTPS.

## 9. Children
- The app is intended for general audiences and is not directed to children under 13.

## 10. Changes
- Updates to this policy will be published in this repository. The “Last updated” date reflects the latest change.

## 11. Contact
- Please open a GitHub Issue in this repository with device/OS/app version and reproduction steps.
