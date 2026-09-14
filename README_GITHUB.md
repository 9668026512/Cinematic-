# Cinematic Android App

This project is prepared for a phone-only GitHub Actions cloud build.

## Build from an Android phone

1. Create/sign in to a GitHub account.
2. Create a new repository, for example `Cinematic`.
3. Upload the contents of this folder to the repository (not the outer ZIP folder).
4. Open the repository's **Actions** tab.
5. Select **Build Cinematic APK**.
6. Tap **Run workflow**.
7. After the workflow finishes, open the run and download the **Cinematic-APK** artifact.
8. The artifact contains `app-debug.apk`.

## Important
The current app uses a UPI payment intent and a demo unlock button. It does NOT verify ₹10 payment with a server/payment gateway. Do not treat the demo unlock as secure payment verification for a public paid app.

UPI ID configured in the app:
9668026512@fam
