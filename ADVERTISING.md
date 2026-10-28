# 📣 Notchy — Promotional & Advertising Kit

> High-converting marketing copy, social media launch threads, community posts, and video scripts for **Notchy (Dynamic Island for Windows)**.

---

## 🎯 1. Value Proposition & Core Hooks

### The Core Problem:
Windows users love the glanceable, contextual convenience of Apple's Dynamic Island, but third-party Windows alternatives are typically:
- Bloated Electron apps consuming 400MB+ of RAM and causing fan noise.
- Sluggish with noticeable mouse delay and laggy window resizing.
- Buggy, intrusive, popping up accidentally when switching browser tabs.
- Cluttered with ugly borders and non-native visuals.

### The Notchy Solution:
**Notchy** brings a butter-smooth, beautifully integrated Dynamic Island to Windows 10 & 11:
- **Rust + Svelte 5 engine (Tauri v2)**: Consumes only ~1% CPU and <70MB RAM.
- **Lock-Free low-level hooks**: 0ms input lag, zero stutter.
- **Seamless Frameless Design**: Soft ambient diffusion shadows that blend naturally into any desktop.
- **Ergonomic hover**: 90ms intent filter avoids accidental triggers when clicking browser tabs.
- **Full Productivity Stack**: Synced live lyrics, universal media controls, interactive notifications, clipboard manager, Pomodoro timer, hydration reminders, and temporary drag-and-drop file shelf.

---

## ⚡ 2. Taglines & One-Liners

### English
- **Punchy**: *"Your Windows laptop didn't come with a Dynamic Island? Now it does."*
- **Feature-focused**: *"Glanceable lyrics, instant notifications, and productivity tools — zero bloat."*
- **Performance-focused**: *"The macOS Dynamic Island experience, engineered natively for Windows in Rust & Svelte 5."*
- **Minimalist**: *"Smart. Subtle. Right at the top of your screen."*

### Bahasa Indonesia
- **Slogan Utama**: *"Laptop Windows-mu nggak punya Dynamic Island? Sekarang punya — lebih cerdas dan super enteng."*
- **Slogan Produktivitas**: *"Lirik lagu real-time, clipboard history, dan timer fokus tepat di ujung layar tanpa bikin laptop panas."*
- **Slogan Developer**: *"Bukan aplikasi Electron yang makan RAM 1 GB. Notchy dibangun dengan Rust & Svelte 5 — CPU cuma ~1%."*

---

## 🧵 3. Twitter / X Launch Thread

**Tweet 1 (The Hook):**
> Windows laptops don't have a Dynamic Island.
>
> So we built one that actually feels native, runs at 60fps, and consumes less than 1% CPU. 🏝️⚡
>
> Meet **Notchy v0.2.3** — your new productivity hub for Windows 10 & 11.
>
> 🧵👇 [Attach: 10s demo GIF / video showing notch expanding smoothly on hover]

**Tweet 2 (Media & Lyrics):**
> 🎵 Universal Media Controls + Live Synced Lyrics
>
> Works seamlessly with Spotify, YouTube, Apple Music, and browser playback.
>
> The notch tints to your album artwork and streams karaoke-style lyrics line-by-line while you work — even when tucked!

**Tweet 3 (Interactive Notifications & Tools):**
> 🔔 No more distracting banner popups.
>
> WhatsApp, Slack, Teams, and Outlook notifications arrive subtly right in the island. Clicking a card jumps directly into your message.
>
> Plus: Pomodoro timer, hydration tracker, to-do list, and an app launcher built right in.

**Tweet 4 (Productivity Shelf & Clipboard):**
> 📋 Clipboard History + 📁 File Shelf
>
> - Copy any text or image snippet with instant micro-confirmation.
> - Drag files from File Explorer into the shelf to park them temporarily while switching apps. No more messy desktop clutter.

**Tweet 5 (Tech Stack & Performance):**
> 🦀 Why does it feel so fast?
>
> Built with @TauriApps v2, Rust (windows-rs), and @SvelteSociety 5 Runes.
>
> - Zero mutex locking in mouse hooks (atomic primitives).
> - 90ms intentional hover cushion (no accidental tab popups).
> - 100% private, no tracking, completely open source.

**Tweet 6 (Call to Action):**
> Ready to upgrade your Windows desktop?
>
> 📦 Download the portable installer (.exe) for free:
> 🔗 https://github.com/RamantyaDS/Notchy/releases/latest
>
> ⭐ If you love it, drop a star on GitHub!

