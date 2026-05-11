# DragScale

A lightweight scale-ruler tool for measuring distances on any to-scale floor plan, elevation, or photograph — directly in your browser. No install, no upload to any server, no account required.

**Live demo:** *(fill in your URL after deploying)*

## Features

- Drop, paste, or take a photo of a floor plan / elevation / drawing
- Drag a virtual ruler onto a known dimension, calibrate once, then measure anywhere on the same image
- Supports cm / m / mm / inch
- Edge snap — auto-aligns the ruler to perpendicular line segments in the image
- Pinch / wheel zoom, pan
- Customizable: ruler body color & opacity, end-line color & length, marker-line color & length
- Multilingual UI: English / 中文 / 日本語 / 한국어
- Works on desktop, iPhone, iPad, Android — single self-contained HTML file

## Privacy

Everything runs locally in your browser. The image you upload, the calibration value, and your settings never leave your device. There is no backend.

## How to use

1. Upload a to-scale floor plan or elevation drawing.
2. Drag the ruler onto a segment of known length and align one end with it. Use the blue endpoints to rotate or resize.
3. Drag the red marker to the other end of that segment.
4. Enter the actual length and press **Calibrate**. The scale stays locked until you calibrate again.
5. Enable **Edge Snap** to auto-align with line segments.
6. The scale must be recalibrated after each new image upload.

**Desktop** — hold `Shift` to lock H/V move or 15° rotation; hold `Option / Alt` to suspend snap during a drag.
**Touch** — tap *📐 Lock* to constrain dragging to H/V or 15°; tap *🧲 Snap* to toggle edge snap on/off.

## Deploy

This is a single static HTML file. Any static host works:

- **GitHub Pages** — push `index.html` to a public repo, then `Settings → Pages → Source: main`.
- **Cloudflare Pages** — connect the repo, no build command needed.
- **Netlify / Vercel** — drag-and-drop or connect the repo.

## License

MIT License — Copyright © 2025 Raymond Lin &lt;raymond.lin@mac.com&gt;

See [LICENSE](LICENSE) for the full text.
