# NYC events calendar

Rebuilt and pushed automatically twice a day (10:30 and 17:00) by the Instagram
event scanner. `index.html` is a single self-contained page — no scripts fetched, no
external assets, story screenshots inlined as data URIs.

History is intentionally a single commit: the page is ~5MB and is replaced wholesale
each run, so keeping every version would grow the repo by ~4GB a year for no benefit.
