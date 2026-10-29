# Visual Reference Analysis

## Dataset
This project uses 10 poster references.

- Ref 01–07: storefront / venue-based posters
- Ref 08: object-based poster (coffee cup)
- Ref 09: multi-object event poster
- Ref 10: object / vehicle-based poster

The goal is not to copy one poster, but to extract a reusable visual system for hand-drawn editorial posters.

---

# 1. Initial Clusters

## Cluster A — Storefront / Facade Posters
Shared traits:
- storefront or venue facade as primary subject
- hand-drawn line illustration
- handwritten or hand-rendered typography
- paper-like surface
- simple vertical poster layout
- moderate to generous negative space

## Cluster B — Single-Object Posters
Shared traits:
- one central object as the main visual anchor
- simplified drawing with few lines
- stronger text-image unity
- minimal composition
- limited color palette

## Cluster C — Multi-Object Event Posters
Shared traits:
- multiple illustrated objects
- more informational event-poster function
- looser composition
- more scattered layout
- still hand-drawn and paper-based

---

# 2. Shared Characteristics Across Most References

## 2.1 Medium / Surface
Observed:
- paper-like or matte surface
- visible grain, scan feel, or printed texture
- non-glossy appearance
- soft off-white / cream / muted paper backgrounds are common

## 2.2 Illustration
Observed:
- simplified hand-drawn line work
- imperfect line quality
- reduced detail rather than realistic rendering
- flat or lightly perspectival drawing
- emphasis on recognizability over precision

## 2.3 Typography
Observed:
- hand-drawn or hand-rendered title lettering is common
- supporting type may be handwritten or simpler secondary text
- text often feels integrated into the image rather than laid out as corporate design
- hierarchy is clear, but not rigid

## 2.4 Composition
Observed:
- mostly vertical poster format
- image and text occupy separate but related zones
- generous open background area
- no dense collage except some multi-object examples

## 2.5 Color
Observed:
- low color complexity
- often 1 background color + 1 ink color
- some references use one accent color
- color is usually broad and simple, not layered

---

# 3. Important Differences Across References

## 3.1 Subject Type
Variable:
- storefront / venue
- cup / food / drink
- truck / object
- multiple objects
- symbolic small icons

## 3.2 Drawing Density
Variable:
- very sparse line drawing
- moderate detail
- more textured / scribbled drawing

## 3.3 Typography Tone
Variable:
- loose handwritten
- bold casual lettering
- mixed handwritten + neat small type
- more expressive title styles

## 3.4 Layout Strategy
Variable:
- centered object poster
- top-title + middle image + bottom info
- scattered event-poster arrangement
- storefront-dominant composition

## 3.5 Color Strategy
Variable:
- monochrome ink on cream
- white ink on colored paper
- one bright accent color
- black line plus colored title

---

# 4. Candidate Visual System Dimensions

These are the dimensions that should later become controllable design parameters.

## 4.1 Subject Mode
- storefront / venue
- single object
- vehicle / mobile object
- multi-object event composition

## 4.2 Illustration Mode
- loose contour
- bold marker-like line
- sketchy / scribbled
- flat icon-like drawing

## 4.3 Typography Mode
- expressive handwritten title
- casual uppercase lettering
- small supporting handwritten text
- neat supporting text

## 4.4 Composition Mode
- title / image / info stack
- central object composition
- dispersed event layout
- storefront dominant layout

## 4.5 Palette Mode
- cream paper + black ink
- cream paper + green ink
- cream paper + blue ink
- colored paper + white ink
- paper + one accent highlight

## 4.6 Texture Mode
- clean matte paper
- grainy paper
- scanned / slightly distressed paper
- printed / imperfect ink feel

---

# 5. What Seems Fixed vs Variable

## Likely Fixed
- hand-drawn illustration language
- simplified readable subject
- paper-like tactile surface
- reduced color complexity
- integrated text-image relationship
- informal / human / editorial feel

## Likely Variable
- exact subject category
- exact color palette
- line weight and sketch density
- typography style
- amount of negative space
- composition structure
- number of illustrated elements

---

# 6. Open Questions Before Building the Skill

1. Should the skill focus on one subject at a time, or allow both single-object and multi-object posters?
2. Should storefront posters and object posters share the same composition system?
3. How much variation in typography should be allowed before the style identity becomes too broad?
4. Should color be a fixed palette system or a relational system (paper / ink / accent)?
5. Should the final skill preserve object recognizability more strictly, or allow more abstraction?

---

# 7. Next Step
Use this analysis to define:
- style-system.md
- color-typography.md
- variation-rules.md
- quality-gate.md
