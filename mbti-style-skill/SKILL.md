---
name: mbti-style-skill
description: Create MBTI-style IP characters, avatars, mascot illustrations, and small scene illustrations that match the analyzed phone image set in this workspace. Use when the user asks for MBTI IP images, same-style character design, low-poly geometric cartoon figures, MBTI personality avatars, or derivative visuals based on the local MBTI-IP-Image reference set.
---

# MBTI Style Skill

## Overview

Use this skill to create new characters or scenes in the same style as the analyzed MBTI IP reference images: low-poly geometric cartoon figures with angular planes, soft white backgrounds, small personality props, and restrained UI-friendly color systems.

Always preserve the style language; do not copy a reference image's exact pose, face, outfit, or composition unless the user explicitly asks for a close variant.

## Required Reference

Before producing style-matched output, read `references/style-guide.md`.

Use `assets/mbti-ip-contact-sheet.jpg` as the visual index when quick comparison is useful. Use `assets/image-metadata.json` only when exact file names, sizes, or dimensions are needed.

## Workflow

1. Identify the requested MBTI type, personality trait, profession, scene, or output format.
2. Choose a matching archetype from `references/style-guide.md`: analyst, helper, performer, explorer, elder mentor, scientist, planner, athlete, or group scene.
3. Build the image around one clear silhouette, one dominant color family, one supporting accent, and two or three props at most.
4. Specify the style using the prompt formula in `references/style-guide.md`.
5. Check the result against the quality checklist: angular low-poly planes, flat vector-like rendering, simple facial features, white background, soft ground shadow, asymmetric pose, and readable props.

## Output Rules

- Prefer square 1:1 images for single characters; use 4:3 or wide formats only for scenes.
- Keep backgrounds minimal: white or near-white, with only light grey stage shapes or simple geometric environment pieces.
- Make characters feel like MBTI IP icons: readable at small size, expressive through posture and props, not through complex facial rendering.
- Avoid photorealism, anime, painterly brushwork, heavy outlines, glossy 3D, thick gradients, detailed texture, complex scenery, or text-heavy UI.
