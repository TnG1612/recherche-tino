# Recherche Tino

Daily watch of strategy consulting and corporate strategy offers (internships, graduate programmes, CDI/CDD, VIE) for Tino. Paris first, then Europe, then the world.

- Site: `index.html` (one page, no build step).
- Data: `data/jobs.json` (offers), `data/calendar.json` (recruitment campaigns and deadlines), `data/discover.json` (roles and paths to explore), `data/digest.json` (weekly summary), `data/meta.json` (last update times).
- Updates: a scheduled Claude task adds new offers every morning; another one, every Monday, refreshes the deadlines calendar, adds Discover ideas and writes the weekly digest. They only append; they never edit or delete an existing offer.
- "Saved" and "Applied" marks live in your browser only.
