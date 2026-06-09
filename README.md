# Commonwealth Accountability Board

Interactive D3 force-graph mapping police and prosecutorial accountability across Massachusetts cases (Juston Root, Sandra Birchmore, John O'Keefe / Karen Read, Ana Walshe, Recruit Enrique Delgado-Garcia).

## Layout
- `index.html` — the entire board, one self-contained file. This is what deploys.
- `tools/` — scratch edit scripts; ignored by git.

## Source of truth (kept separate, in iCloud)
`~/Library/Mobile Documents/com~apple~CloudDocs/Juston Root - Drive Mirror/Commonwealth_Accountability_Board.html`

Edits are made there, then copied here to `index.html` for deployment.

## Deploy
Pushed to GitHub (`JonathanBowen143/Massachusetts-Accountability-Network`) and served free via GitHub Pages, which auto-rebuilds on every push to `main`:

https://jonathanbowen143.github.io/Massachusetts-Accountability-Network/

## Managing with GitHub Desktop
File > Add Local Repository, then choose this folder. Commit and push from there, or from the command line.
