# BLACK SHEEP TOWN English v1.2.2

/vn/ anons rejoice—chapter titles added.

English chapter titles now appear in the in-game chapter selection dialog.
No chapter names are listed here: some contain spoilers.

## Included

- Connects all 63 chapter selections to their existing translated titles.
- Keeps the original title styling and uses automatic sizing for longer titles.
- Adds the chapter-title UI file to the reversible Steam installer.
- Leaves story text, Tips, and typesetting assets byte-for-byte unchanged from v1.2.1.
- Steam Build 13300478 only; Japanese retail remains unsupported.

## Updating

Restore Japanese with your previous patch package first, then install v1.2.2.
Use the **v1.2.2 restore helper** before downgrading: older helpers do not restore
the new chapter-title UI component. No save files are changed by the installer.

## Verification

All 63 title bindings pass static checks. Clean installation, repeat installation,
exact Japanese restoration, cached reinstallation, the documented v1.2.1 upgrade,
corrupt-payload rejection, and transactional rollback passed. Archive contents and
member hashes were checked; the existing narrative and metadata payloads are unchanged.

## Download

Download and extract `BLACK_SHEEP_TOWN_English_v1.2.2.zip`, then follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/).

SHA-256: `5fecf7b2c3d90f88539d962c3a1c282535c8a78d859cf1c4d34ce6435af6a645`
