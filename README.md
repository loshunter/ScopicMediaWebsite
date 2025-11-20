\# ScopicMedia Landing Page



\*\*Retro roots. Future vision.\*\*  

This repo contains the CRT-styled landing page for \*\*ScopicMedia\*\*, a one-person indie game studio building:



\- \*\*HeroByte VTT\*\* – a browser-based, NES/SNES-inspired virtual tabletop  

\- \*\*LowPolyKarter\*\* – a high-octane low-poly kart racer prototype



The site is a single-page experience themed like a PS1/90s console boot screen, complete with CRT scanlines, flicker, and a faux BIOS boot sequence.



---



\## Features



\- \*\*Full CRT Simulation\*\*

&nbsp; - Scanlines, vignette, and subtle flicker overlay

&nbsp; - “Turn on” animation mimicking old CRTs warming up

&nbsp; - Phosphor-style glow for text and UI



\- \*\*PS1-Era Boot Sequence\*\*

&nbsp; - Splash logo animation

&nbsp; - Fake terminal output (`Initializing BIOS…`, `Booting ScopicOS v1.0…`)

&nbsp; - Smooth transition from boot screen into the main site



\- \*\*Retro-Modern UI\*\*

&nbsp; - Tailwind CSS (CDN) for layout and utilities

&nbsp; - Pixel fonts:

&nbsp;   - `Press Start 2P` for headings

&nbsp;   - `VT323` for body and terminal text

&nbsp; - Lucide icons for lightweight vector icons



\- \*\*Project Highlights\*\*

&nbsp; - \*\*HeroByte VTT\*\*

&nbsp;   - System-agnostic, NES/SNES-inspired virtual tabletop

&nbsp;   - Mentions WebRTC voice, real-time sync, Konva rendering

&nbsp;   - Links out to the HeroByte GitHub repo

&nbsp; - \*\*LowPolyKarter\*\*

&nbsp;   - Low-poly arcade kart racer concept

&nbsp;   - Drift-focused, 90s-style racing vibe

&nbsp;   - Links out to the kart game GitHub repo



\- \*\*Developer Logs Section\*\*

&nbsp; - Static dev log cards showing dated updates

&nbsp; - Themed like a retro terminal/dev console



\- \*\*Contact Panel\*\*

&nbsp; - Themed input fields (`USER\_ID`, `COMM\_CHANNEL`, `DATA\_PACKET`)

&nbsp; - Fake submit handler (`alert('TRANSMISSION SENT SUCCESSFULLY.')`)

&nbsp; - Social icon row for future links (Twitter/X, GitHub, Instagram, etc.)



\- \*\*Responsive Layout\*\*

&nbsp; - Tailwind-driven responsive grid and typography

&nbsp; - Mobile-first structure with desktop enhancements



---



\## Tech Stack



This project is intentionally lightweight:



\- \*\*HTML5\*\* – Single `index.html` file

\- \*\*Tailwind CSS\*\* via CDN – No build step required

\- \*\*Google Fonts\*\* – `Press Start 2P` and `VT323`

\- \*\*Lucide Icons\*\* via CDN

\- \*\*Vanilla JavaScript\*\* – Handles boot sequence and simple form behavior



There is \*\*no bundler, framework, or build tooling\*\* required for the current version.



---



\## Getting Started



You can run this site locally in two basic ways: direct file open (for quick preview) or with a tiny static HTTP server (recommended).



\### 1. Clone the Repository



```bash

git clone https://github.com/<your-username>/<your-repo-name>.git

cd <your-repo-name>



