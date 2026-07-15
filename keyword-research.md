# Hooked — SEO Keyword Research & Content Strategy

> Goal: rank for keywords with **download + conversion intent**, not vanity traffic.
> Strategy: one high-converting landing page targeting commercial "app" keywords,
> plus 10 guide pages targeting informational long-tail queries that funnel into the app.

## How the funnel works

- **Commercial keywords** ("crochet app", "row counter app") → land on `/` → download.
- **Informational long-tail** ("how to read crochet patterns") → land on a guide →
  the guide answers the question, then shows how Hooked does it automatically → download.
- Informational queries have 10–50× the volume of commercial ones in this niche, and the
  searcher is *mid-project and frustrated* — the highest-converting moment to offer an app.

## Primary keywords (landing page `/`)

| Keyword | Intent | Where placed |
|---|---|---|
| crochet app | Commercial | H1, title tag, meta description |
| knitting app | Commercial | H1, title tag |
| row counter app | Commercial | Title, H2, hero copy |
| crochet row counter | Commercial | Hero, features |
| crochet pattern app | Commercial | Features, H2 |
| best crochet app for beginners | Commercial-investigational | FAQ, guides |
| stitch counter app | Commercial | Features |
| yarn stash organizer app | Commercial | Features, FAQ |
| crochet tracker / project tracker | Commercial | Features |

Competitors ranking today: My Row Counter (rowcounterapp.com), Crochet Row & Stitch Counter,
Row Counter: Crochet & Knit, YarnBuddy, Yarnventory. Their sites are thin — content-rich
guides are the gap Hooked can win.

## Long-tail keywords → guide pages (`/guides/`)

| # | Guide page | Primary long-tail keyword | Supporting keywords | Intent / pain |
|---|---|---|---|---|
| 1 | how-to-read-crochet-patterns.html | how to read crochet patterns | crochet patterns for beginners, reading crochet instructions, what do asterisks mean in crochet | Beginner staring at a pattern that looks like code |
| 2 | crochet-abbreviations.html | crochet abbreviations | what does sc/dc/hdc mean in crochet, crochet terms list, crochet stitch abbreviations chart | Mid-pattern confusion — instant answer needed |
| 3 | us-vs-uk-crochet-terms.html | US vs UK crochet terms | UK crochet terms conversion, double crochet UK vs US, crochet term converter | Pattern from the "wrong" country ruining a project |
| 4 | how-to-count-crochet-rows.html | how to count rows in crochet | keep track of crochet rows, how to count crochet stitches, losing my place crochet | Frogging pain — the app's core value prop |
| 5 | crochet-row-counter-app.html | crochet row counter app | best row counter app, knitting row counter, digital stitch counter | Highest commercial intent guide — comparison-style |
| 6 | learn-to-crochet.html | learn to crochet | how to crochet for beginners, best app to learn crochet, crochet lessons for beginners | Day-zero beginner, wants a guided path |
| 7 | amigurumi-for-beginners.html | amigurumi for beginners | how to crochet amigurumi, easy amigurumi patterns, magic ring amigurumi | Trend-driven (huge on TikTok/Pinterest), project-first learner |
| 8 | organize-yarn-stash.html | how to organize yarn stash | yarn inventory app, yarn stash organizer, track yarn collection | Stash chaos, duplicate buying |
| 9 | how-much-yarn-do-i-need.html | how much yarn do I need | yarn calculator, yarn yardage for blanket, crochet yarn estimate | Pre-purchase anxiety — high engagement |
| 10 | organize-crochet-patterns.html | how to organize crochet patterns | PDF pattern organizer, import Ravelry patterns, pattern keeper app | Patterns scattered across PDFs/Etsy/Ravelry |
| 11 | left-handed-crochet.html | left handed crochet | how to crochet left handed, left handed crochet tutorial for beginners | Underserved niche, app has a literal feature for it |

## On-page SEO rules applied everywhere

1. One H1 per page containing the primary keyword naturally.
2. Title tag ≤ 60 chars, primary keyword first; meta description ≤ 155 chars with CTA.
3. FAQPage + SoftwareApplication JSON-LD on `/`; Article + FAQPage JSON-LD on guides.
4. Descriptive alt text on every screenshot (keyword-relevant, honest).
5. Internal links: every guide ↔ related guides, every guide → `/` and App Store.
6. FAQ answers are self-contained (featured-snippet bait) with "Learn more" → guide.
7. Semantic HTML (header/nav/main/section/article/footer), fast static page, no JS deps.
8. sitemap.xml + robots.txt included.

## Placeholder domain

All canonical/OG URLs use `https://hookedcrochet.app` — **find & replace with the real
domain before deploying.**

## Sources consulted

- https://hearthookhome.com/best-free-crochet-apps/
- https://rowcounterapp.com/
- https://www.craftyarncouncil.com/standards/how-to-read-crochet-pattern
- https://tlycblog.com/how-to-read-crochet-patterns-for-total-beginners/
- https://haakmaarraak.nl/uk-vs-us-crochet-terms-whats-the-difference
- https://blog.treasurie.com/crochet-abbreviations/
- https://hearthookhome.com/counting-rows-crochet/
- https://www.amandacrochets.com/counting-rows-in-crochet-7-tips/
- https://littleworldofwhimsy.com/my-foolproof-guide-to-crocheting-amigurumi-for-beginners/
- https://www.planetjune.com/blog/amigurumi-help/crochet-basics-left-handed/
- https://myyarnstash.app/ , https://www.yarnbuddy.app/ (competitor scan)
