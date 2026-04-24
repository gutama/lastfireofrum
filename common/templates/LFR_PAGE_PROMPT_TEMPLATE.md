# LFR Page Prompt Template

Use this template to create one comic page image prompt at a time. Fill every bracketed field before generation. Keep final lettering out of the generated art unless the page is a text-free prop close-up; add balloons, captions, SFX, and page numbers in post.

## Page Metadata

- Project: The Last Fire of Rum
- Output file: `[Volume#/Issue##/pages/LFR_V##_I##_P###_v##.png]`
- Issue: `[#]`
- Page: `[# of 24]`
- Source chapter(s): `[chapter number/title]`
- Page function: `[one sentence: what this page must accomplish]`
- Page type: `[silent / action / investigation / dialogue / revelation / architecture / archival insert]`
- Layout type: `[grid / tiered / asymmetric / splash / double-page spread / monument / fracture / corridor / reveal]`
- Panel count: `[#]`
- Text density target: `[silent 0 / light 20-60 / normal 70-120 / dense 120-170 / archival 170-200]`
- Page-turn role: `[setup / reveal / consequence / neutral]`
- Accent color: `[none / ember red / manuscript ochre / Byzantine gold]`

## Continuity Inputs

- Previous page final panel: `[describe final image/state]`
- Current location: `[city, specific place, interior/exterior]`
- Time and light: `[night/day/hour/weather/light source]`
- Characters present: `[names]`
- Character continuity:
  - Leyla: `[clothes, expression, injuries, props]`
  - Kemal: `[clothes, expression, injuries, props]`
  - Marcian: `[clothes, expression, props/case present?]`
  - Narin: `[clothes, phone/device count/status]`
  - Daryabegi: `[clothes, posture, emotional state]`
  - Other: `[operative scar, guards, bystanders, etc.]`
- Prop continuity:
  - Bronze cylinder: `[holder/location/condition]`
  - Lead token: `[holder/location/visible?]`
  - Folio half-leaf: `[holder/location/damage state]`
  - Notebooks/slips/cards: `[which ones, condition]`
- Must preserve from DESIGN.md: `[specific design rules or object details]`

## Art Direction Prompt

Create a single finished comic page for *The Last Fire of Rum*, a mature semi-realistic architectural thriller in black-and-white with restrained spot color.

Overall style:
semi-realistic mature thriller, precise European architectural clarity, restrained noir shadow, realistic faces and hands, cinematic but quiet composition, textured ink linework, clear panel storytelling, no superhero posing, no cartoon exaggeration, no glossy fantasy lighting, no photorealistic stiffness.

Page format:
portrait comic page, 6.625 x 10.25 trim ratio, safe margins respected, clear gutters, readable panel order from top-left to bottom-right, no speech balloons or captions baked into the art unless explicitly requested below.

Color:
mostly grayscale ink and wash. Use `[accent color]` only for `[specific accent purpose]`. Accent color must cover less than 15 percent of any panel. If no accent is chosen, keep the page pure black, white, and gray.

Mood:
`[ash / custody / stone / pressure / surveillance / withheld meaning / route before revelation / aftermath / fear / precision]`

## Panel-by-Panel Direction

### Panel 1

- Size/position: `[wide top panel / small inset / tall left panel / etc.]`
- Camera: `[establishing wide / medium / close-up / extreme close-up / overhead / POV]`
- Action: `[physical action only]`
- Environment: `[architecture, lighting, weather, background detail]`
- Characters: `[who is visible, pose, expression, gaze direction]`
- Props: `[visible objects and exact state]`
- Accent use: `[none or exact accent placement]`
- Continuity note: `[must match / must avoid]`

### Panel 2

- Size/position: `[fill]`
- Camera: `[fill]`
- Action: `[fill]`
- Environment: `[fill]`
- Characters: `[fill]`
- Props: `[fill]`
- Accent use: `[fill]`
- Continuity note: `[fill]`

### Panel 3

- Size/position: `[fill]`
- Camera: `[fill]`
- Action: `[fill]`
- Environment: `[fill]`
- Characters: `[fill]`
- Props: `[fill]`
- Accent use: `[fill]`
- Continuity note: `[fill]`

### Additional Panels

Duplicate the panel block as needed. Delete unused panel sections before generation.

## Lettering Plan For Post-Production

Do not generate final text in the image. Leave clean negative space for:

- Captions: `[location/time/archival/reflection; exact text if known]`
- Dialogue balloons: `[speaker order and rough placement]`
- SFX: `[if any; place in post unless integrated environmental vibration is needed]`
- Page number: `[placement]`

If the page includes manuscript text, route marks, or archival writing, render it as believable handwritten texture unless exact readable text is explicitly required.

## Hard Constraints

- Do not change character ages, silhouettes, ethnic features, or costumes from continuity notes.
- Do not redesign recurring props.
- Do not add extra characters, weapons, symbols, monsters, fantasy effects, glowing magic, decorative orbs, or modern UI graphics.
- Do not place readable fake dialogue in balloons.
- Do not crop important faces, hands, or props outside safe margins.
- Do not let spot color become decorative.
- Do not overfill the page with ancient-looking text.
- Keep architecture spatially legible.
- Hands must be believable and anatomically coherent.
- Faces must remain restrained, intelligent, and emotionally specific.

## Negative Prompt

cartoon style, superhero anatomy, glossy fantasy art, photorealistic celebrity likeness, overdramatic action pose, unreadable panel order, malformed hands, extra fingers, warped faces, bad perspective, fake readable text, gibberish speech balloons, cluttered captions, neon colors, magical glow, generic medieval fantasy, decorative symbols not in the story, excessive blood, lens flare, bokeh, gradient orbs, AI watermark, signature, logo.

## Final Generation Prompt

Paste a cleaned version of the sections below into the image model:

```text
Create a single finished comic page for The Last Fire of Rum.

[Paste Art Direction Prompt]

[Paste Page Metadata summary]

[Paste Continuity Inputs summary]

[Paste Panel-by-Panel Direction]

[Paste Hard Constraints]

[Paste Negative Prompt]
```

## Post-Generation QA

- Panel flow reads correctly at thumbnail size.
- Page matches issue/page function.
- Character designs match CHARACTERS.md.
- Visual style matches DESIGN.md.
- Props match recurring object specs.
- Accent color is meaningful and restrained.
- No unwanted generated text appears.
- Faces and hands are usable.
- Architecture is legible.
- Balloons/captions can be added without covering key art.
- File is saved in the correct issue folder.
