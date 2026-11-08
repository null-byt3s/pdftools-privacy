# Privacy Policy — Stay PDF

**Effective date:** November 8, 2026
**App:** Stay PDF (`com.devcodeapps.pdftools`)
**Developer:** DevCodeApps
**Contact:** under.cntrl.dev@gmail.com

## Summary

Stay PDF processes all of your documents locally, on your device. Your files are never uploaded, scanned, or shared. The free version of the app shows advertisements provided by Google AdMob; the optional Pro subscription removes them. Only the ads and Google Play purchases use the internet; your documents never do.

## Your documents

When you select a PDF or image file inside Stay PDF, the app uses Android's Storage Access Framework to read only the file(s) you explicitly choose. The app:

- Does not request broad storage permissions
- Does not scan, index, or inventory files on your device
- Only reads files you pick through the system picker

Files you process (merged PDFs, compressed PDFs, extracted images, etc.) are written to the app's private storage and made available via the system share sheet or save dialog. The app does not upload, copy, or transmit these files anywhere. **Your documents are never shared with any third party, including our advertising partner.**

## Data we collect

We — DevCodeApps — do not collect, store, or share any personal data ourselves. We have no servers that receive your data, and we have not added our own analytics or crash-reporting tools.

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

Stay PDF requests no runtime permissions, so it never asks for your camera, contacts, location or all your files. It declares these install-time permissions, which come from the ad and billing libraries:

- `INTERNET` and `ACCESS_NETWORK_STATE`: to load ads and reach Google Play
- `com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION` and `ACCESS_ADSERVICES_TOPICS`: advertising identifiers and Android's ad services
- `com.android.vending.BILLING`: Google Play purchases
- `WAKE_LOCK` and `FOREGROUND_SERVICE`: background work run by the ad library
- `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`: a standard Android protection inside the app

## Children's privacy

Stay PDF is a general-purpose tool and is not directed at children under 13. We do not knowingly collect information from children.

## Changes to this policy

If this policy is updated, the new version will be posted at the same URL with a revised effective date.

## Contact

Questions? Email under.cntrl.dev@gmail.com. See also our [Terms of Service](https://null-byt3s.github.io/pdftools-privacy/terms).