---

## 👾 4. Reddit Community Showcase

**Recommended Subreddits**: `r/windows`, `r/software`, `r/pcmasterrace`, `r/rust`, `r/sveltejs`

**Title Options**:
- `[Free & Open Source] I built a lightweight Dynamic Island for Windows in Rust & Svelte 5 — Meet Notchy v0.2.3`
- `Tired of heavy desktop widgets? We built a native Dynamic Island for Windows using Tauri v2 (uses ~1% CPU)`

**Post Body**:
```markdown
Hey everyone! 👋

I’ve always loved the glanceable utility of macOS Dynamic Island, but every existing Windows implementation I tried was either:
1. An Electron app that ate 400MB of RAM and caused fans to spin.
2. Clunky and kept popping up every time I tried to click a browser tab.
3. Buggy with delayed media controls.

So we built **Notchy** — a sleek, native Dynamic Island designed specifically for Windows 10 & 11.

### 🚀 What makes Notchy different?
- **Ultra-lightweight engine**: Powered by Tauri v2, Rust (`windows-rs`), and Svelte 5 Runes. It sits at ~1-2% CPU and under 70MB RAM.
- **Smart Ergonomic Hover**: Added a 90ms intentional hover filter so your cursor casually flying over tabs won't trigger unwanted expansions.
- **Lock-Free Low-Level Hooks**: Win32 mouse/keyboard hooks rewritten using atomic primitives for zero input latency.
- **Frameless Ambient Look**: No ugly solid borders; it features soft diffuse shadows that blend into dark and light desktop wallpapers.

### 🧰 Key Features:
- 🎵 **Universal Media Player**: Spotify, YouTube, Chrome, Apple Music. Shows album art color-tinting and **live synced karaoke lyrics** right in the notch.
- 🔔 **Interactive Notification Mirror**: WhatsApp, Teams, Slack, Outlook. One click jumps to that exact chat.
- ⏱️ **Productivity Tools**: Pomodoro timer, water reminder, to-do list, and quick app shortcuts.
- 📋 **Clipboard Manager**: Micro-feedback copy alerts and text vs. image snippet tags.
- 📁 **Drop Shelf**: Park files at the top of your screen to drag between full-screen apps.
- 🫥 **Screen Etiquette**: Tucks into a hairline when near tabs, hides in full-screen games/movies, and goes to sleep when idle.

It is 100% free, private (zero telemetry, all data stays in `%APPDATA%`), and open-source.

🔗 **GitHub Repo & Download**: https://github.com/RamantyaDS/Notchy/releases/latest

Would love to hear your feedback, bug reports, or feature requests!
```

---

## 🏆 5. Product Hunt Launch Kit

- **Name**: Notchy
- **Tagline**: The lightweight Dynamic Island for Windows 10 & 11
- **Topics**: Windows, Productivity, Open Source, Audio & Music, Developer Tools
- **Pricing**: Free / Open Source

**Maker's First Comment**:
```text
Hey Product Hunt! 🚀

I'm thrilled to introduce Notchy v0.2.3 — the intelligent Dynamic Island for Windows.

We wanted desktop widgets to feel natural rather than distracting. Instead of building another heavy Electron container, we engineered Notchy using Tauri v2, Rust, and Svelte 5. The result? A smooth, 60fps experience that stays below 1% CPU utilization while idling at the top of your screen.

Whether you want live karaoke lyrics while programming, quick clipboard history, or a seamless place to park files while dragging them across apps, Notchy is designed to stay out of your way until you need it.

Key features:
✨ Synced lyrics for Spotify & YouTube
✨ Interactive notification mirroring (WhatsApp, Teams, Slack)
✨ Clipboard history & drag-and-drop file shelf
✨ Pomodoro timer & hydration reminders
✨ 100% offline-first & private

We'd love for you to try it out! Grab the Windows installer on GitHub and let us know what you think! 🏝️
```

---

## 🇮🇩 6. Salinan Komunitas Indonesia (Facebook, Discord, Telegram, LinkedIn)

