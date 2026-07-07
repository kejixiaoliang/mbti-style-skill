# Batch IP Matrix Guide

Use this guide when the user asks for a large set of IP characters, multiple categories, a complete MBTI series, or dozens of prompts. The goal is to plan a coherent design system before generating individual assets.

## Batch Workflow

1. Clarify or infer the total scope: number of IPs, theme, output format, and whether MBTI types are fixed.
2. Create a category taxonomy before designing characters.
3. Assign each category a visual role, dominant color family, silhouette rule, and prop language.
4. Build an IP matrix with one row per character.
5. Check for repetition: no two adjacent characters should share the same main prop, pose, and head shape.
6. Write final prompts only after the matrix is coherent.
7. Generate or hand off in batches of 4-8 characters, then run a consistency review before continuing.

For large sets, do not immediately create images. First present the taxonomy and matrix for confirmation unless the user explicitly says to proceed without review.

## Category Planning Template

```text
Project theme:
Total count:
Output format:
Audience/use case:
Style baseline:

Category system:
1. Category name:
   Character count:
   Personality logic:
   Dominant color:
   Accent color:
   Shared silhouette:
   Prop language:
   Forbidden overlap:
```

## IP Matrix Template

Use this table for every character:

| ID | Name | Keywords | MBTI direction | Category | Main color | Accent | Silhouette | Expression | Pose | Props | Scene cue | Prompt status |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

Then expand each row into:

```text
ID:
Name:
Keyword source:
Concept analysis:
MBTI temperament:
Category:
Dominant color:
Accent color:
Head/hair silhouette:
Outfit geometry:
Expression:
Pose:
Props:
Background cue:
Avoid:
Final prompt:
Negative prompt:
```

## Color System for Sets

Use the original style guide palette, but assign category colors intentionally:

| Category mood | Dominant family | Use for |
| --- | --- | --- |
| Strategy / analysis | Olive green, deep purple, grey | Planners, thinkers, quiet observers |
| Technology / tools | Teal, cyan, charcoal | Engineers, coders, lab roles |
| Creative / expressive | Yellow, lime, warm ochre | Artists, performers, idea people |
| Care / support | Soft teal, light green, warm skin tones | Helpers, healers, coordinators |
| Action / field | Green, yellow, dark grey | Explorers, athletes, challengers |
| Dream / night | Purple, blue-grey, warm lamp yellow | Night thinkers, writers, introverts |

Rules:

- Keep category color identity stable across a set.
- Vary accent colors and props to prevent sameness.
- Do not use more than one dominant hue family per character.
- For 16 MBTI types, do not assign 16 unrelated colors; group them by temperament, then vary accents.

## 16-Type MBTI Planning Grid

Use this as a default if the user asks for a full MBTI set:

| Type | Role | Main color | Accent | Silhouette | Props |
| --- | --- | --- | --- | --- | --- |
| INTJ | Strategist | Deep olive / purple | Grey | Tall robe or angular coat | Chart tablet, wand, chess-like block |
| INTP | Analyst | Teal / grey | Cyan | Narrow body, square glasses | Ruler, notebook, abstract model |
| ENTJ | Commander | Purple / charcoal | Yellow | Strong shoulders, podium stance | Pointer, podium, plan board |
| ENTP | Inventor | Yellow / teal | Lime | Open diagonal pose | Microphone, idea cards, small tool |
| INFJ | Guide | Olive / muted teal | Warm yellow | Long robe, calm vertical shape | Book, lamp, small star |
| INFP | Dreamer | Purple / soft green | Moon yellow | Gentle tilted pose | Book, moon, paper butterfly |
| ENFJ | Mentor | Green / purple | Warm yellow | Open arms, guiding gesture | Speech card, flower, baton |
| ENFP | Spark | Yellow / lime | Teal | Energetic lean | Microphone, butterfly, palette |
| ISTJ | Keeper | Grey / olive | Teal | Upright, compact | Checklist, folder, small clock |
| ISFJ | Helper | Soft teal / green | Warm skin | Rounded but faceted caretaker pose | Cup, clipboard, nurse cap |
| ESTJ | Organizer | Purple / grey | Yellow | Podium or pointing stance | Clipboard, pointer, blocks |
| ESFJ | Host | Green / warm yellow | Purple | Welcoming diagonal | Gift, speech bubble, cup |
| ISTP | Mechanic | Teal / charcoal | Cyan | Lean compact stance | Tool, ruler, goggles |
| ISFP | Artist | Lime / yellow | Purple | Dancing or painting pose | Brush, palette, flower |
| ESTP | Challenger | Yellow / green | Black | Stepping action pose | Sport bag, sunglasses, flag |
| ESFP | Performer | Yellow / purple | Teal | Arms open, smiling | Microphone, confetti-like polygons |

## Example: Large Project Request

User request:

```text
帮我设计 36 个职场人格 IP。
```

Planning response should start like this:

```text
I will first plan the IP system, not generate images yet.

Project theme:
36 workplace personality IPs in the MBTI low-poly style.

Category system:
1. Strategy and decision: 6 characters, olive/purple, charts and podiums.
2. Creation and expression: 6 characters, yellow/lime, microphones and palettes.
3. Technology and execution: 6 characters, teal/grey, tools and screens.
4. Care and coordination: 6 characters, soft teal/green, checklists and cups.
5. Field action and challenge: 6 characters, yellow/green, bags and flags.
6. Reflection and night work: 6 characters, purple/blue-grey, books and lamps.

Next I will build a 36-row matrix with unique names, props, poses, colors, and final prompts.
```

## Batch Consistency Review

After every batch, score each item from 1-5:

| Criterion | Question |
| --- | --- |
| Style fit | Does it clearly match the low-poly MBTI reference style? |
| Concept fit | Does it express the keyword or MBTI role? |
| Set consistency | Does it belong to the same family as the others? |
| Differentiation | Is it distinct from neighboring characters? |
| UI usability | Would it work at avatar/result-card size? |

If two characters feel too similar, vary in this order: prop, pose, head silhouette, accent color, scene cue.
