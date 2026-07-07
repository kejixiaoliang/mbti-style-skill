# MBTI IP Planning Guide

Use this guide when the user gives a short word, a phrase, a vague concept, or asks for prompt writing before image creation. The goal is to turn language into a clear IP design plan before generating anything.

## Core Principle

Plan before making.

Do not jump from a keyword directly to image generation. First translate the keyword into personality logic, visual metaphor, MBTI-style archetype, color, silhouette, props, posture, and a final prompt.

## Single Concept Workflow

For a single phrase such as "夜猫子选手", produce this structure:

```text
Input phrase:
Meaning analysis:
Emotional tone:
Likely MBTI temperament:
Character role:
Visual metaphor:
Dominant color:
Accent color:
Head and hair shape:
Expression:
Pose:
Props:
Scene elements:
Composition:
Do not include:
Final image prompt:
Negative prompt:
```

Keep the plan concise but concrete. Prefer 1-3 options only when the phrase is ambiguous; otherwise choose one strong direction.

## Keyword Interpretation Rules

Analyze the phrase through five lenses:

1. Literal meaning: What object, habit, role, or scene does the phrase name?
2. Emotional tone: Funny, tired, calm, intense, dreamy, social, strict, chaotic, warm, proud, or anxious?
3. Personality direction: Which MBTI temperament or archetype does it imply?
4. Visual symbols: Which 2-4 props or shapes can make it readable at small size?
5. Style translation: How to express it with low-poly geometry, white background, restrained color, and simple UI-friendly composition?

Avoid over-explaining the psychology. The final design must be visually usable.

## MBTI Temperament Shortcuts

Use these shortcuts when the user does not provide a specific MBTI type:

| User wording | Likely direction | Visual direction |
| --- | --- | --- |
| strategy, planning, mastermind, silent observer | INTJ / INFJ / ISTJ | Olive, purple, chart, book, wand, hand-to-chin pose |
| logic, repair, tool, code, lab, analysis | INTP / ISTP | Teal, grey, glasses, ruler, instrument, reserved pose |
| leader, commander, organizer, debate | ENTJ / ESTJ / ENTP | Purple or yellow, podium, pointer, microphone, forward gesture |
| dreamer, night, poetry, soft, inner world | INFP / INFJ | Purple, muted teal, moon, book, lamp, relaxed or thoughtful pose |
| creator, performer, sunshine, restless, idea | ENFP / ENTP / ESFP | Yellow, lime, microphone, butterfly, palette, open diagonal pose |
| helper, caretaker, reliable, warm | ISFJ / ESFJ | Teal, light green, clipboard, cup, medical or service symbol |
| sport, action, field, challenger | ESTP / ESFP | Yellow, green, bag, sunglasses, stepping or leaning pose |
| explorer, backpack, practical, outdoors | ISFP / ISTP / ESTP | Green, grey, cap, backpack, map, walking pose |

## Example: "夜猫子选手"

```text
Input phrase:
夜猫子选手

Meaning analysis:
A person who stays active late at night, half tired but still focused, with a humorous "player/contestant" identity.

Emotional tone:
Quiet, stubborn, slightly funny, focused, late-night self-discipline mixed with exhaustion.

Likely MBTI temperament:
INTP / INTJ / INFP direction. Use a night thinker archetype rather than a literal animal.

Character role:
A late-night MBTI strategist or creator who keeps working under a small lamp.

Visual metaphor:
Moon icon, small desk lamp, coffee cup, sleepy square glasses, angular messy hair, tiny clock showing late night.

Dominant color:
Muted purple and blue-grey night palette.

Accent color:
Warm yellow lamp light and small cyan glasses.

Head and hair shape:
Faceted rectangular head, angular messy purple-black hair like folded paper shards.

Expression:
Tiny tired eyes, short straight mouth, slight determined eyebrow angle.

Pose:
One hand holding a coffee cup, the other holding a small laptop or notebook; shoulders slightly hunched but still upright.

Props:
Coffee cup, mini lamp, moon icon, small clock. Use at most three in the final image.

Scene elements:
White background with a small dark polygon window or moon symbol only; avoid a complex room.

Composition:
Square avatar, centered figure, soft grey oval shadow, character occupying 70-80% height.

Do not include:
Real owl, detailed bedroom, neon cyberpunk lighting, messy full desk, readable text, realistic tired face.

Final image prompt:
Create a square avatar of a "夜猫子选手" as a low-poly geometric MBTI IP mascot. The character is a late-night thinker, standing slightly hunched but determined, holding a small coffee cup and a tiny angular notebook. Use faceted purple-black messy hair, simple sleepy dot eyes behind cyan square glasses, a muted purple and blue-grey outfit with warm yellow lamp accents, crisp polygon planes, flat vector-like shading, no thick outlines, centered on a white background with a small moon icon and a soft grey oval shadow. Make it playful, focused, and readable as a reusable MBTI app avatar.

Negative prompt:
Avoid photorealism, anime, literal owl character, complex bedroom background, neon cyberpunk style, glossy 3D render, thick black outline, detailed facial wrinkles, messy desk clutter, text labels, and overly cute chibi proportions.
```

## Prompt Templates

### Single Avatar

```text
Create a square avatar of [concept name] as a low-poly geometric MBTI IP mascot. The character is [role/personality], [pose], wearing [faceted outfit]. Use [dominant palette] with [accent color], faceted hair and clothing, simple dot-and-line facial features, crisp angular polygon planes, flat vector-like shading, no thick outlines, centered on a white background with a soft grey oval shadow. Add [1-3 readable props]. Make it [mood words] and readable as a reusable MBTI app avatar.
```

### Small Scene

```text
Create a 4:3 low-poly geometric MBTI IP scene for [concept]. Show [1-4 characters] doing [action] with [key props]. Use simple polygon environment pieces, a white or near-white background, soft grey floor shadows, faceted clothing and hair, minimal facial features, and a restrained palette of [colors]. Keep the scene sparse, UI-friendly, and readable at thumbnail size.
```

### Character Sheet

```text
Create a low-poly geometric MBTI IP character sheet for [concept/type]. Include one main full-body pose, two small expression or prop variants, and a compact color palette. Use faceted polygon planes, crisp vector-like edges, minimal facial details, [dominant palette], white background, and soft shadows. Keep all variants consistent as one reusable character system.
```

## Planning Quality Checklist

Before producing a final prompt, confirm:

- The concept has a clear role, not only a literal object.
- The role has a readable MBTI temperament or archetype.
- The design uses one dominant color family and one accent.
- Props are limited and symbolic.
- The background is minimal enough for UI use.
- The prompt contains the visual style constraints from `style-guide.md`.
- The negative prompt blocks the most likely style drift.
