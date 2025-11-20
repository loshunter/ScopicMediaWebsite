ScopicMedia — Landing Page

Retro roots. Future vision.
A CRT-styled, PS1-era boot-screen website for ScopicMedia, a one-person indie game studio developing:

HeroByte VTT — NES/SNES-inspired browser VTT

LowPolyKarter — low-poly, drift-happy kart racer prototype

The page simulates a 90s console startup: CRT scanlines, phosphor glow, fake BIOS output, and a smooth transition into a retro-modern interface.

✨ Features
Full CRT Simulation

Scanlines, vignette, subtle flicker

“Power-on” warmup animation

Phosphor-glow text rendering

PS1-Era Boot Flow

ScopicMedia splash sequence

Fake BIOS logs (Initializing BIOS…, Booting ScopicOS v1.0…)

Automatic transition into main UI

Retro-Modern UI Layer

Tailwind (CDN) for layout + utilities

Pixel fonts: Press Start 2P + VT323

Lucide icons for lightweight vectors

Project Panels
HeroByte VTT

System-agnostic, NES/SNES-themed VTT

WebRTC voice, live sync, Konva rendering

Links to full repo

LowPolyKarter

Low-poly arcade racer prototype

Drift mechanics + 90s vibe

Repo link included

Dev Logs

Static retro terminal “cards”

Date-stamped update entries

Contact Module

Terminal-themed form (USER_ID, COMM_CHANNEL, DATA_PACKET)

Fake transmit handler (alert("TRANSMISSION SENT SUCCESSFULLY."))

Placeholder row for socials

Responsive Layout

Mobile-first Tailwind grid

Scales cleanly up to desktop

🛠 Tech Stack

Minimal on purpose:

HTML5 — single-file index.html

Tailwind CDN — no build step

Google Fonts — Press Start 2P, VT323

Lucide Icons — CDN

Vanilla JS — boot sequence + form logic

No bundler, no framework, no tooling

🚀 Getting Started

Clone and run locally:

git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>


Quick preview (double-click):

index.html


Recommended lightweight server:

npx serve .