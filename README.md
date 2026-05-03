# Inner Groove Vinyl Browser

Patron-facing browser for the Inner Groove Brewing vinyl collection in Verona, PA.

Built as a single static `index.html` — React via CDN, Supabase for data and Realtime updates, no build step. Sister project to [inner-groove-dj](https://github.com/melk724/inner-groove-dj).

## Features

- Browse the collection by cover art (search, sort, filter by genre and decade)
- Tap any record to see tracklist split by Side A/B with a Discogs link
- Wishlist tab where patrons can suggest new albums and upvote others' suggestions
- Real-time vote updates

## Setup

Edit `index.html` and replace the `SUPABASE_URL` and `SUPABASE_ANON` constants near the top of the script tag with values from your Supabase project. Deploy as a static site (Vercel, Netlify, etc.).

Inventory data is seeded by the [companion import tooling](https://github.com/melk724/inner-groove-dj) (not in this repo).
