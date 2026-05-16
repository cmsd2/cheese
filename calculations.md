# Calculations

Handy formulas and conversions for cheese-making. Fill in supplier-specific strengths (rennet IMCU, culture units per pack) once known — placeholders are marked **[TODO]**.

## Yield

Rough rule of thumb (whole cow's milk):

- Fresh cheeses (ricotta, paneer, queso fresco): **10–15 %** of milk weight
- Soft-ripened (camembert, brie): **12–15 %**
- Semi-hard (gouda, tomme): **10–12 %**
- Hard aged (cheddar, parmesan): **8–10 %**

So 4 L milk (≈ 4.12 kg at 1.03 g/mL) → ~410 g hard cheese, ~500 g fresh.

## Milk density

Whole cow's milk ≈ **1.03 g/mL**. Convert litres ↔ kg by multiplying / dividing by 1.03.

## Rennet dosing

Rennet strength is given in **IMCU** (International Milk Clotting Units). A typical liquid calf rennet is ~200 IMCU/mL.

Target dose for a 30–45 min flocculation at ~32 °C:

```
mL rennet = (litres of milk × target IMCU per litre) / rennet IMCU per mL
```

Common target: **40–60 IMCU per litre** of milk. Example, 8 L milk with 200 IMCU/mL rennet at 50 IMCU/L:

```
mL = (8 × 50) / 200 = 2 mL
```

Halve the dose roughly if using double-strength; double it for tablets per pack instructions.

Always dilute rennet in **20× its volume** of cool, non-chlorinated water before stirring into the milk for 30 seconds, then still the milk.

**My rennet strength:** [TODO — fill in IMCU/mL from bottle]

## Flocculation multiplier

Time from rennet addition to floc point × multiplier = total time to cut.

| Style | Multiplier |
|---|---|
| Soft / lactic | 5–6 |
| Camembert / brie | 4–5 |
| Semi-hard (gouda, tomme) | 3–3.5 |
| Hard (cheddar, alpine) | 2.5–3 |

## Culture dosing

Freeze-dried direct-vat-set (DVS) cultures are sold in units (often **U** or **DCU**) sized for a given volume — e.g. 1 U for 100 L milk. For small home batches you typically use **1/8 to 1/4 tsp** per 4–8 L.

**My culture:** [TODO — name, type (meso/thermo), recommended dose per litre]

Rehydrate by sprinkling on the surface of warmed milk and waiting 2–5 minutes before stirring in.

### Inoculation % by style

Recipes are usually expressed as a **percentage by volume of bulk (mother) starter** added to the milk. Match the starter % to the style:

| Style | Bulk % |
|---|---|
| Tommes; soft continental; styles draining at high pH and acidifying in the mould | 1.0 % |
| Gouda; most Spanish/continental | 1.0–1.5 % |
| Hard Italian; semi-lactic | 1.5 % |
| Most workhorse hard cheeses | 1.5–2.0 % |
| Cheddar; pasta filata (cheddared curd) | 2.0 % |
| Cultured mozzarella | 2.0–3.0 % |
| Lactic curd (fast vs slow set) | 1.5–4.0 % |

Default: **start at 1 %** for a new style and adjust from there.

The % is mostly about **make time and acidity curve**, not flavour intensity. Bumping % shortens the make but you must then drive every decision by **pH, not the clock**.

### DCU / DVS ↔ bulk % conversion

| Bulk % | Danisco DVI (DCU/100 L) | Chr Hansen DVS or frozen pellet (U or g per 100 L) |
|---|---|---|
| 0.50 % | 3.25 | 5 |
| 1.00 % | 6.5 | 10 |
| 1.50 % | 9.75 | 15 |
| 2.00 % | 13.0 | 20 |

Linear, so:

```
Danisco:    DCU      = (litres × bulk_percent × 6.5) / 100
Chr Hansen: U or g   = (litres × bulk_percent × 10)  / 100
```

At 1 % Danisco, **1 DCU ≈ 15.4 L** of milk. (A separate post by the same author rounds this to 6.25 DCU/100 L → 16 L per DCU. ~5 % discrepancy, not material for home batches.)

Worked example — 8 L at 1 % bulk equivalent, Danisco:

```
DCU = (8 × 1 × 6.5) / 100 = 0.52 DCU
```

For larger vats per pack, you compensate by **ripening longer** before rennet — one extra doubling period roughly doubles the bacterial count.

### Rennet rate vs pH and temp

Rennet acts fastest at **pH ~5.4** and **42 °C**. It is dramatically slower outside that window — same milk, same rennet dose: **~3 min to set at pH 5.5, ~15 min at pH 6.5**. Useful for sanity-checking unusual flocculation times.

### Rennet — industry rule of thumb

Single-strength rennet (~200 IMCU/mL): **9 mL per 100 lb milk** (≈ 44 L) → ~0.20 mL/L → **≈ 41 IMCU/L**. Sits at the low end of the 40–60 IMCU/L range above, suiting a slower, gentler set.

### Mother-culture cube dosing

A standard ice-cube tray cube ≈ 30 mL. For a US gallon (3.785 L) of milk:

| Cubes / US gal | Volume % |
|---|---|
| 1 | 0.79 % |
| 2 | 1.59 % |
| 3 | 2.38 % |
| 4 | 3.17 % |

→ **2–3 cubes per US gallon** hits the canonical 1.5–2 % bulk window. For a litre-based batch:

```
cubes ≈ (litres × bulk_percent × 10) / 3.785 / cube_mL × 100  (approx)
```

Quick check — 8 L at 1.5 %: 120 mL of mother culture, which is **4 cubes** of 30 mL.

### Ripening time before rennet, by culture form

| Form | Ripening | Why |
|---|---|---|
| DVI powder | ~30 min | Cells must rehydrate |
| Frozen mother-culture cube | 15–20 min | Cells must thaw and reactivate |
| Fresh mother culture (from fridge) | ~5 min | Already active — basically disperse and rennet |

Default without a pH meter: wait until you see the **0.1 pH drop** trigger, or fall back to the timing in the recipe.

### Mother-culture storage

| Parameter | Value |
|---|---|
| Storage / saturation pH (meso) | 4.6 |
| Storage / saturation pH (thermo) | 4.1 |
| Fridge temp | 1 °C (34 °F) |
| Useful fresh life in fridge | ~2 weeks |
| Cell loss after 2 weeks at saturation | ~20 % |
| Frozen cube life | 1–6 months (fast freeze better) |

To compensate for cell death, **progressively increase dose** as a fresh mother culture ages — e.g. roughly +10 % volume in week two.

### Where 6.5 DCU/100 L comes from

Underlying assumption: a healthy bulk starter has ~**2 × 10⁹ CFU/g**. The DCU unit is sized so that **6.5 DCU/100 L** delivers the cell count of a 1 % bulk-starter inoculation. Commercial loss-of-viability assumption: 5–10 %, negligible for home use.

---

*Inoculation %, DCU conversion, and rennet-rate figures: see [references/inoculation-percentages-cheeseforum.md](references/inoculation-percentages-cheeseforum.md) and [references/scaling-milk-volume-cheeseforum.md](references/scaling-milk-volume-cheeseforum.md).*

*Mother-culture dosing, storage, ripening times, and the DCU derivation: see [references/mother-cultures-cheeseforum.md](references/mother-cultures-cheeseforum.md).*

## Calcium chloride

For pasteurised / homogenised shop milk, add **CaCl₂** to restore set:

- **0.2 mL of 32 % solution per litre of milk** (≈ 1/4 tsp per 4 L)
- Dilute in ~20× water before stirring in, just before rennet.

Skip for raw milk.

## Salt

Dry-salted curd: **1.5–2.5 % of drained curd weight**.

Brine for hard cheeses — saturated brine:

- **230 g non-iodised salt per 1 L water** (≈ 18–20 % w/w)
- 1 tsp CaCl₂ (32 %) per litre brine
- ~1 tbsp white vinegar per litre to bring pH to ~5.2
- Chill to **12–14 °C** before use.

Brining time: roughly **1 hour per 500 g of cheese, per inch of thickness**, flipped halfway.

## Acidity targets (pH)

| Stage | pH |
|---|---|
| Fresh milk | 6.6–6.7 |
| Rennet addition | 6.5–6.55 |
| Cutting curd (most styles) | 6.4–6.5 |
| Draining (cheddar) | 6.1–6.3 |
| Milling (cheddar) | 5.2–5.4 |
| Pressed cheese into brine | 5.1–5.3 |

## Temperature conversions

°F = °C × 9/5 + 32. Common cheese temps:

| °C | °F |
|---|---|
| 22 | 72 |
| 30 | 86 |
| 32 | 90 |
| 38 | 100 |
| 54 | 130 |

## Affinage

- **Cave temp:** 10–13 °C
- **Humidity:** 85–95 %
- Wine fridge or insulated box with damp sponge works for home setups.
