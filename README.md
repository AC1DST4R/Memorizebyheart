# Memorize Free

A standalone, no-premium memorization web app inspired by modern scripture/speech/text memorization workflows.

## Included

- Unlimited texts
- Local offline storage
- Text editor
- Search
- Progress and mastery
- Spaced-review scheduling
- Review history
- Practice streaks
- Tap to Reveal
- First Letter
- Fill in the Blank
- Scramble
- Type It
- Multiple Choice
- Listen / text-to-speech
- Speak / speech recognition where supported
- Run Scene
- Familiarize
- Chunks
- Statistics
- Groups and invite codes (local/offline)
- JSON backup import/export
- PWA manifest/service worker
- No premium tier or paywall

## Run

Open `index.html` in a browser, or serve the folder with any static web server.

For the service worker/PWA, use a local server such as:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Notes

The app is an independent implementation. It does not include proprietary source code, branding, or assets from Memorize By Heart.

PDF/OCR import and true multi-device groups require optional libraries/backend integration and are intentionally kept out of this dependency-free starter so the core app works offline with zero setup.
