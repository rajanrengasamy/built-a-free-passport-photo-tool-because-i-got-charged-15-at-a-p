# Built a free passport photo tool because I got charged €15 at a photo studio for a JPEG

ARC overnight build artifact backfilled to GitHub.

## Overview
Photo studios charge €15+ for simply taking a photo and cropping it to standard passport dimensions, which takes 30 seconds. Proposed MVP: A simple Next.js web app where a user uploads a selfie. The app uses face detection to center the face, remove the background, apply a white background, and crop it to exactly 2x2 inches.

## Build metadata
- **Run ID:** `20260313T010029`
- **Project slug:** `built-a-free-passport-photo-tool-because-i-got-charged-15-at-a-p`
- **Track / slot:** `reddit_solve_this` / `primary`
- **Build status:** `SUCCESS`
- **Built at (UTC):** `2026-03-12T14:00:30.567053+00:00`
- **Source signal:** https://reddit.com/r/SideProject/comments/1rbl8sw/built_a_free_passport_photo_tool_because_i_got/
- **Composite score:** 8.136

## Why this was selected
Needed to renew my passport and went to a photo studio. They took one picture, cropped it, and charged me €15 for something that took 30 seconds...

## Artifacts in this repo
- `main.py`
- `PRD.md`
- `build_log.txt`

## Run locally
```bash
python3 main.py
```

## Notes
- This project was produced by the ARC overnight pipeline builder.
- `build_log.txt` captures raw builder output for traceability.
