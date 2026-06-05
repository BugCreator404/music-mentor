# Visual Theory Reference

ASCII diagrams and visual aids for music theory concepts.
Reference material for the `theory.md` and `harmony.md` modules.

---

## CIRCLE OF FIFTHS

```
                    C (0)
              F (1b)   G (1#)
          Bb (2b)           D (2#)
       Eb (3b)                  A (3#)
      Ab (4b)                    E (4#)
       Db (5b)                  B (5#)
          Gb (6b/6#)       F# (6#)
              Cb (7b)   C# (7#)
                    (enharmonic)

Clockwise  = adding sharps (key of G has F#, D has F#C#, etc.)
Counter-CW = adding flats  (key of F has Bb, Bb has BbEb, etc.)
```

**Inner ring (relative minors)**:
```
C major → A minor
G major → E minor
D major → B minor
A major → F# minor
E major → C# minor
F major → D minor
Bb major → G minor
Eb major → C minor
```

**How to use it**:
- Adjacent keys share 6 of 7 notes (easy modulation)
- Keys across from each other (tritone apart) share 0 notes (dramatic modulation)
- ii–V–I always moves counterclockwise: Dm–G–C (D→G→C, each a 5th down)

---

## SCALE PATTERNS ON GUITAR FRETBOARD

### Minor Pentatonic — Position 1 (root on low E string)
```
Root = R (e.g. if R=5th fret, you're in A minor pentatonic)

e |--R--. --|--. --R--|
B |--. --R--|--. --. --|
G |--. --R--|--. --. --|
D |--. --R--|--. --. --|
A |--. --R--|--. --. --|
E |--R--. --|--. --R--|
       ↑
     root fret
```

Pattern (fret numbers relative to root):
```
e |--0--3--|
B |--0--3--|
G |--0--2--|
D |--0--2--|
A |--0--2--|
E |--0--3--|
```

### Major Scale — Position 1 (CAGED: open C position)
```
e |--0--1--3--|
B |--0--1--3--|
G |--0--2--3--|  (shift: no open, use 2nd fret as reference)
D |--0--2--3--|
A |--0--2--3--|
E |--0--1--3--|
```

---

## INTERVAL RECOGNITION — SONG MNEMONICS

| Interval | Ascending song | Descending song |
|---|---|---|
| Minor 2nd (m2) | Jaws theme | Joy to the World |
| Major 2nd (M2) | Happy Birthday | Mary Had a Little Lamb |
| Minor 3rd (m3) | Smoke on the Water | Hey Jude |
| Major 3rd (M3) | When the Saints Go Marching | Goodnight Ladies |
| Perfect 4th (P4) | Here Comes the Bride | Born to Run |
| Tritone (TT) | The Simpsons theme | — |
| Perfect 5th (P5) | Star Wars main theme | Feelings |
| Minor 6th (m6) | The Entertainer | Nobody Knows |
| Major 6th (M6) | NBC chime / My Way | Nobody Knows the Trouble |
| Minor 7th (m7) | Somewhere (West Side Story) | Waterfall |
| Major 7th (M7) | Take On Me | I Love You (Cole Porter) |
| Octave (P8) | Somewhere Over the Rainbow | Willow Weep for Me |

---

## CHORD FUNCTION MAP

```
KEY OF C MAJOR:

  TONIC          SUBDOMINANT      DOMINANT
  (stable)       (away from home) (tension → resolves to I)

  I   = C maj    IV  = F maj      V   = G maj
  iii = E min    ii  = D min      vii°= B dim
  vi  = A min
```

Tension/resolution arc:
```
  I  →  IV  →  V  →  I
  (home) (leave) (tension) (resolution)
```

Common substitutions:
```
vi  substitutes for  I   (both tonic function)
ii  substitutes for  IV  (both subdominant function)
vii substitutes for  V   (both dominant function)
```

---

## MODES AT A GLANCE

All modes of C major, with characteristic note highlighted:

```
Ionian    (I):   C  D  E  F  G  A  B   → Major scale. Bright.
Dorian    (II):  D  E  F  G  A  B  C   → Minor +♮6. Hopeful minor (jazz, funk).
Phrygian  (III): E  F  G  A  B  C  D   → Minor +♭2. Dark, Spanish, flamenco.
Lydian    (IV):  F  G  A  B  C  D  E   → Major +♯4. Dreamy, floating.
Mixolydian(V):   G  A  B  C  D  E  F   → Major +♭7. Bluesy, rock, folk.
Aeolian   (VI):  A  B  C  D  E  F  G   → Natural minor. Melancholic.
Locrian   (VII): B  C  D  E  F  G  A   → Minor +♭2+♭5. Unstable, rarely tonic.
```

Characteristic intervals (what makes each mode unique):
```
Dorian:     ♮6  (raised 6th vs natural minor) → that "hopeful" minor sound
Phrygian:   ♭2  (flat 2nd) → the Spanish/flamenco flavor
Lydian:     ♯4  (raised 4th) → the dreamy, unresolved sound
Mixolydian: ♭7  (flat 7th) → the bluesy, unresolved dominant sound
Locrian:    ♭5  (flat 5th) → maximum instability
```

---

## COMMON CHORD PROGRESSIONS — QUICK REFERENCE

```
Pop/Rock (major):
  I–V–vi–IV    →  C–G–Am–F     "the axis" (hundreds of pop songs)
  I–IV–V       →  C–F–G        rock/country classic
  I–vi–IV–V    →  C–Am–F–G     50s doo-wop

Minor feels:
  i–VII–VI–VII →  Am–G–F–G     natural minor rock
  i–iv–V       →  Am–Dm–E      harmonic minor (classical)
  i–VI–III–VII →  Am–F–C–G     pop minor

Jazz:
  ii–V–I       →  Dm7–G7–Cmaj7     the fundamental motion
  I–vi–ii–V    →  Cmaj7–Am7–Dm7–G7 turnaround

Blues:
  I7–I7–I7–I7
  IV7–IV7–I7–I7
  V7–IV7–I7–V7  (12 bars total)

Flamenco:
  i–VII–VI–V   →  Am–G–F–E     Andalusian cadence
```
