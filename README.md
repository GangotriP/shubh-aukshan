# शुभ औक्षण · तुझ्यासाठी प्रेमाने

A Marathi virtual औक्षण ceremony for celebrating women with warmth, strength, and blessings. The experience runs completely in the browser as a static site.

## Ceremony flow

1. Read and accept the blessings.
2. Choose to take or upload a photo, or use the included portrait.
3. **For a personal photo:** adjust zoom and vertical position, then tap the **forehead** and **crown** on the actual photo. These two landmarks tell the ceremony where to place हळद-कुंकू and अक्षता. Continue only after selecting both points.
4. Perform the four steps in order: दिव्यांनी ओवाळणे → कुंकू/हळद → अक्षता → सुपारी/अंगठी (three left-to-right and return pairs).
5. Read/share the final blessings.

The rice grains land on the chosen crown/hair area, not on the face. The कुंकू dot is above the हळद dot. Only the ring and सुपारी move together along the semi-oval; no hand is shown. The pair touches the left and right edges of the थाळी in three back-and-forth cycles.

## Photo privacy

Personal images are selected and processed **inside the recipient's browser** using browser APIs; the website does not upload them to a server, use a backend, or save them to GitHub. Images are only held in the open page; refreshing the page clears them. A GitHub Pages website link can be shared publicly, but the uploaded photos themselves are never part of that link.

To support different selfie framing, this version intentionally uses **manual, two-point positioning** rather than claiming to recognize faces automatically. Recipients can move or zoom their image and mark the two points themselves. Uploaded photos also use a taller ceremony stage and a lower, smaller thali so the full face stays visible. The ritual arc is positioned relative to the actual thali.

## Publish on GitHub Pages

1. Create a public repository (e.g. `shubh-aukshan`).
2. Upload **`index.html`**, **`.nojekyll`**, and **`README.md`** to the repository root. (Extract the ZIP first.)
3. Open repository **Settings → Pages → Build and deployment**.
4. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, and save.
5. Open the GitHub Pages URL shown after deployment.

This updated layout is **not deployed**. Replace the repository root `index.html` to publish the updated layout under the existing GitHub Pages link. You can also open `index.html` directly in a modern browser for local testing. Camera permission is browser/device-dependent; if the camera picker is unavailable, choose a picture from the photo library.
