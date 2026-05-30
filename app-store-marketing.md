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
Prepare for the Hungarian citizenship interview with 183 flash cards, 133 personalized Q&As, and professional translation tools. Fully offline.
```

### Full Description

```
MagyarReady helps diaspora Hungarians master the language and ace the Hungarian simplified naturalization (egyszerűsített honosítás) citizenship interview.

Whether you're just starting to learn Hungarian or polishing your answers before the consulate appointment, MagyarReady has everything you need — fully offline, no account required.

──────────────────────────────────
WHAT'S INSIDE
──────────────────────────────────

🗂 183 FLASH CARDS — 15 CATEGORIES
Master Hungarian vocabulary organized for the citizenship journey:
• Greetings & Courtesy
• Numbers & Time
• Family & Relationships
• Personal Information
• Occupations & Work
• Hungarian History & Geography
• Citizenship & Legal Terms
• Food, Colors, Adjectives, and more

Track your progress with Learned and Struggling markers. Focus your study time where it matters most.

🎙 133 INTERVIEW QUESTIONS — PERSONALIZED
The app doesn't just give you generic answers. Fill in your Profile (name, family, ancestry, career, language level) and MagyarReady generates answers personalized to YOUR situation:
• "Hol születtek a szülei?" → answers with your parents' actual birthplaces
• "Hogyan tanul magyarul?" → answers with your specific learning methods
• "Mi a foglalkozása?" → answers with your real occupation
• And 77 more personalizable questions across 12 interview categories

Plus 6 full role-play conversation scenarios so you can practice a realistic consulate interview from start to finish.

📚 LEGAL DOCUMENT GLOSSARY
Understand every document in the citizenship application packet:
• 28 documents explained in plain English
• Official Hungarian names with pronunciation
• What each document is, why it's required, and where to get it
• 8 document categories: identity, ancestry, civil status, and more

🔤 ENGLISH ↔ HUNGARIAN TRANSLATION
• Apple's on-device Translation framework (fully private, works offline after setup)
• Quick phrases organized by interview topic
• Hungarian text-to-speech for every card and question
• Pronunciation support for all 183 flash cards

👤 PERSONALIZED PROFILE SYSTEM
Enter your details once — the app uses them everywhere:
• Auto-generates Hungarian phrases about yourself
• Personalizes 80+ interview answers to your specific background
• Tracks section completion so you know what's still missing

──────────────────────────────────
FULLY OFFLINE
──────────────────────────────────

All flash cards, interview prep, legal documents, and conversations work with no internet connection. Perfect for studying on the plane to Hungary or in areas with no signal.

──────────────────────────────────
PREMIUM — REMOVE ALL ADS
──────────────────────────────────

• Monthly: $9.99/month — cancel anytime
• Lifetime: $99.99 — one-time, forever

Premium removes all advertisements and supports continued development of MagyarReady.

Subscriptions auto-renew unless cancelled at least 24 hours before the renewal date. Manage or cancel in iOS Settings → Subscriptions.

──────────────────────────────────
IMPORTANT DISCLAIMER
──────────────────────────────────

MagyarReady provides educational content only. It is not legal advice. Always verify current requirements with your Hungarian consulate and consult a qualified legal professional for your specific situation.

Privacy Policy: https://github.com/defnotallc/MagyarReady-legal/blob/main/privacy-policy.md
Support: defnota.official@gmail.com
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

• 183 Hungarian flash cards across 15 categories
• 133 citizenship interview questions with personalized answers
• 28 legal document descriptions for the citizenship application
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
| **Marketing URL** | https://github.com/defnotallc/learnhungarian *(optional)* |
