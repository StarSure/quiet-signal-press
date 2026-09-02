---
name: quiet-signal-press
description: "Create sparse 3:5 paper editorial posters from themes, writing, photos, or visual references. Use for one-event zine posters, prompt-only recipes, or visual-system analysis."
---

# Quiet Signal Press

Turn a thought, a photograph, or a reference set into a quiet paper editorial: one visual signal, one vivid accent, and deliberate empty space.

## Routes

- **Generate** is the default for a theme, short text, mood, object, article idea, or photo. Return a generated raster plus the final prompt.
- **Prompt-only** applies only when the user explicitly asks for a prompt without an image.
- **Reference analysis** applies when the user asks to extract a reusable system from supplied references. Report evidence, fixed rules, flexible rules, and sample-specific residue; do not generate unless asked.
- **Analyze + generate** first analyzes supplied references, then makes a new composition without reusing source text, logos, or layout.

Read [visual-system.md](references/visual-system.md) for every route. Read [prompt-recipes.md](references/prompt-recipes.md) before generating or returning a prompt, and [quality-checklist.md](references/quality-checklist.md) before delivery.

## Photo role and preservation

When a supplied photo affects the output, classify it as an **edit target**, **style reference**, or **supporting insert**. Treat an uploaded photo paired only with “make a poster” as an edit target. For an edit target, preserve the recognizable subject, its silhouette, defining colors, and explicitly requested details; allow crop, scale, paper treatment, and surrounding layout to change.

Inspect actual images before describing them. Do not reproduce source brands, readable text, signatures, watermarks, dates, or exact layouts from reference-only images.

## Generate workflow

1. Reduce the request to one imageable tension or signal, not a full illustrated scene.
2. Select one material carrier and one chromatic accent from the visual system.
3. Write a concrete prompt: paper field, visual signal, placement/scale, printed material behavior, accent, and avoid list.
4. Generate and inspect. Make one focused retry only when the result loses its open paper field, becomes a commercial ad, lacks a clear signal, or fails declared photo preservation.
5. Return the image, final prompt, chosen recipe, and a one-sentence interpretation. State photo role and preservation when a photo was used.

## Non-negotiable outcome

The default output is a vertical 3:5 paper poster with 72–88% visually open space and one compact visual signal. It must feel printed, scanned, or materially assembled—not like a full-bleed scene, glossy campaign, UI card, or dense scrapbook.
