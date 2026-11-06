<!--
ACTION FOR CULLEN:
1. Replace privacy@mintvision.app with your real contact email before publishing.
2. Confirm the Vision API provider name if still OpenAI (or update the third-party section if the base URL / provider changes).
-->

# MintVision Privacy Policy

**Effective date:** November 5, 2026

**Developer / publisher:** Cullen Chapman  
**App:** MintVision (`com.mintvision.app`)  
**Contact:** privacy@mintvision.app *(placeholder — replace with Cullen’s real contact email before publishing)*

This Privacy Policy describes how MintVision (“we,” “us,” or “the App”) handles information when you use the MintVision Android application, a comic and trading-card game (TCG) scanner.

By using MintVision, you agree to this Privacy Policy. If you do not agree, please do not use the App.

---

## 1. Introduction

MintVision lets you photograph comics or trading cards and receive recognition results via a cloud Vision API. Scan results and your collection are stored **locally on your device**. The App does **not** create in-app user accounts or require sign-in. Subscriptions (after a freemium allotment) are sold through **Google Play Billing**.

We designed this policy to be accurate and conservative based on how the App works today. We do **not** sell your personal data.

---

## 2. Information We Collect

### 2.1 Camera images (scan photos)

When you scan, the App uses the device camera to capture photos of cards or comics. Those images are used for recognition and may be transmitted over the network to a cloud Vision API (see [Third Parties](#4-third-parties)).

### 2.2 Scan results and collection data (on-device)

Recognition results and items you save to your collection are stored **locally on your device** using on-device storage (Room database). This data stays on the device unless you choose to share it yourself outside the App (for example, by taking a screenshot).

### 2.3 Scan usage / freemium state (on-device)

The App tracks a local count of free scans used (3 free scans) so it can show the subscription paywall. This counter is stored on the device.

### 2.4 Purchase / subscription status

If you subscribe, Google Play manages the purchase. MintVision may receive from Google Play only what is needed to unlock premium features (for example, entitlement / subscription status). **MintVision does not receive your full payment card number** or full payment instrument details.

### 2.5 What we do not collect (based on current App design)

As of the effective date, MintVision does **not**:

- Require or offer in-app user accounts or sign-in
- Sell advertising inventory inside the App (no third-party ad SDKs described here)
- Intentionally collect analytics beyond what is necessary for scanning, local storage, and Play Billing entitlements *(if analytics or ads are added later, this policy will be updated)*

We do not invent or claim collection of categories we do not use.

---

## 3. How We Use Information

We use the information described above to:

- Capture and send scan images to a Vision API so the App can identify comics/cards
- Display recognition results and store your collection locally
- Enforce the freemium limit (3 free scans) and unlock premium features after a valid Google Play subscription
- Operate, maintain, and improve core scanning functionality
- Respond to privacy or support requests you send to our contact email

We do **not** sell personal data.

---

## 4. Third Parties

### 4.1 Google Play / Google Play Billing

Subscriptions are offered at **$4.99/month** and **$39.99/year** (prices may vary by region and are set in Google Play). Purchases are processed by **Google Play**. Google’s handling of payment and account data is governed by Google’s own policies (for example, the [Google Play Terms of Service](https://play.google.com/about/play-terms/) and related Google privacy documentation). MintVision does not process full payment card numbers.

### 4.2 Cloud Vision API provider

To recognize a card or comic, the App sends the captured image (and related request data needed for the API call) to a **cloud Vision API**. The App’s documented path uses an **OpenAI Vision–compatible** endpoint; the API base URL is **configurable**. Treat the Vision provider as a **third-party processor** that receives image data for the duration of the recognition request.

> **Confirm before publish:** If the live provider is still OpenAI, keep the OpenAI reference; if you point `VISION_API_BASE_URL` at another provider, update this section to name that provider and link its privacy policy.

The Vision provider processes image data according to its own terms and privacy policy. We use the API only to return recognition results to the App. We do not sell scan images.

### 4.3 No sale of personal data

We do not sell personal information to data brokers or advertisers.

---

## 5. Storage and Retention

| Data | Where stored | Retention |
|------|----------------|-----------|
| Collection / scan results | Locally on device (Room) | Until you delete items in-app or uninstall the App |
| Free-scan counter / premium entitlement cache | Locally on device | Until cleared by App logic, Play entitlement updates, or uninstall |
| Scan images sent for recognition | Transmitted to Vision API for the request | Handled by the Vision provider under its policies; MintVision does not operate a separate cloud collection database for your scans |
| Subscription / payment records | Google Play | Per Google’s retention practices |

**Uninstall:** Uninstalling MintVision removes the App’s local on-device data (collection, scan results, local counters) from that device, subject to normal Android uninstall behavior. It does not automatically cancel a Google Play subscription—manage or cancel subscriptions in Google Play.

---

## 6. Permissions

MintVision requests the **CAMERA** permission so you can photograph comics and cards for scanning. Camera access is used for scanning features. If you deny camera permission, scanning features that require the camera will not work.

---

## 7. Children’s Privacy

MintVision is **not directed to children under 13**. We do not knowingly collect personal information from children under 13. If you believe a child under 13 has provided personal information through the App, contact us and we will take reasonable steps to delete it from systems we control (noting that most App data lives only on the device).

---

## 8. Security

We take reasonable technical and organizational measures appropriate to an on-device collection app that transmits scan images for recognition (for example, using HTTPS for network requests to the Vision API where configured). No method of transmission or storage is 100% secure. You are responsible for keeping your device secured (screen lock, OS updates, etc.).

---

## 9. Your Choices

- **Camera:** You can deny or revoke camera permission in Android system settings.
- **Local data:** You can remove collection items in the App (where supported) or uninstall the App to remove local MintVision data.
- **Subscription:** Manage, cancel, or request refunds according to Google Play’s policies via Google Play / your Google account.
- **Contact:** Email us with privacy questions (see Contact).

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time (for example, if we change Vision providers, add accounts, or add analytics). The “Effective date” at the top will be revised when we publish changes. Continued use of the App after changes means you accept the updated policy. For material changes, we may also provide notice in the App listing or in-app where practical.

---

## 11. Contact

**Cullen Chapman** (MintVision)  
Email: **privacy@mintvision.app**  

> Replace `privacy@mintvision.app` with Cullen’s real contact email before publishing this policy or linking it from Google Play.

For Play subscription issues, use Google Play’s subscription and purchase support channels.

---

*This document is provided for MintVision’s Play Store listing and website use. It is not legal advice. Consider having counsel review before launch if your jurisdiction or business model requires it.*
