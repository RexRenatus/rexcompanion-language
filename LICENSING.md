# Licensing

This repository is licensed per path:

- the course content and its documentation: CC BY-NC-SA 4.0 (Creative Commons
  Attribution-NonCommercial-ShareAlike 4.0 International,
  [LICENSES/CC-BY-NC-SA-4.0.txt](LICENSES/CC-BY-NC-SA-4.0.txt)), copyright 2026 Devin Williams,
  who keeps every right the licence does not grant, commercial use included. Except for the files
  that quote CC BY-SA glosses (see "Hosted decks" below), this covers:
  - the per-language pages and sample cards under `es/`, `fr/`, `ja/`, `ko/` and `zh/`
    (`*/README.md`, `*/samples/*.md`), except the frequency lists under `*/words/`;
  - the documentation and its images: `README.md`, `LICENSING.md` and `docs/`, except the brand images below;
- code (scripts, tooling and CI configuration, for example `*.py`, `*.sh`, `*.js` and
  `.github/`): MIT ([LICENSE](LICENSE)). The tree holds no code files today; the pipeline that
  builds the decks is not published in this repository;
- the brand images `docs/header.jpg` (the Restauratio Regni crest), `docs/hero-banner.png` and
  `docs/hero-banner.svg` (the Rex Renatus banner): Copyright 2026 Devin Williams. All rights
  reserved. The licences in this repository grant no right in them.

## Third-party material

Third-party material is NOT relicensed by this repository: each source keeps its owner's terms.

| material | where | terms |
|---|---|---|
| frequency lists from the OpenSubtitles 2018 corpus, via [HermitDave/FrequencyWords](https://github.com/hermitdave/FrequencyWords) | `es/`, `fr/`, `ja/`, `ko/` and `zh/` under `words/*.txt`, the re-tokenized Japanese UniDic list included | CC BY-SA 4.0, FrequencyWords' licence for its content |
| English glosses from [CC-CEDICT](https://www.mdbg.net/chinese/dictionary?page=cc-cedict), JMdict (through [jamdict](https://github.com/neocl/jamdict)), KANJIDIC and [Wiktionary](https://www.wiktionary.org/) | inside the hosted decks | CC BY-SA, in the version each project states: CC-CEDICT 4.0; KANJIDIC 4.0, under the licence of the Electronic Dictionary Research and Development Group (EDRDG) |
| stroke-order data from [KanjiVG](http://kanjivg.tagaini.net) | inside the hosted decks | CC BY-SA 3.0 |
| stroke-order graphics from [Make Me a Hanzi](https://github.com/skishore/makemeahanzi)'s `graphics.txt`, derived from the fonts AR PL KaitiM GB and AR PL UKai and read through [Hanzi Writer](https://hanziwriter.org)'s data | beside the Writing-Chinese deck, as a separately licensed part distributed as a mere aggregation | the Arphic Public License (Arphic Technology Co., Ltd., 1999), [LICENSES/ARPHICPL.TXT](LICENSES/ARPHICPL.TXT): every copy keeps the licence file `ARPHICPL.TXT` unaltered; a modified file carries a prominent notice of how and when it was changed; modifications are made freely available as a whole under the same licence; and no further restriction may be put on the rights it grants |
| English glosses (dictionary data) from Make Me a Hanzi's `dictionary.txt`, derived from Unihan and CJKlib | inside the Writing-Chinese deck (the meaning on every one of its 5,932 notes) and the Chinese Regular and Cursive workbooks (`Writing-Chinese-Regular.pdf`, `Writing-Chinese-Cursive.pdf`: the meanings they print) | the GNU Lesser General Public License, version 3 or any later version, [LICENSES/LGPL-3.0.txt](LICENSES/LGPL-3.0.txt); its Unihan-derived data also carries Unicode, Inc.'s copyright and permission notice, [LICENSES/Unicode-Unihan-notice.txt](LICENSES/Unicode-Unihan-notice.txt), which must appear with every copy and in its documentation, with a clear notice in each modified data file. CC BY-SA 4.0 does not apply to these glosses |
| CEFR level lists, fonts and the other sources [README.md](README.md#attribution--sources) names | inside the hosted decks, workbooks and textbooks | their owners' terms, as that section records |

## Hosted decks

The downloadable decks, workbooks and textbooks are built from the course content by a pipeline
that is not published here, and hosted outside this repository at `storage.googleapis.com` (the
download links in [README.md](README.md)).

The published decks, workbooks and textbooks that embed CC BY-SA material (English glosses from CC-CEDICT, JMdict through
jamdict, KANJIDIC or Wiktionary, or KanjiVG stroke-order data) are released under CC BY-SA 4.0
(Creative Commons Attribution-ShareAlike 4.0 International,
[LICENSES/CC-BY-SA-4.0.txt](LICENSES/CC-BY-SA-4.0.txt)), the licence that keeps those glosses
and that data compatible. Commercial reuse of those files is allowed under its terms. A
redistribution of those files, or of the CC BY-SA glosses in them, keeps the attribution to
CC-CEDICT, JMdict, KANJIDIC, Wiktionary and KanjiVG, and stays under CC BY-SA 4.0 or a compatible
licence. The same holds for any file in this repository that quotes those glosses, such as a
sample card under `*/samples/` that shows a deck card's dictionary glosses: it is under
CC BY-SA 4.0, not CC BY-NC-SA 4.0.

The Writing-Chinese deck's own content is under CC BY-SA 4.0, as above; its Make Me a Hanzi
glosses are not (see below). Its
stroke-order graphics (Make Me a Hanzi's graphics, read through Hanzi Writer's data) are a
separately licensed part under the Arphic Public License: they are distributed as a mere
aggregation beside the deck, with the licence text
[LICENSES/ARPHICPL.TXT](LICENSES/ARPHICPL.TXT) unaltered, and CC BY-SA 4.0 does not apply to
them. The deck and the Chinese Regular and Cursive workbooks (`Writing-Chinese-Regular.pdf` and
`Writing-Chinese-Cursive.pdf`) also carry Make Me a Hanzi's dictionary data: every one of the
deck's 5,932 notes shows an English gloss from `dictionary.txt` as its meaning, and the workbooks
print those glosses. Those glosses are under the GNU Lesser General Public License, version 3
or any later version ([LICENSES/LGPL-3.0.txt](LICENSES/LGPL-3.0.txt)), and their Unihan-derived
data carries Unicode, Inc.'s copyright and permission notice
([LICENSES/Unicode-Unihan-notice.txt](LICENSES/Unicode-Unihan-notice.txt)). CC BY-SA 4.0 and
CC BY-NC-SA 4.0 do not apply to them. A copy of those files, or of the glosses in them, keeps both
texts with it. LGPL-3.0 builds on the
[GNU General Public License, version 3](https://www.gnu.org/licenses/gpl-3.0.html): it
incorporates that licence's terms and adds the permissions set out in its own text.

The CEFR level a card shows is treated as a fact about the word, not as expression copied from
a level list, so the CC BY-SA decks do not take on the NonCommercial terms of the lists the
levels were read from. Credit for the Spanish and French levels goes to
[CEFRLex](https://cental.uclouvain.be/cefrlex/): ELELex for Spanish and FLELex for French.
Their own licence, CC BY-NC-SA, stays theirs.

The other hosted files carry the content licence, CC BY-NC-SA 4.0. Third-party material inside
any hosted file keeps its owners' terms, as above.
