# BLACK SHEEP TOWN English v1.1.2

This release corrects in-game page control and typesetting without changing a
single word of the English translation. Consecutive dialogue and narration now
accumulate on screen like the Japanese version whenever they fit. Longer
English text clears only at safe input waits when the active message window is
full.

## Included

- Zero changes to visible English text
- Japanese page boundaries preserved across all 63 scenarios
- Same-screen dialogue and narration accumulation restored
- English-only page clears inserted only when required to prevent overflow
- Rebuilt Steam Build 13300478 patch
- Existing English system text and Tips localization retained
- Steam-only release; the original Japanese retail renderer remains unsupported

## Verification

Every compiled scenario in the supported Steam build was reconstructed and
checked against the patched game data. The verifier confirmed every translated
line and control field, every original Japanese page boundary, every added safe
English page clear, and that every page fits the active message window.
The archive was also installed, reinstalled, verified, restored, deliberately
corrupted, and transactionally rolled back against a temporary copy of the
supported Japanese data file. Wine runtime checks covered the Steam build.

## Install

Download and extract `BLACK_SHEEP_TOWN_English_v1.1.2.zip`, then follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/#install).

## SHA-256

`ce8d08a656597d0134b1ff235cee826458d49c8d33f35f287580e8c9b9156204`
