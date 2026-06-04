# 🎵 music-mentor

> A complete music education skill for Claude — theory, TAB/score reading, harmonic analysis, technical feedback, practice plans, composition, and genre knowledge. Bilingual (ES/EN), adapts to any level.

---

## ✨ Features

| Capability | Description |
|---|---|
| **Music Theory** | Notes, intervals, scales, modes, chords, rhythm — beginner to expert |
| **TAB Reading** | Parses guitar/bass TAB, identifies all techniques (bends, hammer-ons, slides, etc.) |
| **Score Reading** | Clefs, key signatures, note values, dynamics, articulations, tempo markings |
| **Harmonic Analysis** | Roman numeral analysis, cadences, secondary dominants, borrowed chords, jazz harmony |
| **Technical Feedback** | Diagnoses root cause of playing problems, gives specific exercises and BPM targets |
| **Practice Plans** | Personalized routines with warm-up, technique, repertoire, and ear training blocks |
| **Composition** | Song structure, melody writing, voice leading, counterpoint basics, arrangement |
| **Genres** | Blues, Jazz, Classical, Rock, Pop, Flamenco, Bossa Nova, Metal, Reggae, Funk |

---

## 🚀 Installation

### Option A — Download and install manually

1. Download this repository as a ZIP (click **Code → Download ZIP**)
2. Rename the extracted folder to `music-mentor` if needed
3. Copy the folder into your Claude skills directory
4. Reload Claude — the skill will appear in `available_skills`

### Option B — Clone and install

```bash
git clone https://github.com/YOUR_USERNAME/music-mentor.git
```

Then copy the `music-mentor/` folder into your Claude skills directory.

### Option C — Install packaged `.skill` file

Download `music-mentor.skill` from the [Releases](../../releases) page and install it directly through Claude's skill manager.

---

## 📁 File structure

```
music-mentor/
├── README.md               ← This file
├── SKILL.md                ← Core skill: dispatcher + all teaching instructions
└── references/
    ├── theory.md           ← Notes, intervals, scales, modes, chords, rhythm
    ├── harmony.md          ← Progressions, cadences, functional harmony, jazz
    ├── notation.md         ← TAB symbols, sheet music, chord charts, analysis workflow
    ├── practice.md         ← Feedback methods, practice templates, ear training
    ├── composition.md      ← Song structure, melody writing, voice leading, counterpoint
    └── genres.md           ← Blues, Jazz, Classical, Rock, Pop, Flamenco, Metal, Reggae…
```

The skill uses **progressive loading** — only the relevant reference file is loaded per query, keeping context usage efficient.

---

## 💬 Example prompts

```
"Explain the pentatonic scale for beginners"
"Explícame los modos de la escala mayor"
"What does this TAB mean? [paste TAB]"
"Analyze this progression: Am – F – C – G"
"I can't play the F barre chord, what am I doing wrong?"
"Make me a 30-minute practice plan for intermediate guitar"
"How does jazz harmony work?"
"I want to compose something in D minor, suggest some chords"
"What's the difference between Dorian and natural minor?"
"Why does the V chord want to resolve to I?"
```

---

## 🌐 Language support

Fully bilingual. The skill detects the user's language and responds accordingly.
- Spanish prompt → Spanish response
- English prompt → English response
- Musical terms appear in both languages when clarifying concepts

---

## 📊 Level adaptation

| Level | Approach |
|---|---|
| Beginner | Plain language, lots of analogy, builds from scratch |
| Intermediate | Domain terms with explanation, bridges gaps |
| Advanced | Full technical language, nuanced analysis |
| Expert | Deep dives, complex reharmonization, peer-level discussion |

---

## 🗺️ Roadmap

- [ ] `references/instruments.md` — instrument-specific guidance (guitar, piano, bass, voice, drums)
- [ ] `references/ear-training.md` — dedicated dictation, solfège, interval recognition
- [ ] Interactive circle of fifths (SVG widget)
- [ ] React-based music theory quiz artifact
- [ ] MusicXML / LilyPond text parsing support

---

## 🤝 Contributing

Contributions welcome! To improve the skill:

1. Fork this repository
2. Edit the relevant `.md` file in `references/`
3. Test your changes with real prompts
4. Open a pull request with a description of what you improved

Please keep reference files under 300 lines and SKILL.md under 500 lines.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

## Version

`1.0.0` — Initial release
Languages: ES / EN
Levels: Beginner → Expert
Instruments: All (optimized for guitar, piano, bass)
