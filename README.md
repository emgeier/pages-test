# TV News Commercial Segment Detector — Documentation Site

A static documentation site explaining how the VCIL Commercial Segmentation Tool works, covering both the backend processing pipeline and the frontend visualization application.

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose `main` branch, `/ (root)` folder
5. Click **Save**

The site will be live at `https://<username>.github.io/<repo-name>/`

## Structure

- `index.html` — Single-page documentation covering:
  - Project overview
  - Backend architecture (Lambda, Step Functions, SAM)
  - Detection algorithm (black frame analysis, pairing heuristics)
  - Frontend application (React, Amplify, timeline visualization)
  - End-to-end data flow
- `style.css` — Styling

## Adding a Demo Video

To embed a demo video, add an `.mp4` file (keep it under 50MB) to the repo and reference it in `index.html`:

```html
<video controls width="100%">
  <source src="demo.mp4" type="video/mp4">
</video>
```

Or embed from YouTube:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
```
