# Quiet Signal Press

> [中文](README.md) · [English](README.en.md)

![MIT](https://img.shields.io/badge/License-MIT-22C55E?style=flat-square)
![Codex Skill](https://img.shields.io/badge/Codex-Skill-10A37F?style=flat-square)

Turn a theme, line of writing, article idea, or photograph into a sparse paper editorial poster: one visual signal, one decisive accent, and a calm field of paper.

This is not a photo filter. It reduces an input to one visible relationship: an almost-touch, an interruption, a trace, or a glimpse.

## Contents

- [Quick start](#quick-start)
- [Four ways to work](#four-ways-to-work)
- [Visual contract](#visual-contract)
- [Examples](#examples)
- [Contribution](#contribution)
- [Attribution](#attribution)

## Quick start

1. Copy `quiet-signal-press` to `~/.codex/skills/`.
2. Upload an image or provide a theme, then write:

   ```text
   Use $quiet-signal-press to make a paper editorial poster about a bookstore after rain.
   ```

The default route returns a raster image and its final prompt. Ask for “prompt only” to skip generation.

### Install

```bash
git clone https://github.com/StarSure/quiet-signal-press.git
cp -R quiet-signal-press/quiet-signal-press ~/.codex/skills/
```

Copying the repository's `quiet-signal-press/` directory on its own also works. Start a fresh Codex conversation, then invoke `$quiet-signal-press`.

## Four ways to work

| Input | Example request | Delivery |
| --- | --- | --- |
| A theme or mood | `Use $quiet-signal-press for a poster about missing the last train.` | Image + final prompt |
| Writing | `Compress this note into a Quiet Signal Press poster.` | Image + relation note |
| A photograph | `Use $quiet-signal-press with this photo; keep the person and yellow raincoat.` | Image + preservation note |
| References | `Analyze this set, then make a new poster.` | System analysis + a new image |

For text only, say: `Use $quiet-signal-press; prompt only, do not generate an image.`

## Visual contract

| Element | Default |
| --- | --- |
| Format | 3:5 vertical |
| Open field | 72–88% visually open paper |
| Signal | One compact event, 7–20% of the poster |
| Colour | One decisive, saturated accent |
| Surface | Fiber paper, dry ink, scan grain, small print errors |

The working system, prompt recipes, and quality checklist live in the [Skill directory](quiet-signal-press/).

## Examples

All four examples below were created for this repository. They use no third-party photographs, marks, or readable type. Their inputs and making notes are in [examples/README.md](examples/README.md).

| Relation | Poster | Technique |
| --- | --- | --- |
| Passing through | ![Thread through paper](examples/output/thread-through-paper.png) | `Interrupted pair` |
| Almost touching | ![Two near paper semicircles](examples/output/almost-touching.png) | `Margin specimen` |
| A glimpse | ![Torn window to a night sky](examples/output/torn-sky.png) | `Clipping window` |
| An archived trace | ![Receipt index with red tape](examples/output/receipt-index.png) | `Index trace` |

## Contribution

New text-free examples and validation cases are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md). Everything submitted must be redistributable and must not carry over names, logos, or text from a reference.

## Attribution

MIT licensed. This independently rewritten, output-compatible derivative is inspired by [gc-minimal-zine-poster](https://github.com/LiamGvchi/gc-minimal-zine-poster); upstream MIT attribution is preserved in [UPSTREAM_NOTICE.md](UPSTREAM_NOTICE.md).
