---
name: xxd-panel-225
description: "Create XXD Panel 225 raster artwork: a faithful photograph paired with a hand-drawn mixed-media collage that retells the source through office objects, paper scraps, sparse handwriting and abundant intentional whitespace. Accepts one image or a directory batch and supports top-bottom, left-right, design-only and four-device wallpaper outputs; multiple ratios or exact sizes; prompt-generated, user-exact or text-free typography. Use whenever the user invokes xxd-panel-225 or asks for this office-object visual-diary collage style."
---

# XXD Panel 225

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is a hand-drawn mixed-media collage that narrates through ordinary office objects—notes, clips, tape, envelopes, stamps, rulers, paper edges—as metaphors, not a sticker dump, planner template, photographic filter, filled collage, cartoon or 3D. Keep abundant intentional whitespace, light paper colour and source-derived accents. Office objects must carry the source's theme; they are not decorative clutter.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-225/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-225-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
