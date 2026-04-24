---
name: last-fire-of-rum-comic
description: Create pages for "The Last Fire of Rūm" graphic novel adaptation. Use whenever the user asks to create, script, draw, layout, or produce a comic page, panel, spread, or issue for this project. Also use when reviewing existing pages for continuity, adjusting character designs, or planning issue breakdowns. Trigger on any mention of "LFR", "Last Fire", "graphic novel page", "comic page", "issue layout", or references to characters/scenes from the novel combined with visual production intent.
---

# THE LAST FIRE OF RŪM — GRAPHIC NOVEL PRODUCTION BIBLE

Version: 1.0
Production Model: B&W + Spot Color (3-accent system)
Format: 18 issues × 24 story pages → 3 collected volumes

---

## 0) AGENT WORKFLOW — READ THIS FIRST

This document is the persistent memory for page-by-page graphic novel production. The agent cannot see previously generated pages between sessions. All continuity depends on this file and the session log at the bottom.

### When the user asks for a page:

**Step 1 — Locate the page.** Determine issue number and page number. Check the issue-chapter map (§1) to find the source novel chapter and scene.

**Step 2 — Check the session log.** Read §16 (Session Log) for the last completed page, any open continuity risks, and the "next page start notes." If no log exists, ask the user where to begin.

**Step 3 — Write the panel script.** Before drawing anything, output a panel script using the template in §3. The script defines panel count, layout, dialogue, captions, action descriptions, camera angles, accent color plan, and continuity notes. Show this to the user for approval.

**Step 4 — Produce the page.** Generate the page as an SVG artifact matching the production specs in §5. Apply the color system (§7), lettering rules (§8), character designs (§10), object designs (§11), and environment rules (§9).

**Step 5 — Run the checklist.** Before presenting, verify against the per-page checklist (§4.5).

**Step 6 — Update the session log.** Append to §16 with the completed page number, any continuity updates, and notes for the next page.

### When the user asks to plan an issue:

Output a 24-page beat sheet using §1 (issue map) and §2 (adaptation rules). Each page gets a one-line function description, POV, accent color, and text density target.

### When the user asks to review or revise:

Check the page against §4 (page grammar), §7 (color system), §10 (characters), and §11 (objects). Flag any violations.

---

## 1) ISSUE-CHAPTER MAP

The novel has 81 chapters (0–80). The adaptation compresses into 18 issues × 24 pages = 432 story pages. Not every chapter gets equal space; some compress to 2 pages, some expand to 8+.

### Volume 1 — Istanbul (Issues 1–6)

| Issue | Chapters | Core content | Climax beat |
|-------|----------|-------------|-------------|
| 1 | 0–3 | Reza's death, Leyla finds father's notation, the wrong seal | Raid team enters |
| 2 | 4–7 | The exchange, safe flat, half-leaf analysis, "not a prayer" | Rūm identification |
| 3 | 8–12 | Token shape, Marcian enters, first Hagia Sophia threshold, the seam | Seam discovery |
| 4 | 13–17 | Unlogged repair, the insert, Darius's hand, broker's fear, gallery route | Malhama spoken |
| 5 | 18–22 | Marble angle, saved by Marcian, cipher note, quiet summons, old accusation | Kemal's disgrace revealed |
| 6 | 23–24 | Attack under stone (Selim killed), eastbound | Operative scar confirmed — Istanbul blown |

### Volume 2 — The Route East (Issues 7–12)

| Issue | Chapters | Core content | Climax beat |
|-------|----------|-------------|-------------|
| 7 | 25–27 | Tabriz under truce, Reza's room, Narin introduced | Narin becomes indispensable |
| 8 | 28–32 | Watched city, provincial archive, weighbridge, Daryabegi's offer, Persian claim | Daryabegi's grievance lands |
| 9 | 33–36 | Blackout archive, wrong prophecy, Darius's refusal, kill list | "The Last Fire" named on Syriac card |
| 10 | 37–41 | Isfahan, Armenian thread, Sister Helena, full title revealed, father's silence | Full title reveal + Darius letter |
| 11 | 42–49 | Naqsh-e Rostam sequence: face/receive/turn, Kemal solves the turn | "NOT BELOW / FACE → RECEIVE → TURN" |
| 12 | 50–52 | Receiver path, narrowing circle, THE BETRAYAL | Marcian's shutter descends — key pieces taken |

### Volume 3 — Return and Revelation (Issues 13–18)

| Issue | Chapters | Core content | Climax beat |
|-------|----------|-------------|-------------|
| 13 | 53–56 | After betrayal, middle way, Daryabegi's fracture, return to Istanbul | Alliance fractures and reforms |
| 14 | 57–58 | Manufactured signs, first attack | Forged line used as public permission |
| 15 | 59–63 | False routes, countermap, narrowest alliance, south service stair, holding point | "Hold there." |
| 16 | 64–68 | Acoustic point, marble/prayer/light, Daryabegi arrives, chamber of leaves, true testament | Chamber opens — charter read |
| 17 | 69–75 | Fraud archive, real payload, competing gospels of custody, building chooses nothing, final leaf | Ideological climax |
| 18 | 76–80 | Access collapse, fire without flame, measured theft, ash on the sleeve, first refuge | Marcian's return + Leyla/Kemal beat + horizon opens |

### Page budget guidance per chapter type

