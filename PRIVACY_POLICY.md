# Privacy Policy — Film Photography Viewfinder

> **Public URL:** https://jonassubver2.github.io/public/PRIVACY_POLICY.html  
> **Last updated:** May 2026 &nbsp;|&nbsp; **Developer:** Jonas Subvert &nbsp;|&nbsp; **Contact:** [jonassubvert@gmail.com](mailto:jonassubvert@gmail.com)

---

## Overview

Film Photography Viewfinder ("the App") includes an optional **Community** feature (profiles, photo posts, comments). The core viewfinder, log book, and tools store most data **on your device only**. When you use Community, selected data is processed by **Google Firebase** (authentication, database, image storage) as described below.

---

## Data stored on your device only

| Data type | Purpose |
|-----------|---------|
| Log book entries | Shot records |
| Custom film formats and lenses | Viewfinder configuration |
| App settings | Preferences |
| Custom film stock entries | Film library |

This local data is not uploaded unless you explicitly use a cloud feature.

---

## Community & Firebase (when you sign in)

If you create an account or use Community, we process:

| Data | Purpose | Where |
|------|---------|--------|
| Email, Auth user id | Sign-in, account security | Firebase Authentication |
| Handle, display name, bio, avatar | Public profile | Cloud Firestore |
| Photos, captions, tags, albums | Community posts | Firestore + Firebase Storage |
| Comments, favourites | Engagement | Firestore |
| Block list, reports | Safety (block/report) | Firestore |
| Mature-content preference | Safety filter | Firestore (`users` doc) |

**Sign in with Apple (iOS):** If you choose it, **Apple** runs the sign-in UI per [Apple’s privacy policy](https://www.apple.com/legal/privacy/). We receive a stable user identifier from Apple and an identity token used with Firebase Auth. On first sign-in, Apple may share your name; email may be your real address or an Apple **Hide My Email** relay — either is stored like other account emails for sign-in and profile.

**Processors:** Google Firebase (see [Google Privacy Policy](https://policies.google.com/privacy)). Sign-in may also use **Google** or **Apple** (their respective policies apply).

We do not sell your data. We do not use third-party advertising or analytics SDKs in the App.

---

## Device permissions

| Permission | Why |
|-----------|-----|
| **Camera** | Viewfinder and light meter |
| **Microphone** | Timer sounds only (not recorded) |
| **Photo Library** | Save captures when you choose |
| **Location** (optional) | Local UV index for alt-process tools |

Community uploads use network access to send images you choose to post.

---

## Retention & deletion

- **On-device data:** Removed when you delete the app or clear app data.
- **Community account:** Delete from **My account → Delete account** (removes Auth login and marks your profile deleted). Email [jonassubvert@gmail.com](mailto:jonassubvert@gmail.com) if you need help removing remaining posts.
- **Reports:** Kept for moderation until resolved.

---

## Children's privacy

The App is not directed at children under 13. Community accounts are not intended for users under 13.

---

## Changes

We may update this policy. The "Last updated" date will change when we do.

---

## Contact

Questions or privacy requests: [jonassubvert@gmail.com](mailto:jonassubvert@gmail.com)
