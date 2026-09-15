# Janon7300 Portfolio

Personal developer portfolio hosted with GitHub Pages.

## Pages

- `/` — editable personal profile
- `/projects/` — project index designed to grow beyond one project
- `/projects/checknuaykit/` — full Check Nuay Kit product case study
- `/projects/expressnon/` — expressnon peer-to-peer transfer case study
- `/projects/image-lens/` — Image Lens browser extension case study

Personal placeholder copy and the profile image slot are marked with HTML comments in `index.html`. Shared colors, typography, layout, and responsive behavior live in `assets/site.css`; reveal and interaction motion live in `assets/site.js`.

## Featured projects

### [Check Nuay Kit](https://checknuaykit.vercel.app/)

A full-stack student platform for checking curriculum credits, planning study progress, reading course reviews, following campus updates, and working with an AI study assistant.

Its local-first transcript engine reads PDF text entirely in the browser with PDF.js, reconstructs rows from text coordinates, repairs legacy Thai glyphs and tone-mark ordering, extracts courses and grades, then evaluates them with a multi-pass curriculum rule engine. Transcript files are not uploaded to the backend for credit checking.

Built with React 19, TypeScript, Express, Firebase, Cloudinary, Upstash Redis, Google Gemini, and Vercel.

### [expressnon](https://expressnon.vercel.app/)

A browser-to-browser transfer tool for sending files, text, and code through a six-character room code. WebRTC DataChannel carries the payload directly; Vercel Functions, Firebase, and Upstash handle only verified connection coordination, short-lived signaling, and abuse controls.

The case study covers the product flow, chunked transfer and backpressure, independent multi-recipient sessions, temporary room lifecycle, security layers, and the honest limits of a STUN-only peer-to-peer architecture.

### [Image Lens](https://github.com/Janon7300/image-lens)

An experimental, open-source browser extension that translates text in webpage images into Thai or English using the user's chosen vision-capable AI provider. Results appear as overlays or in a panel, with an original-view toggle and optional translation after scrolling stops.

Built with HTML, CSS, and JavaScript, with Manifest V3 for Chrome/Edge and Manifest V2 for Firefox Desktop. It loads directly from source without a build step. Users supply their own API key; visible webpage screenshots are sent directly to the configured provider for translation.

## Live site

[janon7300.github.io](https://janon7300.github.io/)

## Built with

- HTML
- CSS
- JavaScript
- GitHub Pages
