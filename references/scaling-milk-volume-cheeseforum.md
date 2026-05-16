# Scaling rennet and culture to milk volume

**Source:** Cheese Forum thread (cheeseforum.org), Sept 2010. Question by *Corina*, answered by *linuxboy*.

Short reference for converting small-batch recipes (e.g. 2 US gal) up to larger volumes (e.g. 10 US gal) for goat-milk Gouda and Cheddar.

## Rennet

> **9 mL of single-strength rennet per 100 lb milk**, where single-strength ≈ 200 IMCU/mL.

Worked through (whole-milk density ≈ 1.03 kg/L):

- 100 lb = 45.359 kg = **44.04 L** of milk
- 9 mL / 44.04 L = **0.204 mL/L**
- × 200 IMCU/mL = **≈ 41 IMCU/L**

That sits at the bottom of the conventional 40–60 IMCU/L range — fine for a longer, gentler set; you'd bump it for a faster floc.

## Culture — bulk % to commercial-product equivalents (per 100 L)

| Bulk % | Danisco DVI (DCU) | Chr Hansen DVS (U) | Chr Hansen frozen pellet (g) |
|---|---|---|---|
| 0.50 % | 3.25 | 5 | 5 |
| 1.00 % | 6.50 | 10 | 10 |
| 1.50 % | 9.75 | 15 | 15 |
| 2.00 % | 13.00 | 20 | 20 |

**Linear in %:**

- Danisco: **6.5 DCU per 100 L per 1 % bulk**
- Chr Hansen: **10 U (or 10 g pellet) per 100 L per 1 % bulk**

Normal range for most cheeses: **1.0 % – 1.5 %**.

## Per-DCU coverage (Danisco)

| Bulk % | DCU per 100 L | L covered by 1 DCU |
|---|---|---|
| 0.50 % | 3.25 | 30.8 L |
| 1.00 % | 6.50 | 15.4 L |
| 1.50 % | 9.75 | 10.3 L |
| 2.00 % | 13.00 | 7.7 L |

## The "25 DCU pack ≈ 200 L" claim

The thread states a 25 DCU pack is good for ~200 L. Computed coverage at each rate:

- 1.0 % → 385 L
- 1.5 % → 256 L
- 2.0 % → 192 L

So the 200 L figure tracks a **~2 % bulk equivalent** (Cheddar / pasta filata territory), not the 1–1.5 % "normal" range mentioned in the same post. Worth bearing in mind when sizing packs.

## Discrepancy note

The earlier thread we summarised ([inoculation-percentages-cheeseforum.md](inoculation-percentages-cheeseforum.md)) quotes **6.25 DCU/100 L per 1 %** for Danisco; this thread gives **6.5**. Same author, three months apart — looks like rounding rather than a real change. The 5–10 % gap doesn't matter for home batches but is worth noting if you ever need precision.

## Practical takeaway for our scale

For our typical small batches, plug into:

```
DCU = (litres × bulk_percent × 6.5) / 100
```

So 8 L of milk at 1 % bulk → 0.52 DCU. A 25 DCU pack would cover ~48 of those batches at 1 %.

For rennet, the simpler formulation already in `calculations.md` (target 40–60 IMCU/L) is equivalent.
