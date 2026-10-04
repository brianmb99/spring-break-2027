# Spring Break 2027

A one-page family itinerary for Red Rock Canyon, Las Vegas, Henderson, Hoover Dam, and Black Canyon.

The site is plain HTML and CSS and is published with GitHub Pages at
https://brianmb99.github.io/spring-break-2027/.

`index.html` holds the current itinerary. Flight details come from the family's
booking screenshot; lodging and activities remain proposed. Keep the overview,
flight cards, stay dates and detailed notes in sync when changing the plan.

## Design

Lead with the destination, dates, lodging nights and a compact chronological
overview. Readers should see the shape of the whole trip before scrolling or
clicking. Small highlight photographs support the stay sequence above the fold;
larger views appear in the details. Only secondary
logistics use disclosures; the daily plan always remains visible.

The layout follows the personal-os `vacation-trip-site` skill. Relevant design
research: [information scent](https://www.nngroup.com/articles/information-scent/)
and [progressive disclosure](https://www.nngroup.com/articles/progressive-disclosure/).

## Preview and verification

Run `python -m http.server 8765 --bind 127.0.0.1` from this directory and open
http://127.0.0.1:8765/ in a browser. Inspect the first viewport at laptop and phone
sizes, not only a full-page screenshot. Check for horizontal overflow, all ten
dated rows, working anchor links, loaded images and usable disclosures. Verify
the live Pages deployment after pushing.
