# Emmaus Care: Pastoral Visit Companion

A calm AI companion that helps pastors and care teams prepare for a pastoral visit in minutes.

Live demo: https://dunoil.github.io/emmaus-care/
Built for the AI for Church Hackathon 2026 (Care and Community track).

## The problem

In many small churches, one pastor carries every hospital visit, every grief call, and every homebound member, often driving straight from a day job with no time to prepare. The visit still happens, but it happens hurried, and the person being visited can feel it.

## What Emmaus Care does

Pick a kind of visit (hospital, grief, homebound, new baby, anxiety or crisis, finding their way back), add a first name and a few honest lines about the situation, and Emmaus Care drafts a complete visit plan:

- The heart of this visit: what actually matters in the room
- Three gentle conversation openers
- A listen-for list, tuned by keywords in your notes (surgery, loneliness, job loss, money pressure, and more)
- Three Scripture options, short public domain excerpts with references, to read in context
- A prayer you can pray aloud, written with the person's name, ready to edit into your own words
- Handle with care: common mistakes to avoid for this kind of visit
- Practical notes, and a dated follow-up plan (tomorrow, in 3 days, at milestones) so nobody slips through

Plans can be copied as text, saved on the device, and printed as a one page visit card.

## Responsible AI, by design

- Private by design: all processing happens locally in the browser. Notes never leave the device, and the app asks for a first name only.
- Human in the loop, always: every plan is labelled a draft to review. The app never diagnoses, never promises outcomes, and directs users to emergency and professional help where safety is at stake.
- Honest about its engine: the drafting engine is a curated, rule based pastoral library built for this hackathon, structured the way an AI assistant would respond, with no external model calls and no data collection. Scripture quotations are short excerpts from the public domain King James Version and World English Bible.

## Tech

One static HTML file with inline CSS and JavaScript. No build step, no dependencies, no tracking. Open `app/index.html` or serve the `app/` folder with any static host.

## Why the name

On the road to Emmaus (Luke 24), a stranger became a companion who listened first and spoke second. That is the posture this tool tries to teach: walk in prepared, listen first.

## License

MIT. Built during the hackathon build window, 30 October to 27 November 2026.
