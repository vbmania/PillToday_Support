# DupCleaner Privacy Policy

Last updated: November 12, 2026

This policy explains how DupCleaner (the “App”) handles information when you review and remove duplicate files in selected folders or duplicate photos and videos in your photo library, use rewarded ads, or make an in-app purchase.

## 1. Files, photos, and data processed on your device

### Files in selected folders

- The file-cleanup feature accesses folders that you explicitly select with Apple’s system file picker.
- File names, paths, sizes, hashes, scan history, cleanup decisions, and security-scoped bookmarks are used to find duplicates and carry out your cleanup choices.
- This file information and the contents of your files are processed locally. Opening or comparing items from iCloud Drive or another file provider may cause that provider to download originals to your device.

### Photos and videos in your photo library

- The photo-cleanup feature requests read-and-write photo-library access through Apple PhotoKit. The App accesses the full or limited library you authorize. You can change this permission in system settings.
- To find candidates, compare originals, display previews, and check cleanup targets, the App may use local photo and video identifiers, creation and modification dates, favorite status, sizes, media types and durations, deletion eligibility, and location metadata embedded in photos. It does not request separate access to your current location.
- The App reads thumbnails and original resources, including resources such as a Live Photo’s video, and calculates comparison hashes and byte counts. It prioritizes locally available data. When you allow original checking over the network, Apple PhotoKit may download originals from iCloud.
- Photo cleanup requests deletion from Apple’s photo library for items you select and confirm. With iCloud Photos, deletion may also affect other devices signed in to the same account. Recovery follows the Photos app’s Recently Deleted feature and Apple’s retention conditions; DupCleaner does not provide a separate recovery copy. See [Apple’s photo deletion and recovery guidance](https://support.apple.com/en-us/104967).

### Local storage and external transmission

- DupCleaner does not upload your file, photo, or video contents, comparison hashes, photo identifiers, or embedded photo location metadata to our servers. App-defined usage events do not include these contents either. Section 2 separately describes information processed by analytics, diagnostics, advertising, and purchase services.
- Versions supporting work restoration, starting with 1.6.2, store file and photo review results, keep/delete selections, candidates and exclusions, errors, and original-check evidence on your device. Photo identifiers, metadata, signatures, and byte counts may also be stored in a local cache to reuse original-comparison results.
- Saved review data does not contain original photo/video content, thumbnails, download consent, deletion approval, or purchase entitlements. Reopening saved work does not automatically start downloading or deleting. See Section 5 for retention and deletion.

## 2. Information processed by service providers

DupCleaner uses the following third-party services. The exact data available to a provider depends on the feature you use, your region, device settings, and privacy choices.

### Firebase Analytics and Firebase Crashlytics

Google Firebase may process app interactions and session information, app and device identifiers, app version, device model, operating-system information, approximate location derived from an IP address, purchase-related events, performance data, crash logs, stack traces, and other diagnostic information. We use this information to understand feature usage, measure purchase and cleanup reliability, diagnose crashes, prevent abuse, and improve the App.

### Google Mobile Ads and User Messaging Platform

When the rewarded-ad option is available or selected, Google Mobile Ads and the User Messaging Platform may process an IP address (including approximate location), app- or device-scoped identifiers, SDK instance identifiers, advertising data, ads viewed, ad and video interactions, app interactions, performance information, crash or diagnostic data, and your consent or privacy choices. This information is used to request and deliver ads, measure ad performance, prevent fraud and abuse, provide analytics, and honor privacy choices.

DupCleaner does not request App Tracking Transparency permission and does not directly access the iOS advertising identifier (IDFA). Google may still use app- or developer-scoped identifiers and limited contextual information as permitted by your device settings, consent choices, region, and Google’s policies. You can reopen the App’s privacy options from Settings when Google requires that entry point.

### Apple StoreKit

Apple processes payments and account information for in-app purchases. DupCleaner receives product, transaction, purchase-status, expiration, and entitlement information needed to grant or restore access. We do not receive or store your full payment-card information.

## 3. Purposes of processing

We and our service providers process the information described above to:

- scan selected folders and authorized photo-library items, detect duplicates, and provide previews and cleanup;
- restore review results and selections, and remember local settings and valid purchase entitlements;
- display and measure rewarded ads after your explicit choice;
- process, verify, and restore in-app purchases;
- analyze App usage and performance;
- investigate crashes, failures, fraud, and abuse; and
- comply with legal, security, and platform requirements.

## 4. Sharing and sale of data

We do not sell your files, photos, videos, or their contents. Information described in Section 2 may be transmitted to Google or Apple to provide analytics, diagnostics, advertising, consent management, and purchase services. These providers process information under their own terms and privacy policies:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites)
- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

We may also disclose information when required by law or when reasonably necessary to protect users, the App, or the public.

## 5. Retention and deletion

- Local scan/review information and settings may remain until replaced by new work, cleared by the relevant reset action, or removed by uninstalling the App. Starting a new scan does not clear all settings and comparison caches. The operating system may purge caches, and uninstalling removes the App’s local stored data. Device backups and data restored from them follow iOS or iPadOS settings.
- Original files, photos, videos, and provider-managed data are separate from the App’s review records. Uninstalling the App does not delete originals; cleanup of selected originals requires separate confirmation in the App.
- Purchase records and transaction history are retained by Apple according to Apple’s policies and legal obligations.
- Google retains Analytics, Crashlytics, consent, diagnostic, and advertising information according to the applicable Firebase, AdMob, and Google account settings and retention policies.
- Uninstalling DupCleaner stops future collection by the App but may not delete information already retained by a service provider. You may use the providers’ privacy controls or contact us for assistance.

## 6. Your choices and rights

- You decide which folders the App can access through the system file picker.
- You can manage full, limited, or denied photo access in system settings. Reducing access does not immediately erase every existing local review record; the App rechecks items according to your current permission.
- You can turn usage analytics and diagnostic sharing off separately in the App’s settings. Turning analytics off resets on-device Analytics data; turning diagnostic sharing off requests deletion of unsent crash reports. These actions are separate from requesting deletion of data already sent to a provider.
- You may decline a rewarded ad and choose a purchase option or cancel cleanup.
- Where required, Google’s consent form provides advertising and privacy choices. A privacy-options entry appears in Settings when required by the User Messaging Platform.
- You can manage or restore purchases through your Apple account and the App’s restore-purchases function.
- Depending on your jurisdiction, you may have rights to access, correct, delete, restrict, or object to processing of personal information. Contact us to make a request. Provider-held information may also require a request directly to Google or Apple.

## 7. Security and international processing

The App uses Apple’s sandbox and security-scoped access controls for local files. Network communication with Google and Apple uses encrypted HTTPS connections. Google and Apple may process information in countries other than your own under their respective legal and contractual safeguards. No system can guarantee absolute security.

## 8. Children

DupCleaner is a general-audience utility and is not directed to children under 13. Advertising and consent behavior may be limited according to applicable law, region, account information, and provider settings.

## 9. Changes to this policy

We may update this policy when the App, service providers, or legal requirements change. The “Last updated” date identifies the latest version. Material changes will be reflected in the App or its store listing when required.

## 10. Contact

For privacy questions or requests, email [contact.aiworkerslab@gmail.com](mailto:contact.aiworkerslab@gmail.com) or open an issue in the [PillToday Support repository](https://github.com/vbmania/PillToday_Support/issues).
