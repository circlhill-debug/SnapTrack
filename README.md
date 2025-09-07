# SnapTrack — USPS Label OCR (Web)

Fast, private, in-browser OCR to grab USPS tracking numbers from a photo and jump straight to the USPS tracking page.

**Live app:** https://circlhill.github.io/snaptrack-usps/

## How it works
- Runs entirely in your browser via Tesseract.js; no images leave your device.
- Take a photo or upload one, drag the crop box over the tracking number, tap **Use crop**.
- If multiple candidates are found, tap the correct one; or copy from **Raw OCR** and paste into the manual box.

## Quick start
1. Open the link above on your phone.
2. Tap **Snap (Camera)** or **Upload from Photos**.
3. Adjust the crop box → **Use crop** → USPS opens in a new tab.

## Tips for best OCR
- Fill the frame with the tracking number.
- Avoid glare; tilt slightly if needed.
- App auto-boosts contrast (B/W threshold) to beat blue backlighting.

## Troubleshooting
- If OCR fails, try another angle or brighter light.
- “Snap” may open only the camera on some phones; use **Upload from Photos** for gallery + cropping.

## Privacy
- All processing happens locally in the browser. No server, no uploads.

## Credits & License
© 2025 Dave. MIT License. See `LICENSE`.
