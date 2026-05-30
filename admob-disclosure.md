# AdMob Configuration — MagyarReady

Internal reference document for AdMob app registration and ad unit IDs.  
**Do not share API keys or PATs. This file contains only public AdMob IDs.**

---

## App Registration

| Field | Value |
|---|---|
| AdMob App Name | MagyarReady |
| AdMob App ID | `ca-app-pub-1306237465756584~1840424805` |
| Bundle ID | `com.defnota.LearnHungarian` |
| Platform | iOS |
| `GADApplicationIdentifier` in Info.plist | `ca-app-pub-1306237465756584~1840424805` |

---

## Production Ad Unit IDs

| Ad Type | Ad Unit ID |
|---|---|
| Banner | `ca-app-pub-1306237465756584/2744796998` |
| Interstitial | `ca-app-pub-1306237465756584/2616274250` |

### Ad Placement

- **Banner**: Anchored to the bottom safe area on all 5 tab root views (Home, Interview, Flash Cards, Profile, Translate). Hidden when `isPremium = true`.
- **Interstitial**: Shown every 4 detail-view exits (flash card deck or interview category), with a 60-second minimum cooldown. Gated by `AdManager.shared`. Hidden when `isPremium = true`.

---

## Test Ad Unit IDs

Used only during development when `AdConfig.useTestAds = true`.

| Ad Type | Test Ad Unit ID |
|---|---|
| Banner | `ca-app-pub-3940256099942544/2934735716` |
| Interstitial | `ca-app-pub-3940256099942544/4411468910` |

> **Production builds must have `AdConfig.useTestAds = false`.** This is enforced in the "Never Do This" rules in `CLAUDE.md`.

---

## Consent & Privacy (UMP)

**SDK:** `GoogleUserMessagingPlatform` 3.1.0 (Swift Package Manager)  
**Package:** `swift-package-manager-google-user-messaging-platform` v3.1.0  
**Implementation file:** `LearnHungarian/Utilities/ConsentManager.swift`

### Consent Flow (implemented in Session 2 — 2026-05-30)

1. `UMPConsentInformation.sharedInstance.requestConsentInfoUpdate(with:)` — fetches user's consent status from Google
2. `UMPConsentForm.loadAndPresentIfRequired(from:)` — shows GDPR consent form if required (EEA users)
3. `ATTrackingManager.requestTrackingAuthorization()` — iOS ATT prompt for IDFA
4. `MobileAds.shared.start()` — starts ads only if `canRequestAds == true`

### ATT Usage Description (in Info.plist)
```
NSUserTrackingUsageDescription = "MagyarReady uses the advertising identifier to show you 
relevant ads that help support the free version of the app. You can opt out at any time in 
iOS Settings → Privacy & Security → Tracking."
```

---

## SKAdNetwork IDs

The app's Info.plist includes the full list of Google-required SKAdNetwork identifiers (57 entries) as required by AdMob for privacy-preserving attribution on iOS 14+.

---

## Revenue Streams Summary

| Stream | Status | Notes |
|---|---|---|
| AdMob Banner | ✅ Active | Production IDs set, `useTestAds = false` |
| AdMob Interstitial | ✅ Active | Every 4 exits, 60s cooldown |
| IAP Monthly $9.99 | ⏳ Needs App Store Connect | ID: `com.defnota.LearnHungarian.premium.monthly` |
| IAP Lifetime $99.99 | ⏳ Needs App Store Connect | ID: `com.defnota.LearnHungarian.premium.lifetime` |
| Amazon Affiliate | ✅ Active | Tag: `defnota-20`, 5 placements |
