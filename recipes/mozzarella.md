# Mozzarella

**Source:** *Home-made Cheese*, Paul Thomas.

A cultured pasta filata (stretched-curd) cow's-milk cheese. Eaten fresh, within a few days.

## At a glance

| Parameter | Value |
|---|---|
| Milk | Whole cow's milk (or buffalo) |
| Culture | Thermophilic, *S. thermophilus*-based |
| Coagulation | Animal rennet, 1:10,000 strength |
| Curd handling | Cut, drained, matted to pH 5.25, milled, salted, stretched in 95 °C water |
| Press | None — shaped by hand |
| Affinage | None — eat fresh, within 5 days for cow's milk |

## Ingredients

Book column is the recipe as written (11.4 L / 3 US gal). "Today" is scaled for **4 L** (factor 0.3509). Calculations:

```
scale       = 4.0 / 11.4 = 0.3509
milk mass   = 4.0 × 1.03 = 4.12 kg
culture     = 2.3 × 0.3509 ≈ 0.81 U
rennet      = 2.5 × 0.3509 ≈ 0.88 mL
salt (pre)  = 21 × 0.3509 ≈ 7.4 g (recompute on actual milled curd at 1.5 % w/w)
stretch H₂O = 1 mL per g milled curd, at 95 °C
```

| Ingredient | Book (11.4 L) | Today (4 L) | Notes |
|---|---|---|---|
| Whole cow's milk | 11.4 L | 4.0 L | Freshest available; non-UHT |
| Chr Hansen TCC-20 (DVI) | 2.3 U | **0.81 U** | ≈ 1.62 % of a 50 U pack = **72 mg** (measured pack: 4.471 g for 50 U → 89.42 mg/U) |
| Rennet (1:10,000) | 2.5 mL | **0.88 mL** | Dilute in ~15 mL cool non-chlorinated water before adding |
| Salt (non-iodised) | ~21 g | **~7.4 g** | 1.5 % w/w of milled curd; weigh actual curd before salting |
| CaCl₂ (32 % soln) | not specified | **1.2 mL** | 0.3 mL/L for pasteurised + homogenised (see calculations.md note from cheddar batch — 0.2 mL/L gave a soft set; trying 0.3 next). Book doesn't list it. |
| Hot water for stretch | ~1.4 L at 95 °C | **~450 mL at 95 °C** | 1 mL per gram of milled curd; have extra on standby |

### Dosing TCC-20 from a 50 U packet

