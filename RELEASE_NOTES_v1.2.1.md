# BLACK SHEEP TOWN English v1.2.1

This maintenance release corrects the in-game English Tips presentation without
changing the finalized story translation.

## Included

- Removes Japanese pronunciation text from all 211 English Tips entries
- Restores spaces at source line joins in English Tips descriptions
- Retains the complete v1.2.0 single-author story manuscript and typesetting
- Rebuilt Steam Build 13300478 patch
- Steam-only release; the original Japanese retail renderer remains unsupported

## Verification

All 29,753 visible story lines and all 6,721 compiled pages remain bound to the
same finalized Steam-source manuscript. The release passes archive topology and
member-hash checks, clean installation, repeat installation, Japanese
restoration, corrupt-payload rejection, transactional rollback, and the
v1.2.0-to-v1.2.1 upgrade/restore/reinstall path. All 211 runtime Tips
pronunciation fields are blank, and the English Tips text contains neither
visible Japanese script nor missing spaces at sentence joins.

Runtime launch was waived after repeated Wine freezes during automated UI
control, so this release makes no new game-launch claim.

## Install

Download and extract `BLACK_SHEEP_TOWN_English_v1.2.1.zip`, then follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/#install).

## SHA-256

`4f09ec06e718a205cd3cbb4fabd9ba755c72b30f6117e16ba3165718f333af22`
