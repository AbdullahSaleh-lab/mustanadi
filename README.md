# مستندي — Mustanadi

The website for **مستندي (Mustanadi)**, an offline PDF toolkit for iPhone: scan,
merge, split, reorder, compress, password-protect, fill and sign, and convert —
all of it on the device, with no file ever uploaded to a server.

This repository holds only the site. The app's source is not published here.

| Page | |
|---|---|
| [Privacy policy](https://abdullahsaleh-lab.github.io/mustanadi/privacy/) | Arabic and English |
| [Support](https://abdullahsaleh-lab.github.io/mustanadi/support/) | Arabic |
| [Home](https://abdullahsaleh-lab.github.io/mustanadi/) | Arabic |
| [ads.json](https://abdullahsaleh-lab.github.io/mustanadi/ads.json) | **The ad switch, and the Mintegral IDs.** The app reads it once per launch. `"ads": false` = no ads, no tracking prompt. Add a complete `"mintegral"` block and flip to `true`, run `publish.sh`, and ads are on from the next launch — no app update. Any failure to read it, or any missing ID, leaves ads off. Format is in `docs/launch-checklist.md`. |

Served by GitHub Pages from `main`, root folder. Static HTML, no build step;
`.nojekyll` keeps Jekyll out of the way. `/privacy/` and `/support/` are
directories rather than `.html` files so the URLs resolve without depending on
the host to infer an extension — the privacy URL is the one App Review follows.

© 2026 Abdullah Saleh. Contact: apps.saleh@pm.me
