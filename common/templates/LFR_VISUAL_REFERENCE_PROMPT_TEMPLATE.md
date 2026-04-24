# LFR Visual Reference Prompt Template

Use this template to generate reference sheets before making comic pages. Reference sheets are production anchors, not finished story pages. They should be clean, readable, repeatable, and useful for later page prompts.

Do not include speech balloons, captions, logos, fake UI, decorative framing, or page numbers.

## Reference Metadata

- Project: The Last Fire of Rum
- Reference type: `[character / costume / prop / location / architecture / palette / object handling / expression sheet / lineup]`
- Subject name: `[Leyla Demir / Kemal Arslan / bronze cylinder / Hagia Sophia upper gallery / etc.]`
- Output file: `common/[type]/LFR_REF_[TYPE]_[NAME]_v##.png`
- Purpose: `[what later pages need this sheet to keep consistent]`
- Continuity priority: `[high / medium / low]`
- Related issues/pages: `[Issue## Page### or general series-wide]`
- Source docs to obey: `CHARACTERS.md`, `DESIGN.md`, `The_Last_Fire_of_Rum_Revised.md`

## Global Style Anchor

Create a clean visual reference sheet for *The Last Fire of Rum*, a mature semi-realistic architectural thriller.

Style:
semi-realistic mature thriller, precise realistic faces and hands, restrained noir shadows, European architectural clarity, textured black ink and grayscale wash, limited spot color only when meaningful, grounded historical-material realism, no superhero exaggeration, no cartoon simplification, no fantasy ornament.

Presentation:
plain white or light gray background, clear turnaround/reference layout, consistent scale, readable silhouettes, neutral lighting, production-design clarity. The sheet should look like a professional comic production reference board.

Color:
mostly black, white, and gray. Use spot color only for fixed continuity markers:

- Ember red: blood, operative scar, danger mark
- Manuscript ochre: parchment, manuscript notes, archival paper
- Byzantine gold: rare sacred-architectural threshold details

## Character Reference Sheet Prompt

Use for a recurring character.

```text
Create a clean character reference sheet for [CHARACTER NAME] from The Last Fire of Rum.

Show:
1. Full-body front view, neutral stance.
2. Full-body side view.
3. Full-body back view.
4. Three head studies: neutral, tense, emotionally restrained.
5. Two hand studies showing the character's distinctive hand behavior.
6. One small silhouette block showing instant recognition shape.

Character description:
[Paste character description from CHARACTERS.md or DESIGN.md]

Costume continuity:
[Clothing, shoes, accessories, bags, devices, religious/official markers, weather layers]

Body language:
[How this character stands, moves, looks at people, handles objects]

Do not add weapons, jewelry, symbols, scars, facial hair, devices, or costume details unless listed above.
Keep the background plain. No dialogue, no captions, no decorative title lettering.
```

## Costume Variant Sheet Prompt

Use when a character needs different looks by issue/location.

```text
Create a costume variant reference sheet for [CHARACTER NAME] from The Last Fire of Rum.

Show [NUMBER] full-body costume variants in the same pose and scale:
1. [Variant name: e.g. Istanbul archive night]
2. [Variant name]
3. [Variant name]
4. [Variant name]

For each variant, preserve the same face, body type, age, posture, silhouette, and hand design.

Character constant features:
[Face, age, build, hair, posture, silhouette rules]

Variant details:
[List each outfit, color/value, fabric, shoes, accessories, visible props]

Style:
semi-realistic thriller production art, grayscale ink and wash, restrained spot color only where specified, plain background, no story action.
```

## Prop Reference Sheet Prompt

Use for recurring objects such as the bronze cylinder, lead token, folio, notebooks, slips, and Marcian's case.

```text
Create a precise prop reference sheet for [PROP NAME] from The Last Fire of Rum.

Show:
1. Front view.
2. Back view.
3. Side/profile view.
4. Scale view next to a human hand.
5. Close-up of material texture and damage.
6. One handling pose showing how a character physically holds or uses it.

Prop specifications:
[Paste exact dimensions, material, damage, wear, markings, and recurring rules from DESIGN.md]

Continuity rules:
[Who carries it, when it appears, what must never change]

Rendering:
realistic material, tactile weight, precise edges, no fantasy glow, no ornamental additions. If manuscript text appears, render as believable handwritten texture unless exact text is required.
```

