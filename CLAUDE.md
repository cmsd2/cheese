# Claude notes for this repo

A personal cheese-making notebook. Markdown only; no code.

## Layout

- `README.md` — index
- `calculations.md` — formulas, ratios, dosing
- `log.md` — chronological batch log, newest at top
- `recipes/` — one file per cheese
- `references/` — summaries of external sources (forum threads, articles, books)

## Defaults to assume

- **Small batches.** Typical milk volume is **3–8 L** (e.g. 6 L today against a recipe written for 11.3 L). Scale recipes proportionally and flag where small-batch behaviour diverges from larger-vat assumptions in source material (e.g. heat loss, surface area, curd-knit dynamics).
- **Culture format: freeze-dried DVI/DVS** from **Danisco** or **Chr Hansen**. When converting "bulk %" or "mother culture" recipes, give the equivalent DVI dose using the conversions in `calculations.md` (Danisco: 6.5 DCU/100 L per 1 %; Chr Hansen: 10 U or 10 g/100 L per 1 %). Don't suggest growing a mother culture unless asked.

## Calculations — always use a tool

**Never guess arithmetic.** For any numeric result — yields, rennet doses, brine concentrations, DCU ↔ litres, percentage conversions, temperature conversions, anything — run it through a tool:

- Python (Bash → `python -c "..."`) for one-shot calculations
- A computer-algebra system / `sympy` for symbolic work, unit handling, or rearranging formulas

This applies even when the answer "looks obvious". A wrong number in a recipe is worse than a slow one.

When a calculation is used in a written answer or file, **show the expression that was evaluated** (not just the result) so the user can audit it.

## Writing references

When the user pastes a web page to summarise:

- Save to `references/<slug>.md`. Slug = short kebab-case derived from topic + source (e.g. `inoculation-percentages-cheeseforum.md`).
- Open with a **Source** line: site, author if known, date.
- Prefer structured summary (tables, bullets, short sections) over prose paraphrase. Strip forum back-and-forth into the underlying claims.
- Keep the author's units (°C, litres, %) — this is a UK/metric kitchen.
- If the page contains formulas, tables, or dosing numbers, **also** fold those into `calculations.md` with a back-link to the reference file. Reference is the narrative; `calculations.md` is the working bench card.

## Writing recipes

One file per cheese under `recipes/`. Expected sections: ingredients (with quantities for a specific milk volume), equipment, timeline by pH targets where possible, notes on cultures/rennet used. Cross-link from `log.md` entries.

## Log entries

Use the template at the bottom of `log.md`. Newest entries go **above** the `<!-- Add new entries above this line -->` marker, not at the file end.

## Style

- UK English spelling (flavour, colour, mould, pasteurised).
- Metric units. Show °F in parentheses only when quoting a US source.
- No emojis unless the user explicitly asks.
- Plain markdown tables; no HTML.
