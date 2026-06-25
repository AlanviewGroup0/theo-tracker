# theo-tracker

Auto-updating dashboard of everything **Theo (t3.gg)** is talking about on X and YouTube.

- Live data in `data.json`, rendered by `index.html` (static, no build step).
- Updated **daily** by an Aside agent routine: pulls @theo's tweets/replies/quotes + recent YouTube uploads (auto-transcripts), regenerates `data.json`, and commits here. Vercel auto-deploys on push.

_Not affiliated with Theo._
