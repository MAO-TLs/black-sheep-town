# BLACK SHEEP TOWN — MAO English v1.1.1

A complete English translation patch for two Japanese Windows releases of
*BLACK SHEEP TOWN*, with the full Steam-authoritative Japanese and English
script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.1.1 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.1.1)

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

- Patch archive SHA-256: `2a3dbaca07355d5fe270967373d9719b9ce72639ac9a0f386f7c081baeaf171a`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `be6be6da6f14ddf59e94398478ccc4119b94600ea5fe4a4f3868eb12e0e88979`
- Retail Japanese `data.unity3d`: `0ae68bbd6a1490edfc9410f5134cb49d14a996ae4ec5d6bcd313ec86fb3306cc`
- Retail English `data.unity3d`: `78f96a5bc70b20d3b58e1b19d69a8e73cd188d95b13d54364e7d2b6cff21aa44`
- Canonical translation TSV: `7bdb991a881425bc123ae28e5164435f7df78ec54e4e6646ff66fccb8516228a`
- Runtime-visible Steam corpus: `89b92548d7019d7550dfd9040fb052410cab4b283e0852fd72fa2c82638aa0c7`
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
