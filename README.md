# ClipPilot — Free Starter (V1)

A mobile-friendly, free-first video clipping web app. It runs in the browser and does not require an account or backend.

## Features
- Upload a video from your device for local preview.
- Choose clip start and end points with trim sliders.
- Generate simple evenly spaced clip suggestions.
- Preview the selected section.
- Export the selected section as a WebM file where the browser supports `MediaRecorder` and video `captureStream()`.
- Recognize TikTok, Instagram, Facebook and YouTube URLs.
- PWA manifest and service worker for install/offline shell support.

## Important limitations
- Social URLs are recognized, not downloaded. These platforms restrict direct video extraction and require their own authorized access flows.
- Automatic suggestions are evenly spaced starter segments, not AI highlight detection.
- Export compatibility depends on the browser/device. Latest Chrome is recommended. WebM is the export format in this starter.
- Video processing happens locally in the browser; large files may use substantial device memory.

## Run locally
Open `index.html` in a modern browser. For installable PWA/offline support, host the files over HTTPS.

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload **the contents** of the folder to the root of your `ClipPilot` GitHub repository (so `index.html` is at the repository root).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish the site.

If the repository is private, GitHub Pages availability depends on your GitHub plan and repository settings. If Pages is unavailable, make the repository public or use another free static host.

## Next upgrades
AI highlight detection, subtitles, 9:16 reframing, more export formats, cloud projects and shareable clip links require additional implementation and (for some features) a backend or third-party services.
