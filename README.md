# Convertly
A buildless, dependency-free website. Upload the contents of `dist/` to any static host. No Node runtime, database, or paid API is required in production.

## Local preview
Run `python preview.py` from this directory and visit http://localhost:4173. Stop any previous server on that port with Ctrl+C first. The launcher resolves the site folder relative to itself and disables browser caching. Copy buttons work on localhost or HTTPS.

CSS and JavaScript URLs include content versions so a reload picks up updated assets. If an already-open VS Code browser still shows the earlier design, reload it or reopen `http://localhost:4173/?refresh=20261030`.

The portable copy at `E:\Projects\Codex Projects\convertly-complete-project` stores `index.html` directly at its root; do not use `--directory dist` there. Its `preview.py` supports that layout too.

## Included tools
- ISO and Unix dates, calendar input, timezone display, copy all
- Length, weight, volume, temperature
- Decimal and binary data storage
- Exact integer base conversion using BigInt
- Unicode Base64, URL component encoding, text case
- Accessible mobile navigation, theme preference, live tool search

## Public launch checklist
The Sites preview is private by default. Before public launch, supply the operator contact address and finalize the policy pages with actual business practices. Change canonical URLs, robots.txt and sitemap.xml when moving to another domain. Submit the sitemap after launch.

## AdSense
Ads are intentionally disabled. No fake publisher ID or live ad script is included. Obtain AdSense approval for the public site, add the exact account-provided ads.txt entry and verified publisher script, and configure required consent management. Keep ad slots clearly labeled and separated from buttons and inputs. Update the privacy policy to match the actual integration. AdSense approval and revenue are not guaranteed. Private previews are not suitable for public ad review.

## Low-cost hosting
The dist folder is portable to static hosting, including Cloudflare Pages or GitHub Pages subject to their current terms and limits. No backend is needed. A custom domain may have a separate annual cost. See HOSTING.md for verified references.

## Limits
Measurements display up to 12 significant digits. Number-base conversion accepts up to 4,096 integer digits. Text conversion accepts 200,000 characters. Date parsing requires explicit units and offsets. No live currency, document, image, or video conversion is claimed.
