# ⚡ Beamdrop

Send files, photos and text between any two devices. Free, private, no sign-up.

## Use
1. Open Beamdrop on device A — a QR code and 6-character code appear instantly.
2. On device B, scan the QR (or open the link / type the code).
3. Drop files, paste an image, or send a message. Done.

## Host it free
GitHub Pages: push the files → Settings → Pages → Deploy from `main`.
Netlify Drop and Cloudflare Pages work too. Use `https://`. Local test: `python -m http.server`.

## Files
`index.html` — the whole app (structure, design and logic in one file)

## How it works
Browsers connect directly (WebRTC) using PeerJS's free public pairing server. Files are sent in 32 KB chunks and never stored on a server.

## Notes
Both devices need internet to pair. Keep the tab open while sending. Very large files depend on device RAM.

MIT License