- **Action chapter** (raid, attack, chase): 6–10 pages — lots of panels, few words
- **Investigation chapter** (archive, analysis, translation): 4–6 pages — medium panels, medium text
- **Revelation chapter** (title reveal, charter reading, betrayal): 4–8 pages — fewer panels, bigger beats
- **Archival insert** (Darius's hand, Darius's refusal): 2–3 pages — caption-heavy, distinct visual style
- **Transition chapter** (travel, mood shift): 2–4 pages — environmental panels, light dialogue

---

## 2) ADAPTATION RULES — NOVEL TO COMIC

### 2.1 What to show, not tell

The novel is prose-driven and interior-heavy. The comic must externalize. Rules:

- **Interior monologue → facial acting + body language.** Never caption what a face can show.
- **Intellectual discovery → object close-up + reaction shot.** Show the text fragment, then show Leyla's eyes.
- **Route logic → architectural panels + movement lines.** The reader should feel the spatial argument through panel composition, not through explanation.
- **Repeated restatement → one definitive visual.** Where the novel restates an insight three times across chapters, the comic states it once with a strong image.

### 2.2 Dialogue compression

Novel dialogue runs long. Comic dialogue must be compressed. Rules:

- Maximum 3 exchanges per panel (speaker A → B → A)
- No speech balloon over 25 words
- If a novel speech runs 100+ words, extract the 15-word core and let visuals carry the rest
- Preserve the novel's best single-line kills verbatim: "The most common error in later readers is not ignorance. It is appetite." These are panel-ending lines.

### 2.3 What to cut entirely

- Descriptive passages that duplicate what the art shows (city descriptions, room layouts)
- Internal recaps of events the reader already witnessed
- Emotional processing paragraphs — let silence and panel rhythm do this work
- Repeated spatial explanations — one clear architectural panel replaces three paragraphs

### 2.4 What to expand

- Physical action the novel compresses (the raid in Ch 4 is 2 paragraphs → 4–6 pages)
- Silent environmental sequences (entering Hagia Sophia, crossing the Zayandeh Rud)
- Object handling (the token examination, the folio unrolling — give these room to breathe)
- The operative's scar — small in the novel, visually recurring in the comic

---

## 3) PANEL SCRIPT FORMAT

Before producing any page, write a script in this format:

```
═══════════════════════════════════════
PAGE SCRIPT: Issue [##] / Page [##]
Source: Chapter [##] — [Chapter Title]
═══════════════════════════════════════

PAGE FUNCTION: [one sentence — what this page accomplishes]
POV: [character whose perspective drives the page]
ACCENT COLOR: [none / red / ochre / gold — with usage note]
TEXT DENSITY: [light <70 / normal 70-120 / dense 120-170 / archival 170-200]
LAYOUT TYPE: [grid / asymmetric / splash / spread / tiered]

---

PANEL 1 [size: wide/tall/square/full-width] [position: top-left/etc.]
CAMERA: [establishing wide / medium shot / close-up / extreme close-up / overhead / POV]
ACTION: [what is physically happening in the panel]
ENVIRONMENT: [location details, lighting, weather]
CHARACTERS: [who is visible, their pose/expression, where in frame]
PROPS: [objects visible, their state]
DIALOGUE:
  LEYLA: "..."
  KEMAL: "..."
CAPTION: [if any — type: location / time / archival / reflection]
ACCENT: [color usage in this panel, if any]
NOTES: [continuity, transition, special rendering]

PANEL 2 [size] [position]
...

---

PAGE-TURN SETUP: [what the reader expects vs. what the next page delivers]
CONTINUITY FLAGS: [anything that must match on adjacent pages]
```

---

## 4) PAGE AND PANEL GRAMMAR

### 4.1 Panel count by page type

| Page type | Panels | Characteristics |
|-----------|--------|----------------|
| Quiet / architectural | 1–3 | Wide panels, deep perspective, minimal text |
| Dialogue / investigation | 4–6 | Medium shots, shot-reverse-shot, moderate text |
| Action / chase | 4–7 | Varied sizes, diagonal energy, minimal text |
| Revelation | 1–4 | Large panels, object or face emphasis, dramatic space |
| Archival insert | 2–4 | Caption-heavy, distinct border/background treatment |
| Silent | 1–6 | Zero dialogue, zero captions — pure visual storytelling |

### 4.2 Layout patterns

**The Corridor** — 3 equal horizontal panels stacked. Use for: walking sequences, time passage, environmental immersion. Panels share a continuous horizon line.

**The Interrogation** — 2×3 grid of equal panels. Use for: dialogue-heavy investigation scenes, alternating close-ups. Shot-reverse-shot rhythm.

**The Descent** — panels get progressively smaller top to bottom, compressing the page. Use for: approaching danger, narrowing options, entering confined spaces.

**The Reveal** — 2–3 small setup panels across the top third, then one large panel filling the bottom two-thirds. Use for: object discovery, location arrival, character entrance.

**The Fracture** — irregular panel borders, overlapping edges, tilted frames. Use for: violence, betrayal, psychological rupture. Use sparingly — maximum 2 per issue.

**The Monument** — full-page splash with inset panels. Use for: Hagia Sophia interiors, Naqsh-e Rostam, major architectural reveals. The architecture IS the panel.

### 4.3 Page-turn rules

Always reserve the page turn (right-hand page → left-hand page) for the reader's moment of maximum anticipation. Rules:

- The right-hand page ends on a question, a glance, a reaching hand, an unopened door
- The left-hand page delivers the answer, the reveal, the consequence
- Never waste a page turn on continued dialogue with no new information
- The best page turns work even without text — the image sequence alone creates the pull

### 4.4 Silent-page rules

A page with zero text must accomplish at least one of:

- Let architecture dominate (reader feels the space)
- Re-center emotion after violence (decompression)
- Let the reader infer a connection the characters haven't spoken
- Make an object feel consequential through staging and light

### 4.5 Per-page checklist

Before finalizing any page, confirm:

1. ☐ Readable at thumbnail size? (panel flow clear, no ambiguous reading order)
2. ☐ Key reveal lands visually before text explains it?
3. ☐ All faces, hands, props, balloons inside safe zone (0.5" from trim)?
4. ☐ Gutter-side balloons have extra 0.125" clearance?
5. ☐ Architecture clear enough to orient reader in space?
6. ☐ Spot color serves meaning, not decoration? (max one dominant accent per page)
7. ☐ Text density within target range for page type?
8. ☐ Character appearances match §10 specifications?
9. ☐ Recurring props match §11 specifications?
10. ☐ Mood consistent with adjacent pages (no tonal whiplash without cause)?
11. ☐ Panel count appropriate for page type?
12. ☐ Page-turn setup properly loaded (if right-hand page)?

---

## 5) PRODUCTION SPECIFICATIONS

### 5.1 Trim and safe areas

| Measurement | Value |
|-------------|-------|
| Final trim | 6.625" × 10.25" |
| Bleed | 0.125" on top, bottom, outer edge |
| Master artboard | 6.875" × 10.5" (0.125" buffer all sides) |
| Safe zone | 0.5" inside trim on all sides |
| Extra gutter caution | +0.125" on bind side |

### 5.2 Resolution

- Line art master: 600 dpi minimum
- Print export: 300 dpi minimum, 600 dpi preferred
- Web preview: 150 dpi / 72 dpi screen

### 5.3 SVG output specifications (for agent-generated pages)

When generating pages as SVG artifacts:

- **viewBox:** `0 0 662.5 1025` (trim size in points at 100pt/inch scale)
- **Background:** white (`#FFFFFF`)
- **Line art:** black (`#1A1A1A`) — not pure black, slightly warm
- **Gray values:** use 4–6 value steps: `#F5F5F5`, `#D0D0D0`, `#A0A0A0`, `#707070`, `#404040`, `#1A1A1A`
- **Spot Red:** `#8B2500` (ember/blood — muted, not fire-engine)
- **Spot Ochre:** `#C4A035` (manuscript gold — warm, not metallic)
- **Spot Gold:** `#D4A845` (Byzantine tessera — brighter than ochre, used rarely)
- **Panel borders:** 2pt black stroke, slightly rounded corners (rx="1")
- **Gutter width between panels:** 8–12pt
- **Safe zone indicator:** do not render, but keep all text/faces within `x:50 y:50` to `x:612 y:975`

### 5.4 Color mode

Grayscale + spot color on separate conceptual layers:

- Layer 1: Line art (black)
- Layer 2: Gray values (fills, shadows, textures)
- Layer 3: Spot color accents (applied over or replacing gray in specific areas)

For CMYK print export: convert spot colors to controlled CMYK equivalents. Do not rely on true Pantone spot inks.

---

## 6) TEXT DENSITY AND LETTERING

### 6.1 Word count targets per page

| Page type | Words | Notes |
|-----------|-------|-------|
| Silent | 0 | Pure visual |
| Light action | 20–60 | SFX + brief exclamations only |
| Normal dialogue | 70–120 | Standard page |
| Dense investigation | 120–170 | Manuscript analysis, multi-speaker |
| Archival insert | 170–200 | HARD CAP — rare, for Darius inserts only |

### 6.2 Balloon rules

- Maximum 3 balloons per panel
- Ideal: 1–2 per panel
- Maximum 25 words per balloon (hard limit)
- Reading order: top-left to bottom-right within each panel
- Balloon tails must point clearly to the speaker
- Never obscure a face with a balloon — move the balloon or crop differently

### 6.3 Caption rules

Captions are used ONLY for:

1. **Location/time shifts:** "Istanbul. 3:17 AM." — brief, typographic
2. **Archival inserts:** Darius's notebook entries, route notes, receiver slips — use distinct visual style (see §6.5)
3. **Rare reflective transitions:** maximum 1 per issue, only at major act breaks

No running prose narration. The comic must never feel like illustrated novel text.

### 6.4 Dialogue font style

- **Regular dialogue:** Clean sans-serif or humanist comic font. Uppercase. Not too playful, not too technical. Think: Blambot's "Might Makes Right" or similar. Regular weight for speech, bold for emphasis (max 2–3 bold words per balloon).
- **Whisper:** Smaller size, dashed balloon border
- **Shouting:** Larger size, jagged balloon border, bold
- **Foreign language (Persian/Arabic/Syriac):** Italicized, with translation caption below if needed
- **Phone/radio/digital:** Rectangular balloon with antenna marks, slightly different font

### 6.5 Archival insert style

For Darius's notes, route fragments, and manuscript excerpts, use a visually distinct treatment:

- **Background:** Ochre-tinted panel or inset box
- **Border:** Rough/torn edge effect, not clean geometric
- **Font:** Serif italic, smaller than dialogue, left-aligned (not centered like balloons)
- **Marker:** Small glyph or icon in corner to signal "archival voice" — a pen nib or fragment mark
- **Rule:** These inserts float over or beside panels, not inside balloons. They are documents, not speech.

### 6.6 SFX

- Minimal — integrated into environment art
- Hand-lettered style, not typeset
- Reserved for: gunshots, doors, shutters, stone, water, fire
- Never manga-scale unless the scene specifically earns it
- SFX in the shutter-descent scene (Ch 52): the mechanical exhale should be rendered as environmental vibration in the panel art, not as a floating text effect

---

## 7) COLOR SYSTEM (B&W + 3-ACCENT SPOT)

### 7.1 Base principle

The book is primarily black, white, and gray. Accent color appears only when meaning intensifies. A page with no accent color is normal and correct. A page with all three accents is almost certainly wrong.

### 7.2 The three accents

#### SPOT A — Ember Red (`#8B2500`)

Triggers:
- Blood (Reza's death, Selim's death, Murat's shooting)
- Danger emphasis (the operative's scar — always red)
- Weapon light (muzzle flash, laser dot)
- False prophecy / manipulated media (forged Telegram posts, cropped Syriac card in digital circulation)
- Route urgency (the moment a route becomes dangerous rather than intellectual)

Usage: Most common accent. Appears in ~30% of pages across the series.

#### SPOT B — Manuscript Ochre (`#C4A035`)

Triggers:
- Folio close-ups (the half-leaf, any charter fragment)
- Manuscript inserts / archival panels (Darius's notes, route slips, Helena's register)
- Old paper textures (when a document dominates a panel)
- Memory / inheritance moments (Leyla recognizing her father's hand)

Usage: Second most common. Appears in ~20% of pages. Dominant in archive/investigation sequences.

#### SPOT C — Byzantine Gold (`#D4A845`)

Triggers:
- Hagia Sophia sacred-architectural moments (the acoustic discovery, the chamber opening, mosaic light)
- True threshold moments (not ordinary decoration — the moment custody becomes visible)
- The charter's true meaning revealed (Ch 68)

Usage: Rarest. Appears in <5% of pages. Reserved for genuine monumental beats. If you're using gold, the moment must earn it.

### 7.3 Color rules

- **One dominant accent per page.** Never two fighting for attention.
- **Never all three on one page** unless the scene is the novel's absolute climax (Ch 68 chamber reading is the only candidate).
- **Red + ochre can coexist** when danger and manuscript intersect (e.g., the kill list page).
- **Gold never appears with red** on the same page — they represent opposing registers (sacred vs. violent).
- **Accent color should occupy <15% of any panel's area.** It is emphasis, not fill.
- **The operative's scar is always rendered in Spot A red,** even when the rest of the panel is pure B&W. This is the scar's visual signature.

### 7.4 Black design

- Use deep blacks for volume, mood, and noir shadow
- Do not crush all midtones — keep architectural detail readable in shadow
- Reserve total black fields for: shock, void, tunnel interiors, blackout scenes, page-end emphasis
- Blackout scenes (Tabriz, Ch 33) should feel genuinely dark — panels with 60%+ black fill

---

## 8) VISUAL STYLE

### 8.1 Style target

**Semi-realistic architectural thriller.** Reference artists/works for tone calibration:

- **Sean Phillips** (*Criminal*, *Fatale*) — noir shadow design, restrained acting, environmental mood
- **Mazzucchelli** (*Asterios Polyp*) — architectural consciousness, how buildings think on the page
- **Taniguchi** (*The Walking Man*, *A Distant Neighborhood*) — quiet environmental pacing, silent pages that breathe
- **Greg Rucka / Michael Lark** (*Lazarus*) — geopolitical thriller pacing, competent adults under pressure
- **Gipi** (*Notes for a War Story*) — grayscale + wash, handmade line quality, moral weight

The book should feel like: *Criminal* meets *Asterios Polyp* in Istanbul, with the pacing discipline of Taniguchi.

### 8.2 What to avoid

- Cartoon exaggeration or superhero anatomy
- Glossy digital rendering (no airbrush gradients, no lens flares)
- Over-rendered photorealism that kills pacing
- Generic "thriller" darkness — shadows must have architectural logic, not mood-board atmosphere
- Clean-line franco-belgian if it makes the book feel too bright or too controlled
- Manga speed lines and impact frames (except very sparingly in Ch 4 and Ch 23 action)

### 8.3 Line quality

- Confident, slightly rough — not mechanical, not sketchy
- Thicker outlines for figures and architecture in foreground
- Thinner lines for background detail and texture
- Hatching for shadow rather than smooth gradient fills (keeps the handmade feel)
- Architectural lines can be straighter/more precise than figure lines — the buildings are more certain than the people

### 8.4 Core mood vocabulary

These words should be legible in the art without anyone saying them: ash, custody, stone, pressure, withheld meaning, surveillance, displaced inheritance, route before revelation.

---

## 9) ENVIRONMENT DESIGN

### 9.1 Istanbul

**Light:** Sodium-orange night. Cool gray overcast day. Archive-lamp yellow in interiors. Hagia Sophia gets its own warm amber that deepens as chapters progress.

**Architecture:** Layered stone, damp corridors, urban compression. Streets feel narrow and watched. Interiors feel old and institutional. Hagia Sophia is rendered with genuine architectural precision — the dome's geometry, the gallery proportions, the scaffolding and maintenance infrastructure that the novel uses as route logic.

**Key locations requiring consistent design:**
- Murat's exchange room (Ch 4): Ottoman-era upper floor, walnut table, tea service, one window
- The safe flat (Ch 5–7): Spartan, functional, kitchen table as war room
- Hagia Sophia exterior approach, ground floor, galleries, upper maintenance corridors, the seam location, the acoustic chamber
- Selim's underground meeting point (Ch 16, 23)

### 9.2 Tabriz

**Light:** Dry cold, brown/granular. Blackout scenes are genuinely dark (not cinematic dark — actual power-failure dark). Daytime is washed-out, tired, post-war infrastructure.

**Architecture:** Low, horizontal, weathered. Workshops, shutters, customs yards, tea stalls. Streets feel watched but not dramatically — ordinary surveillance by ordinary men.

**Key locations:**
- Reza's room (Ch 26): Sparse, scholarly, already searched
- The blackout archive annex (Ch 33): Damaged, dark, government-neglected
- The watched tea stall (Ch 30): Street-level, the operative visible in a doorway

### 9.3 Isfahan

**Light:** Elegant decay. Blue-tile reflections by day, bridge stone by night. The Zayandeh Rud should feel diminished — not the tourist postcard version.

**Key locations:**
- Si-o-se-pol bridge (Ch 37): Night, low water, reflected arches
- New Julfa Armenian archive (Ch 38–39): Beeswax and wool smell rendered through warm light and careful shelving
- Sister Helena's cabinet room: Small, curated, air between objects

### 9.4 Naqsh-e Rostam

**Light:** Harsh desert daylight. The rock face should feel monumental and indifferent. The kings' facades are tests, not destinations.

**Key rendering rule:** The site must be drawn accurately enough that the "face → receive → turn" spatial logic is visually legible. The reader needs to understand that the kings face outward, that receiving happens at the base, and that the turn is a bodily correction — not just an intellectual one.

### 9.5 Custody / receiver spaces

Should feel: practical first, sacred only later. Never fantasy-magical. Shaped by handling, not spectacle. Stone that has been touched for centuries looks different from stone that has been preserved — show the handling.

---

## 10) CHARACTER SPECIFICATIONS

Every character has three levels of description: **silhouette** (recognizable at thumbnail), **medium** (readable at panel size), and **detail** (visible in close-up). The agent must maintain all three consistently.

### 10.1 Leyla Rahmani

**Age:** Early 30s
**Build:** Slim, medium height, precise posture — not stiff, but controlled
**Face:** Iranian features. Angular jaw, dark eyes that evaluate before they react. Minimal makeup. Slight dark circles from overwork visible in close-ups.
**Hair:** Black, straight, usually tied back or clipped. Working hair, not styled hair. Loose only in moments of exhaustion.
**Hands:** The camera loves her hands. She handles objects with trained care — cotton gloves for manuscripts, bare hands for route notes. Her grip on a pen is specific: between index and middle finger, not standard hold.
**Clothing:** Earth tones, practical layers. Field jacket or coat with interior pockets. Never ornamental. Scarves for warmth, not fashion. Shoes made for walking stone corridors.
**Silhouette ID:** Tied-back hair + field jacket + slightly forward lean when examining something
**Emotional range:** Control → micro-cracks → cold fury → quiet grief. Never theatrical. Her biggest emotional moments are the stillest.

### 10.2 Kemal Erden

**Age:** Late 30s
**Build:** Solid, broad-shouldered, physical without being bulky. Moves like someone who understands load-bearing — weight always placed deliberately.
**Face:** Turkish features. Strong brow, stubble (maintained, not groomed). Eyes that read architecture before faces. Habitual slight frown of assessment.
**Hair:** Dark brown, short, slightly unruly. Receding slightly at temples.
**Hands:** Large, capable, scarred from stone work. He touches walls, door frames, window sills — always reading structure through his palms.
**Clothing:** Work-appropriate layers. Sturdy jacket, boots with tread. Pockets contain pencils, a small measuring tape, a folding knife. Never suits. Never formal.
**Silhouette ID:** Broad shoulders + hands touching architecture + slight forward stance
**Emotional range:** Irritation → competence → quiet protectiveness → controlled anger. His version of tenderness is spatial — he positions himself between Leyla and danger without announcing it.

### 10.3 Marcian Varela

**Age:** Mid 50s
**Build:** Lean, tall, clerical posture — upright without military rigidity. Moves with the economy of a man who has entered many rooms and knows how to make each entrance count.
**Face:** Southern European (Portuguese-Spanish). Lined, intelligent, composed. Silver at the temples. Eyes that listen. A face that could be kind or calculating depending on the panel's shadow design.
**Hair:** Gray-silver, neat, swept back. Always controlled.
**Hands:** Scholar's hands — long fingers, careful gestures. He handles documents with reverence that is also possessiveness.
**Clothing:** Dark clerical-adjacent layers. Not a visible collar, but the silhouette suggests clergy who dresses down. Black coat, dark shirt, good shoes. The most formally dressed person in any room.
**Silhouette ID:** Tall + lean + dark vertical silhouette + slightly inclined head
**Panel rule:** When Marcian enters a panel, the composition should subtly reorganize around him. He draws the eye through placement, not action. Other characters adjust their positions relative to him.
**Emotional range:** Composed helpfulness → controlled sorrow → moral certainty that is indistinguishable from arrogance → one moment of genuine devastation (Ch 77).

### 10.4 Narin

**Age:** Mid 20s
**Build:** Small, wiry, tightly coiled energy. Posture of someone always ready to leave.
**Face:** Iranian-Kurdish features. Sharp jaw, sharper gaze. Low patience visible in the set of her mouth. Young but not naive — her youth reads as speed, not innocence.
**Hair:** Dark, short or cropped, practical. Might have one asymmetric detail (shaved side, undercut) but nothing attention-seeking.
**Hands:** Always holding a device. Two phones minimum, sometimes three. Cable coils in pockets. She types without looking.
**Clothing:** Layered tech-functional. Dark hoodie under jacket, cargo pants or utility trousers. USB drives on a lanyard, earbuds. Moves between "invisible civilian" and "tactical operator" registers.
**Silhouette ID:** Small frame + devices visible + hood up or down as situation indicator
**Emotional range:** Sharp impatience → clinical precision → rare moments of dry warmth → the single word "Well" that carries entire scenes.

### 10.5 General Arash Daryabegi

**Age:** Late 50s
**Build:** Commanding without being physically imposing. Military bearing domesticated into political authority. Stillness is his primary physical trait.
**Face:** Persian features. Heavy brow, deep-set eyes, short graying beard precisely trimmed. A face that has given orders and watched them carried out.
**Hair:** Gray, military-short, receding.
**Clothing:** No uniform in the field. Dark civilian coat, quality fabric. His authority is legible without insignia. In formal settings, a well-cut suit. Never casual.
**Silhouette ID:** Rigid upright posture + hands behind back or at sides (never in pockets) + stillness
**Emotional range:** Measured authority → controlled grievance → the specific fury of a man whose civilization has been curated by others → one moment of genuine fracture (Ch 55).

### 10.6 Reza Namazi

**Age:** Late 40s (appears older from exhaustion)
**Build:** Thin, bent by the weight he carries — both physical (the cylinder) and moral.
**Face:** Iranian features. Gaunt, unshaved, eyes that have stopped expecting rest. A kind face under pressure that has made kindness expensive.
**Hair:** Dark with premature gray, uncombed.
**Clothing:** Worn field clothes, dusty coat, practical shoes that have walked too many borders.
**Silhouette ID:** Hunched forward + carrying something + looking over shoulder
**Note:** Reza appears only in the prologue (Ch 0) and in flashback/memory. His visual presence should feel mortal and specific — the reader must believe this man is about to die.

### 10.7 The Operative (unnamed)

**Age:** 30s–40s (deliberately hard to pin)
**Build:** Medium, unremarkable. Professional anonymity is his design feature.
**Face:** Not clearly ethnic-specific. Forgettable on purpose. The reader should struggle to identify him except by the scar.
**The scar:** Small, circular, base of left thumb. **Always rendered in Spot A red** regardless of the rest of the panel's color treatment. This is the reader's visual anchor for recognizing him across appearances.
**Clothing:** Changes per location. In Istanbul: dark jacket, civilian. In Tabriz: local adaptation. The clothing is always correct for context — that's what makes him dangerous.
**Silhouette ID:** Unremarkable frame + left hand visible + red scar dot
**Appearances:** Ch 4 (introduction), Ch 23 (Selim's death — scar confirmed), Ch 30 (Tabriz stationery doorway), optional Ch 58 (Narin's footage).

### 10.8 Sister Helena

**Age:** 60s
**Build:** Small, precise. Economy of movement that comes from decades of convent discipline.
**Face:** Armenian features. Deep lines of patience, not of suffering. Eyes that evaluate by watching what happens during pauses.
**Hair:** Hidden under plain veil.
**Clothing:** Simple religious habit, unadorned. Hands unringed.
**Appears:** Ch 38–39 only. 3–5 pages maximum.

---

## 11) OBJECT SPECIFICATIONS

These objects are recurring visual anchors. They must remain consistent across every appearance. When in doubt, reference these specs over memory of previous drawings.

### 11.1 Bronze cylinder

- **Size:** ~12" long, 3" diameter — holdable in two hands
- **Material:** Tarnished bronze, green-brown patina in crevices
- **Threads:** Old, hand-cut. Visible threading at one end for cap
- **Interior:** Wear marks from the folio being inserted/removed over centuries
- **Weight:** Heavy. Must look heavy in how characters hold it — two hands, deliberate grip
- **Surface detail:** No ornamental engraving. Tool marks from manufacture. Practical, not decorative.
- **Appearances:** Prologue (Reza carrying it), Ch 4–6 (exchange + examination), later as empty shell / decoy

### 11.2 Lead token (Byzantine)

- **Size:** ~35mm diameter, 4mm thick — slightly larger than a US half-dollar
- **Material:** Dense lead, matte gray, cold-looking
- **Obverse:** Suggestive but degraded design — a partial architectural element? A compass? Never fully legible in early appearances. Clarity increases as the novel progresses (the reader learns to see it as the characters do).
- **Reverse:** Smoother from centuries of handling, slight thumbprint depression
- **Wear:** Asymmetric — one edge more worn, suggesting it was carried in the same orientation
- **Weight:** Must feel dense. When placed on a table, it lands with authority.
- **Visual rule:** The token should be drawn slightly larger than realistic in close-up panels — it is symbolically heavier than its physical size.
- **Appearances:** Ch 5 onward. Constant companion. Kemal carries it in coat pocket or places it on surfaces as orientation device.

### 11.3 Folio half-leaf

- **Size:** ~14" × 10" — large enough to require a table
- **Material:** Parchment/vellum, aged to amber-brown
- **Damage map (maintain consistently):**
  - Left margin: burned, charred edge, ink partially consumed
  - Upper quadrant: soot staining, darker
  - Center-right: water disturbance — blurred ink, tide mark visible
  - Lower portion: best preserved, densest text
- **Script:** Compressed Persian hand, small, urgent. Do not render as legible text — render as texture with occasional visible letter forms. The script should look like language, not decoration.
- **Rendering rule:** Always use Spot B (ochre) when the folio is the dominant subject of a panel. The parchment itself glows.

### 11.4 Notebooks and route slips

- **Darius's notebooks:** Hardcover, dark, small format (~A5). Pages dense with multi-directional writing. Marginalia. Tabs. Coffee rings. These notebooks have been worked in, not kept pristine.
- **Route slips:** Small paper fragments, various ages and conditions. Some brittle, some modern photocopies. Always show specific fold patterns, handling damage, and archival markings. Never theatrically aged — functionally aged.
- **Syriac index card:** Small, yellowed, ribboned. The specific card naming "The Last Fire" has heat-browning at edges and one clear central line in compressed Syriac hand. When shown in digital circulation (forged context), it appears cropped against black background with Arabic caption — a different visual context from its archival truth.

### 11.5 Marcian's case

- **Type:** Dark leather document case, not a briefcase. Slim, purpose-built for flat documents.
- **Condition:** Well-maintained but old. Brass clasps, not modern zippers.
- **Significance:** In Ch 52, he gathers papers into this case. In Ch 77, he arrives without it. The absence of the case in the Ch 77 doorway is a visual signal the reader should register.

### 11.6 The remote (Ch 52 only)

- **Type:** Small, rectangular, industrial. The kind used for loading-bay doors and warehouse shutters. Not a dramatic prop — mundane, which makes it worse.
- **Visual treatment:** One panel where Marcian's hand holds it, thumb on the button. The reader sees it before understanding what it does.

---

## 12) SCENE-TYPE VISUAL RECIPES

### 12.1 Archive / investigation scene

- **Panel rhythm:** Slow. 4–5 panels per page, mostly medium shots and close-ups.
- **Camera:** Eye-level or slightly above (looking down at documents). Close-ups of hands, objects, text fragments.
- **Light:** Warm pools (archive lamps) in otherwise dark spaces. Spots of ochre accent.
- **Dialogue density:** Medium-high. Characters thinking aloud, debating interpretations.
- **Movement:** Minimal. People lean forward, adjust glasses, turn pages. The drama is in the objects.

### 12.2 Action / violence scene

- **Panel rhythm:** Fast. 5–7 panels per page, varied sizes, diagonal compositions.
- **Camera:** Multiple angles per page — overhead establishing → medium action → extreme close-up of consequence. Never static eye-level throughout.
- **Light:** High contrast. Deep shadows, harsh light sources (muzzle flash, flashlight sweep). Spots of red accent.
- **Dialogue density:** Minimal. SFX, one-word exclamations, body language carries everything.
- **Movement:** Visible. Speed lines used sparingly but effectively. Panel borders can break during violence.

### 12.3 Dialogue / confrontation scene

- **Panel rhythm:** Measured. 4–6 panels, shot-reverse-shot with environmental cutaways.
- **Camera:** Face-level medium shots. Close-ups for critical lines. Pull back to wide shot when power dynamics shift.
- **Light:** Contextual — whatever the environment provides. No dramatic spotlighting unless the scene earns it.
- **Dialogue density:** High. This is where the novel's best lines live. Compress but preserve.
- **Key technique:** When a line is a "killer" (e.g., "The most common error in later readers is not ignorance. It is appetite."), give it its own panel. The character speaks; the panel belongs to the line.

### 12.4 Environmental / transition scene

- **Panel rhythm:** Wide and slow. 2–3 panels per page, horizontal format.
- **Camera:** Establishing shots, architectural panoramas, figures small in landscape.
- **Light:** Location-specific. See §9 for each city's palette.
- **Dialogue density:** Zero to minimal. Caption for location/time only.
- **Key technique:** The Corridor layout (three horizontal panels sharing a horizon) works well here.

### 12.5 Archival insert scene (Darius's voice)

- **Panel treatment:** Distinct from all other scenes. Use ochre-tinted backgrounds, rough-edge panel borders, serif italic caption text.
- **Camera:** Close-ups of handwriting, notebook pages, torn margins. No characters visible — only hands, paper, ink.
- **Dialogue density:** Caption-heavy (150–200 words). This is the one place where prose narration is permitted.
- **Key technique:** The insert pages should feel like interruptions from another document tradition — the reader should sense they have entered a different textual layer.

### 12.6 Betrayal scene (Ch 52 specific)

- **Panel rhythm:** Starts measured (4 panels), accelerates to 6–7 as Marcian separates materials, then slows to 2–3 large panels for the shutter descent and aftermath.
- **Camera:** Tight on hands during the paper-separation sequence. Wide shot when the shutter drops. Close-up on Kemal's palms reading the door. Final panel: Leyla's face, emptied.
- **Accent color:** None during the conversation. Red only on the shutter mechanism. The emotional violence is rendered in black and white.
- **Sound design:** The mechanical exhale of the shutter should be rendered as a vibration effect in the panel art — distorted panel borders, slight blur on architectural lines.

---

## 13) RECURRING VISUAL MOTIFS

Track these across issues for visual coherence:

### 13.1 Hands

Hands are the novel's primary visual language. Every major character has a distinctive hand vocabulary:

- Leyla: careful, gloved, precise grip
- Kemal: palms flat on surfaces, reading through touch
- Marcian: long fingers, tidying documents, performing organization
- Narin: typing, swiping, cable-coiling
- Daryabegi: hands behind back or at sides, never casual
- The Operative: left hand, scar visible

**Rule:** At least one close-up hand panel per page in investigation sequences.

### 13.2 Doors and thresholds

Every door in the novel means something. Render them with attention:

- Doors that open: opportunity, trust, entry into knowledge
- Doors that close: betrayal, loss of access, route collapse
- Doors that are stuck: institutional resistance, buried truth

The Ch 52 door (Kemal hitting it three times) should be the most viscerally rendered door in the entire series.

### 13.3 The gaze direction

When characters look at objects/documents, their eye-line should be trackable by the reader. The reader follows the character's gaze to the object, creating a guided reading experience within the panel.

### 13.4 Architectural framing

Characters framed by architecture (doorways, arches, columns, window frames) should feel contained by history — the building is always larger than the person. This is especially critical in Hagia Sophia sequences.

---

## 14) FILE NAMING

### Page files
`LFR_I[##]_P[###]_v[##].svg` — e.g., `LFR_I01_P001_v01.svg`

### Export files
`LFR_I[##]_P[###]_PRINT_v[##].tif`
`LFR_I[##]_P[###]_WEB_v[##].jpg`

### Reference/design files
`LFR_REF_[TYPE]_[NAME]_v[##]` — e.g., `LFR_REF_CHAR_Leyla_v02.svg`

---

## 15) CONTINUITY TRACKING PROTOCOL

Because the agent cannot see previously generated pages between sessions, continuity depends entirely on this document and the session log below. Rules:

### 15.1 What to track after every page

After completing each page, append to §16:

1. **Page ID:** Issue/page number
2. **Character appearances:** Who appeared, what they wore, any visible changes
3. **Prop states:** Where is the cylinder? Who has the token? Is the folio visible?
4. **Environmental state:** Time of day, weather, interior/exterior, lighting condition
5. **Injury/damage tracking:** Any character injuries, prop damage, environmental destruction
6. **Accent color used:** Which spot color, in what proportion
7. **Open threads:** What the reader expects on the next page

### 15.2 Continuity rules

- If a character is wounded, the wound persists until explicitly healed
- If it's night, it stays night until a time-skip caption says otherwise
- If a character is wearing a specific garment, they keep wearing it until a scene break
- The token stays with whoever last held it
- Narin's phone count: track which phones are active, dead, or burned

### 15.3 Cross-issue continuity

At the start of each new issue, check:

- How did the previous issue end? (last panel state)
- What cliffhanger or page-turn is being resolved?
- Which characters are present in the opening scene?
- What is the dominant mood carry-over?

---

## 16) SESSION LOG

*Append after each work session. Do not delete previous entries.*

```
══════════════════════════════════
SESSION: [date]
══════════════════════════════════
Pages completed: [list]
Last panel state: [describe final panel of last completed page]

CHARACTER STATES:
- Leyla: [clothing, injuries, emotional state, location]
- Kemal: [clothing, injuries, emotional state, location]
- Marcian: [present/absent, last seen location]
- Narin: [present/absent, device status]
- Daryabegi: [present/absent]
- Operative: [last sighting]

PROP STATES:
- Cylinder: [with whom, condition]
- Token: [with whom, last visible]
- Folio: [with whom, condition]
- Marcian's case: [present/absent]
- Narin's phones: [count, status]

ENVIRONMENT:
- Current location: [city, specific place]
- Time: [day/night, approximate hour]
- Weather/light: [condition]

ACCENT COLOR LOG:
- Pages using red: [list]
- Pages using ochre: [list]
- Pages using gold: [list]

OPEN CONTINUITY RISKS:
- [list anything that needs checking on next page]

NEXT PAGE START NOTES:
- Next page: Issue [##] / Page [##]
- Source: Chapter [##]
- Must-keep beat: [the one thing this page must accomplish]
- Must-keep visual: [the one image that must appear]
- Accent plan: [color intention]
- Risk to avoid: [specific pitfall]
══════════════════════════════════
```

---

## 17) DEFAULT AGENT INSTRUCTIONS

When starting any page, assume the following unless the user explicitly overrides:

1. Read §16 (Session Log) first. If empty, ask the user where to begin.
2. Write the panel script (§3 format) before producing any visual output.
3. Maintain character appearances per §10 — do not drift between sessions.
4. Maintain prop appearances per §11 — do not improvise visual changes.
5. Apply color system per §7 — default to no accent color; add only when the scene earns it.
6. Keep text density within the target range for the page type.
7. Prioritize architecture, object handling, and page-turn tension.
8. When unsure, choose clarity over flourish and tension over spectacle.
9. After completing a page, update §16 before ending the session.
10. Never generate a page without checking the previous page's end state.
