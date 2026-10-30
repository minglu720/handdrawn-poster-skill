---
name: hand-drawn-editorial-poster
description: Create original editorial event posters with expressive hand-drawn line illustrations, loose typography, intentional negative space and tactile paper/ink qualities. Works with storefronts, buildings, objects, food, concepts, photographs and user-provided event details. Use for generating posters, analyzing references, or compiling production prompts.
---

# Hand-Drawn Editorial Poster Skill

## Purpose
Turn user content into an original, recognizable yet flexible hand-drawn poster system. Learn visual grammar from the seven study references; never replicate specific brands, event identities, artwork or exact layouts.

Read `references/visual-analysis.md` before making visual decisions.

## Input
Accept a theme, event brief, exact text, single object, storefront/building, source photograph, intended platform or size, desired color, or additional references. All fields are optional unless exact event information needs to be displayed. Do not invent unknown factual event details.

Distinguish image roles: **style reference** (style only), **source/edit target** (preserve defining features), and **supporting insert** (specified object/component). If a user supplies a specific subject photograph, prioritize its recognizable structure.

## Core rules
1. **Human line, readable structure.** Use organic, moderately irregular contours, variable pressure and occasional overlaps. Keep the form legible; avoid sterile uniform vector linework.
2. **Selective drawing, not tracing.** Preserve recognizable cues; omit unnecessary detail. Architectural motifs can show simplified windows, doors, awnings and hatching; isolated objects should not be rendered as storefronts.
3. **Editorial hierarchy.** Coordinate an expressive title, one focal illustration, and clearly readable supporting information. Lettering may vary between handwriting, cursive and restrained serif/sans.
4. **Paper is part of the composition.** Allow meaningful open background and modest tactile grain. Paper must not automatically mean heavy faux-vintage distress.

## Adjustable design controls (defaults, not source measurements)
- Canvas: portrait 4:5 unless specified otherwise.
- Negative space: aim for ~35–60% open page; flex with copy length and subject complexity.
- Palette: one ink + paper by default. Optional monochromatic reverse treatment or a restrained accent. Never enforce black-and-cream if subject warrants color.
- Texture: low-to-moderate paper flecks and print irregularity, not muddy noise.
- Typography: no required font family; handwritten title and legible details is a strong default.

## Decide illustration pathway
- IF a storefront/building is supplied → study its silhouette, entrance, windows, canopy and distinguishing visible features; produce a selective architectural sketch.
- ELSE IF a singular object or food is supplied → draw an economical icon-like object with a few distinctive contours and marks.
- ELSE IF an abstract concept is supplied → propose one simple, concrete drawable visual metaphor; avoid gratuitous collage.
- IF a detailed scene is drawn → reduce lettering flourishes and ornaments.
- IF a very simple symbol is drawn → allow bolder or more idiosyncratic title lettering.
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
