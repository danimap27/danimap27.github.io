# danimap27.github.io — author site + paper mirrors

Static site published with GitHub Pages, aimed at making the papers readable, quotable
and citable by search engines and LLM answer systems.

- `/` — author page (entity + publication list)
- `/papers/cmes-082712/` — paper landing page: summary, results tables, FAQ, JSON-LD (ScholarlyArticle + FAQPage)
- `/files/*.pdf` — PDF mirrors (only for CC BY 4.0 papers)
- `/llms.txt` — machine-readable summary for LLMs
- `/robots.txt` — explicitly allows all major AI crawlers

## Adding a paper

1. `mkdir papers/<slug>/`, copy `papers/cmes-082712/index.html` and rewrite the text.
2. Keep the four blocks that actually matter: one-paragraph quotable summary, a results
   table with real numbers, a FAQ whose questions are literal search queries, and JSON-LD.
3. Add the PDF to `files/` with a descriptive filename, add the URLs to `sitemap.xml`, `llms.txt`.
4. `git add -A && git commit -m "paper: <slug>" && git push`
