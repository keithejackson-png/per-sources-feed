# Per Sources — feed

The two files the paper is made of, published here so persourcesdynasty.com can
read them without a deploy.

| file | what it is |
|---|---|
| `data.json` | every number — rosters, box scores, standings, odds, trades, valuations |
| `content.json` | every word — the lead, the columns, recaps, previews, the ledger |

**This is a mirror, not the source.** The paper is written and stored on its
Claude artifact. The weekly runs publish there first; these files are copied
across afterwards. If the two ever disagree, the artifact is right.

The site reads these over raw.githubusercontent.com and falls back to its own
deployed copies if that fails, so a bad push shows the last good issue rather
than an empty page. To undo one, revert the commit and push — nothing else.

Nothing here is private. The same two files are served at
persourcesdynasty.com/data.json and /content.json.
