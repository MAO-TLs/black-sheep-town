# BLACK SHEEP TOWN English v1.1.1

This release corrects the boundaries of inline Tips links without changing the
visible English translation. English plurals, possessives, contractions, and
compound endings that belong to a linked term now remain inside the same Tips
span instead of appearing as detached text after it.

## Included

- 1,737 Tips-boundary corrections across 1,625 rows
- Zero changes to visible English text
- Exact preservation of every Tips ID sequence
- Rebuilt Steam Build 13300478 and original Japanese retail patches
- Updated bilingual script browser using the same corrected authority
- Existing English system text and sentence-aware page wrapping

## Verification

The complete 29,754-row editorial manuscript and 29,753-row visible runtime
corpus passed source-field, Japanese-hash, control-tag, terminology, Tips-ID,
markup-balance, and pagination checks. The archive was installed, reinstalled,
verified, restored, deliberately corrupted, and transactionally rolled back
against temporary copies of both supported Japanese data files. Every rebuilt
and restored hash matched exactly. The validation performed zero game launches.

## Install

Download and extract `BLACK_SHEEP_TOWN_English_v1.1.1.zip`, then follow the
[installation guide](https://mao-tls.github.io/black-sheep-town/#install).

## SHA-256

`2a3dbaca07355d5fe270967373d9719b9ce72639ac9a0f386f7c081baeaf171a`
