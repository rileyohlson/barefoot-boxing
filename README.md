# Barefoot Boxing Wagga (concept site)

Static site, no build step, no JavaScript. Pages: `index.html` and `privacy.html`.
Deploy this repo to Cloudflare (no build command, output directory `/` (the repo root)).
Font: Figtree (self-hosted, SIL OFL, see `fonts/OFL-Figtree.txt`). The favicon and small header mark are a placeholder "B" drawn for this site; the real logo is `img/logo.jpg`.

## Facts used (from the Facebook page): confirm with the owner
Name, not-for-profit description, "COVID safe business", address 1 Kyeamba Ave Wagga Wagga NSW, phone 0421 821 144, Facebook page link, 2.2K followers.

## Still to fill in (yellow `[brackets]`)
Who it is for, session names and times, fees, first-visit info, opening hours, ABN/association number, privacy approval.
Postcode is not on the page and not included. About text is the owner's own wording (supplied). The Facebook "COVID safe business" line was left out; add back if wanted.

## Before it goes live
- Remove the `noindex` meta tag in both HTML files
- Remove the sample-site bar and the "Sample website design" footer line
- Add the owner's own photos (update the CSP `img-src` only if needed; `'self'` already covers local images)
- Turn on Always Use HTTPS in Cloudflare on the custom domain

## Photos (`img/`, supplied from the gym's Facebook; metadata stripped)
- `logo.jpg` (logo, cropped a few px to remove a stray edge line), `gym.jpg` (group photo), `plaque.jpg` (engraved plaque).
- Confirm the owner supplied them and is happy for them to be on the site.
- `gym.jpg` shows identifiable people, including young people: get the owner's confirmation that everyone (or their parent or guardian) agreed to the photo being published.
- "On Wiradjuri Country" comes from the plaque. Ask the owner whether they want it on the site and how they would like it worded.
