# `.watchy` data (archived)

**Frozen as of 2026-07-28.** The daily-commit pipeline here is superseded by a Cloudflare Worker that polls hourly and appends events to D1 — see [watchy]'s [`cfw/`] and the live [event feed] / [health] pages. This repo's git history (2025-07-06 → 2026-07-21) was backfilled into the D1 event log (`source='git'`).

Historical operation: [`.github/workflows/update.yml`](.github/workflows/update.yml) [ran daily][runs], snapshotting GitHub stargazer and follower data to [github/](github) using [watchy].

[watchy]: https://github.com/runsascoded/watchy
[`cfw/`]: https://github.com/runsascoded/watchy/tree/main/cfw
[event feed]: https://watchy.ryan-0dc.workers.dev/
[health]: https://watchy.ryan-0dc.workers.dev/health
[runs]: https://github.com/ryan-williams/.watchy/actions/workflows/update.yml