### Varian 1: Casual & Relatable (Cocok untuk Discord WPU / Koding Indonesia / Komunitas IT)
> **Halo temen-temen! Mau share project open-source seru nih 🏝️✨**
>
> Sering ngerasa bagian atas layar laptop Windows rada ngebosenin atau pengen punya fitur kayak Dynamic Island di Mac tapi takut laptop jadi lemot?
>
> Kenalin **Notchy** — aplikasi Dynamic Island untuk Windows 10 & 11 yang super enteng dan fungsional!
>
> **Kenapa wajib coba?**
> - ⚡ **Super Ringan**: Dibangun pakai **Rust + Svelte 5 (Tauri v2)**, pemakaian CPU cuma ~1% dan RAM minim banget (bukan Electron yang rakus memori!).
> - 🎵 **Lirik Berjalan (Synced Lyrics)**: Dengerin Spotify/YouTube, lirik lagunya otomatis jalan baris demi baris di notch.
> - 📋 **Clipboard History & File Shelf**: Simpen riwayat copy teks/gambar dan tempat naruh file sementara buat drag-and-drop.
> - ⏱️ **Fitur Produktivitas**: Timer Pomodoro, pengingat minum air, to-do list, dan pintasan aplikasi.
> - 🛡️ **Ergonomis**: Nggak bakal kaget kebuka sendiri pas klik tab browser karena ada filter jeda 90ms.
>
> 100% gratis, open-source, dan aman tanpa registrasi akun.
>
> 📥 **Download installer .exe**:
> 👉 https://github.com/RamantyaDS/Notchy/releases/latest
>
> Monggo dicoba dan kasih masukan ya! Kalau suka, jangan lupa tinggalkan ⭐ di GitHub-nya! 🙏

---

### Varian 2: Professional / Tech Showcase (Cocok untuk LinkedIn)
> **Engineering a High-Performance Dynamic Island for Windows using Rust & Svelte 5 🦀⚡**
>
> Most desktop utility widgets for Windows struggle with two main trade-offs: high memory footprint (often built on Chromium/Electron) and intrusive UI behaviors that disrupt normal workflow.
>
> With **Notchy v0.2.3**, we set out to prove that desktop enhancement apps can be both visually stunning and virtually cost-free in system resources:
>
> 🔹 **Architecture**: Built on Tauri v2 with native Win32/WinRT bindings in Rust (`windows-rs`), combined with a reactive Svelte 5 frontend.
> 🔹 **Lock-Free Concurrency**: Mouse and keyboard hooks operate entirely without mutex contention using atomic primitives (`std::sync::atomic`), eliminating input stutter.
> 🔹 **Context-Aware Ergonomics**: Smart 90ms hover intention filters prevent accidental expansions when interacting with top-level browser tabs.
> 🔹 **Feature Rich**: Live media lyrics, notification routing, clipboard caching, and Pomodoro timers neatly tucked into an ambient frameless island.
>
> The project is fully open source. Check out the release here:
> 🔗 https://github.com/RamantyaDS/Notchy
>
> #Rust #Svelte #Tauri #Windows11 #OpenSource #SoftwareEngineering #UIUX

---

## 🎬 7. Short-Form Video Script (TikTok / Reels / Shorts - 35s)

**Format**: Fast-paced screen recording with background lo-fi / upbeat beat.

| Time | Visual on Screen | Voiceover / Text Overlay |
|---|---|---|
| **00:00 - 00:04** | Zoom in to boring Windows top bezel. Cursor hovers at top center -> smooth black island gracefully expands. | *"Your Windows PC doesn't have a notch? Now it does, and it's actually insane."* (Text: **Mac features on Windows? 🏝️**) |
| **00:05 - 00:11** | Spotify is playing. Notch shows album artwork color tint, and synchronized karaoke lyrics scroll line-by-line. | *"Universal music controls with synced real-time lyrics that scroll right inside the island."* |
| **00:12 - 00:18** | WhatsApp / Teams notification pops up in the notch. Click it -> chat window opens instantly. | *"Notifications drop down cleanly without messy Windows popups. One click takes you straight to the chat."* |
| **00:19 - 00:25** | Quick scroll through views: Pomodoro timer, Water reminder, Clipboard history with green '✓ Tersalin!' badge. | *"Built-in Pomodoro, water reminders, and a super fast clipboard manager."* |
| **00:26 - 00:30** | Task Manager shows CPU at 0.8% and RAM at 50MB. Cursor clicks top browser tab without triggering notch accidentally. | *"And the best part? It's built in Rust and uses less than 1% CPU. Zero lag, zero bloat."* |
| **00:31 - 00:35** | GitHub release page with download button. | *"It's 100% free and open source. Link in bio / comments! Download Notchy today."* |
