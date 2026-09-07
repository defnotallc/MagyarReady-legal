# App Store Marketing — MagyarReady

Reference document for App Store Connect listing. Copy-paste into the appropriate fields.

---

## App Identity

| Field | Value |
|---|---|
| **App Name** | MagyarReady |
| **Subtitle** | Hungarian Language & Citizenship |
| **Bundle ID** | `com.defnota.LearnHungarian` |
| **Primary Category** | Education |
| **Secondary Category** | Reference |
| **Age Rating** | 4+ |
| **Content Rights** | No third-party content |
| **Price** | Free (with in-app purchases) |

---

## App Description

### Promotional Text (170 chars max — shown above description, can be updated without new build)

```
Prepare for the Hungarian citizenship interview: 333 flash cards, personalized answers, legal document guide. Fully offline.
```

### Full Description (3,159 chars — App Store Connect safe, no special Unicode)

```
Do you have Hungarian ancestry and need to prove it at the consulate?

MagyarReady is built specifically for the Hungarian simplified naturalization (egyszerűsített honosítás) citizenship interview. Whether you grew up hearing the language or are just beginning to prepare, MagyarReady walks you through everything you need - offline, at your own pace.

INTERVIEW PREP THAT KNOWS YOU

Most Hungarian apps teach you to order coffee. MagyarReady teaches you to answer "What is your connection to Hungary?" in front of a consulate officer.

Fill in your profile once - your name, birthplace, family history, occupation, and reasons for applying - and MagyarReady generates personalized Hungarian answers for over 80 interview questions. Your answers, not generic ones.

- "Where were your parents born?" answered with your parents' actual birthplaces
- "What is your occupation?" answered with your real job title in Hungarian
- "Why are you applying?" answered in your own words, in Hungarian
- "Tell me about your ancestry" answered with your family's real story

333 FLASH CARDS - 15 CATEGORIES

Master Hungarian vocabulary that actually comes up in citizenship interviews, not restaurant menus. Greetings, Numbers, Family, Personal Information, Occupations, History, Geography, Citizenship Terms, Food, Culture, and more.

Track every card. Mark what you know. Flag what needs work. Come back to struggling cards until they stick.

139 INTERVIEW QUESTIONS ACROSS 12 TOPICS

Real questions organized by category: Personal Details, Family Background, Hungarian Ancestry, Career and Education, Daily Life, Motivations, Language Ability, Hungarian History, Geography, Culture, Civic Knowledge, and Closing.

Plus 6 full role-play conversations - practice a complete interview from "Jó reggelt kívánok" to "Köszönöm szépen." Hear every exchange out loud with built-in Hungarian text-to-speech.

28 LEGAL DOCUMENTS EXPLAINED

The citizenship application requires documents most people have never heard of. What is an apostille and where do you get it? What is an anyakönyvi kivonat? Which documents need a certified Hungarian translation?

Every document is explained in plain English with its Hungarian name, why it's required, and where to obtain it.

ENGLISH TO HUNGARIAN TRANSLATION

Powered by Apple's on-device Translation - your words never leave your device. Translate anything, hear it spoken aloud in native Hungarian, save phrases for practice. Works offline after a one-time language pack download.

FULLY OFFLINE

Study on the plane to Budapest. Review flash cards in the consulate waiting room. Practice conversations with no signal. Everything works without an internet connection.

GO PREMIUM - REMOVE ALL ADS

The free version is fully featured. Premium removes all banner and interstitial ads so you can study without interruptions. Choose a monthly subscription (cancel anytime) or a one-time lifetime purchase.

NOTE: MagyarReady is an educational tool only. Always verify current requirements directly with your Hungarian consulate and consult a qualified legal professional for advice specific to your situation.

Sok sikert - Good luck!
```

---

## Keywords (100 chars max, comma-separated)

```
hungarian,citizenship,interview,language,flash cards,vocab,naturalization,honosítás,translation
```

**Keyword strategy notes:**
- "hungarian citizenship" and "hungarian language" are the primary search terms
- "naturalization" and "honosítás" capture the specific use-case audience
- "interview prep" and "flash cards" cover discovery from language learners
- Avoid generic terms like "learn" or "study" (too competitive, low conversion)

---

## What's New (Version 1.0 — Initial Release)

```
Welcome to MagyarReady!

• 333 Hungarian flash cards across 15 categories
• 139 citizenship interview questions with personalized answers
• 38 legal document descriptions for the citizenship application
• 6 full conversation scenarios
• English ↔ Hungarian translation with text-to-speech
• Fully offline — study anywhere
```

---

## App Store Screenshots Guide

Use `AdConfig.screenshotMode = true` in AdConfig.swift before taking screenshots to hide ads.

### Required Sizes
- **6.9" iPhone** (iPhone 16 Pro Max): 1320 × 2868 px
- **6.5" iPhone** (iPhone 14 Plus): 1242 × 2688 px  
- **5.5" iPhone** (iPhone 8 Plus): 1242 × 2208 px
- **13" iPad Pro**: 2048 × 2732 px *(if submitting for iPad)*

### Recommended Screenshot Sequence (5 screens)

1. **Home tab** — show the flag gradient header, progress stats, Quick Start cards
2. **Interview Prep** — show the embassy-style hero banner + category list
3. **Flash Cards** — show a card face with Hungarian + phonetic, with the per-category color
4. **Profile → Interview answer** — show a personalized answer generated from profile data
5. **Translate tab** — show translation + TTS in action

### Screenshot Copy Overlays (optional)

| Screen | Headline | Subhead |
|---|---|---|
| Home | "Your citizenship journey starts here" | "Master Hungarian for the consulate interview" |
| Interview | "133 real interview questions" | "Personalized to your exact background" |
| Flash Cards | "183 vocabulary cards" | "Track what you know. Master what you don't." |
| Profile | "Your answers, your words" | "Fill in your profile. Get personalized Hungarian." |
| Translate | "English ↔ Hungarian" | "On-device. Private. Offline." |

---

## App Review Notes (for App Store Connect)

```
Test Account: Not required — no login or account system.

The app uses Google AdMob for advertisements and Google UMP SDK for GDPR consent. 
The consent flow appears at first launch. For review purposes, you can dismiss it 
and use all features normally.

The Translation tab uses Apple's on-device Translation framework. 
A Hungarian language pack download (~200MB) is required for first use.

In-App Purchases:
- Monthly Premium: com.defnota.LearnHungarian.premium.monthly ($9.99/month)
- Lifetime Premium: com.defnota.LearnHungarian.premium.lifetime ($99.99)
Both products remove advertisements.

The app is designed for adults preparing for the Hungarian simplified naturalization 
citizenship interview. All content is educational.
```

---

## Support & Privacy URLs (for App Store Connect)

| Field | URL |
|---|---|
| **Support URL** | https://github.com/defnotallc/MagyarReady-legal/blob/main/support.md |
| **Privacy Policy URL** | https://github.com/defnotallc/MagyarReady-legal/blob/main/privacy-policy.md |
| **Marketing URL** | https://github.com/defnotallc/MagyarReady-legal *(optional — must be a public URL; the app repo is private)* |
