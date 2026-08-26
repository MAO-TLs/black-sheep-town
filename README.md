# BLACK SHEEP TOWN — MAO English v1.1.2

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.1.2 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.1.2)

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.1.2. Its
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

- Patch archive SHA-256: `ce8d08a656597d0134b1ff235cee826458d49c8d33f35f287580e8c9b9156204`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `bb397d3909a6d8c6da6f21122cee78e9fcc0b5018049f78ce1e085bfdbeb1dda`
- Canonical translation TSV: `7bdb991a881425bc123ae28e5164435f7df78ec54e4e6646ff66fccb8516228a`
- Runtime-visible Steam corpus: `89b92548d7019d7550dfd9040fb052410cab4b283e0852fd72fa2c82638aa0c7`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The verification records cover the complete semantic audit, Steam compilation,
archive topology and member hashes, clean installation,
repeated installation, Japanese restoration, fast reinstallation, corruption
rejection, transactional rollback, exact page-control projection, and Wine
runtime checks for the supported Steam release.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
