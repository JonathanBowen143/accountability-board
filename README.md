# Massachusetts Accountability Network

Interactive D3 force-graph mapping police and prosecutorial accountability across Massachusetts cases (Juston Root, Sandra Birchmore, John O'Keefe / Karen Read, Ana Walshe, Recruit Enrique Delgado-Garcia).

## Location
This repository lives on local disk at `~/Developer/Massachusetts Accountability Network`, deliberately outside iCloud Drive. A Git repo inside an iCloud-synced folder causes sync locks that stall folder operations.

## Layout
- `index.html` — the entire board, one self-contained file. Edit this directly; pushing deploys it. (GitHub Pages requires this exact filename, so it is not renamed.)
- `tools/` — scratch scripts and a backup of the former iCloud source; ignored by git.

## Deploy
Pushed to GitHub (`JonathanBowen143/Massachusetts-Accountability-Network`) and served free via GitHub Pages, which auto-rebuilds on every push to `main`:

https://jonathanbowen143.github.io/Massachusetts-Accountability-Network/

## Managing with GitHub Desktop
File > Add Local Repository, then choose this folder. Commit and push from there, or from the command line.
