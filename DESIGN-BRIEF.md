> **Superseded 2026-10-07 on the owner's call:** the live site's zenburn palette and monospace type stay (see `style.css`); the paper/light direction below is not pursued. Register, structure and facts discipline still apply.

# bokondo.net — design brief

For the Claude Design session. Written 2026-08-21, alongside the content
restructure of index.html (journey-narrative page → outcomes-first
business card).

## What this page is

The professional face. One of four properties, each with its own job:

- **bokondo.net** — this: the resume/business card. Outcomes first.
- **qry.zone** — essays and deep dives (dark zenburn garden).
- **sloppydisq.com** — the channel (camp, pixel-grid, CC0).
- **chasmlogic.com** — corporate satire universe (brutalist).

The doctrine (owner's words, from the positioning work): *post-LLM-boom,
AI-forward portfolios read as "poser" in qualification contexts — lead
with outcomes, AI as subject matter, never as the claim.* The page must
read as a senior engineer's card that HAPPENS to include an agents
research block, not an AI-guy's landing page.

## Audience and job

Recruiters, hiring managers (DevRel / creative-technologist / senior
product engineering), and potential freelance clients — mid-scroll,
often from a link in an email. The page's single job: the gist in ten
seconds, one credible click-path deeper for each audience (GitHub for
engineers, qry.zone for readers, chasmlogic for creative-tech).

## Structure (already in the HTML — keep it)

1. Name, role line, contact row
2. Two-sentence lede + availability
3. Recent work: four outcome items (title / meta line / one paragraph
   with 1–2 verifiable numbers)
4. Agents & research block (one paragraph + three links)
5. Toolbox (one paragraph, not a tag cloud)
6. Footer

## Register

Plain, confident, concrete. Numbers over adjectives ("2.4M products,
one month, essentially solo" — never "passionate" or "results-driven").
No hedging, no exclamation marks. The existing site's honesty streak
(a commit literally says "added some more modesty") is the personality:
understate and let the numbers carry.

## Visual direction

- **Handcrafted, not corporate.** It should feel like a well-set
  personal letterhead, not a SaaS landing page or a resume-builder
  export. Print sensibility: strong typographic hierarchy, generous
  measure (~42rem), restrained palette.
- **Distinct from the siblings:** NOT zenburn/dark-mono (qry.zone owns
  that), NOT pixel-camp (sloppydisq), NOT brutalist (chasm). Light,
  paper-like, calm is the open lane.
- **One accent, used sparingly** — links and hairlines. The current
  #2456a4 steel blue is a placeholder; choose deliberately.
- **Typography carries it.** A characterful display face for the name
  and headings, quiet body face. This page can afford one beautiful
  type choice because there is almost nothing else on it.
- Anti-slop list applies (owner's standing rule): no purple-blue
  gradients, no glassmorphism, no Inter-by-default, no hero metric
  grids, no card shadows, no bounce easing.
- Dark scheme: supported (tokens exist), but the light/paper look is
  primary — this page gets read in daylight contexts.
- Print stylesheet is a worthy bonus: this page IS the resume; ctrl+P
  should produce a clean one-pager.

## Token contract

`--paper --ink --dim --accent --rule --measure` in index.html. Swap
values, keep names. Content is final-ish; don't rewrite copy except
where a design need demands a shorter line.

## Facts discipline

Every claim traces to the owner's work records. Client names are
deliberately withheld ("a two-company client", "a Belgian e-commerce
company") — keep it that way unless the owner explicitly adds them.
Do not invent numbers, logos, or testimonials.
