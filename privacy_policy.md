# Privacy Policy — Stay PDF

**Effective date:** November 9, 2026
**App:** Stay PDF (`com.devcodeapps.pdftools`)
**Developer:** DevCodeApps
**Contact:** under.cntrl.dev@gmail.com

## Summary

Stay PDF processes all of your documents locally, on your device. Your files are never uploaded, scanned, or shared. The free version of the app shows advertisements provided by Google AdMob; the optional Pro subscription removes them. We use Google Analytics and Firebase Crashlytics to learn which tools are used and to fix crashes. Only ads, Google Play purchases, usage statistics, crash reports and app settings use the internet; your documents and file names never do.

## Your documents

When you select a PDF or image file inside Stay PDF, the app uses Android's Storage Access Framework to read only the file(s) you explicitly choose. The app:

- Does not request broad storage permissions
- Does not scan, index, or inventory files on your device
- Only reads files you pick through the system picker

Files you process (merged PDFs, compressed PDFs, extracted images, etc.) are written to the app's private storage and made available via the system share sheet or save dialog. The app does not upload, copy, or transmit these files anywhere. **Your documents are never shared with any third party, including our advertising partner.**

## Data we collect

We — DevCodeApps — have no servers of our own that receive your data. The app uses the Google services described below. We can see the statistics and crash reports they produce in the Firebase console.

**None of these services ever receives your documents, their contents, their file names, or any password you type.**

### Usage statistics (Google Analytics for Firebase)

To see which features are used and where the app needs work, the app reports:

- Which screens are opened
- Which tool was used and which variant of it (for example, compress to a target size), whether it finished, failed or was cancelled, and the kind of error if it failed
- How long a tool took and how large its result was, only as ranges (for example, "1 MB to 10 MB")
- Whether a result was saved, shared or opened, and when files arrive from another app (type and number, as a range)
- When a free limit is reached, the Pro screen is shown, a purchase is started and how it ended, and when the app asks Google Play for its rating dialog
- Whether you have Pro

Google Analytics also collects, automatically, an app instance ID, the Advertising ID, device model, Android version, language, app version, approximate location (from your IP address) and how long the app is used.

### Crash reports (Firebase Crashlytics)

If the app crashes, a report is sent with the technical details of the crash: the code location, device model, Android version, app version, free memory and storage, and an installation identifier. The app adds only which tool was running and whether you have Pro.

### App settings (Firebase Remote Config)

The app downloads a small set of settings from Firebase, such as how often ads may appear and the free-version limits. The request includes an identifier for this installation of the app. If it can't be downloaded, the app uses its built-in values.

### Your choice

In the EEA, the UK and Switzerland, usage statistics and crash reports are turned on only if you allow storing information on your device in Google's consent form, and they stop if you withdraw it. You can change your choice at any time under **Settings → Ad privacy options**. Google's handling of this data is described in [Privacy and Security in Firebase](https://firebase.google.com/support/privacy).

### Advertising (free version)

The free version shows interstitial ads served by **Google AdMob**. To serve and measure ads, Google may collect and process data such as:

- Advertising ID and other device identifiers
- IP address and approximate location
- App and ad interactions, such as impressions and clicks
- Diagnostic information, such as crash and performance data from the ad service

This processing is governed by [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's advertising policies](https://support.google.com/admob/answer/6128543). In regions where consent is required (the EEA, the UK and Switzerland), the app shows Google's consent form before any ads are requested, and you can change your choice at any time under **Settings → Ad privacy options**.

### Pro subscription

Pro is an optional, auto-renewing monthly subscription processed entirely by **Google Play Billing**. We never receive or store your payment details. You can cancel at any time in Google Play (Payments & subscriptions → Subscriptions); Pro stays active until the end of the period you already paid for. While Pro is active the app shows no advertising, so no ad-related data is processed. Pro purchases made earlier as a one-time "lifetime" upgrade remain valid.

## Permissions

Stay PDF requests no runtime permissions, so it never asks for your camera, contacts, location or all your files. It declares these install-time permissions, which come from the Google libraries the app uses:

- `INTERNET` and `ACCESS_NETWORK_STATE`: to load ads, reach Google Play, send usage statistics and crash reports, and download app settings
- `com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION` and `ACCESS_ADSERVICES_TOPICS`: advertising identifiers and Android's ad services
- `com.android.vending.BILLING`: Google Play purchases
- `BIND_GET_INSTALL_REFERRER_SERVICE`: lets Google Analytics learn which Play listing or campaign led to the install
- `WAKE_LOCK` and `FOREGROUND_SERVICE`: background work run by Google's libraries
- `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`: a standard Android protection inside the app

## Children's privacy

Stay PDF is a general-purpose tool and is not directed at children under 13. We do not knowingly collect information from children.

## Changes to this policy

If this policy is updated, the new version will be posted at the same URL with a revised effective date.

## Contact

Questions? Email under.cntrl.dev@gmail.com. See also our [Terms of Service](https://null-byt3s.github.io/pdftools-privacy/terms).
