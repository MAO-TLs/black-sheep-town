# BLACK SHEEP TOWN English v1.2.0

This release replaces the complete Steam-source English manuscript with a
single-author literary revision. Every change was made against the Japanese,
then projected back into the same native Steam script topology used by the
patch and bilingual browser.

## Included

- 10,465 substantive English revisions across 63 scenarios
- 29,754 editorial lines, including one non-display line
- 29,753 visible Japanese/English lines in the browser and game projection
- Existing finalized character names, proper nouns, Tips, ruby, and system text retained
- Rebuilt Steam Build 13300478 patch
- Steam-only release; the original Japanese retail renderer remains unsupported

## Typesetting

All 6,347 Japanese page boundaries are retained. Every one of the 6,351
shipped Japanese pages was measured in its active message window, across all
18 window layouts. Consecutive dialogue and narration accumulate whenever they
fit; the English projection adds 200 conservative overflow clears. Of those,
199 land at complete sentences. One unusually long sentence in a two-line
interstitial continues across a clause boundary. Long one-line cinematic text
is locally resized instead of split.

The runtime projection also converts only in-word curly apostrophes to the
engine-safe straight form, preventing contractions and possessives from
breaking after the apostrophe. The public manuscript remains typographically
unchanged.

## Verification

The final manuscript passes its complete row, reference, source-field, control
markup, terminology, honorific, and language sentinels with zero failures. The
release archive passes member-hash and topology checks. Its installer was
exercised against isolated copies for clean installation, repeat installation,
fast reinstallation, verification, Japanese restoration, corrupt-payload
rejection, and transactional rollback. No game-launch claim is made for this
release.

## Install

Download and extract `BLACK_SHEEP_TOWN_English_v1.2.0.zip`, then follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/#install).

## SHA-256

`e966d4fbcda8e9559f9a016f54c40c42069c68d1b58e5f611a82a1ef7d707c49`
