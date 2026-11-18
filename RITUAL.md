# Update ritual

What to do every time Alex says "update with latest info" (or similar). Do every step, in order. Don't skip a step because it was skipped before. If a step can't be done, say so in the report.

Trip: Singapore → destination, out **Wed 23 Dec 2026**, back **Sat 26 Dec 2026**, 1 adult, economy, SGD. Source: Google Flights.

## 0. Start
- Pull both repos: `axxng/eight` (brain) and `axxng/christmas-getaway-2026` (this site).
- Read this file, the brain entry `memory/2026-11-christmas-trip-flights.md`, and the latest version in `index.html` (the `SNAPS[0]` snapshot).
- Tell Alex in one line what you're about to do.

## 1. Re-price every destination in both tables
- For each destination: the cheapest outbound and the cheapest return, each about 12 hours or less door to door. Prefer nonstop where the table already uses nonstop.
- Record flight numbers, airlines, local times (+1 for next day) and layovers for both legs.
- Check by hand the routes where the automatic pick lands on a bad routing (so far: Tokyo, Harbin, Goa). Price last time's itinerary and look at the outbound list for anything better.

## 2. Price every seller for each chosen itinerary
- Open the itinerary's booking options and expand "more booking options".
- Record: cheapest seller, airline direct (one booking and two tickets), Trip.com, Expedia, Booking.com, Agoda and Traveloka.
- Gotogate, Mytrip and Flightnetwork are Etraveli Group, which runs Booking.com flights. Everything else outside the trusted list is "lesser-known".

## 3. Recheck the struck-off and not-added list
- Everything in the struck-off table (Nagoya, Brisbane, Auckland, Clark, Kaohsiung, Europe…). Reinstate anything back under SGD 1,500 with a sensible routing.

## 4. Look for new destinations
- Search a fresh batch of candidates with a Christmas angle that haven't been checked before.
- Add any under SGD 1,500 with a sensible routing. List the rest as "checked, not added".

## 5. Re-evaluate strike-offs
- Strike off if the cheapest sensible round trip is over SGD 1,500, or there's no sensible routing (about 12h each way, or you'd lose most of the three days).
- Flag (don't strike) anything that's under a price line only through a lesser-known agent.
- Move destinations between "Under SGD 1,000" and "SGD 1,000–1,500" by cheapest price, and mark the move.

## 6. Itineraries
- Rewrite the itinerary for any destination whose flight times changed (arrival day, last day, airport time).
- Write a new itinerary for every new destination.
- Recheck Christmas event dates if they're unconfirmed.

## 7. Page content
- Best bets, "What changed" (moved bands, added, struck off, biggest drops and rises, how many cheaper/dearer/unchanged), and the stamp.
- **History:** add the update as a new version snapshot at the front of `SNAPS`. Never edit or delete older versions.

## 8. Test before publishing
- iPhone SE, iPhone 13, tablet (800–900px) and desktop (1280px).
- No sideways page scroll. Every section pill visible. Table headers and destination column pinned and aligned. Jump links land below the bar. Every version tab renders.

## 9. Publish
- Claude page (artifact "Christmas Getaway Fares") and GitHub Pages (push to `main`).
- Load https://axxng.github.io/christmas-getaway-2026/ and confirm the new stamp is live.

## 10. Save and report
- Update the brain entry with today's prices and changes, commit and push, and say whether the push went through.
- Report: what moved, what was added, what was struck off, the biggest changes, the best bets, and anything you couldn't do. Cite sources.
