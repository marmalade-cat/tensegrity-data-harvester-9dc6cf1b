Tensegrity Data Harvester (prototype)

Open index.html in a modern browser. Paste a paper URL. The tool fetches the page (subject to CORS), extracts links, attempts to download linked files, and checks for CSV/TSV/JSON/plain numeric files. It then builds a normalized per-module time-series JSON and CSV and shows a short report of failures and suggestions.

Limitations: Runs in-browser, so cross-origin requests may be blocked by CORS. The format checks are heuristic and conservative. This is a prototype for exploration, not a production crawler.