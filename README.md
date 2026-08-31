# sarahjenningsre-preview

**SANDBOX / PREVIEW ONLY — not the live website.**

| | Production | This repo |
|---|---|---|
| Repo | [RGJIV/sarahjenningsre](https://github.com/RGJIV/sarahjenningsre) | [RGJIV/sarahjenningsre-preview](https://github.com/RGJIV/sarahjenningsre-preview) |
| Public URL | [https://sarahjenningsre.com](https://sarahjenningsre.com) | [https://rgjiv.github.io/sarahjenningsre-preview/](https://rgjiv.github.io/sarahjenningsre-preview/) (after Pages is enabled) |
| Custom domain | Yes (`CNAME` = sarahjenningsre.com) | **Never** |

Created 2026-08-31 so Grok / experiments can change files without touching the live site.

## Hard rules

1. Do **not** add a `CNAME` file. That would fight production for [sarahjenningsre.com](https://sarahjenningsre.com).
2. Do **not** push to [RGJIV/sarahjenningsre](https://github.com/RGJIV/sarahjenningsre) unless Richard explicitly says deploy to live.
3. Do **not** overwrite real photos (`assets/images/headshot/*`, `assets/images/hero/hero-main.jpg`) without a deploy plan.
4. Promote to production only after Richard reviews the preview URL.

## Enable GitHub Pages (one-time)

1. Open this repo on GitHub.
2. **Settings → Pages**.
3. Build and deployment → Source: **Deploy from a branch**.
4. Branch: **main** / folder: **/ (root)** → **Save**.
5. Wait 1–2 minutes, then open [https://rgjiv.github.io/sarahjenningsre-preview/](https://rgjiv.github.io/sarahjenningsre-preview/).

Official docs: [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## What is not here yet

HTML pages and photos have **not** been copied from production. Next step is to seed this repo with a working preview (HTML + assets), still with no `CNAME`.
