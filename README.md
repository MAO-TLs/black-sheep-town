# BLACK SHEEP TOWN — MAO English v1.1.0

A complete English translation patch for two Japanese Windows releases of
*BLACK SHEEP TOWN*, with the full Steam-authoritative Japanese and English
script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.1.0 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.1.0)

## Supported releases

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)
- Original Japanese Windows retail release (`Bst_Data/data.unity3d`)

The two patches and the browser derive from the same finalized Steam-source
manuscript. The browser contains 29,753 visible rows across 63 scenarios; the
published editorial corpus contains 29,754 rows, including one non-display row.

## Requirements

- A legally obtained supported Japanese copy of *BLACK SHEEP TOWN*
- Python 3.10 or newer
- Up to 2.1 GB of free space while the translated data file is rebuilt

The included helpers install, verify, and restore the patch on Windows or
through Wine on macOS/Linux. The installer detects the supported release,
verifies its exact source hash, and never launches the game. The archive
contains binary differences and original MAO files, not the Japanese game.

## Integrity

- Patch archive SHA-256: `4fda54ae008755f71fdedc9da4ab80186e4eae40a2fdeec8f2420ab43ddb6104`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `f0d52fa855800acf8d9a122ae675534e64bae8c2c5e2dde9957101b36d51b2bf`
- Retail Japanese `data.unity3d`: `0ae68bbd6a1490edfc9410f5134cb49d14a996ae4ec5d6bcd313ec86fb3306cc`
- Retail English `data.unity3d`: `9848cc7b1a7e649dd2985df1100b3aa60ab5f03a6479abea3d338989842c470b`
- Canonical translation TSV: `c8fec31c0b00a6309f90a17fb67088b3e4ceefb3083e36999c30b49d8d6bd37c`
- Runtime-visible Steam corpus: `e48a141e22b67626455584a8202e392486027f01ad32a3968abf379baed91d65`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The verification records cover the complete semantic audit, Steam compilation,
retail projection, archive topology and member hashes, clean installation,
repeated installation, Japanese restoration, fast reinstallation, corruption
rejection, and transactional rollback for both supported releases. These tests
operate on temporary copies and do not launch the game.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
