# NICEIC Insurance prototype

A clickable prototype of a cobranded insurance product for NICEIC-registered contractors, built by Superscript.

It combines two parts in one page:

- **NICEIC Insurance website**: home, insurance product pages, guides and resources, existing customers, make a claim, free insurance check and contact pages.
- **Quote journey and customer portal**: trade triage, business and trade questions, covers, vehicle and fleet insurance, agreements, results, checkout and the customer portal (policies, billing, claims, cover update requests, contact us, guides).

## Running it

It's a single, self-contained `index.html` file with no build step. Open it in a browser, or host it on any static host (GitHub Pages, Netlify and so on).

The page asks for a password before showing anything. This only hides the prototype from casual visitors: the password is in the page's code, so don't rely on it for anything sensitive.

## Prototype helpers

- **Fill this page** (⌘E or Ctrl+E) fills the current journey page with sample answers.
- **Restart journey** clears all answers.
- Adding `#triage`, `#login`, `#portal-home`, `#portal-claims` or `#portal-support` to the URL opens that part of the journey or portal. Any other page name (for example `#guides`) opens the website.

## Notes

- Prices, policy numbers, claims, authors and articles are sample data.
- Photography and partner logos are included for prototype use only. Check usage rights before sharing publicly.
