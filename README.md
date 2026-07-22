# AI Daily Digest

Automated daily digest of AI industry news and notable research papers, published via GitHub Pages.

- `index.html` — running list of days, newest first, plus a "Topic requests" section
- `digests/YYYY-MM-DD.html` — one page per day's automated digest
- `topics/SLUG.html` — one page per on-demand topic request
- `seen.json` — dedup manifest (normalized URL/title → date first covered), used by the daily digest to avoid repeating stories already covered in the last ~14 days

## Requesting a topic

Open an issue on this repo with the topic in the title (e.g. "research: state of AI regulation in the EU"). An hourly scheduled agent checks for open issues, researches the topic, publishes `topics/SLUG.html`, comments on the issue with a link, and closes it.

Generated daily/hourly by scheduled agents. Not manually edited.
