# Typography

## Reference files

For type 3 handwriting, inspect:

- assets/type-03-approved-poster.png — approved third-version poster.
- assets/type-03-handwriting-reference.png — original lettering reference.

The approved poster establishes the default lettering effect.
The original reference provides supporting letterform observations.

Use these images as lettering references only. Do not copy their wording,
event details, illustrations, backgrounds or layouts into unrelated work.

When using type 3, also read handwriting-layout.md.

## Active typography roles

| ID | Source | Allowed roles |
| --- | --- | --- |
| 1 | Removed | Do not use |
| 2 | Deferred | Future alternative to type 3 |
| 3 | Image-guided handwriting | Title or all content |
| 4 | Devanagari Sangam MN Regular | Supporting paragraphs and practical small text |
| 5 | Basier Square Mono Regular | Supporting text or specimen labels |

Type 2 is not currently enabled.
Do not invent its trigger keywords or assign a substitute font.
Its font and keyword routing will be configured later.

## Type 3 — light, relaxed handwriting

### Default character

Match the approved third-version poster:

- Fine pen strokes and light pressure.
- Airy, open letterforms.
- Mostly disconnected letters.
- Naturally varied proportions and spacing.
- Gentle differences in height and inclination.
- Slight contour wobble.
- Minimal retracing.
- A relaxed, unforced writing rhythm.

The result should feel written by hand with a fine pen.
Do not make it look like a mechanically consistent handwriting font.

Avoid heavy outlines, generic brush lettering, polished calligraphy,
excessive retracing and exaggerated crookedness.

Natural variation is the default.
More noticeable deviations should be occasional accents,
following handwriting-layout.md.

### Title

Use expressive letter construction without making the title overpower
the illustration or supporting information.

Preserve open counters and breathing room between letters.
Allow individual letters to differ without making every letter eccentric.

Follow the title-scale controls in SKILL.md unless the user specifies otherwise.

### Description and supporting information

Use the same light writing character at a smaller scale.

Keep descriptions, dates, times and locations readable.
Supporting text should feel quieter than the title rather than heavier
or equally dominant.

Do not force title-sized irregularity into small text.
Reduce variation when necessary to protect punctuation, numbers,
email addresses, handles and other exact information.

### Roles

Type 3 may be used:

- Throughout the poster, with hierarchy established mainly by size,
  spacing and placement.
- For titles only, paired with type 4 or type 5.

Do not switch to a different lettering style for every information block.

Image-guided handwriting is a stylistic interpretation,
not an exact font or a verified complete alphabet.

The supplied references primarily demonstrate Latin lettering.
Do not claim equivalent fidelity for an unsupported writing system.

## Type 4 — supporting text

Font: Devanagari Sangam MN.
Preferred face: Regular.

Use for:

- Paragraphs.
- Short descriptions.
- Dates and times.
- Addresses.
- Practical small text.

When no paragraph is present, type 4 may still be used for dates,
addresses and other practical details.

Do not use it as the display title or as the sole typography family
for an entire poster.

No replacement supporting fonts are configured yet.

Resolve the font from a supplied file or the local environment.

On the user's current Mac, the supplied collection is:

/System/Library/Fonts/Supplemental/Devanagari Sangam MN.ttc

Verify the collection face and required glyph coverage before typesetting.
Do not silently use fallback glyphs and identify them as this font.

## Type 5 — supporting text and specimen labels

Font: Basier Square Mono.
Face: Regular.
Supplied filename: basier-square-mono-regular.ttf.

Resolve it from a supplied file or the local environment.
Do not assume a machine-specific Desktop path exists elsewhere.

Type 5 may:

- Replace type 4 for supporting text.
- Provide specimen labels when a third information level is needed.

Examples of label roles:

- Category: WORKSHOP.
- Edition: VOL. 02.
- Index: NO. 03.
- Section marker: FIELD NOTES.

Do not invent a label merely to introduce a third font.
Labels are not automatically the smallest text.

Use the actual monospaced character of Basier Square Mono.
Do not add artificial serif shapes or distressed ink by default.

## Enabled combinations

### 3 alone

Type 3 handles titles and supporting information.
Establish hierarchy chiefly through size, spacing and placement.

### 3 + 4

Type 3: title.
Type 4: supporting descriptions and practical information.

### 3 + 5

Type 3: title.
Type 5: supporting information.

### 3 + 4 + 5

Type 3: title.
Type 4: supporting descriptions and practical information.
Type 5: specimen labels.

Choose the simplest combination that serves the content.
Do not introduce extra typography roles without a corresponding
information role.

## Rendering

For type 3, inspect the approved reference and use reference-guided
image generation or individually drawn lettering.

For types 4 and 5, use actual font files when exact typography is required.
Reserve text-free areas during illustration generation,
then typeset separately.

Do not claim exact named-font rendering from image generation alone.

Preserve editable text when supported by the output format.
Do not silently replace an unavailable font.

## Quality gate

Check that:

- Type 3 retains the approved poster's thin, light and relaxed character.
- Natural variation is visible without exaggerated distortion.
- Titles and supporting text belong to a coherent writing family.
- Supporting information remains comfortably readable.
- Exact wording, numbers and punctuation are correct.
- Selected typography roles and pairings are respected.
- Font substitution has not occurred without disclosure.
- Handwritten placement follows handwriting-layout.md.

## Specimen comparison

Compare enabled combinations using identical copy, canvas,
background and text regions.

Include a title, short description, date, time and location.
Include a label only when demonstrating that role.

Mark invented specimen information as sample copy outside the artwork.
Do not present it as factual event information.
