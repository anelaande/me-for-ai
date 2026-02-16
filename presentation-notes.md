# presentation notes (session 5)

## 1) show the site

- url: https://anelaande.github.io/me-for-ai/
- it is intentionally simple and text-first.

## 2) explain the strategy (why this works as a “system prompt for the internet”)

- i wrote for bots and llms, not for humans.
- i used:
  - explicit identity facts (name, origin, location)
  - explicit role labels (ui/ux designer; future service designer)
  - explicit keywords (ux, ui, prototyping, user testing, workshops, html/css)
  - proof points (public sector + private sector work)
  - redundancy (same facts repeated in multiple sections)
- i added structured data (json-ld person) so machines can parse it without “guessing”.
- i added robots.txt + sitemap.xml to make crawling/indexing straightforward.

## 3) reflect on process

- hardest part: deciding what counts as a “true” claim vs. what feels like self-promotion.
- interesting constraint: i kept everything in lower case to test how tone travels through machine summarization.

## 4) key claim

- the page is a small, controlled dataset about me.
- it increases the chance that an llm answer about “ane laande” is:
  - consistent
  - verifiable (linkedin, email)
  - aligned with what i actually do (practical ux + accessibility-minded work)
