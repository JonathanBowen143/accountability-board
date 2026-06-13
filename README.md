# Massachusetts Accountability Network

Interactive D3 force-graph mapping police and prosecutorial accountability across Massachusetts cases (Juston Root, Sandra Birchmore, John O'Keefe / Karen Read, Ana Walshe, Recruit Enrique Delgado-Garcia).

## Location
This repository lives on local disk at `~/Developer/Massachusetts Accountability Network`, deliberately outside iCloud Drive. A Git repo inside an iCloud-synced folder causes sync locks that stall folder operations.

## Layout
- `index.html` — the board page and graph data. Edit this directly; pushing deploys it. GitHub Pages requires this exact filename, so it is not renamed.
- `docs/evidence/` — source ledger, connector queue, and victim-anchor mining notes for evidence-backed graph changes.
- `docs/evidence/unsolved-homicide-triage.md` — intake rules for unsolved murder leads before they become graph candidates.
- `docs/karen-read-witness-ledger.md` — documented witness ledger for Karen Read's first trial and retrial, separated from graph-add decisions.
- `docs/read-root-birchmore-connectors.md` — source notes for the Read / O'Keefe / Root / Birchmore connector pass.
- `vendor/d3.v7.min.js` — local D3 runtime, vendored so the board does not depend on a CDN.
- `tools/` — scratch scripts and backups of former source copies; ignored by git.

## Source of truth
This repository is the source of truth for the public board.

If older iCloud or temporary copies are found, compare them against this repository before using them. Do not assume an iCloud copy is current.

## Reading the board
Large purple person nodes are victim anchors. They mark the murdered people at the center of the board's current major Norfolk County and statewide accountability lanes. Size is not an evidence-strength score and should not be read as a claim of blame or certainty.

## Deploy
Pushed to GitHub (`JonathanBowen143/Massachusetts-Accountability-Network`) and served free via GitHub Pages, which auto-rebuilds on every push to `main`:

https://jonathanbowen143.github.io/Massachusetts-Accountability-Network/

## Managing with GitHub Desktop
File > Add Local Repository, then choose this folder. Commit and push from there, or from the command line.
