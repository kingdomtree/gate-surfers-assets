# GATE SURFERS — Prompt Assembly (FRAME)

Use this structure for every shot and sheet generation. One generation at a time. Strip markdown when pasting into the model.

```
[ANCHOR]     Visual Bible section 1, verbatim, every time
F  FOCUS     Who or what. The locked character block, or the prop block
R  REGION    Where. Gate mouth, throat, span, Tank, threshold. Section 10
A  ANGLE     Camera. Position, height, distance, lens, movement
M  MOOD      Light and color. Section 3 and section 4
E  EFFECT    Restate two technique words. Heavy ink, hard two-tone
[NEGATIVE]   Section 2 global, plus the block's EXTRA NEGATIVE
```

## Order of paste

1. **[ANCHOR]** — Visual Bible §1, word-for-word. Never edit.
2. **F FOCUS** — Locked character block (sex-first, body, costume) or prop block. Attach approved reference sheets when available.
3. **R REGION** — Location from Visual Bible §10 (Gate mouth / throat / span / Tank / threshold, etc.).
4. **A ANGLE** — Camera: position, height, distance, lens, movement.
5. **M MOOD** — Light and color from Visual Bible §3–4.  
   - Sheets: flat even neutral, mid-grey, no dramatic shadow.  
   - Shots: hard single-source chiaroscuro (half the face in flat black).
6. **E EFFECT** — Always restate: heavy black ink linework with brush weight variation; hard two-tone cel shading, no gradients.
7. **[NEGATIVE]** — Visual Bible §2 global negative, then append that block’s EXTRA NEGATIVE (if any).

## Sheet vs shot

| Mode   | Lighting override                         | Background              |
|--------|-------------------------------------------|-------------------------|
| Sheet  | Flat even neutral. No dramatic shadow.    | Plain mid-grey only.    |
| Shot   | Anchor chiaroscuro is binding.            | Region from §10.        |

## Rules

- One generation at a time.
- Never paste the whole Visual Bible.
- Character sheets override lighting only; everything else in the anchor stays.
- Real calibers / prop language / tosei-gusoku / frosted shark scale: use the locked prop or character block, do not improvise.
- Sex-first on every character FOCUS line.
- No illuminated optics, no polymer, no picatinny clutter, no helmets.

## Filing

Approved outputs:
```
GS_CHAR_<NAME>_DIRT_vXX.png
GS_CHAR_<NAME>_HARNESS_vXX.png
GS_CHAR_<NAME>_EXPR_vXX.png
GS_PROP_<NAME>_vXX.png
GS_PLATE_STYLE_vXX.png
GS_PLATE_CONTACT_vXX.png
GS_PLATE_FORMATION_vXX.png
GS_SHOT_<EP>_<S>_vXX.png
```
Bump version. Never overwrite.

