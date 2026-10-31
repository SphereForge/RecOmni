# Privacy Policy for RecOmni

**Last Updated: November 1, 2026**

Thank you for using RecOmni. Your privacy is important. This privacy policy explains how information is handled in my application, RecOmni.

---

### 1. About RecOmni's Monetization Model

*   **Free Version:** The App is free to download and use. This version is supported by third-party advertising.
*   **Pro Upgrade (In-App Purchase):** Users can choose to make a one-time in-app purchase to upgrade to the "Pro" version. This upgrade permanently disables all advertisements, terminates all ad-related data collection, and unlocks all premium features in the App.

---

### 2. Core App Functionality (Local Processing)

RecOmni is designed to operate entirely on your device. The App provides screen recording, camera facecam overlay, microphone audio recording, screenshot capture, and batch video conversion/compression tools. 

**All video recordings, audio tracks, converted files, and photos are processed locally on your device hardware:**

*   **Screen Capture & Facecam:** Screen projection and camera feeds are captured and encoded in real time directly by your device's native hardware encoders.
*   **Audio Recording:** Microphone input and internal device sound are captured, mixed, and encoded entirely on-device.
*   **Media Conversion & Compression:** All video and audio files you import or export are transcoded locally on your device using local system codecs.

RecOmni does not host external media storage servers and does not access, view, upload, or transmit any of your personal recordings, photos, or media files. Your media never leaves your device and is never seen by me.

---

### 3. Device Permissions Used by RecOmni

To provide its core functionality, RecOmni requests the following Android permissions:

*   **Camera (`android.permission.CAMERA`):** Used strictly when you enable the floating facecam or camera overlay to capture video/photos.
*   **Microphone (`android.permission.RECORD_AUDIO`):** Used to capture microphone audio and mix dual audio (internal sound + microphone) during recording sessions.
*   **Storage / Media Access (`READ_MEDIA_VIDEO`, `READ_MEDIA_IMAGES`):** Used solely to read videos you select for compression or conversion and save exported results to your device gallery (`Movies/RecOmni`, `Pictures/RecOmni`, and `Music/RecOmni`).
*   **Screen Recording (`MediaProjection` & `FOREGROUND_SERVICE_MEDIA_PROJECTION`):** Used exclusively to capture your screen contents when you initiate a recording session.
*   **Overlay (`SYSTEM_ALERT_WINDOW`):** Used to display the radial floating control widget and the draggable facecam feed over other applications.
*   **Notifications (`POST_NOTIFICATIONS` & Foreground Services):** Used to display real-time recording status, export progress, and persistent service controls.

---

### 4. Third-Party Advertising & Mediation SDKs

To support the App and offer it for free, the free version of RecOmni integrates third-party advertising services.

My advertising partners are:
*   **Unity LevelPlay (Mediation)**
*   **Unity Ads**
*   **ironSource (part of Unity)**
*   **Google AdMob**

With your consent, these services may collect and process pseudonymous identifiers and technical data from your device to provide personalized and relevant advertising. I do not access, store, or manage this data directly. This data may include:
*   **Device Identifiers:** Such as your Android Advertising ID (GAID).
*   **General Location Data:** Non-precise location, such as country or city.
*   **Technical Information:** Device model, operating system version, carrier, and mobile network type.
*   **Ad Engagement Data:** Information about ads shown, viewed, and clicked.

Declining consent for personalized ads will not stop ads from being shown, but they will be generic and not tailored to your interests.

*Note: If you upgrade to the Pro version of RecOmni, all ad displays and ad-related SDK operations are completely deactivated, and data collection for advertising purposes ceases entirely.*

---

### 5. How This Data Is Used

The information collected by my advertising partners is used by them for the following purposes:
*   **To Monetize the App:** Displaying ads allows me to offer RecOmni to you for free.
*   **To Personalize Advertising:** To display ads relevant to your interests (with your consent).
*   **For Analytics, Fraud Detection, and Reporting:** To measure ad delivery, prevent fraudulent activity, and analyze mediation performance.

---

### 6. Diagnostic Logs & Crash Reports

To ensure high performance and stability, RecOmni relies on standard anonymous diagnostic tools:
*   **Google Play:** If the App crashes, your Android OS may generate an anonymous stack trace sent to my Google Play Console. This data is purely technical and helps identify OS-specific bugs. This is controlled by your system setting under **Settings > Google > Usage & diagnostics**.
*   **Unity:** The integrated Unity SDK collects "Essential Data" (anonymous technical and diagnostic data, including IP address and hardware specifications) necessary to ensure their SDK operates reliably, detects runtime errors, and prevents fraudulent traffic.

Neither of these services accesses your personal media files. This data is used solely for the purpose of identifying bugs, ensuring service stability, and detecting invalid traffic.

---

### 7. User Consent Choices & Regional Rights (GDPR & US Regulations)

RecOmni complies with regional data privacy frameworks, including the European Union General Data Protection Regulation (EU GDPR), UK GDPR, and applicable US state privacy regulations.

*   On initial launch, users in applicable jurisdictions are presented with a consent dialog powered by Google's certified **User Messaging Platform (UMP)**.
*   You can review, modify, or revoke your consent preferences at any time from within the App by opening the navigation drawer and tapping **Privacy Choices**.

---

### 8. In-App Purchase (Pro Upgrade)

If you choose to upgrade to the Pro version via the one-time Google Play in-app purchase:
*   The App permanently terminates all ad requests and deactivates all advertising SDK functions. Consequently, data collection for advertising purposes ceases entirely.
*   All payments are processed securely by the Google Play Store. I do not collect, see, or store any of your financial information. The App simply verifies the purchase with Google Play to confirm your Pro status.

---

### 9. Data Security & Third-Party Privacy Policies

As the core functionality of RecOmni does not collect your data, I rely on the robust security measures of my advertising partners to protect the information they collect. You are strongly encouraged to review their privacy policies for more details:

*   **Unity (for Unity Ads & LevelPlay / ironSource):** [https://unity.com/legal/game-player-and-app-user-privacy-policy](https://unity.com/legal/game-player-and-app-user-privacy-policy)
*   **Google (for AdMob & Play Services):** [https://policies.google.com/privacy](https://policies.google.com/privacy)

---

### 10. Children's Privacy

RecOmni is intended for a general audience and is not directed to children under the age of 13 (or the applicable age in your jurisdiction). I do not knowingly collect personal information from children. If a parent or guardian wishes to stop personalized advertising data collection on a device, they can reset or delete the Android Advertising ID under **Settings > Google > Ads**.

---

### 11. Changes to This Privacy Policy

I may update this Privacy Policy from time to time. Any updates will be posted to this page with an updated "Last Updated" date.

---

### 12. Contact Me

If you have any questions, feedback, or bug reports regarding this Privacy Policy or RecOmni, please contact me:

*   **Email:** [sphereforge.apps@gmail.com](mailto:sphereforge.apps@gmail.com)
*   **GitHub Issues:** [https://github.com/SphereForge/RecOmni/issues](https://github.com/SphereForge/RecOmni/issues)
*   **Website:** [https://sphereforge.github.io](https://sphereforge.github.io)
