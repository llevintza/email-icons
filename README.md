# Email Icons

PNG icons for email signatures, resumes and other documents, served from GitHub Pages as a small personal CDN.

**Base URL:** `https://llevintza.github.io/email-icons/img/`

> **Never rename, overwrite or delete a published file.** Every email already sent points at these URLs. To change an icon, add a new file (e.g. `x-v2.png`) and point new signatures at it.

## Colored set (`img/color/`, 64×64, used by the email signature)

| Icon | URL |
|---|---|
| <img src="img/color/phone.png" width="16"> Phone | `https://llevintza.github.io/email-icons/img/color/phone.png` |
| <img src="img/color/linkedin.png" width="16"> LinkedIn | `https://llevintza.github.io/email-icons/img/color/linkedin.png` |
| <img src="img/color/github.png" width="16"> GitHub | `https://llevintza.github.io/email-icons/img/color/github.png` |
| <img src="img/color/x.png" width="16"> X | `https://llevintza.github.io/email-icons/img/color/x.png` |
| <img src="img/color/zoom.png" width="16"> Zoom | `https://llevintza.github.io/email-icons/img/color/zoom.png` |
| <img src="img/color/web.png" width="16"> Website / portfolio | `https://llevintza.github.io/email-icons/img/color/web.png` |

## Black-square set (`img/`, 512×512)

| Icon | URL |
|---|---|
| <img src="img/telephone-symbol-button.png" width="16"> Phone | `https://llevintza.github.io/email-icons/img/telephone-symbol-button.png` |
| <img src="img/linkedin.png" width="16"> LinkedIn | `https://llevintza.github.io/email-icons/img/linkedin.png` |
| <img src="img/github.png" width="16"> GitHub | `https://llevintza.github.io/email-icons/img/github.png` |
| <img src="img/x.png" width="16"> X | `https://llevintza.github.io/email-icons/img/x.png` |
| <img src="img/zoom.png" width="16"> Zoom | `https://llevintza.github.io/email-icons/img/zoom.png` |

`img/twitter.png` is the same X logo as `img/x.png`. It's kept so links that already use it keep working.

## Usage

```html
<img src="https://llevintza.github.io/email-icons/img/color/github.png" width="16" height="16" alt="GitHub" style="display:block">
```

Use the GitHub Pages URLs. The old `raw.githubusercontent.com/...` URLs still work, but raw.githubusercontent.com is rate-limited and only cached for about 5 minutes, so it isn't meant for images embedded in email.

Show icons at 16px. The 64px files keep them sharp on high-resolution screens.

## Sources and licences

The SVG source for each new icon is in `src/`. PNGs are rendered from them with headless Chrome, at 64×64 for the colored set and 512×512 for the black Zoom icon.

| Icon | Source | Licence |
|---|---|---|
| LinkedIn, GitHub, X | [Simple Icons](https://simpleicons.org) v13.21.0 paths, in each brand's colour (#0A66C2, #181717, #000000) | CC0 1.0 |
| Phone glyph | Material Design Icons "call" path, white on a #1E88E5 circle | Apache 2.0 |
| Website globe | Material Design Icons "public" path in #3498DB (the signature's rule colour) | Apache 2.0 |
| Zoom | A plain video-camera shape drawn for this repo, in Zoom blue #0B5CFF / white on black | — |
| `img/github.png`, `linkedin.png`, `telephone-symbol-button.png`, `twitter.png` | Original 2025 set | as before |

LinkedIn, GitHub, X and Zoom are trademarks of their owners. These icons are used only to link to Leo's own profiles and booking page.

---

*Maintained by [llevintza](https://github.com/llevintza)*
