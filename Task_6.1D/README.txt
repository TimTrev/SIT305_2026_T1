To get this Android Studio project working.



Replace "YOUR_GEMINI_API_KEY_HERE" with your own API key

Steps:
1. Open https://aistudio.google.com/
2. Navigate to API Keys
3. Create API Key
4. Copy API Key into the project under the file app/helper/LlmHelper.java
5. The destination is located by the '//' comment and code snippet below.


// ============ NOTE: Replace " YOUR_GEMINI_API_KEY_HERE " with your Gemini API key ============

 private void sendPrompt(String prompt, LlmCallback callback) {
        String apiKey = "YOUR_GEMINI_API_KEY_HERE";

        if (apiKey == null || apiKey.trim().isEmpty()) {
            callback.onError(prompt, "Gemini API key is missing.");
            return;
        }