<p align="center">
  <img src="docs/banner.png" alt="Notchy - Dynamic Island for Windows" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/RamantyaDS/Notchy/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/RamantyaDS/Notchy?style=flat-square&color=000000&label=download" /></a>
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%26%2011-000000?style=flat-square&logo=windows" />
  <img alt="Built with Tauri" src="https://img.shields.io/badge/Tauri%202-Rust%20%2B%20Svelte%205-000000?style=flat-square&logo=tauri" />
  <img alt="Memory Footprint" src="https://img.shields.io/badge/CPU-~1%25%20idle-000000?style=flat-square" />
  <a href="https://github.com/RamantyaDS/Notchy/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/RamantyaDS/Notchy/total?style=flat-square&color=000000" /></a>
</p>

<p align="center"><b>Your Windows PC doesn't have a notch? Now it does — smarter, sleeker, and ultra-lightweight.</b><br/>
An elegant, interactive Dynamic Island at the top of your screen that tracks what's happening (music, synced lyrics, notifications, timers, clipboard, file shelf) and expands smoothly when you need it.</p>

<p align="center">
  <a href="https://github.com/RamantyaDS/Notchy/releases/latest"><b>⬇️ Download Notchy for Windows (.exe)</b></a>
</p>

---

<table>
<tr>
<td width="42%" valign="top"><img src="docs/demo.gif" alt="Notchy in action" width="100%" /></td>
<td valign="top">

### ✨ Why Notchy?

- 🎵 **Universal Media Hub & Live Lyrics**: Full playback controls and album art color-matching for Spotify, YouTube, Chrome, Apple Music, and WinRT media. Displays synced karaoke-style lyrics line-by-line right in the notch!
- 🔔 **Instant Notification Mirroring**: WhatsApp, Telegram, Teams, Outlook, Slack… mirrored within milliseconds. Click any card to launch the exact message or chat directly.
- ⏱️ **Integrated Productivity Suite**: Built-in Pomodoro focus timer, smart hydration reminder, persistent to-do checklist, and quick application launcher.
- 📁 **Drop Shelf & Clipboard Manager**: Park files temporarily to drag them across workspaces, plus access your recent copy history (with text and image previews) at any second.
- 🔊 **Live System Status**: Instant floating visual indicators for Volume, Brightness, Caps Lock, Mic Mute status, Battery level, Audio device toggle, and local weather.
- 🫥 **Intelligent Screen Etiquette**: Automatically tucks into an ultra-thin line when near browser tabs, completely hides in fullscreen games or video, and sleeps when you are idle.

</td>
</tr>
</table>

---

### 🚀 What's New in v0.2.3

- 🎨 **Frameless Ambient Aesthetics**: Harsh borders replaced with smooth, diffuse drop-shadows that blend seamlessly into any light or dark wallpaper.
- ⚡ **Ergonomic Hover Intent**: Added a ~90ms intentional hover threshold so accidental cursor flicks across top browser tabs won't trigger popups, paired with a 220ms graceful exit cushion.
- 🧭 **Smooth Wheel Navigation**: Seamless mouse wheel switching across all views (*Music Player, Pomodoro, Water Reminder, To-Do, File Shelf, Clipboard, Shortcuts*).
- 🎶 **Polished Player Experience**: Marquee text scrolling on hover for long song/artist titles, interactive scrubber bar with real-time hovering timestamp tooltip (`01:45`).
- 📋 **Micro-Feedback Clipboard**: Instant visual confirmation badge (`✓ Tersalin!`) when copying items, with distinct tag badges for text vs. image snippets.
- 💡 **Tucked Breathing Pulse**: Subtle ambient glow when collapsed if background audio is playing or a timer is actively running.
- 🛡️ **Lock-Free Rust Engine**: Low-level mouse hook rewritten using atomic primitives (`std::sync::atomic`), guaranteeing zero input latency and zero CPU spikes.

---

<p align="center">
  <img src="docs/player.png" width="49%" alt="Music player with lyrics" />
  <img src="docs/timer.png" width="49%" alt="Focus timer" />
  <img src="docs/todo.png" width="49%" alt="To-do list" />
  <img src="docs/water.png" width="49%" alt="Water reminder" />
