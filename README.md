 <div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/19228318/202900211-95e8474b-edbb-4048-ba0b-a581a6d57fc4.png" width=200>
    <img alt="arRPC" src="https://user-images.githubusercontent.com/19228318/203024061-064fc015-9096-40c3-9786-ad23d90414a6.png" width=200>
  </picture>
  <br>
  <a href="https://choosealicense.com/licenses/mit/l"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
  <a href="https://github.com/OpenAsar/arrpc"><img alt="OG Repo" src="https://img.shields.io/badge/Forked From-OpenAsar/arrpc-blue.svg"></a>
  <br>
  <a href="https://github.com/vexsyx/arrpc-exe/releases/latest"><img alt="Latest Release" src="https://img.shields.io/github/v/release/vexsyx/arrpc-exe?label=Latest%20Release"></a>
  <a href="https://github.com/vexsyx/arrpc-exe"><img alt="Downloads" src="https://img.shields.io/github/downloads/vexsyx/arrpc-exe/total.svg?label=Total Downloads"></a>
</div>

# arRPC (fork)

This repository is a **fork of [OpenAsar/arRPC](https://github.com/OpenAsar/arRPC)** modified to build as a standalone Windows EXE. It bundles the original Node code and adds packaging scripts while respecting the work of the upstream author. Please star and support the original project if you enjoy this fork.

arRPC re‑implements Discord's local RPC servers in Node.js so apps can send
rich presence data anywhere, especially web clients and alternative
Discord clients. It's lightweight, experimental and works best with the
**WebRichPresence (arRPC)** plugin installed in Vencord (required).

## Quick start

1. Download or build the EXE from this repo.
2. Run `arrpc-exe` (or `npx arrpc` in Node), a console will appear.
3. In Discord/Vencord, enable the **WebRichPresence (arRPC)** plugin.
4. Use any app with Discord RPC <small>*(like [Oyster Detector](https://oysterdetector.vexsys.site)!)*</small>; web clients should now receive your status.

## Notes

- This fork exists solely to provide a portable EXE; all core logic comes from the original arRPC project.
- For regular use, consult the upstream README: https://github.com/OpenAsar/arRPC
- A modern (>=18) Node.js runtime is required when not using the bundled EXE.

---

*Supported transports & commands are identical to upstream.* 
