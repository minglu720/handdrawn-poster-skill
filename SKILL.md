---
name: hand-drawn-editorial-poster
description: Create original editorial event posters with expressive hand-drawn line illustrations, loose typography, intentional negative space and tactile paper/ink qualities. Works with storefronts, buildings, objects, food, concepts, photographs and user-provided event details. Use for generating posters, analyzing references, or compiling production prompts.
---

# Hand-Drawn Editorial Poster Skill

## Purpose
Turn user content into an original, recognizable yet flexible hand-drawn poster system. Learn visual grammar from the seven study references; never replicate specific brands, event identities, artwork or exact layouts.

This review draft uses the installed skill’s references/visual-analysis.md as historical analysis. The production overrides below take precedence. Original installed files remain unchanged.

## Input
Accept a theme, event brief, exact text, single object, storefront/building, source photograph, intended platform or size, desired color, or additional references. All fields are optional unless exact event information needs to be displayed. Do not invent unknown factual event details.

Distinguish image roles: **style reference** (style only), **source/edit target** (preserve defining features), and **supporting insert** (specified object/component). If a user supplies a specific subject photograph, prioritize its recognizable structure.

## Core rules
1. **Human line, readable structure.** Use organic, moderately irregular contours, variable pressure and occasional overlaps. Keep the form legible; avoid sterile uniform vector linework.
2. **Selective drawing, not tracing.** Preserve recognizable cues; omit unnecessary detail. Architectural motifs can show simplified windows, doors, awnings and hatching; isolated objects should not be rendered as storefronts.
3. **Editorial hierarchy.** Coordinate an expressive title, one focal illustration, and clearly readable supporting information. Lettering may vary between handwriting, cursive and quiet non-serif supporting lettering.
4. **Paper is part of the composition.** Allow meaningful open background and modest tactile grain. Paper must not automatically mean heavy faux-vintage distress.

## Adjustable design controls (defaults, not source measurements)
- Canvas: portrait 4:5 unless specified otherwise.
- Negative space: aim for ~35–60% open page; flex with copy length and subject complexity.
- Palette: one ink + paper by default. Optional monochromatic reverse treatment or a restrained accent. Never enforce black-and-cream if subject warrants color.
- Texture: low-to-moderate paper flecks and print irregularity, not muddy noise.
- Typography: no required font family; handwritten title and legible details is a strong default.

## Decide illustration pathway
- IF a storefront/building is supplied → study its silhouette, entrance, windows, canopy and distinguishing visible features; produce a sparse facade doodle, not an architectural drawing.
- ELSE IF a singular object or food is supplied → draw an economical icon-like object with a few distinctive contours and marks.
- ELSE IF an abstract concept is supplied → propose one simple, concrete drawable visual metaphor; avoid gratuitous collage.
- IF a detailed scene is drawn → reduce lettering flourishes and ornaments.
- IF a very simple symbol is drawn → allow more idiosyncratic letterforms within the title-size cap below.
- IF text is lengthy → limit expressive handwriting to headline and use precise readable type for logistics.
- IF dark colored paper is requested → use light/reversed ink and preserve contrast.

## Layout selection — choose by content, not at random
A. **Title / illustration / details**: a clear vertical editorial hierarchy.
B. **Illustration as signboard**: handwriting integrated into the drawn subject when semantically appropriate.
C. **Symbolic stack**: two or three small drawn elements forming a visual sentence, useful for food, time or a concept.
D. **Expressive calligraphy plus quiet drawing**: title carries emotional weight; small accurate drawing and footer.
Vary architecture, spacing and subject scale across outputs rather than repeating one arrangement.

## Modes
- **Analyze**: summarize evidence and fixed/variable rules; do not generate an image unless asked.
- **Generate**: parse brief → choose subject pathway, palette, title hierarchy and layout → write final image prompt → generate image with available generation capability → inspect results.
- **Prompt only**: provide production-ready prompt without claiming an image was generated.
- **Analyze + Generate**: first extract rules and then produce a new poster.

