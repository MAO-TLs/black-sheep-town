# BLACK SHEEP TOWN — MAO English v1.2.5

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.2.5 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.2.5)

## Dialogue punctuation correction

v1.2.5 fixes ten quote-final periods that should be commas before continued
lowercase dialogue tags. All wording and Japanese source text are preserved.
The v1.2.4 Sai-kit pronoun fixes, Tips index, chapter titles, system UI, artwork,
and typesetting remain intact.

When upgrading, restore Japanese with your previous package first, then install
v1.2.5. Save files are not modified.

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.2.5. Its
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

- Patch archive SHA-256: `46cd13995290592817d0d097ab081cc8420f2a3b1c3d5c46b870093dbe10c9a7`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `bd8ad463bd55de022d17497eab44762e8813a93fb802ac964a6fc604257ebdb9`
- Canonical translation TSV: `5070d46184547b50d554f698e301d75f82994ce407b56449a5d62b64d5c245d6`
- Runtime-visible Steam corpus: `8ed31bbc13815ac1051d0809cc0d2739c8c1a217eabc3224dabf3ea22c4833a2`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The correction passes ten-mark punctuation isolation, exact compiled-grid and
pagination parity across all 63 scenarios, archive integrity, installation,
upgrade, restore, and rollback checks. No new native in-game visual/playthrough
verification is claimed. Earlier verification files remain historical records;
the v1.2.5 reports describe this correction.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
