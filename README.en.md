# XSXB-Band-Samples

[中文](README.md)

Instruments made for [XSXB-Band](https://github.com/sparklecatta-lang/XSXB-Band): the author's voice, a real guzheng, suona and xiao, a public-domain sample crate, home-made record chops and G-funk synths. Everything is released under **CC0 1.0**: use, modify and sell freely, no attribution needed.

XSXB-Band downloads these on demand. Each instrument also has an `.sfz` file for SFZ samplers such as sforzando.

| ID | Name | Samples | Range | Upstream |
|---|---|---|---|---|
| `xsxb-voice` | 小宝人声 | 74 | E2–A#5 | original |
| `xsxb-voice-f` | 小宝人声 · 女声 | 53 | G#3–D6 | original |
| `xsxb-voice-beatbox` | 小宝人声 · Beatbox | 18 | — | original |
| `guzheng` | 古筝 | 34 | D2–D6 | CC0 1.0 |
| `suona-oboe` | 唢呐 · 双簧管代 | 87 | A#3–F6 | CC0 1.0 |
| `xiao` | 箫 | 56 | F3–C6 | CC0 1.0 |
| `crate-classical` | 采样盒 · 古典乐句 | 6 | — | Public domain / CC0 (per chop) |
| `crate-speech` | 采样盒 · 讲话 | 10 | — | Public domain / CC0 (per chop) |
| `crate-vocals` | 采样盒 · 人声 | 10 | B3–F#4 | CC0 1.0 (per chop) |
| `nujabes-chops` | 采样盒 · 自制爵士唱片切片 | 18 | — | original |
| `gfunk-lead` | 合成器主音 · G-funk 哼鸣 | 52 | C4–C7 | original |
| `gfunk-bass` | 合成器贝斯 · Moog 式 | 30 | C1–D#3 | original |

Every upstream source is CC0 or public domain, or was recorded / synthesised in the studio, so the processed results can be CC0 as well. Sources:

| ID | Source | Upstream licence |
|---|---|---|
| `xsxb-voice` | Recorded by the author with voice-kit | original |
| `xsxb-voice-f` | Derived from xsxb-voice (WORLD vocoder formant shift) | original |
| `xsxb-voice-beatbox` | Recorded by the author with voice-kit | original |
| `guzheng` | https://freesound.org/people/Pufermufin/sounds/396868/ | CC0 1.0 |
| `suona-oboe` | https://github.com/sgossner/VSCO-2-CE (oboe), reshaped toward a suona | CC0 1.0 |
| `xiao` | https://github.com/sgossner/VCSL (recorder), reshaped toward a xiao | CC0 1.0 |
| `crate-classical` | Wikimedia Commons recordings, see docs/SAMPLE-CRATE.md in XSXB-Band | Public domain / CC0 (per chop) |
| `crate-speech` | NASA, JFK Library, Freesound, see docs/SAMPLE-CRATE.md in XSXB-Band | Public domain / CC0 (per chop) |
| `crate-vocals` | Freesound, see docs/SAMPLE-CRATE.md in XSXB-Band | CC0 1.0 (per chop) |
| `nujabes-chops` | An original jazz phrase rendered in the studio from CC0 samples (VCSL sax, VSCO piano, Meatbass, Virtuosity ride), then aged and chopped | original |
| `gfunk-lead` | Synthesised in the studio | original |
| `gfunk-bass` | Synthesised in the studio | original |

- 48 kHz FLAC. Sustains carry loop points (in `instrument.json` and the SFZ).
- Crate chops (`crate-*`, `nujabes-chops`) carry their source tempo as `bpm`; XSXB-Band time-stretches them to the song tempo.
