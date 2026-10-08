# XSXB-Band-Samples · 小宝乐队自制音源

[English](README.en.md)

[XSXB-Band · 小宝乐队](https://github.com/sparklecatta-lang/XSXB-Band) 自己做的音源：像素小宝 (sparklecatta-lang)的人声、真古筝、唢呐和箫、公版采样库、自制唱片切片、G-funk 合成器。全部以 **CC0 1.0** 发布，可以随意使用、修改、商用，不需要署名。

工作室用到这些乐器时会自动从这里下载。也可以单独用：每件乐器有一个 `.sfz` 文件，能直接加载到 sforzando 等 SFZ 采样器里。

| ID | 名称 | 采样数 | 音域 | 上游素材 |
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

所有上游素材都是 CC0 或公有领域，或者是在工作室里录制、合成的原创内容，所以加工后的结果也可以用 CC0 发布。上游来源见下表，采样库每一条的出处、时间点和校验值见 XSXB-Band 的 `docs/SAMPLE-CRATE.md`。

| ID | 来源 | 上游许可 |
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

- 48 kHz FLAC。持续音带循环点，写在 `instrument.json` 和 `.sfz` 里。
- 采样库切片（`crate-*`、`nujabes-chops`）带原始速度 `bpm`，在 XSXB-Band 里会自动拉伸到歌曲速度。
