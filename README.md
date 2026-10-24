# Barefoot Boxing Wagga (concept site)

Static site, no build step, no JavaScript. Pages: `index.html` and `privacy.html`.
Deploy this repo to Cloudflare (no build command, output directory `/` (the repo root)).
Font: Figtree (self-hosted, SIL OFL, see `fonts/OFL-Figtree.txt`). The favicon and small header mark are a placeholder "B" drawn for this site; the real logo is `img/logo.webp`.

## Facts used (from the Facebook page): confirm with the owner
Name, not-for-profit description, "COVID safe business", address 1 Kyeamba Ave Wagga Wagga NSW, phone 0421 821 144, Facebook page link, 2.2K followers.

## Still to fill in (yellow `[brackets]`)
Who it is for, session names, public holiday hours, ABN/association number, privacy approval.
Postcode is not on the page and not included. About text is the owner's own wording (supplied). The Facebook "COVID safe business" line was left out; add back if wanted.

## Before it goes live
- Remove the `noindex` meta tag in both HTML files
- Remove the sample-site bar and the "Sample website design" footer line
- Add the owner's own photos (update the CSP `img-src` only if needed; `'self'` already covers local images)
- Turn on Always Use HTTPS in Cloudflare on the custom domain

## Photos (`img/`, supplied from the gym's Facebook; metadata stripped)
- `logo.webp` (logo, cropped a few px to remove a stray edge line), `gym.webp` (group photo), `plaque.webp` (engraved plaque).
- Confirm the owner supplied them and is happy for them to be on the site.
- `gym.webp` shows identifiable people, including young people: get the owner's confirmation that everyone (or their parent or guardian) agreed to the photo being published.
- "On Wiradjuri Country" comes from the plaque. Ask the owner whether they want it on the site and how they would like it worded.

## Reviews
Three Facebook reviews are in `#reviews` in `index.html`, spelling and punctuation kept as written ("Bearfoot", "awsome", "exelent"), and the page says so. Reviewer names were not supplied, so none are shown.
- Compare each with the live review on Facebook and keep a dated screenshot. The owner confirmed the long third review is one review.
- Remove a quote if the review is deleted or edited on Facebook.
- Get the owner's OK, and ideally each reviewer's (one mentions their son).

## SEO (done) and still to do at launch
Done: keyword title and description, Open Graph tags, schema.org data (gym, address, phone, hours), `robots.txt`, WebP images with alt text, fast static pages.
At launch, once the domain is known:
- Add `<link rel="canonical">`, `og:url`, and an `og:image` (absolute URL, e.g. the logo, ideally a 1200x630 version) to `index.html`.
- Add `sitemap.xml` and a `Sitemap:` line to `robots.txt`.
- Remove the `noindex` meta tags.
- Claim and fill in the Google Business Profile (same name, address, phone and hours as the site) and link it to the site. This matters more for local search than anything on the page.
