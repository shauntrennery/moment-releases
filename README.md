<p align="center">
  <img src="app-icon.png" width="128" height="128" alt="Moment app icon" />
</p>

<h1 align="center">Moment</h1>

<p align="center">
  <strong>Just a Moment.</strong><br />
  News, weather, sports, money, podcasts, AI summaries, and what to watch tonight.<br />
  A lightweight, privacy-first macOS menu bar app built for South Africans.
</p>

<p align="center">
  <a href="https://github.com/shauntrennery/moment-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/shauntrennery/moment-releases?label=download&style=flat-square" alt="Latest release" />
  </a>
</p>

---

## Download

Grab the latest `.dmg` from [Releases](https://github.com/shauntrennery/moment-releases/releases/latest). Requires a Mac with Apple Silicon (M1 or later).

Open the `.dmg` and drag **Moment** into your Applications folder.

---

## What's Inside

Moment ships with **12 built-in plugins** — enable only the ones you care about.

### SA News
Aggregated headlines from News24, Daily Maverick, MyBroadband, IOL, SABC News, and more. Articles are auto-categorised (Sport, Tech, Business, Politics, Crime, World, Energy) and each source can be toggled on or off.

### Weather
Current conditions, 5-day forecast, and an embedded Vox Weather video. Location is auto-detected or set to any South African city. Requires a free [WeatherAPI](https://www.weatherapi.com/) key.

### Sports
Live scores and results for **rugby** (URC, Rugby Championship, Currie Cup), **cricket** (SA20, T20 World Cup), **soccer** (PSL, Premier League, Champions League), and **Formula 1** (full race results with driver/team details). Live matches surface first, with completed and upcoming games following. Sources are individually configurable.

### Money
Live ZAR exchange rates against USD, GBP, EUR, AUD, and Bitcoin. Shows current rate, 24-hour change, and comparison against the previous business day.

### What to Watch
Trending, new, and now-in-cinemas movies and TV shows from TMDB, filtered to the South African region. Switch between views and filter by movies, shows, or both.

### Listen
South African and international radio streams and podcasts — 702, CapeTalk, 5FM, BBC World Service, The Daily, and more. Built-in audio player with adjustable playback speed (1x–2.5x). The tray icon animates while audio is playing.

### Daily Deals
Today's biggest discounts from OneDayOnly.co.za, sorted by discount percentage. In-stock items only.

### Machine Stats
Live CPU, memory, disk, and network usage. Color-coded progress bars (green → yellow → red) and per-interface bandwidth in Mbps.

### Focus Timer
Pomodoro-style work sessions with configurable work/break/long-break durations. Tracks completed sessions per day. Also supports custom countdown events (e.g. "🎄 Christmas — 290 days").

### Notes
Quick persistent notes — add, edit, and delete right from the menu bar.

### Wordle
A daily five-letter word puzzle with streak tracking, guess distribution, and stats that persist across sessions.

### AI Quick Access
A conversational AI assistant with built-in actions (Summarise, Translate, Explain, Rewrite) and optional web search. Aware of your other plugin data — ask it about the weather, latest news, or exchange rates. Supports multiple providers:

- **Apple Intelligence** — on-device, no API key, no data leaves your Mac (requires macOS 26+)
- **OpenAI**, **Anthropic Claude**, **Google Gemini** — cloud providers, bring your own API key

---

## AI Briefing

When AI is available, Moment generates a combined briefing at the top of the home screen — a short, spoken-word-ready summary of your news, weather, sports, and market data. Includes **text-to-speech** playback with word-by-word highlighting and auto-scroll.

### Text-to-Speech Engines
- **System** — built-in macOS speech synthesis
- **Piper** — offline ML-based voices (Aria, James, Luna, Marcus, and more)
- **ElevenLabs** — premium cloud TTS (requires API key)

---

## Voice Dictation

Hold-to-record dictation that transcribes and pastes text into any app.

- **Apple Speech** — fast, built-in macOS recogniser
- **Local Whisper** — offline, highly accurate, multiple model sizes (tiny → large-v3-turbo)

Includes voice activity detection, filler-word removal, and optional AI cleanup for grammar and punctuation.

---

## Settings & Customisation

- **Theme** — System, Light, or Dark
- **Per-plugin settings** — toggle sources, set refresh intervals, configure max items, enter API keys
- **Timezone** — configurable footer clock (any IANA timezone)
- **TTS & Dictation** — choose engine, voice, speed, input device, and model

All settings are stored locally. No accounts, no cloud sync, no analytics.

---

## Auto-Updates

Moment checks for updates automatically in the background. When a new version is ready you'll see a prompt to download and install. You can also check manually from the About screen.

---

## Links

- [moment.co.za](https://moment.co.za)
- [Feedback & Feature Ideas](https://moment.co.za/#feedback)
