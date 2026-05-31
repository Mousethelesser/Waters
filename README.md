# Clear Eyes

A free, evidence-grounded resource for survivors of narcissistic abuse and coercive control. Four companion guides that work together as a mobile-first website and installable iOS app — no app store required.

---

## The four guides

| File | Purpose |
|---|---|
| `index.html` | Hub — start here |
| `the-cycle.html` | Understanding the four phases, 7 stages, and why the bond forms |
| `the-anchor.html` | For when the pull to go back arrives — interactive checklist, private notes, protocol |
| `the-undertow.html` | Self-check tool with live meter — catch the drift before it becomes contact |
| `clear-eyes.html` | The complete guide — all four parts including the blame, guilt &amp; your own struggles |

---

## How to publish as a live website (GitHub Pages)

### Step 1 — Upload the files

1. Go to your repo: **github.com/Mousethelesser/The-Cycle**
2. Click **Add file → Upload files**
3. Drag in everything from the `site/` folder:
   - `index.html`
   - `the-cycle.html`
   - `the-anchor.html`
   - `the-undertow.html`
   - `clear-eyes.html`
   - `shared.css`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png` *(see icons note below)*
   - `icon-512.png`
4. Scroll down, write a commit message like `Add Clear Eyes site`, click **Commit changes**

### Step 2 — Enable GitHub Pages

1. In your repo, click **Settings** (top tab)
2. In the left sidebar, click **Pages**
3. Under **Source**, choose **Deploy from a branch**
4. Set Branch to **main** and folder to **/ (root)**
5. Click **Save**

GitHub will show you a URL like:
```
https://mousethelesser.github.io/The-Cycle/
```
It takes about 60 seconds to go live. That's your website.

---

## How to install as an iOS app (no App Store needed)

1. Open the site in **Safari** on iPhone (must be Safari, not Chrome)
2. Tap the **Share** button (the box with an arrow pointing up)
3. Tap **Add to Home Screen**
4. Give it a name — "Clear Eyes" — and tap **Add**

It will appear on your home screen like a native app. It works fully offline once installed — no internet needed after the first visit.

> This works because all five HTML files include the `apple-mobile-web-app-capable` meta tag and link to a Web App Manifest (`manifest.json`). The service worker (`sw.js`) caches all pages for offline use.

---

## About the icons

The manifest references `icon-192.png` and `icon-512.png`. You can:
- **Use any image** — rename it to those filenames and place it alongside the HTML files
- **Skip them** — the site works perfectly without icons; iOS will just generate a screenshot-based icon automatically

---

## Notes saved by users

The Anchor and Clear Eyes guides let users write and save private notes (reasons for leaving, their safe people). These are stored **only in the user's browser localStorage** on their device. Nothing is ever transmitted, logged, or sent anywhere. Users can clear their notes at any time by saving with empty text boxes, or by clearing their browser data.

---

## Sources

- Dutton &amp; Painter (1981; 1993) — Traumatic Bonding; power imbalance &amp; intermittent reinforcement
- van der Kolk, B. (2014) — *The Body Keeps the Score*
- Bowlby, J. (1969) — *Attachment and Loss*
- Warshaw et al. (2014) — Substance-use coercion, National Center on DV, Trauma &amp; Mental Health
- Freyd (1997); Harsey &amp; Freyd (2020) — DARVO
- Khantzian (1985; 1997) — Self-medication hypothesis
- Wuest &amp; Merritt-Gray (1999) — "Not Going Back"
- Khaw &amp; Hardesty (2009) — Leaving as a cyclical process
- Melemis (2015), *Yale Journal of Biology and Medicine* — Three-stage relapse model
- DSM-5-TR (2022) — NPD diagnostic criteria
- Prochaska &amp; DiClemente — Stages of Change model

For a full corrections log, see `SOURCES_AND_CORRECTIONS.md`.

---

## Disclaimer

For educational purposes and self-support only. Not a substitute for professional care, therapy, legal advice, or safety planning with a qualified advocate. In an emergency, call 911. DV Hotline: 1-800-799-7233.
