# BLACK SHEEP TOWN — MAO English v1.2.4

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.2.4 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.2.4)

## Pronoun correction

v1.2.4 corrects four references to Ma Sai-kit in X3-2 and X17 to he/his or son.
The Japanese source and all other prose are preserved. The v1.2.3 Tips index
fix, chapter titles, system UI, artwork, and typesetting are unchanged.

When upgrading, restore Japanese with your previous package first, then install
v1.2.4. Save files are not modified.

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.2.4. Its
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

- Patch archive SHA-256: `e8917de3185d205f83b77a8c7a374bf3535f6246434c90b5ca2085e1641ef683`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `7b66876b0b71e2bb05c36a83c204a13352dc860b4f27d2c68acedd071c65ce92`
- Canonical translation TSV: `d7523c561889505095990c5852b039c67c2be36d4281e8484ccd1c865df48c56`
- Runtime-visible Steam corpus: `8e1eb8183021a27e2d99ec86a62ffb0e4a8cabc6e262f6c4606817018a96dc0d`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The correction passes four-line manuscript isolation, exact compiled-grid and
pagination parity across all 63 scenarios, archive integrity, installation,
upgrade, restore, and rollback checks. No new native in-game visual/playthrough
verification is claimed. Earlier verification files remain historical records;
the v1.2.4 reports describe this correction.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
