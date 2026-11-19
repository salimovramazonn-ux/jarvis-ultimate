JARVIS AI ULTIMATE — iPhone PWA starter

This is a mobile web app prototype, not a native iOS app or a system keyboard extension.

To install on iPhone:
1. Upload the contents of this folder to an HTTPS static host (for example GitHub Pages, Netlify, or Cloudflare Pages).
2. Open the resulting HTTPS website in Safari on iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Open JARVIS AI from the Home Screen.
5. Allow microphone access when Safari asks. Voice recognition support varies by iOS version/browser/language.

Current features:
- Iron Man-inspired blue HUD interface
- Local clock and date
- Basic voice input where browser support exists
- Speech synthesis using available iPhone voices
- Text studio with copy/read controls
- Offline caching after first successful load

Limitations:
- No live ChatGPT/AI backend is connected. Add a secure server endpoint before using an AI API; never put a private API key in browser JavaScript.
- Web apps cannot install a true iOS keyboard extension or control iPhone system functions.
- iOS may limit background audio, speech recognition, and offline behavior.
- A male voice is not guaranteed; available voices depend on iOS language/voice downloads.
