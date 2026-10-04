# BLACK SHEEP TOWN English v1.2.4

Corrects four references to Ma Sai-kit in the game patch and bilingual reader:

- X3-2:r122: “his cell phone,” not “her cell phone.”
- X3-2:r124: “He/he,” not “She/she.”
- X3-2:r191: “father and son,” not “father and daughter.”
- X17:r293: “his elbow,” not “her elbow.”

The Japanese source identifies Sai-kit as male. These were English translation
errors; the Japanese source, inline tags, and page controls are unchanged.
All other game-data objects are byte-identical to v1.2.3, including the restored
Tips index, chapter-title UI, system UI, and artwork.

## Updating

Restore Japanese using your previous patch package first, then install v1.2.4.
Save files are not modified. Steam Build 13300478 only; Japanese retail remains
unsupported. The included offline reader and online reader contain the same
corrected manuscript as the game patch.

## Verification

All 63 scenario grids pass exact manuscript and pagination checks. The release
passes archive integrity, clean installation, repeat installation, exact
Japanese restoration, restore-then-upgrade from v1.2.3, mixed-state rejection,
and corrupt-payload rollback checks. Only the X scenario book changes from
v1.2.3, with exactly eight corrected cells (four lines in both runtime text
columns). No new native in-game visual/playthrough verification is claimed.

## Download

Download `BLACK_SHEEP_TOWN_English_v1.2.4.zip` and follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/).

SHA-256: `e8917de3185d205f83b77a8c7a374bf3535f6246434c90b5ca2085e1641ef683`
