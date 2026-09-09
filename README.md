# MovieHouse releases

What changed in each version of the MovieHouse Android app, and the images the app
shows on its update page.

- `whatsnew.json` — read by the app when it opens the update page or "What's new".
- `shots/` — the images those entries point to.

This repository is public only so that `raw.githubusercontent.com` can serve those
two things to the app; the app's own source repository is private. Nothing here is
secret and nothing here is code.

No APK is published here. The app updates itself from
`https://account.sourovstore.dev/download`, which is the only place a phone should
ever get MovieHouse from. The archive of published APKs is private.

Source of truth: `release/whatsnew.json` in the app repository, mirrored here by
`ops/publish_whatsnew.py`.
