---
name: data-cleaning
description: Clean and standardise spreadsheets and CSVs, such as supplier catalogues or lead lists. Use for dedupe, formatting, unit and header fixes, and CSV template preparation.
---
## Steps
1. Work on a COPY. Never edit the original. Name it with date and "cleaned".
2. Profile the data: row count, empty cells, duplicates, odd values,
   mixed units.
3. Apply only the requested fixes. Typical: trim spaces, consistent
   capitalisation, dedupe, standard country names, uniform units (keep
   original units in a separate column), valid URLs.
4. Do NOT invent or "correct" technical values (TID, temperature, ratings)
   by guessing. Flag suspicious ones in a "needs review" column.
5. Add a change log tab: what changed, how many rows, assumptions.
6. Report counts before and after, and anything I could not fix.