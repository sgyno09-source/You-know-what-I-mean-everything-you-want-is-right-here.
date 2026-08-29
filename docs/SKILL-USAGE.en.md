# Skill Usage Tutorial

<p align="center">
  <a href="./SKILL-USAGE.zh-CN.md"><kbd>🇨🇳 中文教程</kbd></a>
  &nbsp;&nbsp;
  <a href="./SKILL-USAGE.en.md"><kbd>🇺🇸 English Tutorial</kbd></a>
</p>

This guide applies to every Skill in this repository.

You do not need to write code. The basic workflow is:

**Choose a Skill → import its `SKILL.md` → provide a character / outfit / expression / reference image → ask the model to follow the Skill and produce the final prompt or visual plan.**

---

## 1. What is a Skill?

Each `SKILL.md` acts like a reusable visual-directing rule set.

A normal prompt describes one image. A Skill can additionally define:

- trigger intent
- character identity consistency
- outfit and accessory consistency
- Front / Side / Back / Headshot layout rules
- expression logic
- titles, labels, UI, and prop behavior
- replaceable variables
- quality-control rules

This makes Skills useful for repeated production, batch generation, and long-term visual consistency.

---

## 2. Quick Start

### Step 1 — Choose a Skill

Open the repository and pick the Skill that matches your target:

- `01` — three-view outfit boards
- `02` — mirror-selfie Look Books
- `03` — fixed white-studio outfit presets
- `04` — dark cinematic emotion character cards
- `05` — ultrawide UI × street advertising visuals
- `06` — four-column bilingual fashion catalogs
- `07` — four-panel bilingual wedding Lookbooks

Then open that folder's `SKILL.md`.

### Step 2 — Import `SKILL.md`

In any tool that supports custom Skills, Agent instructions, system prompts, or reusable workflows, import the full contents of the selected `SKILL.md`.

If your tool does not support Skill files directly:

1. open `SKILL.md`
2. copy the full file
3. paste it into the tool's custom instruction / Agent instruction / system prompt area
4. send your real task afterward

Do not copy only the sample prompt. The consistency, layout, trigger, and quality-control rules are part of the Skill.

### Step 3 — Send your task

Example:

```text
Use this Skill.

Character: use my uploaded reference image and preserve facial structure, features, hairstyle, skin tone, and identity.

Outfit: black camisole mini dress, sheer black tights, black pointed heels.

Expression: vulnerable / slightly hurt, moist eyes, corners of the mouth slightly lowered.

Output: a complete ChatGPT-Image prompt.
```

The Skill should automatically apply its composition, lighting, layout, consistency, and quality rules.

---

## 3. Two Types of Skills

### A. General generators

Example: `01`.

These mainly provide reusable rules. You can freely replace the character, outfits, and expressions.

Example:

```text
Use Skill 01.

Shared character: clearly adult East Asian woman, long black wavy hair, fair skin.

LOOK 1:
White shirt + black mini skirt
Expression: innocent gaze

LOOK 2:
Black camisole dress
Expression: mischievous smirk

Output each Look as a separate complete prompt.
```

### B. Fixed-preset Skills

Examples: `03 / 04 / 05 / 06 / 07`.

These already contain complete Looks or visual templates.

You can simply say:

```text
Use OUTFIT 4 from Skill 07.
Replace the model with my uploaded reference image.
Keep the wedding-dress construction unchanged.
Change the expression to Natural Smile.
Output a complete ChatGPT-Image prompt.
```

You do not need to rewrite the full built-in outfit description every time.

---

## 4. How to Use `{{variables}}`

Some Skills include placeholders such as:

```text
{{人物参考图}}
{{服装}}
{{歌曲名}}
{{专辑封面}}
{{城市}}
{{街道}}
{{目的地}}
```

Treat them as replaceable variables.

For example, if Skill 05 contains:

```text
City: {{城市}}
Area: {{区域}}
Destination: {{目的地}}
```

You can provide:

```text
City: Tokyo
Area: Shibuya
Destination: Shibuya PARCO
```

There is no need to edit the Skill file itself.

---

## 5. Using a Character Reference Image

When uploading a reference image, a useful instruction is:

```text
Use the uploaded character reference as the only identity reference.
Strictly preserve face shape, facial proportions, hairstyle, hair color, skin tone, adult age impression, and overall recognizability.
Only change outfit, pose, expression, and scene.
```

For multi-panel outputs, add:

