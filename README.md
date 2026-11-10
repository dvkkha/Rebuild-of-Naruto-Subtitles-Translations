# Rebuild of Naruto – Subtitle Translations

This repository provides **translated subtitles** for the fan edit *Rebuild of Naruto*.

All translations are based on the revised English subtitles by **Maediem**:
👉 [Maediem/Rebuild-of-Naruto-Subtitles](https://github.com/Maediem/Rebuild-of-Naruto-Subtitles/)

Many thanks to Maediem for the improved English subtitles timed to the Rebuild cuts. This project would not be possible without them.

> ⚠️ **Disclaimer:** This project is **not affiliated with the *Rebuild of Naruto* fan edit itself** and is not responsible for it. It only provides subtitles for viewers of the Rebuild version.

---

## Available languages

| Language | Folder | File suffix | Episodes | Notes |
|---|---|---|---|---|
| 🇩🇪 German | [`ger/`](ger/) | `.ger.srt` | 73 / 73 | Jutsu names in Japanese, with a German translation in parentheses on first mention |
| 🇳🇱 Dutch | [`dut/`](dut/) | `.dut.srt` | 73 / 73 | Jutsu names in Japanese, with a Dutch translation in parentheses on first mention in each episode. With help from **Vinstaro** |
| 🇳🇱 Dutch (alternative) | [`dut-alternative/`](dut-alternative/) | `.alt.dut.srt` | 73 / 73 | Same text, but with Dutch jutsu names (*Schaduwkloon-jutsu* instead of *Kage Bunshin no Jutsu*) |

Each language folder has its own README in that language.

**Not included:** *The Last – Naruto the Movie* (S07E01), because there is no English source for it.

---

## Download

- **One language only:** download the ZIP for your language from the [Releases](https://github.com/dvkkha/Rebuild-of-Naruto-Subtitles-Translations/releases) page.
- **Everything:** *Code → Download ZIP* at the top of this page.

---

## Timing

All translations keep Maediem's **numbering and timestamps** unchanged. This means they match the **Rebuild-specific cuts**, not the original TV episodes.

For readability, lines in the Dutch version are wrapped to at most 42 characters and 2 lines. The German version keeps Maediem's original line breaks.

---

## Folder structure and file names

Every language folder uses the same season folders and file names as Maediem's English subtitles. Only the language suffix is different:

```
Rebuild of Naruto - S01E01 - Academy Days [1080p][4x3][AV1].en.srt       (English, Maediem)
Rebuild of Naruto - S01E01 - Academy Days [1080p][4x3][AV1].ger.srt      (German)
Rebuild of Naruto - S01E01 - Academy Days [1080p][4x3][AV1].dut.srt      (Dutch)
Rebuild of Naruto - S01E01 - Academy Days [1080p][4x3][AV1].alt.dut.srt  (Dutch, alternative)
```

| Season folder | Episodes |
|---|---|
| `Season 01 - Naruto` | S01E01 – S01E17 |
| `Season 02 - Naruto Gaiden` | S02E01 – S02E05 |
| `Season 03 - Kakashi Gaiden` | S03E01 – S03E03 |
| `Season 04 - Naruto Shippuden` | S04E01 – S04E23 |
| `Season 05 - Naruto Senjou` | S05E01 – S05E19 |
| `Season 06 - Itachi Shiden` | S06E01 |
| `Season 07 - Naruto Hiden` | S07E02 – S07E04 |
| `Season 08 - Naruto Next Generations` | S08E01 – S08E02 |

### Getting your player to load the subtitles

Put the `.srt` file in the same folder as the video file and give it the **same name as the video**, followed by the language suffix (e.g. `.ger.srt`). Most players (VLC, mpv, Plex, Jellyfin, Kodi …) then load it automatically.

If your video files are named differently, **rename the subtitles** to match. Tools like [FileBot](https://www.filebot.net/) can help, or you can rename them by hand.

---

## Reference material

The [`docs/`](docs/) folder contains reference material for translators and for anyone curious about the terminology:

| File | Contents |
|---|---|
| [`Jutsu-List.csv`](docs/Jutsu-List.csv) / [`.xlsx`](docs/Jutsu-List.xlsx) | Nearly 600 jutsu, styles and proper names in **Japanese, English, German and Dutch**, with the episode where each first appears |

---

## Adding a new language

New translations are welcome! To keep everything consistent:

1. Base the translation on **Maediem's English subtitles**. Keep the numbering and timestamps unchanged.
2. Create a folder named after the **ISO 639-2 language code** (e.g. `fre`, `spa`, `ita`, `por`) with the same season folders and file names, using the matching suffix (`.fre.srt` …).
3. Add a short `README.md` in your language to the folder.
4. Add a row for your language to the table at the top of this README.
5. Use the [jutsu list](docs/Jutsu-List.csv) as a starting point for jutsu names. A column for your language is welcome too.

Then open a **pull request**, or get in touch via an issue or on Discord.

---

## Credits

- **Maediem** – revised English subtitles that all translations are based on ([Maediem/Rebuild-of-Naruto-Subtitles](https://github.com/Maediem/Rebuild-of-Naruto-Subtitles/))
- **Vinstaro** – help with the Dutch subtitles

---

## Found a mistake?

Please report typos, wrong jutsu names or timing problems as an **issue**, or fix them directly with a **pull request**. Mention the language, episode and subtitle number, e.g. *dut, S04E12, #835*.

---

## Community

For discussion and news about the Rebuild, join the Discord:
**[Rebuild of Naruto Discord](https://discord.gg/yDfYvsDKjR)**
