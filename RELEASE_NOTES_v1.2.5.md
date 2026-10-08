# BLACK SHEEP TOWN English v1.2.5

Fixes ten dialogue-punctuation slips in the game patch and bilingual reader.
Quotes followed by a continued dialogue attribution now end with a comma,
not a period: for example, “I’m sorry,” followed by “she says.” The correctly
lowercase dialogue tags are preserved.

Affected quotation lines: A4:r393, A6:r329, B4-1:r326, E5:r174, F4:r369,
G1:r60, X1:r271, X11:r585, X3-3:r41, and X3-3:r101.

Only those ten punctuation marks change from v1.2.4. The previous Sai-kit
pronoun corrections, Japanese source, inline tags, page controls, Tips index,
chapter titles, system UI, and artwork are preserved.

## Updating

Restore Japanese using your previous patch package first, then install v1.2.5.
Save files are not modified. Steam Build 13300478 only; Japanese retail remains
unsupported. The included offline reader and online reader contain the same
corrected manuscript as the game patch.

## Verification

All 63 scenario grids pass exact manuscript and pagination checks. The release
passes archive integrity, clean installation, repeat installation, exact
Japanese restoration, restore-then-upgrade from v1.2.4, mixed-state rejection,
and corrupt-payload rollback checks. Only six scenario-book objects change,
with exactly twenty corrected cells (ten punctuation edits duplicated in both
runtime text columns). All other objects are byte-identical to v1.2.4.
No new native in-game visual/playthrough verification is claimed.

## Download

Download `BLACK_SHEEP_TOWN_English_v1.2.5.zip` and follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/).

SHA-256: `46cd13995290592817d0d097ab081cc8420f2a3b1c3d5c46b870093dbe10c9a7`
