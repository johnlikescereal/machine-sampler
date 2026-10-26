# machine sampler

A playable copy of the operating unit from buildthemachine.commonmagic.xyz. Same drawing and colors, but every part is a working control on a 16-step drum machine. All sound is synthesized with the Web Audio API, so there are no sample files. It starts muted.

Open `index.html` through any static server:

```bash
python3 -m http.server 4317
```

| Part | Does |
|---|---|
| Keys (dinner … party) | Kick, snare, closed hat, open hat, clap, walking tom, chord stab. Taps record to the nearest step while running. Double-click clears a track. |
| start | Play/stop. |
| ops dial | Tempo, 60–180 bpm. Drag, scroll, arrow keys; click adds 5. |
| trust knob | Low-pass filter. |
| fun knob | Swing and drive. Only turns one way. |
| antenna | Radio mode: narrow, crackly band-pass. |
| speaker / mute switch | Level meter / mute toggle. |
| screen | Click for pattern, scope and level pages. |
| screws | Remove all four for bank B (8-bit voices). |

Keyboard: `1`–`7` or `A`–`J` for keys, `space` start, `M` mute.
