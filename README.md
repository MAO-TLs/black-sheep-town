# BLACK SHEEP TOWN — MAO English v1.2.2

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.2.2 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.2.2)

## Chapter titles

/vn/ anons rejoice—chapter titles added.

English titles now appear in the in-game chapter selection dialog. All 63
bindings pass static checks.
Story text, Tips, and typesetting assets are unchanged from v1.2.1.

When upgrading, restore Japanese using your previous package first, then install
v1.2.2. Use the v1.2.2 restore helper before downgrading: older helpers do not
restore the new chapter-title UI component.

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.2.2. Its
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

- Patch archive SHA-256: `5fecf7b2c3d90f88539d962c3a1c282535c8a78d859cf1c4d34ce6435af6a645`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `07b25694a7a11fba4191663ddab414ae6846e4bb0d72df5badb4cbd730d6d0a2`
- Canonical translation TSV: `1ad73fa502627500d1ac56bf5bd18de530b8296288fb5676cfaab7a467e24a3b`
- Runtime-visible Steam corpus: `27f89a6aee7a5bcb7822d0d9f4e24096fed613b267a2cb8dd50aa53bebce7ddd`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The retained v1.2.1 Tips UI validation confirms that all 211 English pronunciation
fields are blank, all visible English Tips text is free of Japanese script,
and all sentence-join spacing checks pass.

The verification records cover the complete single-author literary revision,
Steam compilation, archive topology and member hashes, clean installation,
repeated installation, Japanese restoration, fast reinstallation, corruption
rejection, transactional rollback, and exact page-control projection. This
release is statically verified; no new game-launch claim is made for v1.2.2.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
