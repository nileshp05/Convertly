# Hosting Convertly

Recommended low-cost option: Cloudflare Pages static hosting. Cloudflare documents free, unlimited static-asset requests on both free and paid plans (checked October 25, 2026): https://developers.cloudflare.com/pages/functions/pricing/

1. Open Cloudflare Pages and choose Direct Upload.
2. Upload the contents of `dist/` (or the supplied static-site ZIP).
3. Deploy to the provided pages.dev subdomain. No build command or environment variables are needed.
4. If adding a custom domain, update the canonical URLs in HTML, sitemap.xml, and robots.txt to match. Domain registration is a separate cost.

Official upload instructions: https://developers.cloudflare.com/pages/get-started/direct-upload/
A Direct Upload project cannot later switch to Git integration; create a separate Git-integrated project if needed.

## Advertising launch
The delivered site contains no active advertising script. Configure your real publisher ID and ad slots only after account/site setup. Use the exact ads.txt entry from your account. Update the privacy policy and implement the applicable consent solution before loading advertising scripts.

Google eligibility: https://support.google.com/adsense/answer/9724
Google connection and review: https://support.google.com/adsense/answer/7584263

A public crawlable site, operator contact details, finalized policies, and Google approval are still required. The private Sites deployment is for owner review, not an AdSense-approved public launch.