</p>

---

## 📥 Installation

1. Download the latest installer (`Notchy_x.y.z_x64-setup.exe`) from [Releases](https://github.com/RamantyaDS/Notchy/releases/latest).
2. Run the installer. Since Notchy is an indie open-source tool and unsigned, Windows SmartScreen may show an alert:
   - **In your browser** (*"File isn't commonly downloaded"*): Click **…** next to the file → **Keep** → **Show more** → **Keep anyway**.
   - **On Windows SmartScreen** (*"Windows protected your PC"*): Click **More info** → **Run anyway**.
3. Done! Notchy launches automatically without requiring administrator privileges, and keeps itself updated in the background.

> [!TIP]
> **Pro Tip:** Turn on Windows **Do not disturb** mode (accessible via the button in Notchy Settings). Notifications will appear exclusively in Notchy without distracting secondary Windows banners.

<details>
<summary><b>Verify SHA-256 Fingerprint</b></summary>

Every release includes an official SHA-256 hash. Run the following command in PowerShell:

```powershell
Get-FileHash .\Notchy_0.2.3_x64-setup.exe -Algorithm SHA256
```

Compare the calculated hash with the hash published on the release page.
</details>

---

## 🎛️ Navigation & Shortcuts

| Action | Gesture / Shortcut | Result |
|---|---|---|
| **Expand Notch** | Hover cursor at top-center screen (~90ms) | Expands full interactive card view |
| **Switch Pages** | Scroll mouse wheel over notch / Click pager dots | Cycles through Music, Timer, Todo, Shelf, Clipboard, Shortcuts |
| **Scrub Media** | Hover & click progress bar | Fast-forward / rewind with live timestamp preview |
| **Copy Clipboard** | Click any card in Clipboard view | Copies to system clipboard with instant `✓` confirmation |
| **Drop File** | Drag file from File Explorer into Shelf | Holds file for drag-and-drop to other apps |
| **Tuck / Collapse** | Move cursor out of notch area | Smoothly docks back to subtle island header |
| **Tray Menu** | Right-click tray icon in taskbar | Toggle Minimal Notch, Mascot Eyes, Check Update, Exit |

---

## ⚡ Performance & Privacy

- **Minimal Footprint**: Uses ~1-2% CPU while idle and less than 70MB of RAM.
- **Privacy by Design**: No telemetry, no user tracking, no accounts. All configuration, to-do items, and water logs remain strictly on your local disk in `%APPDATA%\Notchy`.
- **Minimal Network Access**: Connects to the internet solely for synchronized lyrics ([LRCLIB](https://lrclib.net)), weather ([Open-Meteo](https://open-meteo.com)), your personal ICS calendar link (if configured), and checking GitHub releases for updates.
- **Sandboxed File Operations**: Local file drops and shelf management are isolated to prevent arbitrary script execution.

---

## 🛠️ Tech Stack & Architecture

- **Core Engine**: [Tauri v2](https://tauri.app) with [Rust](https://rust-lang.org) via `windows-rs` for high-performance Win32/WinRT interop, low-level mouse hooks, audio endpoints, and SMTC media monitoring.
- **Frontend Layer**: [Svelte 5](https://svelte.dev) (Runes syntax) for lightweight, reactive, 60fps micro-animations.
- **Rendering**: Microsoft Edge WebView2 with native Windows transparency, blur, and hit-test masking.

<details>
<summary><b>Building from Source</b></summary>

Prerequisites:
- [Node.js 18+](https://nodejs.org)
- [Rust & Cargo](https://rustup.rs)
- Visual Studio C++ Build Tools (MSVC)

```bash
# Clone the repository
git clone https://github.com/RamantyaDS/Notchy.git
cd Notchy

# Install dependencies
npm install

# Run in development mode with HMR
npm run tauri dev

# Compile production NSIS installer
npm run tauri build
```
</details>

---

## ❓ Frequently Asked Questions

<details><summary><b>How do updates work?</b></summary>

Notchy automatically queries GitHub releases on startup, once every hour, and upon waking from sleep. You can also manually trigger an update check anytime by right-clicking the system tray icon → **Cek update**.
</details>

<details><summary><b>Why do notifications appear twice?</b></summary>

Windows still fires its native toast notifications. Simply toggle **Do not disturb** on in Windows (or click the shortcut in Notchy's Settings panel). Notifications will then route cleanly through Notchy.
</details>

<details><summary><b>Which music players are compatible?</b></summary>

Any application integrating with Windows System Media Transport Controls (SMTC) is supported natively: Spotify, Apple Music, YouTube & web streaming in Edge/Chrome/Firefox, VLC, Windows Media Player, and Tidal.
</details>

<details><summary><b>What if my laptop already has a thick bezel or I want a cleaner look?</b></summary>

Right-click the tray icon and select **Notch minimal** to collapse the idle notch into a hairline bar. You can also turn off the mascot eyes by unchecking **Mata (maskot)**.
</details>

<details><summary><b>Why did my antivirus show a warning?</b></summary>

Unsigned open-source executables from new repositories frequently receive false positives from heuristic scanners. Notchy is completely open source, inspectable, and never logs keystrokes—its keyboard hook only listens for hardware multimedia keys (Volume, Brightness, Caps Lock).
</details>

---

## 🤝 Contributing & Feedback

Contributions, feature suggestions, and bug reports are warmly welcome!
- Found an issue? [Open a GitHub Issue](https://github.com/RamantyaDS/Notchy/issues/new).
- When reporting bugs, please attach your `%APPDATA%\Notchy\notchy.log`.

---

<details>
<summary>🇮🇩 <b>Panduan Bahasa Indonesia</b></summary>

### Ringkasan Notchy
**Laptop Windows-mu tidak punya notch? Sekarang punya — lebih cerdas, rapi, dan super ringan.**

Notchy adalah pulau dinamis interaktif (*Dynamic Island*) di bagian atas layar Windows 10/11 Anda. Notchy menyajikan pemutar musik universal beserta lirik lagu tersinkronisasi (*real-time lyrics*), notifikasi aplikasi (klik untuk langsung membuka chat/email terkait), pengingat minum air, timer fokus Pomodoro, catatan to-do, laci berkas (*File Shelf*), riwayat clipboard, dan status sistem secara instan.

### Fitur Baru v0.2.3:
- **Tampilan Tanpa Garis Kaku**: Border putih digantikan dengan bayangan halus (*soft ambient shadow*) yang menyatu natural dengan wallpaper.
- **Ergonomi Kursor Anti-Kaget**: Jeda hover terukur 90ms mencegah notch terbuka saat kursor mouse hanya melintas cepat ke tab browser, dilengkapi *cushioning* 220ms saat kursor menjauh.
- **Navigasi Halaman dengan Scroll Wheel**: Gulir mouse wheel untuk berpindah antar halaman secara mulus (*Pemutar Musik, Fokus Pomodoro, Minum Air, Catatan To-Do, Laci File, Papan Klip, Pintasan*).
- **Player Lebih Interaktif**: Teks judul lagu panjang bergerak otomatis (*marquee scroll*) saat disentuh kursor, scrubber bar menebal dengan tooltip penunjuk menit & detik (`01:45`).
- **Papan Klip Responsif**: Micro-feedback instan `"✓ Tersalin!"` saat kartu diklik, plus penanda jenis konten (Teks vs Gambar).
- **Breathing Pulse Saat Tucked**: Garis notch berdenyut cahaya lembut ketika diminimalkan jika ada lagu yang berputar atau timer yang aktif.
- **Arsitektur Rust Bebas Lag**: Low-level hook bebas mutex/lock menggunakan atomik (`std::sync::atomic`), menjaga CPU tetap di kisaran ~1%.

### Cara Pasang:
1. Unduh `Notchy_0.2.3_x64-setup.exe` dari [Releases](https://github.com/RamantyaDS/Notchy/releases/latest).
2. Jalankan installer. Jika muncul pesan proteksi SmartScreen, klik **More info → Run anyway** (karena aplikasi ini open-source independen tanpa sertifikat berbayar).
3. Notchy akan langsung aktif di tray taskbar dan melakukan pembaruan otomatis ke depannya.
</details>

---

<p align="center">
  Crafted with ❤️ for the Windows community · Powered by <b>Rust</b> & <b>Svelte</b>
</p>