For a 4 L batch at the book rate (2.3 U / 11.4 L = 0.20 U/L — much hotter than Chr Hansen's standard ~0.01–0.02 U/L baseline, but normal for mozzarella where a fast ~4-hour drop to pH 5.25 is the design intent):

**Measured pack contents: 4.471 g for 50 U → 0.08942 g/U (89.42 mg/U).**

| Rate | U needed | % of 50 U pack | Mass to weigh | One pack covers |
|---|---|---|---|---|
| Book (0.20 U/L) | 0.81 U | 1.62 % | **72 mg** | 250 L = ~63 × 4 L batches |

Three approaches, best first:

1. **Weigh the powder** (0.01 g scale). Weigh the unopened packet, calculate 1.62 % of the gross-minus-foil weight, tip out that mass. Most accurate. Re-seal and freeze the remainder.
2. **Reconstitute and aliquot.** Tip the whole pack into 50 mL chilled, recently-boiled water → **1 U/mL** → dose **0.81 mL** by syringe. Use within a few hours; viability drops fast once rehydrated.
3. **Re-package once.** Open the pack indoors away from drafts, weigh-divide into 10 small foil envelopes (each = 5 U = ~25 L of milk at book rate), heat-seal, freeze.

Store the unopened pack frozen until use; treat the same as the R704 R704 pack — viability drops once opened, so weigh quickly and re-freeze the remainder.

### Expected yield

Cultured mozzarella typically yields **10–12 %** of milk weight.

| Yield | Book | Today |
|---|---|---|
| 10 % | ~1.17 kg | ~412 g |
| 12 % | ~1.40 kg | ~494 g |

At 200 g per ball, today's batch makes **2–3 balls** (or 3–4 smaller balls at 120–150 g).

## Equipment

- Stockpot or vat ≥ 6 L (for the 4 L batch)
- Thermometer (digital, ±0.5 °C)
- pH meter — **calibrated** (mill pH 5.25 is the make-or-break number; lessons from the cheddar batch apply)
- Long curd knife and a clean whisk
- Slotted spoon or curd ladle
- Colander and clean muslin/cheesecloth
- Heatproof bowl (3–4 L) for stretching
- Wooden spoon for stirring the stretch
- **Heat-resistant silicone gloves** — 95 °C water is dangerous; cotton oven mitts don't work (soak and conduct heat)
- Cold-water / ice-water bath bowl
- Storage container with cool water, in the fridge

## Targets — temperature and pH

| Stage | Temp (°C) | pH | Notes |
|---|---|---|---|
| Pre-culture (record) | 37 | record | Baseline before inoculation |
| Ripening | 37 | drift down | **1 hour**, stirring gently. **Maintaining 37 °C is critical** |
| Rennet addition | 37 | — | Stir in, then still for **50 min** total |
| Coagulation signs | 37 | — | Expect at ~25 min in |
| Cutting curd | 37 | — | One direction at 2 cm, then whisk-finish to 1 cm over 15 min — aim for cottage-cheese texture |
| Settle | 37 | — | 5 min for curds to sink |
| Drain | 37 | record | Pour off whey |
| Acidify in colander | warm, slowly falling | dropping | Turn every 15–20 min; **~4 h** to reach mill pH |
| Mill trigger | warm | **5.25** | Test whey running off the curd; verify with a stretch test (below) |
| Salt | warm | ~5.25 | 1.5 % w/w of actual milled weight |
| Stretch | curd into 95 °C water | — | Stir until single mass; lift, separate, shape |
| Cold bath | 4 °C | — | Set the shape |
| Storage | fridge | — | Cool water; use within 5 days |

The book's **fixed times** (1 h ripen, 50 min set, 4 h acidify) are targets. Drive transitions by pH and visible curd state where possible. The **mill pH (5.25)** is the most important number — it gates whether the curd will stretch.

## Decision rules — pH over clock, with a stretch test

### Mill pH

5.25 is the textbook number. Tolerable range:

- **5.30–5.25**: stretchable, milder flavour, slightly drier ball.
- **5.20–5.10**: classic mozzarella stretch, more tang, slightly wetter.
- **> 5.35**: curd won't melt into a single mass — crumbly cottage-style result.
- **< 5.05**: stretches but tears easily, sour flavour.

### Stretch test (more reliable than the meter)

Before milling, **test a small piece of curd**:

1. Take a walnut-sized lump from the curd block.
2. Drop it into a small cup of water at 75–80 °C.
3. After 30 s, prod it with a spoon.
4. **Stretches into a smooth, glossy ribbon ~30 cm before tearing** → pH is right, mill.
5. **Crumbles or won't elongate** → not yet; give it 15–30 min more and re-test.
6. **Tears at ~5 cm, ragged surface** → over-acid; mill immediately.

This is much more reliable than trusting an uncalibrated pH meter — the stretch test is the actual physical property you care about.

### Trigger windows for acidification

| t (from drain) | Action |
|---|---|
| 0–2 h | Don't stretch-test yet; pH still well above target |
| 2–5 h | Stretch-test every 30 min; mill at first good stretch |
| > 5 h, no good stretch | Investigate — curd cooling, culture stalling, meter drift. Re-warm the colander, give it another hour, but don't push past 6 h |

### Asymmetric risk

- **Mill too high**: cheese won't form a single mass. Lose the batch.
- **Mill too low**: cheese forms but is sour and tears. Edible but inferior.

→ When in doubt, **err slightly low** (5.20 over 5.30). **Opposite asymmetry from cheddar** (where over-acid is the worse failure mode).

## Process — book steps

Transcribed from *Home-made Cheese* (Paul Thomas) with today's numbers.

1. **Heat** milk to **37 °C**, stirring. **Maintaining 37 °C throughout is critical** (use a bain-marie, induction at lowest setting with frequent stirs, or an insulated pan). Record pH₀.
2. *(Optional, recommended for pasteurised/homogenised milk)* **Add CaCl₂** — **1.2 mL** of 32 % solution (= 0.3 mL/L) diluted in a splash of water. Stir in.
3. **Inoculate** with TCC-20 (today: **0.81 U** = **72 mg** = 1.62 % of the 50 U pack). Sprinkle over the milk surface, wait 1 min for rehydration, then stir through. Leave to stand **1 hour** at 37 °C, stirring gently every 10–15 min (also keeps the cream layer incorporated on non-homogenised milk).
4. **Add rennet** (today: **0.88 mL** of 1:10,000 in ~15 mL water), stir in for ~30 s, then leave to stand still **50 min** at 37 °C. Coagulation signs should appear by **25 min**; full set at 50.
5. **Check for clean break.** Cut the curds in **one direction only at 2 cm** spacing, then **stir gently with a whisk** to finish the cut over **15 min**, aiming for **1 cm cubes**. Stop if cubes get too small. Aim for cottage-cheese consistency.
6. **Allow the curds to sink** as the whey separates. **Settle 5 min.** **Drain off the whey** into a colander lined with muslin.
7. **Acidify the curd in a warm place** — wrap the colander in towels with a warm water bottle alongside, or set over (not in) a pan of warm water. **Turn the curd block every 15–20 min** to help drainage. Hold temperature ~32–37 °C through this phase — same lesson as the cheddar batch.
8. **Test pH** of any whey running off. Target **5.25**; expect **~4 h total** from drain, longer if curds cool. **Verify with the stretch test before milling.** Curd should feel **springy**.
9. **Mill the curd** by hand into ~1 cm chunks. **Weigh the curd**, compute **1.5 % salt**, sprinkle and mix.
10. **Stretch.** Put milled, salted curds into a heatproof bowl. Add **1 mL per g of milled curd of water at 95 °C** (today: ~450 mL for ~450 g curd). Stir with a wooden spoon until the curds melt into a single mass. The water will go cloudy.
11. **Shape.** By hand (gloves on), lift the mass, separate into pieces ~200 g each, stretch, and shape into balls. **Don't overwork** — makes the curd tough and rubbery.
12. **Smooth.** Fold each ball in on itself until the surface is smooth and glossy. Keep it hot by re-immersing briefly in hot water if it cools and starts to tear.
13. **Preserve** in cool (not cold) water. Use immediately, or refrigerate in cool water. **Use within 5 days** for cow's milk; less for buffalo.

## Stretching technique notes

- **95 °C water is just below boiling.** Splashes from stirring can scald instantly. Gloves on, sleeves down, stand back when pouring.
- **Pour the water down the side of the bowl**, not directly onto the curds — reduces splash.
- **Stir slowly** at first; the curds will start to merge in ~30 s.
- If the mass cools and stops merging, **top up with another 100–200 mL of fresh 95 °C water** and continue.
- **The pull test**: lift a portion with the spoon; it should stretch into a smooth ribbon ~30 cm before tearing. If it tears at ~5 cm, the curd is over-acid or under-hot.
- **Working temperature**: keep the curd ~60–70 °C while shaping. Below ~55 °C it stops being plastic; above ~75 °C it starts to feel like glue.

## Storage

- **First**: cold-water bath (tap water + ice) for 5 min to set the shape and stop further softening.
- **Then**: cool tap water in a sealed container, in the fridge.
- **Alternative**: light brine (~3 % salt) for storage — extends shelf life by 1–2 days and maintains internal salt level.
- **Eat within 5 days** for cow's milk mozzarella. Best in the first 48 h.

## Quick-reference timeline (today, 4 L)

| t | Stage | Action |
|---|---|---|
| 0:00 | Warm to 37 °C | Record pH₀; CaCl₂ in |
| 0:05 | Culture in | 0.81 U TCC-20 |
| 1:05 | Rennet | 0.88 mL diluted |
| 1:30 | Floc signs expected | Note time |
| 1:55 | End of 50-min set | Test for clean break |
| 2:00 | Cut directional, 2 cm | |
| 2:00–2:15 | Whisk-finish to 1 cm | Cottage-cheese consistency |
| 2:20 | Settle | |
| 2:25 | Drain | Record pH |
| 2:25 onwards | Acidify in warm colander | Turn every 15–20 min |
| 4:30 | First stretch-test | |
| ~5:30–6:30 | Reach pH 5.25 / good stretch | Weigh curd, measure 1.5 % salt |
| +5 min | Mill, salt, mix | |
| +5 min | Add 95 °C water, stir | Single mass forms |
| +10–20 min | Shape into 200 g balls | Smooth and glossy |
| +5 min | Cold-water bath | Set shape |
| Then | Into cool water in fridge | Eat within 5 days |

Total active time: **~6–7 h start to finish**; most of it is the 4-hour acidification wait, during which you can do other things. The stretching itself is fast — 15–20 min from mill to balls in cool water.

## Notes & open questions

- **CaCl₂ not in the book recipe** but added here on the back of the cheddar experience — pasteurised/homogenised milk benefits from it.
- **Pack viability.** TCC-20 is freeze-dried; treat like R704 — keep frozen until use, weigh quickly when opening, re-seal and re-freeze the remainder. Cold-chain hiccups in delivery are a known risk.
- **Buffalo milk** would change the recipe slightly (faster acidification, higher fat → higher yield ~14 %). Stick with cow's for first attempts.
- **Stretch-water alternative.** Some recipes use an 80–85 °C bath instead of 95 °C pour-over. Lower splash risk, slower softening. Stay with the book's 95 °C unless burns are a real concern.
- **Acidification temperature.** Cheddar batch showed acid generation crashes if curd cools to ambient. Plan an active warming setup (bain-marie / hot-water-bottle wrap / oven on lowest setting) for the 4 h acidification window.

## Cross-references

- [calculations.md](../calculations.md) — IMCU dosing, DCU conversions, brine/salt formulas, pH milestones
- [cheddar.md](cheddar.md) — same source (Paul Thomas), same milk-volume scaling pattern; lessons on uncalibrated pH meters and curd-warming carry over
- [log.md](../log.md) — record this batch when made
