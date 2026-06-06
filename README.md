# VoiceFlow

**Talk. It types.** VoiceFlow turns your voice into text anywhere on your Mac — in any app, any text field, with a single hotkey.

Free to download. Runs fully on your Mac.

---

## Download

[**⬇️ Download VoiceFlow for macOS**](https://github.com/hzyu-hub/VoiceFlow-Updates/releases/latest/download/VoiceFlow.dmg)

Works on both Apple Silicon (M1/M2/M3/M4) and Intel Macs. macOS 13 or later.

## Install

1. Open the downloaded `VoiceFlow.dmg`
2. Drag **VoiceFlow** into your **Applications** folder
3. Launch it from Applications

> First launch: right-click the app → **Open** to get past Gatekeeper, then grant **Microphone** and **Accessibility** permissions when prompted (Accessibility lets VoiceFlow type into other apps for you).

## How to use

1. Click into any text field — notes, chat, email, code editor, anything
2. **Hold the Fn (🌐 Globe) key** and speak naturally
3. **Release** the key — your words appear as text, right where your cursor is

Hold to talk, release to type. That's it — no account required.

## Why you'll like it

- **Fast & on-device** — speech recognition runs locally on your Mac
- **Works everywhere** — any app, any text field
- **Private by default** — your voice and text stay on your machine
- **Free** — no subscription, no sign-up
- **Auto-updates** — always get the latest version automatically

## Custom vocabulary

Teach VoiceFlow the names, jargon, and spellings you use so it gets them right every time.

Open **Settings → Vocabulary** and add your terms:

- Separate entries with commas, new lines, semicolons, or slashes
- Force a specific spelling with `alias -> Preferred Name` — e.g. `voice flow -> VoiceFlow`
- Map several spoken variants to one term with `|` — e.g. `vf | voice flow -> VoiceFlow`

## Smarter cleanup (optional)

Connect an AI model to automatically polish your dictation — punctuation, capitalization, and tidier phrasing — while respecting your custom vocabulary.

Open **Settings → Transcription → Post-processing & context** and:

1. Enter the **Base URL** and **API key** for any OpenAI-compatible service
2. Pick a **model**
3. Turn on **Post-processing (smart cleanup)**

This is entirely optional. Without it, your speech is transcribed locally and inserted as-is. With it on, your transcribed text is sent to the service you configure here for cleanup.

## Privacy

VoiceFlow processes your speech locally on your Mac. Your audio and transcripts are not uploaded anywhere by default.

If you turn on optional post-processing, your transcribed text is sent to the AI service you configure. If you also enable context-aware cleanup, VoiceFlow may additionally send details about your active window — its title, any selected text, and a screenshot of that window — to the same service to improve corrections. These features are off by default; nothing leaves your Mac unless you turn them on.

## Updates

VoiceFlow checks for new versions automatically and updates itself. You can always grab the newest build from the [Releases page](https://github.com/hzyu-hub/VoiceFlow-Updates/releases/latest).

---

*VoiceFlow is free software, shared for anyone to use.*
