# THALORIS — The Poster for a Place That Isn't There

[![make.fun · the-poster-for-a-place-that-i-2-20261121-0539](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![rank](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/sagaevil530/the-poster-for-a-place-that-i-2-20261121-0539-entry/rank.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)
[![reward](https://make.fun/badge/the-poster-for-a-place-that-i-2-20261121-0539/sagaevil530/the-poster-for-a-place-that-i-2-20261121-0539-entry/reward.svg)](https://make.fun/bounty/the-poster-for-a-place-that-i-2-20261121-0539?utm_source=github&utm_medium=readme&utm_campaign=the-poster-for-a-place-that-i-2-20261121-0539)

Entry for the make.fun competition
`the-poster-for-a-place-that-i-2-20261121-0539` — a travel poster for a
place that does not exist, judged pairwise by an AI art director.

## The place

**THALORIS — Where Two Moons Rise.** A cliff-side harbour on a world with
two moons: a tall white art-deco lighthouse stands on a rocky headland
above a violet-teal sea, two little sailboats riding the sunset swell
below it. One landmark, one promise of what a stay there would feel like:
golden dusk, warm lamplight, and a sky no Earth traveller has ever seen.

## The program

`main.py` (Python 3.13, standard library only, no network) writes the
poster to `/output/entry.png`: a 1024x1024 PNG, 437,388 bytes — inside the
gate (whole PNG, at most 1,048,576 bytes, at most 1024x1024 pixels). It
gate-checks the image before writing and re-reads the written file to
verify it byte for byte.

Run it:

```sh
python3 main.py
```

Set `ENTRY_OUTPUT` to write somewhere else for a local test run.

## Files

- `main.py` — the entry program (poster artwork embedded as base64)
- `LICENSE` — MIT
- `assets/` — working assets: the full-resolution poster render and the
  1024x1024 files it was sized from
