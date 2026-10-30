---
name: hand-drawn-editorial-poster
description: Create original editorial posters with sparse hand-drawn doodles, image-guided handwriting, configurable typography pairings, intentional negative space and tactile backgrounds. Supports storefronts, objects, food, concepts, source photographs and uploaded background images.
---

# Hand-Drawn Editorial Poster

## Purpose

Create original posters using economical doodles, expressive but controlled lettering and intentional open space.

Read references/visual-analysis.md for historical visual observations.
Read typography.md for active typography roles and pairings.

The production rules in this file and typography.md take precedence over conflicting defaults in the historical reference analysis. Never copy reference brands, event identities, artwork or exact layouts.

## Inputs

Accept any combination of:

- Theme, subject or event brief.
- Exact title and supporting copy.
- Source photograph.
- Uploaded background image.
- Handwriting reference.
- Font names or font files.
- Canvas size, palette or typography pairing.

Do not invent unknown factual event details.

Distinguish image roles:

- Style reference: learn visual characteristics only.
- Subject reference: preserve defining subject features.
- Background asset: use as the actual composition background.
- Lettering reference: learn letterform characteristics.
- Supporting insert: include a specified component.

One image may have multiple roles only when the user explicitly requests them.

## Illustration rules

### Doodle first

Use quick, economical strokes with visible human irregularity:
slight wobble, changing pressure, contour gaps and occasional overlaps.

Keep the subject recognizable with only a few defining cues.
Avoid polished vector outlines, photorealism and fully rendered scenes.

### Storefronts and buildings

Draw a sparse facade doodle rather than an architectural illustration.

Prioritize:

- Overall silhouette.
- Entrance.
- Main window arrangement.
- Distinctive canopy or sign shape.

Preserve distinctive proportions from a source photograph, while simplifying detail.

Omit interior equipment, furniture inventories, ornate cornices,
masonry patterns, individual leaves and dense crosshatching unless requested.

Do not compensate for an overly detailed drawing by changing typography.
Simplify the drawing first.

### Objects and food

Use an economical drawing with a few defining contours and marks.
Do not introduce storefronts or architecture around an isolated object.

### Abstract concepts

Choose one simple, concrete drawable metaphor.
Avoid unrelated doodles and gratuitous collage.

## Composition

Default canvas: portrait 4:5.

Aim for approximately 35–60% intentional open background.
This is a flexible design target, not a measured reference statistic.

Choose composition according to content:

- Title / doodle / supporting information.
- Lettering integrated into a signboard when appropriate.
- Two or three small symbols forming a visual sentence.
- Expressive title with a quiet, smaller doodle.

Vary placement, spacing and subject scale across outputs.
Do not repeat the same storefront layout for every subject.

## Title scale

Use a provisional title bounding-box height of 15–25% of canvas height,
including all title lines, and a maximum width of approximately 80%.

These are operational starting points, not historical reference measurements.
They implement the preference for a smaller title after the initial evaluation.
The original skill had no numeric title range.

Expressiveness should come from letterforms, rhythm and spacing,
rather than automatically enlarging the title.

Explicit user sizing overrides these defaults.
If strict numeric compliance is requested, measure the finished layout;
prompt percentages alone do not guarantee dimensions.

## Typography

Follow typography.md.
When using type 3 handwriting, also read handwriting-layout.md.

- Type 1 is removed.
- Type 2 is deferred.
- Type 3 is the active image-guided handwriting.
- Type 4 is supporting text only.
- Type 5 is supporting text or specimen labels.

Retain readable small-copy scale.
Do not shrink practical information merely to create hierarchy.

Use only as many typography roles as the content needs.
Do not add a third font without a third information role.

## Palette and texture

Default to one dominant ink color on a quiet background.

Allow restrained accents or reversed light ink on dark backgrounds.
Do not enforce black and cream for every subject.

For generated backgrounds, use subtle paper fibers, grain or print irregularity.
Avoid heavy grunge, stains, torn edges and decorative aging unless requested.

## Uploaded backgrounds

Inspect a supplied background and use it as the actual editing or compositing base.

Preserve its recognizable content, colors and texture.
Do not replace it with generated cream paper or automatically add grain.

Fit without stretching.
Choose a crop that preserves important content; clarify if unavoidable cropping
would remove a meaningful feature.

Place text and drawing over quiet areas and select contrasting ink.
If readability requires altering the background, explain the proposed adjustment.

When exact pixel preservation matters, use separate overlays and compositing.
Do not claim that generative editing guarantees unchanged background pixels.

## Font rendering

Distinguish image-guided lettering from exact font typesetting.

For type 3:
inspect the supplied lettering reference and generate related hand lettering.
Do not claim an exact font or a verified complete alphabet.

For exact named fonts:
verify the font file and required glyphs, reserve text-free areas during image
generation, then typeset using the actual font in a separate layout step.

Do not silently substitute an unavailable font.
Request the font file or agree on an alternative.

Preserve editable text when supported by the deliverable format.

## Modes

- Analyze: describe visual rules without generating an image.
- Generate: interpret the brief, choose composition and typography,
  compile a prompt, generate, inspect and revise when needed.
- Prompt only: provide a production-ready prompt without claiming generation.
- Analyze + Generate: extract reference characteristics, then create new artwork.

## Prompt compiler

Include, in order:

1. Subject, defining features and exact supplied copy.
2. Composition, title scale, doodle placement and negative space.
3. Typography roles, selected pairing and rendering method.
4. Sparse drawing technique and details to omit.
5. Background role, preservation requirements and ink contrast.
6. Exclusions: copied identities, photorealism, polished vectorism,
   dense rendering, unnecessary ornaments and invented event information.

Use concrete visual relationships rather than abstract style adjectives alone.

## Quality gate

Inspect the actual result for:

- Correct supplied wording.
- Recognizable subject.
- Sparse doodle character rather than architectural rendering.
- Visible human line irregularity.
- Clear hierarchy at thumbnail scale.
- Controlled title size and readable supporting copy.
- Correct typography roles and pairing.
- Intentional open background.
- Restrained palette and texture.
- Preservation of supplied background requirements.
- Original composition rather than reference copying.
- No invented factual event details.

A recognizable building can still fail if it is excessively detailed.
Readable lettering can still fail if the title overwhelms the page.

Revise material failures when possible.
Report remaining limitations honestly.
