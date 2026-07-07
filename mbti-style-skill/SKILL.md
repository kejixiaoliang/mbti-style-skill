---
name: mbti-style-skill
description: Plan and create MBTI-style IP characters, avatars, mascot illustrations, prompt sets, and multi-character design systems in the analyzed low-poly geometric visual style. Use when the user provides a short keyword such as "night owl player", asks for same-style character design, MBTI personality avatars, batch IP planning, dozens of categorized IP concepts, or derivative visuals based on the local MBTI-IP-Image reference set.
---

# MBTI Style Skill

## Overview

Use this skill to first plan, then create new characters or scenes in the same style as the analyzed MBTI IP reference images: low-poly geometric cartoon figures with angular planes, soft white backgrounds, small personality props, and restrained UI-friendly color systems.

Always convert the user's words into a structured IP design before writing final image prompts or generating assets. Preserve the style language; do not copy a reference image's exact pose, face, outfit, or composition unless the user explicitly asks for a close variant.

## Required Reference

Read the minimum reference needed for the task:

- For any visual output, read `references/style-guide.md`.
- For short keyword, phrase, or vague concept inputs, read `references/planning-guide.md`.
- For multi-IP sets, categorized systems, or dozens of characters, read `references/batch-ip-matrix.md`.

Use `assets/mbti-ip-contact-sheet.jpg` as the visual index when quick comparison is useful. Use `assets/image-metadata.json` only when exact file names, sizes, or dimensions are needed.

## Workflow

1. Classify the task as a single keyword/concept, a single named MBTI type, a small scene, or a batch IP system.
2. Analyze the user's words before making anything: infer mood, personality direction, visual metaphors, props, posture, palette, and unsuitable elements.
3. Produce a concise structured plan. For batch work, produce a category system and IP matrix first; do not generate images until the plan is clear or the user asks to proceed.
4. Translate the plan into one or more final prompts using the templates in `references/planning-guide.md` or `references/batch-ip-matrix.md`.
5. Create or instruct the next production step only after the design logic is explicit.
6. Check the result against the quality checklist in `references/style-guide.md`: angular low-poly planes, flat vector-like rendering, simple facial features, white background, soft ground shadow, asymmetric pose, and readable props.

## Output Rules

- For vague inputs, show the analysis and final prompt before producing the image unless the user explicitly asks for direct generation.
- For large sets, plan the taxonomy, colors, silhouettes, props, and prompt matrix before making assets.
- Prefer square 1:1 images for single characters; use 4:3 or wide formats only for scenes.
- Keep backgrounds minimal: white or near-white, with only light grey stage shapes or simple geometric environment pieces.
- Make characters feel like MBTI IP icons: readable at small size, expressive through posture and props, not through complex facial rendering.
- Avoid photorealism, anime, painterly brushwork, heavy outlines, glossy 3D, thick gradients, detailed texture, complex scenery, or text-heavy UI.
