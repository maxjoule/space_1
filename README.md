# Space Academy - HTML5 Android Browser Version

This version runs as plain HTML5 in Android Chrome. No APK is required.

## How to test on PC

1. Open this folder in VS Code.
2. Install the VS Code extension **Live Server**.
3. Right-click `index.html`.
4. Click **Open with Live Server**.

## How to run on Android phone

### Recommended method

1. Upload this folder to any simple web hosting.
2. Open `index.html` in Android Chrome.
3. Rotate the phone to landscape mode.
4. Use the on-screen buttons:
   - ◀ Move left
   - ▶ Move right
   - JUMP
   - FIRE

### Add to Home Screen

In Android Chrome:

1. Open the game link.
2. Tap the three-dot menu.
3. Tap **Add to Home screen**.
4. The game will appear like an app icon.

This is still HTML5, not an APK.

## Important note

Opening `index.html` directly from phone storage may work, but browser security can block some features later, especially if you add JSON files, audio, save data, or service worker caching.

For best results, run it from a web server.

## Included improvements

- Mobile touch controls
- Responsive canvas scaling
- Low-gravity astronaut jump
- Slower responsive movement
- Smooth camera
- PWA manifest
- Basic service worker cache
