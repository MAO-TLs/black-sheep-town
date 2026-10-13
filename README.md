# BLACK SHEEP TOWN — MAO English v1.3.0

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.3.0 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.3.0)

## Astra editorial pass

GPT-6 Astra reviewed all 29,753 visible passages across all 63 scenarios. The
checks covered meaning, referents, chronology, voice, emotional turns,
recurring language, and earlier difficult editorial decisions.

108 source-checked corrections were accepted after independent adjudication
and a contextual reread. This is an editorial review, not a retranslation.
Japanese source, Tips, chapter titles, system UI,
artwork, and the previous pronoun and punctuation fixes are preserved.
Revised scenes are reflowed through the existing typesetting pipeline.

The published manuscript also incorporates 142 older wording differences already
present in the v1.2.5 game and reader. These are synchronization changes to the
manuscript file, not 142 new Astra corrections.

When upgrading, restore Japanese with your previous package first, then install
v1.3.0. Save files are not modified.

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.3.0. Its
separate text renderer did not meet the same verified typesetting standard.

## Requirements

- A legally obtained Japanese Steam copy of *BLACK SHEEP TOWN*
- Python 3.10 or newer
- About 300 MB of free space while the translated data file is rebuilt

The included helpers install, verify, and restore the patch on Windows or
through Wine on macOS/Linux. The installer verifies the exact Steam source
hash and never launches the game. The archive
contains binary differences and original MAO files, not the Japanese game.

## Integrity

- Patch archive SHA-256: `38f60933763459befc897095612482c202249a1ff04e1c3f1c2ef67b84089a39`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `13984a7e4d7b37bf12859276f76ba85bbbb21b22beddf9237c726076f9c95efa`
- Canonical translation TSV: `fe2ba7e5b0eaf55e3624ef7b6b4d4f68eddedac63a96be36d5850078ef784473`
- Runtime-visible Steam corpus: `23951b56c0434710732336b050486841f70717ffbef95b760670b4ae1e4c67e9`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

Verification covers the exact accepted text changes, preservation of all other
shipped rows, compiled-grid and pagination parity across all 63 scenarios,
archive integrity, installation, upgrade, restore, and rollback. No new native
in-game visual test or full-game playthrough is claimed. Earlier verification
files remain historical records; the v1.3.0 reports describe this release.

## Credits

- Project Lead: MAO
- Translator: GPT-6 Astra
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
