# GLYF word lists

Four-letter word lists used by **GLYF**, a word-ladder game (change one letter at a time).
Published so that anyone can reuse them, as the source licenses require.

*Türkçe özet: GLYF oyununda kullanılan 4 harfli kelime listeleri. Kaynakların lisansı gereği herkese açık paylaşılır.*

## Files (`lists/`)

| File | Contents |
|---|---|
| `xx_4.txt` | All accepted 4-letter words, one per line, lowercase |
| `xx_common.txt` | Well-known words used for start and target words |
| `tr_lemma.txt` | Turkish: word → dictionary form, e.g. `kalk kalkmak` (used for dictionary links) |

All lists were filtered for this game: only 4-letter words, no proper names or abbreviations, offensive words removed,
accents simplified where the game does so (French é→e, Portuguese ç→c, etc.).

## Sources and licenses

| Language | Files | Source | License of these files |
|---|---|---|---|
| Türkçe | `tr_4.txt`, `tr_lemma.txt` | [Zemberek-NLP](https://github.com/ahmetaa/zemberek-nlp) lexicon © Ahmet A. Akın, Mehmet D. Akın; verb roots and regular derivations (-lI, -cI, -Iş, -mA) generated from it | Apache 2.0 (`LICENSES/Apache-2.0.txt`) |
| Türkçe | `tr_common.txt` | Selected by the GLYF author from `tr_4.txt` | Apache 2.0 |
| English | `en_4.txt` | ENABLE word list | Public domain |
| English | `en_common.txt` | ENABLE, ranked with [FrequencyWords](https://github.com/hermitdave/FrequencyWords) (Hermit Dave, OpenSubtitles 2018) | CC BY-SA 4.0 |
| Deutsch, Español, Français, Italiano, Português | `de/es/fr/it/pt_4.txt` | [Wiktionary](https://en.wiktionary.org) via [kaikki.org](https://kaikki.org) (wiktextract) | CC BY-SA 4.0 (`LICENSES/CC-BY-SA-4.0.txt`) |
| same | `de/es/fr/it/pt_common.txt` | Wiktionary, ranked with FrequencyWords | CC BY-SA 4.0 |
| 日本語 | `ja_4.txt`, `ja_common.txt` | [JMdict](https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project) © Electronic Dictionary Research and Development Group, used under its [licence](https://www.edrdg.org/edrdg/license.html) | CC BY-SA 4.0 |

Word lists derived from CC BY-SA sources are shared under the same license (CC BY-SA 4.0).
The GLYF game code is not covered by these licenses.
