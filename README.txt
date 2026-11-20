# Hidden Camera Detector (starter web app)

This is an Android-friendly web app starter, not a guaranteed hidden-camera detector and not an APK.

## Run it
1. Extract the ZIP.
2. Upload `index.html` to a static HTTPS host (for example GitHub Pages or another static host).
3. Open the HTTPS page in Chrome on Android.
4. In Chrome, use the menu -> **Add to Home screen** (or **Install app**, if offered).

Camera preview requires a secure HTTPS origin and your permission. This project does not access the internet, scan nearby Wi-Fi devices, or send camera footage anywhere.

## Important limitations
- Browser apps cannot enumerate devices connected to your Wi-Fi network.
- A phone's magnetometer is not a reliable hidden-camera detector.
- Lens reflections are not proof; ordinary shiny objects can reflect light, and many cameras will not be detectable this way.
- This starter provides a live camera preview and a practical inspection checklist. It does not automatically confirm that a hidden camera is present.
