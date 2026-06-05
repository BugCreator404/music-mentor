# Notation & TAB Reading Reference

Load when user pastes a TAB, asks about sheet music symbols, wants to understand
notation, or asks "what does this mean" about any written musical content.

---

## GUITAR TAB FORMAT

```
e |--0--3--5-----|
B |--1--3--5-----|
G |--0--2--5-----|
D |--2--0--5-----|
A |--3-----5-----|
E |--------------|
```

**Reading order**:
- Lines represent strings: **e B G D A E** (top = highest pitch = thinnest string)
- Numbers = fret number (0 = open string)
- Read left to right = time
- Numbers stacked vertically = played simultaneously (chord)
- Numbers in sequence = played one at a time (melody/riff)

### TAB technique symbols

| Symbol | Technique | ES | Description |
|---|---|---|---|
| `h` | Hammer-on | Ligado ascendente | Pick first note, hammer finger down for second without picking |
| `p` | Pull-off | Ligado descendente | Pick first note, pull finger off to sound lower note |
| `b` | Bend | Bend | Push string up (or down) to raise pitch |
| `b(n)r` | Bend & release | Bend y soltar | Bend to pitch n, then release back |
| `/` | Slide up | Deslizamiento ↑ | Slide finger up to target note |
| `\` | Slide down | Deslizamiento ↓ | Slide finger down to target note |
| `~` | Vibrato | Vibrato | Oscillate pitch up/down rapidly |
| `x` | Mute / dead note | Nota apagada | Touch string lightly — percussive thud |
| `<n>` | Harmonic | Armónico | Touch string lightly at fret n |
| `PM` | Palm mute | Palma | Rest palm near bridge for muted tone |
| `t` | Tap | Tapping | Use picking hand finger to tap fret |
| `wh` | Whammy/vibrato bar | Palanca | Use tremolo arm |

### Reading example with techniques:
```
e |--12b14--12--10h12--10p8--|
B |-------------------------|
```
Reading: play 12th fret, bend to 14, come back to 12, slide/play 10, hammer to 12, play 10, pull-off to 8.

---

## BASS TAB FORMAT

Same as guitar but 4 lines (E A D G, low to high):
```
G |--2--2--0-----|
D |--2--2--2-----|
A |--0--0--2-----|
E |--------0-----|
```

---

## READING SHEET MUSIC

### Staff and clef
```
Treble clef (𝄞): Used for higher-pitched instruments (guitar, violin, right hand piano)
   Lines (bottom to top): E G B D F  ("Every Good Boy Does Fine")
   Spaces (bottom to top): F A C E  ("FACE")

Bass clef (𝄢): Used for lower instruments (bass guitar, left hand piano, cello)
   Lines (bottom to top): G B D F A  ("Good Boys Do Fine Always")
   Spaces (bottom to top): A C E G  ("All Cows Eat Grass")
```

### Key signatures
Number of sharps/flats indicates the key:
```
0 sharps/flats = C major / A minor
1 sharp  (F#)  = G major / E minor
2 sharps (F#C#)= D major / B minor
3 sharps       = A major / F# minor
4 sharps       = E major / C# minor
1 flat   (Bb)  = F major / D minor
2 flats (Bb,Eb)= Bb major / G minor
3 flats        = Eb major / C minor
4 flats        = Ab major / F minor
```

### Note values (visual reference)
```
○         Whole note (redonda)     = 4 beats
♩         Half note (blanca)       = 2 beats
♩         Quarter note (negra)     = 1 beat
♪         Eighth note (corchea)    = 1/2 beat
𝅘𝅥𝅯         Sixteenth (semicorchea)  = 1/4 beat
```
**Dot** after a note = adds half its value (♩. = 1.5 beats)
**Tie** = two notes connected = hold for combined duration (don't re-attack)
**Slur** = curved line over different notes = play legato (connected)

### Dynamics
```
ppp  = pianississimo (extremely soft)
pp   = pianissimo (very soft)
p    = piano (soft)
mp   = mezzo-piano (medium soft)
mf   = mezzo-forte (medium loud)
f    = forte (loud)
ff   = fortissimo (very loud)
fff  = fortississimo (extremely loud)
<    = crescendo (gradually louder)
>    = decrescendo / diminuendo (gradually softer)
sfz  = sforzando (sudden accent)
```

### Articulations
```
.    = staccato    — short, detached (play about half value)
-    = tenuto      — hold full value, slight emphasis
>    = accent      — emphasize this note
^    = marcato     — strongly accented
tr~  = trill       — rapidly alternate with note above
```

### Tempo markings (Italian, common)
```
Largo      = very slow (40-60 BPM)
Adagio     = slow (66-76 BPM)
Andante    = walking pace (76-108 BPM)
Moderato   = moderate (108-120 BPM)
Allegro    = fast (120-168 BPM)
Vivace     = lively (168-176 BPM)
Presto     = very fast (168-200 BPM)
rit.       = ritardando (gradually slower)
accel.     = accelerando (gradually faster)
a tempo    = return to original tempo
```

---

## CHORD CHARTS & LEAD SHEETS

Format used in jazz, pop, folk — just chord symbols above lyrics or rhythm slashes.

### Reading chord symbols
```
C          = C major triad
Cm         = C minor triad
C7         = C dominant 7th
Cmaj7      = C major 7th
Cm7        = C minor 7th
Cdim / C°  = C diminished triad
Cdim7      = C diminished 7th
Cm7♭5 / Cø = C half-diminished
Csus2      = C suspended 2nd (C D G)
Csus4      = C suspended 4th (C F G)
Cadd9      = C major + 9th (C E G D)
C/E        = C major with E in bass (1st inversion)
C/G        = C major with G in bass (2nd inversion)
```

### Nashville Number System
Numbers replace chord names — works in any key:
```
1    = I (tonic)
4    = IV
5    = V
1-4-5-1 = C-F-G-C in the key of C
         = G-C-D-G in the key of G
```
Useful for: transposing quickly, communicating with musicians in different keys

### Roman numeral analysis
```
Uppercase = major chord    (I, IV, V)
Lowercase = minor chord    (ii, iii, vi)
° = diminished             (vii°)
+ = augmented
7 after = 7th chord        (V7, ii7)
♭ before = lowered         (♭VII, ♭III)
```

---

## HOW TO ANALYZE ANY PIECE OF NOTATION

### For TAB:
1. Count the lines → identify instrument
2. Read left to right, note fret numbers
3. Identify technique symbols
4. Group vertical numbers → these are chords
5. Try to identify: is this a scale run? arpeggio? chord riff? melody?
6. Look at fret positions → infer approximate key/scale

### For sheet music:
1. Read key signature → identify possible keys
2. Read time signature → understand the rhythmic framework
3. Scan for recurring patterns → motifs, phrases
4. Find the cadences → where phrases end (look for V or V7 → I motion)
5. Identify the form: verse/chorus? ABA? through-composed?

### For chord charts:
1. Identify the key (usually the first chord or the chord where things "rest")
2. Assign Roman numerals to each chord
3. Look for secondary dominants (dominant 7th chords that aren't V7 of the key)
4. Name the cadences
5. Describe what each section does emotionally
