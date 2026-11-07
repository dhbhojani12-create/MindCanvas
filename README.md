# MindCanvas

A free mind map canvas that runs in the browser. One file (`index.html`), no server, no build step.

## Put it on GitHub Pages (about 2 minutes)

1. Go to https://github.com/new and create a **public** repository, e.g. `mindcanvas`.
2. Click **Add file → Upload files**, drag in `index.html` and `README.md`, then click **Commit changes**.
3. Open **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, then **Save**.
4. Wait about a minute. Your app will be at `https://<your-username>.github.io/mindcanvas/`.

## Features

- **Mind map editing**: Tab = add child, Enter = add sibling, double-click or just start typing to edit, Delete to remove, arrow keys to move around, Space to collapse a branch, Ctrl+Z / Ctrl+Y for undo/redo.
- **Drag** a node to move it. Drop it **on another node** to move it there. Drag a main branch across the centre to switch sides. "Tidy layout" resets manual moves.
- **Pan** by dragging empty space. **Zoom** with the mouse wheel, a trackpad pinch, or the +/- buttons. Fit to screen is in the left toolbar.
- **Node style**: branch colour, link, note, image, and **Combine sub-points into one box** (Node style tab on the right).
- **Images**: add one from your computer, paste it (Ctrl+V), or drag and drop it onto the canvas.
- **Photo from phone**: click *Photo from phone* on the laptop and scan the QR code with your phone. Take a photo and tap *Send to laptop*. It arrives as a new node.
- **Export**: PNG, PDF, SVG, Markdown, JSON (a backup you can reopen with the folder icon), FreeMind (.mm). You can include or leave out photos, use a transparent background, or export only the selected branch.
- **Auto-save**: the map is saved in your browser. Export JSON to back it up or move it to another computer.

## Gemini AI (free)

1. Get a free key at https://aistudio.google.com/apikey
2. In the app, click the sliders icon in the AI panel, paste the key, press **Load models**, choose a model, and **Save**.
3. Under **Add AI results as**, choose **One box** (the default: all points for a topic go into one bulleted box) or **Separate boxes**.
4. Then use *Expand ideas*, *Summarise map*, *Map from photo* (reads notes or whiteboard photos), *Map from topic*, or just ask a question.

The key is kept only in your browser's storage. It is never put in your GitHub code. The free tier has daily limits set by Google. If you hit one, the app can switch to the fastest model for you (option in AI settings).

## Notes

- Phone pairing uses a free public connection service (PeerJS) to link the two devices. The photo goes directly from phone to laptop. Keep the QR window open while sending. A few strict office or school networks block direct connections. If that happens, use "Upload from this computer instead".
- Pairing only works from the GitHub Pages link, not when you double-click the file on your computer.
- Browser storage holds about 5 MB. If you add many large photos, export JSON now and then.
