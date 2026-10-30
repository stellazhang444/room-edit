# Room Edit

An interactive room-redesign prototype: upload a room photo, set design preferences, compare example results, and export an image.

## Try it

[Open Room Edit](https://stellazhang444.github.io/room-edit/) — no sign-up required.

1. Start a new project and upload a photo, or choose a Living room example.
2. Select a room type and visual style. Optionally add colors, materials, items to retain, a budget, reference images, and notes.
3. Preview the prepared living-room example. Use Original, Result, and Compare to inspect the images.
4. Export a single image or before-and-after layout as PNG or JPG.

## Prototype scope

Live AI generation and AI editing are not connected. Living-room examples use prepared images. Uploaded photos are not automatically redesigned. Area selection and written revision instructions demonstrate the intended editing interaction only. Budget inputs do not validate product prices.

Photos and selections are held in browser memory and reset on reload. This static version does not upload photos to a generation service.

## Run locally

No build step or package installation is required. With Python installed:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000.

## Publish

In repository Settings → Pages, select **Deploy from a branch**, then **main** and **/(root)**.
