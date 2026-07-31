# 🌸 Hridaya OS

[![npm version](https://img.shields.io/npm/v/hridaya-os.svg)](https://www.npmjs.com/package/hridaya-os)
[![Downloads](https://img.shields.io/npm/dw/hridaya-os.svg)](https://www.npmjs.com/package/hridaya-os)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A human-friendly CLI — type naturally, no strict commands needed.
> Works on Windows, Mac, Linux and Android (Termux).

## 🚀 Install

```bash
npm install -g hridaya-os
```

```bash
hridaya
```
---

## 🖥️ Application Management

> Fix common application errors in seconds — no searching through forums.
> ⚠️ Windows only | 🔒 Official links only — no cracks, no piracy.

```text
scan app photoshop.exe      → check application requirements
fix app photoshop.exe       → show what's missing + fix links
fix error msvcp140.dll      → common DLL fix
list apps                   → 18 supported applications
```

**18 Supported Applications** — Adobe Photoshop, Premiere Pro, Illustrator,
After Effects, AutoCAD, Autodesk 3ds Max, Microsoft Word, Microsoft Excel,
VLC Media Player, OBS Studio, Visual Studio Code, 7-Zip, WinRAR,
HandBrake, Blender, Discord, Spotify and Zoom.

---

## 🎮 Game Management
> Fix DLL errors in seconds — no YouTube, no ChatGPT detours.
> ⚠️ Windows only | 🔒 Official links only — no cracks, no piracy.

```
scan my system              → full PC game-readiness check
scan game gta_sa.exe        → check all requirements
fix game gta_sa.exe         → show what's missing + fix links
fix error d3dx9_43.dll      → instant DLL fix
fix error 0xc000007b        → error code fix
fix all games               → fixes 90% of errors in one go
check directx               → DirectX version + legacy runtime
check visual c++            → all VC++ versions
list games                  → 36 supported games
what games can i play       → check which supported games will run
```

**36 Supported Games** — GTA series, NFS, Max Payne, CS, Minecraft, Valorant,
Witcher, Assassin's Creed, Batman Arkham, RDR2, Cyberpunk, Elden Ring, PUBG,
Fortnite, FIFA, Rocket League, Hogwarts Legacy, Mortal Kombat 11 and more.

---

## 💿 Disk Management

```
show disk space                      → all drives with usage bars
what's taking up space               → largest folders ranked
how much space is downloads using    → specific folder size
find duplicate files                 → finds wasted space
clean temp files                     → safely deletes junk
empty recycle bin                    → instant cleanup
save disk report                     → saves .txt report
warn me when disk goes below 5GB     → background watcher
start disk history                   → tracks over time
show larger files                    → find files over 1GB
```

---

## 💾 Memory Management

```
what's eating my memory              → top RAM hungry apps
kill whatever is eating my RAM       → kills heaviest process
show memory usage                    → total, used, free
save memory report                   → saves .txt report
compare chrome and discord memory    → side by side
warn me when RAM goes above 80%      → background watcher
start memory history                 → tracks every 60 seconds
system info                          → OS, CPU, cores, uptime
kill chrome                          → kill a specific application
list running processes               → list all active processes
```

---

## 📁 File Management

```
create a folder named projects
delete the folder named old
copy file notes.txt to backup/notes.txt
move folder work to archive/work
arrange my files                     → auto sorts images, videos, code
create 3 folders named a, b, c
read the file notes.txt
write Hello World to notes.txt
list all files
open notes.txt
hide notes.txt
unhide notes.txt
show hidden files
search for notes.txt
how big is notes.txt
count files
clear folder projects
go to downloads
zip projects
unzip projects.zip

```

---

## 🚀 Project Scaffolding

```
create a react app named myapp
create a next.js project named blog
create an express app named api
create a django project named site
create a node project named tool
create a spring boot app named svc
create a vite app named myapp
create a fastapi project named api    
create a nestjs project named backend   
create a flutter app named myapp
create a react native app named myapp

```

---

## 🗂️ Project Structure

```
hridaya-os/
├── index.js         ← CLI entry point
├── parser.js        ← Understands natural language
├── fileSystem.js    ← File & folder management
├── memory.js        ← Memory management
├── disk.js          ← Disk management
├── game.js          ← Game management
├── gameDB.js        ← Game requirements database 
├── app.js           ← Application management 
├── detector.js      ← Real-Time Detection Engine
├── appDB.js         ← Application requirements database 
├── scaffolder.js    ← Project scaffolding
└── package.json     ← Project configuration
```

---

## 🗺️ Roadmap — v5.x.0 Continuous Improvement

### ✅ v5.0.0 — Real-Time Detection Engine
> Upgrading Game + App Management from database matching to actual system detection.

| What | How |
|------|-----|
| `scan installed games` | Scans Steam, Epic, Rockstar, EA, Ubisoft + common game paths |
| `scan installed apps` | Finds installed desktop apps and software across your PC |
| `real scan gta_sa.exe` | Finds exact install path → tests real system & game DLLs |
| `detect launchers` | Shows all game launchers installed on your PC |
| `real scan photoshop.exe` | Finds actual install path → tests real system & apps DLLs |

### ✅ v5.1.0 — Smart Game & Multi-Drive Engine (Current Release)
- **Multi-Drive Scanning:** Automatically finds games on secondary drives (`D:\`, `E:\`, `F:\`) — no manual path setting needed.
- **Standalone & Cracked Game Support:** Now detects classic and direct-installed games (GTA series, old PC games, non-launcher titles).
- **Smarter Launcher Detection:** Instantly finds Steam, Epic Games, Rockstar, EA, and Ubisoft even if installed in custom folders.
- **Multi-Library Steam Support:** Auto-scans all your Steam library folders across every connected SSD/HDD.
- **Expanded Coverage:** Game database expanded to 51+ titles and 100+ common missing DLL error fixes.

### ✅ v5.1.1 — System App Engine Patch
- **Engine Hotfix:** Fixed app detection scanner for deep subfolder structures and multi-drive installations.
  
### v5.2.0 — Application Management Expansion
- More software supported (Adobe CC full suite, Autodesk full suite)
- Microsoft Office deep fix support
- Visual Studio / JetBrains IDE support

### v5.3.0 — Project Scaffolding Expansion
- More frameworks: SvelteKit, Astro, Remix, Bun
- Mobile: Expo, Capacitor
- Backend: Hono, Elysia, tRPC
- Full-stack templates: T3 Stack, MERN, MEAN

### v5.4.0 — Cross-Platform Polish
- Better Mac/Linux support for all phases
- Termux (Android) improvements
- Unified experience across all platforms

---

## ⭐ Support Hridaya OS

If Hridaya OS helps you, you can support the project in two ways:

⭐ Star the project on GitHub
https://github.com/Mohith933/HridayaOS

▶️ Subscribe on YouTube for new features, tutorials and release updates.
https://www.youtube.com/@mohithsaib

Bug reports and feature requests are always welcome.

---

Made with Mohith Sai ❤️ — Hridaya OS — a terminal that speaks human!
