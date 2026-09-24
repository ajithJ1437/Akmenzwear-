AK MENZ WEAR - PLAY STORE ANDROID PROJECT

Package name: com.akmenzwear.app
Version: 1.0 (versionCode 1)

WHAT THIS PROJECT DOES
- Wraps the current AK Menz Wear HTML storefront in an Android WebView.
- Uses the current Firebase-backed HTML file in app/src/main/assets/index.html.
- Supports JavaScript, Firebase web services, local storage and HTML file upload.
- Supports multiple product-photo selection from the Android file picker.
- Opens UPI, WhatsApp, phone, mail and geo links in Android apps when available.
- Uses the AK Menz Wear logo as the launcher icon.

BUILD
1. Open this folder in Android Studio.
2. Let Gradle sync/download Android dependencies.
3. Test on a real Android phone.
4. Build > Generate Signed Bundle / APK.
5. Select Android App Bundle (.aab) for Google Play.
6. Create a release keystore and keep the keystore/password safely.

IMPORTANT
- Firebase rules still control product/photo/order security.
- A QR code alone does not provide automatic payment verification.
- WhatsApp links open WhatsApp; automatic invoice messaging needs WhatsApp Business/API.
- Before Play Store release, add a public Privacy Policy URL and complete Play Console Data Safety declarations.
- Update versionCode/versionName for every Play Store update.
