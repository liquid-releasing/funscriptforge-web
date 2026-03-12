# funscriptforge-web

Marketing and download site for **FunscriptForge** — hosted at [funscriptforge.com](https://funscriptforge.com).

## What's here

Single-page static site (`index.html`) deployed to Cloudflare Pages. No build step, no framework — push to `main` and it's live.

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — hero, features, how-it-works, system requirements, download CTA, footer |
| `funscriptforge-banner.png` | Hero banner image |
| `funscriptforge-logo-wide.png` | Nav bar logo |
| `funscriptforge.png` | Square icon (favicon fallback) |
| `anvil.png` | Feature card icon — Structural analysis |
| `worktable.png` | Feature card icon — Per-phrase transforms |
| `spark.png` | Feature card icon — Live phrase preview |
| `oven.png` | Feature card icon — One-click export |
| `forge-social-banner.png` | Social / OG image (future use) |
| `liquid-releasing-Color-Logo.svg` | Footer branding |

## Deployment

Hosted on **Cloudflare Pages** (free tier). Any push to `main` triggers an automatic redeploy — typically live within 60 seconds.

Custom domain: `funscriptforge.com` → DNS managed via Cloudflare.

## Download links

Download buttons point to the public releases repo:

```
https://github.com/liquid-releasing/funscriptforge-releases/releases/latest/download/FunscriptForge-windows.zip
https://github.com/liquid-releasing/funscriptforge-releases/releases/latest/download/FunscriptForge-macos.zip
https://github.com/liquid-releasing/funscriptforge-releases/releases/latest/download/FunscriptForge-linux.tar.gz
```

Using `/releases/latest/download/` means the links always resolve to the newest release — no manual update needed when a new version ships.

## Related repos

| Repo | Purpose |
| --- | --- |
| [`liquid-releasing/funscriptforge`](https://github.com/liquid-releasing/funscriptforge) | App source code (private) |
| [`liquid-releasing/funscriptforge-releases`](https://github.com/liquid-releasing/funscriptforge-releases) | Public release artifacts (Windows + macOS + Linux) |

---

*© 2026 Liquid Releasing. FunscriptForge™ is a trademark of Liquid Releasing.*