```text
Every panel must show the exact same character identity, not merely similar people.
```

---

## 6. Choose an Output Model

The same Skill can be adapted to different image models.

Add one of these at the end of your request:

```text
Output a ChatGPT-Image version.
```

```text
Output a Midjourney version.
```

```text
Output a Flux / SDXL version.
```

```text
Give me a compact token-saving version.
```

The Skill should preserve the visual logic while adjusting prompt syntax and density.

---

## 7. Full Example — Skill 07

After importing:

`skills/07-bilingual-wedding-lookbook-presets/SKILL.md`

Upload a character reference image and send:

```text
Use Skill 07.

Use my uploaded image as the only model reference.
Choose OUTFIT 3: Slit Lace Mermaid Wedding Dress.
Keep the bridal design unchanged.
Change the expression to Shy Downcast Smile.

Keep:
Front / Side / Back / Headshot four-panel layout
pure white studio
bilingual wedding-dress title
bilingual expression label
realistic lace, embroidery, tulle, and train details

Output a complete ChatGPT-Image prompt.
```

Because OUTFIT 3 is already defined inside the Skill, you do not need to paste the full dress description again.

---

## 8. Batch Multiple Looks

Example:

```text
Use Skill 06.
Convert OUTFIT 1–8 into separate complete prompts.
Use the same reference person for every Look.
Do not merge outfits.
Output all prompts in ChatGPT-Image format.
```

For batch work, one independent prompt per Look is usually more stable than putting all outfits into one giant prompt.

---

## 9. Useful Modification Commands

### Replace only the character

```text
Keep all outfits, composition, labels, and expressions unchanged. Replace only the character identity with the new reference image.
```

### Replace only the outfit

```text
Keep the character, background, four-panel layout, and expression unchanged. Replace only the clothing with: ...
```

### Replace only the expression

```text
Keep the outfit and composition unchanged. Change only the Headshot expression to: ...
```

### Remove text

```text
Keep the visual layout but remove all titles, numbers, and bilingual labels.
```

### Change the background

```text
Keep the character and outfit unchanged. Replace the white studio with a low-saturation charcoal studio.
```

---

## 10. Troubleshooting

### The outfit changes across views

Add:

```text
Front / Side / Back must show the exact same garment construction.
Keep neckline, straps, waistline, hem length, fabric, footwear, bag, and accessories consistent.
No outfit drift.
```

### The character identity changes

Add:

```text
Every panel must depict the exact same person.
Preserve facial structure, facial proportions, hairstyle, hair color, skin tone, and adult age impression.
```

### Text becomes garbled

Complex text rendering varies between image models. Reduce text density when necessary:

```text
OUTFIT 01
Front
Side
Back
Headshot
```

If clothing fidelity matters more than typography, generate a text-free version first and add typography afterward.

### Hands are malformed

Add:

```text
natural hand anatomy, five fingers on each hand, no extra fingers, no fused fingers, no duplicated hands
```

### The layout looks like a random collage

Add:

```text
premium editorial layout, balanced spacing, consistent margins, intentional magazine composition, unified typography, not a random collage
```

---

## 11. Recommended Workflow

```text
Character reference
↓
Choose Skill
↓
Choose built-in Look / define a new Look
↓
Confirm expression
↓
Choose target image model
↓
Generate final prompt
↓
Generate image
↓
Change only one or two variables per revision
```

Avoid changing the character, outfit, background, expression, composition, and lens all at once. Small controlled revisions are easier to keep consistent.

---

## 12. Add Your Own Preset

Example:

```text
Follow the structure of Skill 06 and add OUTFIT 09.
Outfit: ...
Expression: ...
Keep the original four-column layout, bilingual titles, and quality-control rules.
```

If the result works well, append the new preset to the relevant `SKILL.md` and keep numbering sequential for easier maintenance.

---

## 13. Core Principle

The goal of this repository is not to stack adjectives. It is to make visual workflows repeatable and controllable:

**consistent identity → consistent outfit → consistent composition → controllable expression → replaceable variables → reusable output.**

Whenever you find yourself reusing the same prompt structure repeatedly, that structure is a good candidate for a new Skill.

---

<p align="center">
  <a href="../README.en.md"><kbd>← Back to English Home</kbd></a>
  &nbsp;&nbsp;
  <a href="./SKILL-USAGE.zh-CN.md"><kbd>中文教程 →</kbd></a>
</p>
