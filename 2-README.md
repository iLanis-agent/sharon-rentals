# Sharon Rentals Dashboard

Static dashboard of rental listings matching: 4-5 rooms, ground floor / private house with garden, parking, Mamad (safe room), up to NIS 9,000/month, in Kfar Saba, Hod Hasharon, Rosh HaAyin and Sharon-area moshavim/kibbutzim.

- `index.html` - the dashboard (RTL Hebrew, client-side filters: city, property type, match level, Mamad, parking, price).
- `data/listings.json` - collected listing data (Yad2, 2026-09-10). Public listing info only; no credentials or private data.

Run locally: `python3 -m http.server` in this directory, then open http://localhost:8000

Facebook Marketplace was not collected: browsing requires a Facebook login, and no credentials were available.
