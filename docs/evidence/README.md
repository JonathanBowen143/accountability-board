# Evidence Ingestion Surface

Last updated: June 9, 2026.

This folder is the project-owned evidence layer for the Commonwealth Accountability Board. The board itself can stay compact and visual; this folder is where source records, extracted claims, and connector decisions should hold up over time.

## Files

`source-ledger.md` records reviewed or identified source surfaces.

`connector-queue.md` records graph decisions, holds, and next actions.

`victim-anchor-mining.md` records why larger victim-anchor nodes exist and how connector mining is progressing for those people.

## Durability Rules

Do not add a graph connector from memory alone. A connector should have a source record in `source-ledger.md`, a decision or open item in `connector-queue.md`, and enough citation detail to recover the evidence if the local Drive mirror moves again.

Prefer primary records first: court filings, public-record productions, official reports, OCR extracted from those records, and direct agency materials. Use news reporting for context and verification, but mark it separately from primary-record evidence.

Treat local research notes as leads unless they cite a recoverable source. The local `_CAREER_INVENTORY_NorfolkCounty.md` file is useful because it preserves prior work, but it is not by itself a final source for new graph edges.

## Status Labels

- `ingested`: reviewed in this project folder and summarized with source detail.
- `indexed`: present in a Drive index or mirror inventory, but the content was not reviewed in this pass.
- `lead`: useful for future research, but not enough for a graph change.
- `graph-ready`: strong enough to support a graph connector if the board needs it.
- `hold`: do not graph yet; requires OCR, official copy, or corroboration.

## Current Root Mirror

The active local mirror found this pass is:

`/Users/jonathanbowen/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror`

The most useful starting files are `_DRIVE_FULL_INDEX.tsv`, `_OCR_03-09-20_Norfolk_DA_Report.txt`, `_OCR_Godin_IAD2022-0053.txt`, and `_CAREER_INVENTORY_NorfolkCounty.md`.
