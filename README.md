# BLACK SHEEP TOWN — MAO English v1.2.3

A complete English translation patch for Steam Build 13300478 of
*BLACK SHEEP TOWN*, with the full Japanese and English script published online.

- [Download and installation guide](https://mao-tls.github.io/black-sheep-town/)
- [Bilingual script browser](https://mao-tls.github.io/black-sheep-town/script.html)
- [v1.2.3 release](https://github.com/MAO-TLs/black-sheep-town/releases/tag/v1.2.3)

## Tips index correction

v1.2.3 restores all 211 Tips index values removed by an earlier cleanup, fixing
missing entries in “All Tips.” Japanese readings appear beside English titles
again. English prose, chapter titles, typesetting, and unlock conditions are preserved.

When upgrading, restore Japanese with your previous package first, then install
v1.2.3. Use the v1.2.3 Restore helper before downgrading.

## Supported release

- Steam Build 13300478 (`Bst_Data/sharedassets0.assets`)

The patch and browser derive from the same finalized Steam-source manuscript.
The browser contains 29,753 visible lines across 63 scenarios; the published
editorial corpus contains 29,754 lines, including one non-display line.

The original Japanese Windows retail release is not supported in v1.2.3. Its
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

- Patch archive SHA-256: `b9f9cdf666df97dc89bbb74a491d51e2bc1ce28241c0de717fc4a278d3fbb0aa`
- Steam Japanese `sharedassets0.assets`: `3246bf3b15e275eacbcb2dc2c89d3e00a7d256d5ba52d9401159bed1f0102cb8`
- Steam English `sharedassets0.assets`: `256890f024e5132d7c89661c84bf4e186a174f4c868a9351d4229f78b7841942`
- Canonical translation TSV: `1ad73fa502627500d1ac56bf5bd18de530b8296288fb5676cfaab7a467e24a3b`
- Runtime-visible Steam corpus: `27f89a6aee7a5bcb7822d0d9f4e24096fed613b267a2cb8dd50aa53bebce7ddd`
- Final Tips manuscript: `d8dd6a496dc020f96e6ca558f7ba7ee140a1d7a217a697ce0c765c072615e17a`

The correction passes source-index parity, object isolation, archive integrity,
installation, upgrade, restore, and rollback checks. In-game visual verification
of the title and game menus remains incomplete. Earlier verification files
remain historical records; the v1.2.3 reports describe this correction.

## Credits

- Project Lead: MAO
- Translator: GPT-5.6 Sol
- Special Thanks: gambs

This is an unofficial, noncommercial fan translation. The original work and
trademarks belong to their respective owners.
