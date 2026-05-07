## Google Cloud API Key Setup

This application requires a Google Cloud API key with the following APIs enabled:

- Maps SDK for Android
- Places API

To run the application:

1. Create a Google Cloud API key from the Google Cloud Console.

2. Replace "YOUR_GOOGLE_CLOUD_API_KEY_HERE" in:

   - `CreateAdvertActivity.java`
Location: // ########## NOTE: Replace "YOUR_GOOGLE_CLOUD_API_KEY_HERE" with your actual Google Cloud API key ##########

   - `AndroidManifest.xml`
Location: private static final String API_KEY = "YOUR_GOOGLE_CLOUD_API_KEY_HERE";

3. Re-build and run
