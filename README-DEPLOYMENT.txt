# Boostaro website package

## Included
- `index.html` — homepage based on the supplied HTML
- `main.css`, `main.js` — responsive styling and FAQ interaction
- `images/` — supplied product and bonus images
- `privacy-policy.html`, `terms.html`, `fda-disclaimer.html`
- `contact.html`, `shipping-policy.html`, `refund-policy.html`
- `sitemap.xml`, `robots.txt`
- Bing IndexNow key file: `9d7f24fd56c6433dad549ffe182e0fbf.txt`

## Deploy to Vercel
1. Extract this ZIP.
2. Import the extracted folder into a GitHub repository, or deploy the folder using Vercel.
3. Set the Vercel project to serve the folder as a static site (no build command; output directory `.`).
4. Confirm the live homepage opens at `https://en-boostaro.vercel.app/`.
5. Open `https://en-boostaro.vercel.app/sitemap.xml` and `https://en-boostaro.vercel.app/robots.txt` to confirm they load.

## Google Search Console
- The homepage retains the Google verification meta tag supplied in your HTML.
- Add the property `https://en-boostaro.vercel.app` in Google Search Console.
- If Google asks for verification, use the HTML tag method and confirm the saved token matches the property. Do not edit or guess the token.
- Submit `https://en-boostaro.vercel.app/sitemap.xml` in the Sitemaps section.
- Google does not offer general-purpose URL indexing API submission for ordinary product/affiliate pages. Use URL Inspection and request indexing where available; indexing is not guaranteed.

## Bing Webmaster Tools
- The homepage retains the Bing `msvalidate.01` meta tag supplied in your HTML.
- Verify `https://en-boostaro.vercel.app` in Bing Webmaster Tools and submit `https://en-boostaro.vercel.app/sitemap.xml`.
- IndexNow key is `9d7f24fd56c6433dad549ffe182e0fbf`. The key file is available at `https://en-boostaro.vercel.app/9d7f24fd56c6433dad549ffe182e0fbf.txt`.
- Submit updated URLs using Bing Webmaster Tools or an IndexNow-compatible client.

## Affiliate link
All purchase CTA destinations in this package use this exact URL:
`https://mwebkivo.com/9673/16838/6/?`

## Important checks before publishing
- Confirm the Google/Bing verification tokens belong to this Vercel domain.
- Confirm product price, shipping, bonus, refund and guarantee claims against the live seller checkout.
- The provided HTML listed nine ingredients in one section but described the formula as eight ingredients elsewhere; check the current product label and align all copy before publishing.
- The source HTML contained a rotating “recent purchase” popup with invented sample buyers. That popup was removed.
- Confirm ownership/permission to use the Boostaro brand, images, testimonials, and product claims.
- Replace or confirm any support email and business contact details before publication. The legal pages supplied originally referenced a different domain.
- The product is a dietary supplement; keep medical claims conservative and retain the FDA disclaimer.