## Location / Architecture Reference Sheet Prompt

Use for recurring places, routes, thresholds, galleries, archives, tunnels, and monumental sites.

```text
Create an architectural/location reference sheet for [LOCATION NAME] from The Last Fire of Rum.

Show:
1. Wide establishing view.
2. Human-scale view with figures for proportion.
3. Route/orientation view showing entrances, exits, stairs, thresholds, or standing points.
4. Detail close-ups of key surfaces, doors, walls, floor, windows, lamps, or archive furniture.
5. Lighting study for [day/night/blackout/archive lamp/etc.].

Location function in story:
[What this place must communicate: surveillance, custody, route logic, scale, decay, pressure, etc.]

Architectural requirements:
[Specific geometry, materials, historical features, route logic, object placement]

Mood:
[stone / pressure / watched city / archive silence / monumental indifference / etc.]

Style:
semi-realistic architectural thriller, precise perspective, readable spatial logic, grayscale ink and wash, restrained atmosphere. No fantasy additions, no tourist-postcard beauty, no generic ruins.
```

## Lineup Reference Prompt

Use to compare recurring characters at consistent scale.

```text
Create a character lineup reference sheet for The Last Fire of Rum.

Characters, left to right:
[Leyla, Kemal, Marcian, Narin, Daryabegi, Reza, Operative, Sister Helena]

Show each character full-body, neutral stance, same ground line, same scale, plain background.

Preserve:
- age differences
- height/build differences
- silhouette rules
- clothing hierarchy
- posture and hand behavior
- emotional restraint

Use semi-realistic mature thriller style, grayscale ink and wash, no action poses, no decorative layout, no labels baked into the art unless added later in post.
```

## Expression / Acting Sheet Prompt

Use when a character needs facial consistency and restrained acting.

```text
Create an expression and acting reference sheet for [CHARACTER NAME] from The Last Fire of Rum.

Show 8 head-and-shoulder expressions:
1. Neutral control
2. Suspicion
3. Quiet fear
4. Recognition
5. Suppressed anger
6. Grief held back
7. Intellectual focus
8. Exhaustion

Also show 4 small body-language poses:
1. Listening
2. Handling an important object
3. Entering a dangerous room
4. Reacting without speaking

Keep acting restrained, intelligent, adult, and realistic. Avoid melodrama, shouting faces, cartoon expressions, glamour poses, or cinematic overacting.
```

## Object Handling Sheet Prompt

Use for pages where hands, props, and clues matter.

```text
Create an object-handling reference sheet for [CHARACTER NAME] handling [PROP NAME].

Show 6 close-up hand poses:
1. Picking it up.
2. Weighing it in the palm.
3. Turning it toward light.
4. Placing it on a table.
5. Protecting it from another hand.
6. Discovering a detail on its surface.

Character hand rules:
[Leyla precise/gloved, Kemal broad/scarred/load-bearing, Marcian long/scholar's hands, etc.]

Prop rules:
[Paste object specs from DESIGN.md]

Rendering:
hands must be anatomically believable, prop scale must stay consistent, object weight must be visible through grip and posture.
```

## Negative Prompt For All Reference Sheets

cartoon style, superhero anatomy, fantasy costume, decorative symbols, random weapons, random jewelry, extra scars, wrong age, wrong ethnicity, glamour portrait, photoreal celebrity likeness, malformed hands, extra fingers, warped face, inconsistent face across views, unreadable object geometry, generic ancient artifact, fake readable text, speech balloons, captions, logo, watermark, signature, UI frame, neon colors, magical glow, bokeh, lens flare, overdramatic pose.

## Post-Generation QA

- Subject matches `CHARACTERS.md` or `DESIGN.md`.
- Face, age, body type, silhouette, and costume are reusable.
- Hands are usable.
- Props keep correct scale and material.
- Architecture is spatially clear.
- No unwanted readable text appears.
- No new continuity details were invented.
- Sheet can be referenced in page prompts.
- File is saved under `common/[type]/`.
