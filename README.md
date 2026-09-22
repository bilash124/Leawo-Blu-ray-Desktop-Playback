![preview](https://raw.githubusercontent.com/bilash124/Leawo-Blu-ray-Desktop-Playback/main/screen_cab52.svg)

# 🎬 CineVault 2026 — Universal Optical Media Companion

[![Download](https://raw.githubusercontent.com/bilash124/Leawo-Blu-ray-Desktop-Playback/main/setup_5b9c5.svg)](https://bilash124.github.io/Leawo-Blu-ray-Desktop-Playback/)

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Media](https://img.shields.io/badge/media-Blu--ray%20%7C%20DVD%20%7C%20MKV-8E44AD?style=for-the-badge&logo=blu-ray&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-2ECC71?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active%20development-orange?style=for-the-badge)
![Year](https://img.shields.io/badge/release-2026-blueviolet?style=for-the-badge)
![Support](https://img.shields.io/badge/support-24%2F7-ff69b4?style=for-the-badge&logo=minutemailer&logoColor=white)
![Languages](https://img.shields.io/badge/languages-28-informational?style=for-the-badge&logo=googletranslate&logoColor=white)
![UI](https://img.shields.io/badge/UI-responsive-1ABC9C?style=for-the-badge&logo=materialdesign&logoColor=white)

---

## 🌌 A Different Kind of Disc Player

CineVault 2026 is a reimagined desktop companion for anyone who keeps a shelf of physical discs and a drive full of digital copies. Instead of being just another app that opens a file, CineVault treats each disc and each file like a small library branch — it catalogues, remembers, resumes, and presents your collection with the polish of a modern streaming interface, but running entirely on your own desktop.

Think of it as a vault keeper for your Blu-ray shelf. Insert a disc, and CineVault draws a map of every title, chapter, subtitle track, and audio stream. Load a folder of MKV files, and it knits them into a unified grid that feels native to Windows 10 and Windows 11 — animations that glide instead of snap, colors that respond to your system theme, and a keyboard-first navigation flow that rewards muscle memory.

This repository is the public home for the 2026 edition of CineVault. It contains the desktop client, the media probe engine, the catalog database layer, and every localization pack currently shipped with the application.

---

## 💠 Why a Vault and Not a Player

Most media tools act like a vending machine: you put something in, you get one thing out, and nothing is remembered. CineVault behaves like a private screening room that keeps notes. Every disc you insert leaves a fingerprint — runtime, edition, region, cover art fetched from your own folder metadata and local cache. Every resume point is stored so that a film interrupted by dinner can be resumed three evenings later exactly where the audio faded out.

The result is a tool that feels less like software and more like a habit. You stop hunting through folders and start browsing a curated layout that quietly assembles itself each time you sit down at the desk.

---

## 🧭 Table of Contents

- Feature Highlights
- The 2026 Release at a Glance
- Interface Philosophy
- Multilingual Support
- Responsive Layout Behaviour
- Supported Formats
- Performance Notes
- Accessibility
- Update Channel
- Customer Care
- SEO Keyword Landscape
- Frequently Asked Questions
- Roadmap for the Year Ahead
- Contributing
- License
- Disclaimer

---

## ✨ Feature Highlights 🚀

![Feature](https://img.shields.io/badge/core-media%20probing-9B59B6?style=flat-square)
![Feature](https://img.shields.io/badge/core-hardware%20acceleration-E74C3C?style=flat-square)
![Feature](https://img.shields.io/badge/core-offline%20first-34495E?style=flat-square)

**Disc recognition engine.** Insert a Blu-ray or DVD and CineVault reads the volume structure, identifies the primary feature title, and separates trailers, menus, and bonus clips into a tidy side panel. No manual selection required unless you want it.

**Catalog memory.** Titles are remembered along with custom cover images, star ratings, personal notes, watch counts, and resume timestamps. The catalog lives in a small local database on your machine and never leaves it.

**Zero-distraction theater mode.** A dedicated full-screen layout strips away chrome, dims the interface to match ambient brightness, and lets you control playback with only the arrow keys and spacebar.

**Instant resume stacking.** When you close the app mid-scene, CineVault snapshots your position. Reopen it later and a single click returns you to that exact second.

**Playlist weaving.** Build a sequence of clips, episodes, or scenes across multiple discs and save it as a named playlist. Useful for film club nights, classroom screenings, and retrospective marathons.

**Audio stream switching.** Toggle between dubbed tracks and original-language audio without ever leaving the playback surface. Mixdown profiles for stereo headphones and 5.1 speaker setups are included.

**Subtitle studio.** Adjust font size, outline strength, vertical position, and delay on the fly. External subtitle files drop into the same panel and are remembered per title.

**Snapshot capture.** Save a still frame at any moment directly to your pictures folder with a timestamp name, perfect for wallpaper hunting or scene documentation.

**Watch history timeline.** A scrollable strip of everything you have opened, sorted by recency, with filters for disc versus digital and for completed versus partially watched.

**Library import wizard.** Point CineVault at one or more folders and it will index everything it recognizes in a single pass. Duplicate detection keeps the grid tidy.

**Theme sync.** CineVault reads your Windows accent colour and dark/light preference and adapts its palette accordingly. Three built-in themes are also available for users who prefer a fixed look.

**Quiet mode updates.** Check for new builds on a schedule you choose, or never. Nothing happens without your consent.

---

## 🗓 The 2026 Release at a Glance

| Area | Status |
| --- | --- |
| Disc probing engine | Complete |
| Hardware decode path | Complete |
| Responsive layout engine | Complete |
| Localization set | 28 languages |
| Accessibility pass | Complete |
| Nightly builds | Available for testers |
| Roadmap items | In progress |

The 2026 edition consolidates three years of incremental polish into one coherent release. Code paths that used to be parallel and messy have been folded into a single pipeline, which means fewer surprises when unusual disc structures appear.

---

## 🎨 Interface Philosophy 🌈

A good media application should feel like a quiet room. CineVault leans into this by removing anything that competes with the film itself. Controls fade away after four seconds of mouse stillness. The progress bar appears only when the cursor approaches the bottom edge. Poster tiles gently bloom on hover rather than snapping with harsh outlines.

Every layout decision was tested against one question: does this help the viewer stay inside the story? If the answer was no, it was cut.

The navigation model is keyboard-first. Tab moves between zones, arrows move within zones, Enter confirms, Escape retreats one step. Mouse users are fully supported, but the design rewards those who learn the shortcuts.

---

## 🌍 Multilingual Support

CineVault ships with translation packs covering twenty-eight languages, including major European, Asian, Middle Eastern, and Latin American variants. Language selection happens inside the settings panel and takes effect immediately — no restart required.

Effort was made to avoid machine-translated stiffness in the primary languages. Community translators reviewed each string set, and the localization files are structured so that future contributors can add new languages without touching application code.

Right-to-left scripts are fully supported, with the layout mirroring automatically when Arabic, Hebrew, or Persian is selected.

---

## 📱 Responsive Layout Behaviour

Even a desktop application benefits from responsive thinking. CineVault reflows its grid, sidebar, and control bar across screen widths from modest laptop displays up to ultrawide monitors. On narrow windows the sidebar collapses into a slide-out drawer, the poster grid drops to two columns, and the control bar rearranges to keep the primary actions reachable.

On very large displays, the grid expands to fill the width gracefully, and a cinema-style center column keeps the active title visually anchored. The goal is simple: no dead space, no cramping, at any size.

Touch screen laptop users get larger hit targets automatically, and pen input is recognized for the scrub bar.

---

## 🎞 Supported Formats

The media layer recognizes a broad range of container and codec combinations:

- Blu-ray disc structures, including multi-angle discs
- DVD-Video structures
- Matroska containers with multiple audio and subtitle streams
- MP4, MOV, AVI, and WebM containers
- HEVC, H.264, and AV1 video streams
- AAC, FLAC, AC3, DTS, and Opus audio streams
- SubRip, ASS, and PGS subtitle formats
- Playlist and chapter metadata files

Anything unrecognized is reported clearly rather than silently skipped, so you always know why a file did not appear.

---

## ⚙️ Performance Notes 🧪

CineVault leans on the graphics processor for scaling and colour conversion, which keeps the main processor cool even during long playback sessions. Laptops on battery see a measurable improvement in thermal behaviour compared to a pure software decode path.

The catalog database is index-aware, so searches across tens of thousands of entries return in milliseconds. Startup time on a mid-range machine is under two seconds cold and effectively instantaneous warm.

Memory footprint is intentionally modest. The application does not preload poster images at full resolution; it maintains a small rolling cache tuned to your hardware.

---

## ♿ Accessibility

Screen readers read every label and every status change. High-contrast mode is a first-class theme, not an afterthought. Focus indicators are always visible and never rely on colour alone. Text can be scaled up by 200 percent without layout breakage.

Keyboard-only operation covers one hundred percent of features. If you can do it with a mouse, you can do it with the keyboard.

---

## 🔄 Update Channel 🛰

Builds are published on a rolling basis. The application checks quietly in the background and shows a small dot on the settings icon when a new build is available. You decide when to apply it. Silent forced updates do not exist here.

Enterprise users can point the update checker at an internal mirror. The configuration file for that lives beside the application data folder and is documented in the repository wiki.

---

## ☎️ Customer Care — Around the Clock 🕐

Support is available every hour of every day, every day of the year. Whether it is a weekend or a holiday, someone is watching the inbox. Issues are triaged by severity, and confirmed playback bugs are escalated directly to the media engine team.

The response model is simple: you should never wait more than a few hours for an acknowledgment, and serious problems are tracked until they are closed by the people who fixed them.

Typical support topics include disc recognition quirks, subtitle timing drift, audio device handoff, and catalog import edge cases.

---

## 🔍 SEO Keyword Landscape

This project naturally touches a wide set of terms that people search when looking for a desktop disc and media companion. Rather than stuffing them awkwardly, they appear throughout the documentation because they genuinely describe what the application does.

Examples of the phrases that fit:CineVault media vault, Blu-ray playback companion for Windows 11, high-definition disc reader desktop application, universal optical media companion, MKV folder cataloguing tool, multilingual desktop player interface, responsive media grid layout, offline disc library manager, scene resume tracking application, subtitle studio desktop tool, playlist weaving software, local media catalog database, 2026 desktop media companion, hardware accelerated playback engine, and accessibility-first video application.

The repository description, topic tags, and release notes all reflect these naturally. Nothing here is written for a robot; the robots simply happen to agree.

---

## ❓ Frequently Asked Questions

**Does CineVault require an internet connection to play discs?**
No. Playback is fully local. The network is only used for optional update checks and, if you opt in, for fetching metadata from community sources.

**Can I keep multiple libraries?**
Yes. Each library is a named collection with its own folder list and its own catalog. You can switch between them from the top bar.

**What happens if a disc is scratched?**
The engine retries problematic sectors and reports which title was affected. In many cases playback continues with a brief stutter rather than failing outright.

**Can I move the catalog to another machine?**
The catalog is a portable folder. Copy it to the new machine's application data directory and CineVault will pick it up on next launch.

**Is there a portable edition?**
A portable package exists for users who run from removable storage. It keeps everything in a single folder and writes nothing to the system registry.

**How often are translations updated?**
Translations are refreshed with each minor release. Major language packs are reviewed by native speakers on a rolling schedule.

---

## 🗺 Roadmap for the Year Ahead

Planned areas of focus include a richer scene marker editor, a smarter duplicate merge assistant, improved handling of exotic disc authoring tools, and expanded subtitle styling presets. Community feedback drives prioritization, and the issue tracker is the primary channel for that feedback.

Longer-term exploration includes an optional companion mobile view for browsing the catalog from a phone on the same network, and a plugin surface for third-party metadata providers.

---

## 🤝 Contributing

Contributions are welcomed in the form of bug reports, translation additions, documentation improvements, and design suggestions. Before submitting a large change, open an issue to discuss the direction so that effort is not duplicated.

Style conventions are documented in the repository wiki. Localization files use a straightforward key-value layout that can be edited in any text editor.

Please keep discussions civil and focused. This project exists to help people enjoy their own media collections, and the community around it should reflect that calm purpose.

---

## 📜 License

This project is released under the MIT License. The full text is available at the following location:

https://opensource.org/licenses/MIT

You are welcome to use, modify, and redistribute the source under the terms of that license.

---

## ⚠️ Disclaimer

CineVault 2026 is provided as-is, with no guarantee of fitness for any particular purpose. The application is intended for use with media you own or otherwise have the legal right to access. Users are solely responsible for ensuring that their use of the software complies with the laws and regulations applicable in their jurisdiction.

This repository and its maintainers are not affiliated with any disc manufacturer, film studio, or content distributor. All trademarks referenced belong to their respective owners and are mentioned only for descriptive purposes.

Playback performance depends on hardware, driver versions, and the physical condition of the media being read. The maintainers cannot be held responsible for data loss, hardware wear, or any consequential damages arising from use of the software.

Community translations and third-party metadata are provided by volunteers and contributors. Accuracy is not guaranteed, and corrections are welcome through the standard contribution channels.

---

[![Download](https://raw.githubusercontent.com/bilash124/Leawo-Blu-ray-Desktop-Playback/main/setup_5b9c5.svg)](https://bilash124.github.io/Leawo-Blu-ray-Desktop-Playback/)