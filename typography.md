# Typography

## Active roles

| ID | Source | Allowed roles |
| --- | --- | --- |
| 1 | Removed | Do not use |
| 2 | Deferred | Future alternative to type 3 |
| 3 | assets/type-03-handwriting-reference.png | Title or all content |
| 4 | Devanagari Sangam MN Regular | Supporting paragraphs, dates, addresses and small text |
| 5 | Basier Square Mono Regular | Supporting text or specimen labels |

Type 2 is not currently enabled.
Do not invent its trigger keywords or substitute a font for it.
Its font and keyword routing will be configured later.

## Type 3 — image-guided handwriting

Inspect assets/type-03-handwriting-reference.png before generating lettering.

This image is a lettering reference only.
Do not copy its event wording, dates, colored panels or layout.

### Shared characteristics

- Individually drawn, mostly disconnected letters.
- Thin to medium pen strokes.
- Uneven letter heights and baseline.
- Naturally changing tilt and spacing.
- Open counters.
- Slight wobble and occasional retracing.
- Casual doodle character.

Avoid polished calligraphy, mechanical consistency and generic brush lettering.

### Variations within the reference

The top black lettering is thin, airy and loosely constructed.
Use this as the default letterform direction.

The middle red lettering is larger and more playful.
Use it as an optional energy variation.

The bottom green time lettering is heavier and slanted,
while its address lettering is quieter.

Do not force all variations into one poster.
Choose a coherent treatment appropriate to the supplied content.

### Roles

Type 3 may be used:

- Across the whole poster, with hierarchy mainly established by size.
- For titles only, paired with type 4 or type 5.

Preserve readability in small text.
If generated small lettering is unreliable, use an enabled supporting font.

Image-guided lettering is a stylistic interpretation,
not an exact font or a verified complete alphabet.

## Type 4 — supporting text

Font: Devanagari Sangam MN.
Preferred face: Regular.

Use for:

- Paragraphs.
- Short descriptions.
- Dates and times.
- Addresses.
- Other practical small text.

Type 4 may be used only for dates and addresses when no paragraph is present.
It must not be the sole typography family for an entire poster.
Do not use it as the display title.

No replacement supporting fonts are configured yet.

Resolve the font from a supplied file or the local environment.
On the user's current Mac, the supplied collection is:

/System/Library/Fonts/Supplemental/Devanagari Sangam MN.ttc

Before typesetting, verify the collection face and required glyph coverage.
Do not silently render fallback glyphs and identify them as this font.

## Type 5 — supporting text and specimen labels

Font: Basier Square Mono.
Face: Regular.
Supplied filename: basier-square-mono-regular.ttf.

Resolve it from a user-supplied file or the local environment.
Do not assume a machine-specific Desktop path exists elsewhere.

Type 5 has two uses:

1. Replace type 4 for supporting text.
2. Provide specimen labels when a third hierarchy level is needed.

Examples of label roles:

- Category: WORKSHOP.
- Edition: VOL. 02.
- Index: NO. 03.
- Section marker: FIELD NOTES.

Do not invent labels merely to introduce another font.
Labels are not automatically the smallest text.

Basier Square Mono replaces the earlier provisional description
of type 5 as a distressed typewriter font.
Do not add artificial serif shapes or distressed ink by default.

## Enabled combinations

### 3 alone

Type 3 handles titles and supporting information.
Establish hierarchy chiefly through size and spacing.

### 3 + 4

Type 3: title.
Type 4: supporting paragraphs and practical information.

### 3 + 5

Type 3: title.
Type 5: supporting information.

### 3 + 4 + 5

Type 3: title.
Type 4: supporting paragraphs and practical information.
Type 5: specimen labels.

Choose the simplest combination that serves the content.

## Rendering

Use reference-guided image generation for type 3.

For types 4 and 5, use actual font files when exact typography is required.
Generate illustration with reserved text-free areas, then typeset separately.

Keep text editable when the output format supports it.
Do not claim exact named-font rendering from image generation alone.

## Specimen comparison

Compare the four enabled combinations using:

- The same title.
- The same short description.
- The same date and time.
- The same address.
- A label only where that role is being demonstrated.
- The same canvas, background and placement.

Mark invented specimen information as sample copy outside the artwork.
Do not present it as factual event information.

Check title scale, small-text readability, line spacing,
letter spacing and distinction between information roles.
