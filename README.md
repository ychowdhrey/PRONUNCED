# PRONUNCED

Scripts, automation tools, and content workflows powering the **PRONUNCED** YouTube channel — a short-form "how to say it" pronunciation channel.

One word, said correctly, broken down. One word = one Short.

---

## What's in here

| File / folder | What it is |
|---|---|
| `playlist_context.md` | The channel's tagging rulebook. Encodes the channel identity, the full playlist roster, and the rules for sorting any word into the right playlists. Paste it at the start of a tagging request to get consistent, demand-grounded results. |
| `Playlist_-_31st_May_UPDATED_v2.xlsx` | Per-video tagging for the current word list — every word mapped to a primary playlist + up to two secondaries, with rationale notes and a review tab. |
| `New_Playlists_Generated.xlsx` | Proposed new Type playlists (Nut, Chili Pepper, Tea & Infusion, Mushroom, Dumpling, Cured Meat) with paste-ready descriptions and seed-vs-expansion word lists. |
| `Pronunciation-Channel-Blueprint_UPDATED.xlsx` | The full channel architecture: ~66 playlists across 10 sections, build phases, paste-ready descriptions, community signal, and the home-tab layout plan. |
| `Shorts/` | Source material for videos, organised by type (e.g. `2_Syllable`). |

---

## The tagging workflow

1. Collect a raw list of candidate words (one per row).
2. Paste `playlist_context.md`, then the word list, with: *"Organise these into the channel playlists using playlist_context.md."*
3. Optionally attach Semrush / keyword-volume data for priority scoring.
4. Output: a tagged table (primary + secondary playlists per word), flagged items, and any new-playlist candidates.

The rulebook handles the tricky parts: single-country cuisines, shared dishes that span countries, taxonomy checks (e.g. ube is a yam, not a fruit), and keeping the difficulty playlists a *layer* rather than a dumping ground.

---

## Channel structure (high level)

Ten sections: **By Sound & Difficulty**, **Food & Drink** (the largest, ~35 playlists), **Names & People**, **Places & Travel**, **Brands & Products**, **Tech & Internet**, **Animals & Nature**, **Medical & Science**, **Culture/Myth/Belief**, and **Languages of Origin**.

Two kinds of playlists: *title-search* playlists whose title is itself the keyword (e.g. "Hard Words to Pronounce"), and *aggregator* playlists that house high-volume individual videos (e.g. "Cheese Name Pronunciation"). Full breakdown, build phases, and the home-tab layout are in the blueprint file.

---

## Notes

- Spreadsheets are `.xlsx` (binary), so GitHub won't show line-by-line diffs — each commit replaces the file.
- This is a public repo: don't commit API keys, tokens, or anything private.
