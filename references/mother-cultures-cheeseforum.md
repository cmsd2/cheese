# Mother cultures from DVI

**Source:** Cheese Forum thread (cheeseforum.org), Jan–Feb 2011. Contributors: *Scarlet Runner* (OP), *Sailor Con Queso*, *linuxboy*, *ArnaudForestier*.

A long thread on whether and how to grow your own bulk (mother) culture from a freeze-dried DVI packet, to stretch a packet across many makes and gain the consistency that fresh culture brings.

## Why bother

DVI (direct-vat inoculation / DVS) packets are convenient and shelf-stable, but each make consumes a measured dose. Growing a **mother culture** from a small pinch of DVI lets one packet inoculate many batches at a fraction of the cost, and a *fresh* mother culture also gives:

- A shorter, more predictable lag before acidification — useful for hitting the **0.1 pH drop → rennet** trigger reliably.
- Stronger curd set due to more accurate bacterial population at rennet time.
- Better batch-to-batch consistency, *if* you re-make from DVI on a regular cycle.

## The method (Sailor Con Queso's photo essay)

1. Use a **tiny pinch** of DVI — not the whole packet. Smaller inoculum better preserves the original strain proportions and reduces contamination/mutation risk.
2. Sterilise ~1 quart of skimmed (or 1 %) milk by holding in a hot water bath; cool to the strain's optimum temp.
3. Inoculate, hold at the strain's optimum temp until coagulation just shows.
4. Refrigerate immediately at saturation pH (see below) to halt acidification.
5. Use fresh from the fridge within ~2 weeks; freeze the remainder in small aliquots (ice-cube trays) for 1–6 months.

## Form vs ripening time

How long the milk needs to ripen *before* adding rennet depends on how awake the bacteria are:

| Form | Ripening time | Notes |
|---|---|---|
| DVI / DVS powder | ~30 min | Cells must rehydrate and reactivate |
| Frozen mother-culture cube | 15–20 min | Cells must thaw and wake; temper in warm milk to shorten |
| **Fresh** mother culture | ~5 min | Cells already active — basically just disperse and rennet |

Without a pH meter, **15 minutes** is a safe default after adding a frozen cube.

## Storage

- **Fresh mother culture** in the fridge: stable ~2 weeks. As cells die over time, **progressively use more** to keep live cell count consistent. After 2 weeks at saturation pH, ~**20 %** cell death from the starting population.
- **Saturation (storage) pH**: ~**4.6** for mesophilic, ~**4.1** for thermophilic.
- **Fridge temp**: ~**1 °C** (34 °F).
- **Frozen** cubes: 1–6 months. Cell death is much slower for the first few months. Fast freezing (small ice crystals) is better than slow freezing.

If pulling a frozen cube, you can drop it into a small glass of warmed milk to thaw while the main pot comes up to temp.

## Dosing mother culture

Standard rule: **1–2 %** of milk volume (the usual bulk equivalent for most cheeses), occasionally up to 4 % for fast-set lactic curds.

Cube-based rule of thumb: **1–4 ice-cube-sized cubes per US gallon** of milk, picking within the 1.5–2 % band by weight.

A standard ice cube is ~30 mL:

| Cubes per US gallon (3.785 L) | Volume % |
|---|---|
| 1 | 0.79 % |
| 2 | 1.59 % |
| 3 | 2.38 % |
| 4 | 3.17 % |

So 2–3 cubes per gallon hits the canonical 1.5–2 % window. Adjust for cube size if yours aren't 30 mL.

## Re-culturing from cubes — generally don't

You *can* propagate culture-from-culture for several generations, but unless you have microbiological training, strain proportions drift and contamination accumulates. The recommended practice for amateurs:

- Make a fresh mother culture **directly from DVI** for each batch (or each cycle of batches).
- Don't propagate from a cube into a new mother culture.
- Size each fresh mother culture to your anticipated 1–3 day make schedule (e.g. for a weekend with 3 makes, mix a primer big enough for those three).

This is presented in the thread as a hybrid of true factory-style daily mother-culturing and straight DVI-into-vat: you get the consistency of DVI sourcing with the freshness benefits of mother culture.

## Holding the incubation temperature

Mesophilic strains differ widely in optimum growth temperature — you can't blanket-culture them all at the same temp. **Flora Danica is not the same as a cheddar culture.** Get the optimum from the strain's spec sheet.

Generic-ish defaults seen in the thread:

- Meso *room-temp* incubation works at 60 °F / 16 °C but is slow; 70–86 °F / 21–30 °C is more typical depending on strain.
- An oven with **just the bulb on** maintains ~75–78 °F (24–26 °C) for many ovens and is a reasonable amateur incubator.

Plastic milk jugs sometimes fail in the hot-water sterilisation step; a Mason jar is more reliable.

## Why DCUs work as a proxy

The DCU unit (Danisco) is engineered so that **1 % bulk-starter equivalent ≈ 6.5 DCU per 100 L** of milk. Underlying assumption: a healthy bulk starter has ~**2 × 10⁹ CFU/g**. Commercial production assumes 5–10 % viability loss from the packet, which is negligible for our purposes.

In a *mother* culture, DCUs are less meaningful — you're aiming for peak population at the moment of harvest, then halting. Even if some of the seed DVI cells were dead, the live ones bloom and dominate; the culture just takes a touch longer to set.

## Practical takeaway

For a typical home make:

- Grow a small mother culture every 1–2 weeks from a pinch of DVI.
- Use fresh from the fridge by preference; freeze cubes for buffer.
- Dose 1.5–2 % of milk volume (or 2–3 standard cubes per US gallon).
- Don't over-engineer: 1 % vs 1.5 % is ~10 min of make-time difference, not a different cheese. The pH targets drive the make, not the inoculum size.

## Aside — a contested worked example

ArnaudForestier tried to convert a tomme recipe given as "2.5 DCU per 500 lb milk, doubled for pasteurised milk = 5 DCU/500 lb" into a bulk percentage for a 4 US gal batch, and got **2.27 % bulk equivalent**.

Re-running the calculation:

```
batch:        4 US gal = 15.14 L = 15.60 kg = 34.38 lb
DCU/batch:    5/500 × 34.38         = 0.344 DCU
DCU/100 L:    0.344 / 15.14 × 100    = 2.27 DCU per 100 L
bulk %:       2.27 / 6.5             = 0.35 %      ← correct bulk %
```

The 2.27 figure is **DCU per 100 L**, not a percentage. Paul read it as a percentage and his spreadsheet drove a 343.7 mL primer dose into 15.14 L of milk — which coincidentally is also 2.27 % by volume, so the mistake was self-reinforcing.

linuxboy's reply ("2.27 is too high for a tomme, max 1.5 %") corrects the symptom but the underlying recipe figure (0.35 %) is suspiciously low — likely a transcription error in the original recipe Buck47 supplied (possibly 25 DCU/500 lb, or 2.5 DCU per smaller weight). The thread's real takeaway is just: **start at 1–1.5 % for tomme**, don't try to back-derive percentages from contested DCU figures.
