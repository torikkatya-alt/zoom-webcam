# Zoom Webcam Interface

Interactive Zoom-style interview scene with a local webcam, microphone controls, scripted chat and a looping interviewer video. This is an independent interface prototype, not the Zoom service. Some service buttons are visual placeholders.

Open the GitHub Pages HTTPS URL and allow camera access. Camera and microphone streams stay on the visitor's device; this code does not record or upload them.

## GitHub Pages

Settings → Pages → Deploy from a branch → main → /(root). No build step or dependencies.

## TouchDesigner

Create a Web Render TOP, paste the GitHub Pages URL, enable Media Stream and Active. For clicks and keyboard interaction use the webBrowser palette component.