## Image prompt compiler
For each output, assemble these instructions in order:
1. Concrete original subject and necessary preservation features, with title and supplied information.
2. Selected layout and positioning of drawing, typography and negative space.
3. Illustration technique, line character, selective details, paper material, ink palette.
4. Exclusions and quality constraints: no copied names/artwork, no photorealism or polished vectorism, no clutter or unnecessary ornaments.
Use clear nouns and visual relationships rather than only abstract adjectives.

## Quality gate
Confirm: (1) correct user-supplied wording where text is essential, (2) recognizable subject when required, (3) visible hand-drawn irregularity, (4) confident visual hierarchy at thumbnail scale, (5) paper and background retained as an intentional part of design, (6) palette restrained, (7) not a copy of a reference, (8) no hallucinated event details. If a generated image fails, revise the prompt and retry when possible. For exact typographic fidelity, warn that image generation may require later layout editing.

## Examples
- “用这个 skill 把我上传的咖啡店照片做成开幕活动海报，保留店面门窗，标题 OPENING NIGHT。”
- “以一碗意大利烩饭和一只钟为主体做一张新的手绘活动海报；不要画店面。”
- “只分析参考文件夹里的线条、字体、材质和留白规则，不生图。”
- “给我三个不同的版式方案，但要保持同一个手绘编辑风格。”

## Revised production defaults — user feedback takes precedence

These controls supersede conflicting architectural, title-scale and typography suggestions above and in the historical references.

### Doodle rather than architectural illustration
Use quick, economical, irregular strokes and a few defining cues. A storefront needs its silhouette, entrance, main window and distinctive canopy, not a rendered building study. Omit interior equipment, furniture inventories, ornate cornices, masonry, individual leaves and dense crosshatching unless requested. Slightly skewed proportions, gaps and overlapping lines should feel casual while preserving recognition. If the scene grows dense, simplify the drawing first. Detailed architectural rendering fails this quality gate even when recognizable.

### Smaller display titles and non-serif supporting text
Reduce the title size upper limit by approximately 20% relative to the first evaluation’s visual scale, not by 20 percentage points. The previous skill defined no numeric title range, so there is no existing measured cap to reduce exactly. As a new provisional control, target a title bounding box of 15–25% of canvas height, including all title lines, and no more than 80% of canvas width. Verify visually rather than treating prompt percentages as guaranteed dimensions. Explicit user sizing overrides this default. A simple symbol allows expressive letter shapes, not an automatically oversized title.

Retain the successful small-copy scale. Prefer the TIME evaluation’s plain, spaced, monoline handwritten or sans-like supporting lettering. Do not default to serif details. Serif is available only when explicitly requested.

### Uploaded background asset
Accept a supplied background image as the actual base, distinct from a style reference or subject photograph. Inspect and use it in editing/compositing; preserve its recognizable content, texture and colors. Fit without stretching and disclose necessary cropping; clarify only if important content would be lost. Do not replace it with generated cream paper or automatically add grain. Place content over quiet regions and choose contrasting ink. Seek user direction if readability requires altering the background. Use separate overlay/compositing layers when exact background preservation matters; generative editing alone does not guarantee unchanged pixels.

### Specified display font and pairing
Accept a display handwriting font name, font file or lettering sample, plus a separate supporting font, weight, tracking and case when supplied. Honor the requested pairing. If only display is specified, choose a quiet non-serif monoline or sans companion; avoid competing decorative lettering.

Distinguish approximate font-inspired image lettering from exact font rendering. For stylistic approximation, inspect the sample and guide letterforms without claiming exact font use. For exact typography, verify the real font file is available, generate illustration with reserved text-free areas, then typeset using that font in a separate layout step. Do not silently substitute a missing named font; request the file or agree an alternative. Preserve editable text when supported by the deliverable format.

### Revised prompt and inspection gate
Compile each prompt with sparse doodle features and explicit omissions, title bounding-box limits, display/support pairing, small non-serif copy, background role and preservation requirements. Inspect the actual image for these properties in addition to the original gates. Report dense architecture, excessive title scale, unrequested serif copy or substituted background/font as failures or partial results even if the original evaluation expectations pass. Numeric bounds require layout measurement if strict compliance is requested.
