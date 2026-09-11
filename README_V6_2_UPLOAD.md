# FLOW FILIPINO AI v6.2 — Pipeline Fix

## GitHub upload
Copy the included `android/app/src/main/assets/index.html` over the existing file in your repository.

Target:
`android/app/src/main/assets/index.html`

The Android Java project does not need to change for this UI update.

## Fixed flow
WELCOME → READY → GENRE → START → 5 STORY CHOICES → STORY PROCESSING → CHARACTER MASTER REFERENCE → STORYLINE → 15 SCENES → IMAGE → VIDEO → PREVIEW/DIALOGUE CHECK → COMPILE → EXPORT.

## Locked production rules
- Exactly 5 episodes
- Exactly 3 scenes per episode
- 90 seconds per episode
- 15 total scenes
- 9:16 vertical
- Character MasterRef identity lock
- Dialogue speaker lock
- Wan Local / ComfyUI marked NO CREDIT REQUIRED
- Cloud engines are not falsely described as free

## Important
This package fixes the app flow/UI. Actual text-to-image and image-to-video files still require a connected rendering backend such as local Wan 2.1 + ComfyUI. The UI does not fake a real generated video file.
