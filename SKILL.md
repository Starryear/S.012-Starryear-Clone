---
name: starryear-dual-subject-clone
description: Transform one photograph into a vertical evidence triptych whose upper and lower generated panels each shrink, clone, and invert a different source-derived subject around an untouched middle crop. Use for S.012, Starryear-Clone, 星年·克隆, 双主体克隆, 人物与物件分别复制倒置, or source-faithful surreal triptychs. Do not use for same-subject repetition in both panels, ordinary crowds, generic collage, full-image filters, or unrelated fantasy scenes.
---

# 【S.012】Starryear-Clone｜星年·克隆

Create one borderless vertical 2:3 triptych from a single photograph. Keep a crop-only, untouched evidence panel in the middle. Select two different recognizable source subjects: subject A drives the upper panel; subject B drives the lower panel. In each generated panel, keep one normal-scale anchor, then make the selected subject smaller, more numerous, and mostly upside down inside believable photographic space. Preserve decisive scene anchors such as a boat, mountain, skyline, landmark, or distinctive structure whenever they establish the source's identity.

## Workflow

1. Inspect the source and list its immutable scene anchors, then select two different cloneable subjects with clear silhouettes or modules. Prefer a primary living subject for A and a distinctive object or structure for B when available.
2. Lock the middle evidence panel to source pixels only. Permit crop, proportional scaling, and placement; forbid regeneration, retouching, overlays, or recoloring.
3. Build the upper panel from subject A: retain one near-source-scale anchor; create 8–20 smaller clones; rotate at least two thirds upside down; distribute them irregularly through near, middle, and far depth.
4. Build the lower panel from subject B, never by reusing subject A. Retain one normal-scale B anchor; create 10–22 smaller B modules; rotate at least two thirds upside down; make them cross rock, water, shadow, railing, road, architecture, or another source-supported boundary.
5. Give the generated panels different camera logic, dominant boundary, density center, and movement. The lower panel must remain visibly different from both the upper panel and middle evidence even when all clones are hidden.
6. Preserve all immutable scene anchors that remain visible in the chosen crop. Integrate every clone with local light, perspective, occlusion, atmosphere, reflections, material wear, and depth of field.
7. Generate upper and lower panels separately, then assemble them around the untouched crop with [scripts/compose_triptych.py](scripts/compose_triptych.py). Return exactly one borderless vertical 2:3 image without text.

## Guardrails

- The two generated panels must clone different source-derived subjects. Sharing the method is required; sharing the cloned object is forbidden unless the user explicitly overrides it.
- Do not delete, replace, enlarge, or relocate decisive scene anchors such as boats, mountains, landmarks, skyline silhouettes, or source-specific structures.
- Most clones in each generated panel must be visibly smaller and upside down. Avoid grids, equal spacing, uniform scale, ordinary crowds, fence fields, and sticker-like repetition.
- Keep human and animal bodies complete, safe, and natural. Never create gore, injury, detached parts, fused flesh, malformed anatomy, or extra limbs.
- Object clones must preserve the source object's defining construction. A railing clone, for example, must retain its top bar, posts, joints, paint wear, and readable inversion.
- Keep the setting ordinary and photographically credible. Reject generic fantasy, portals, neon glow, glossy CGI, monumental invented architecture, and unrelated symbols.
- The middle panel must contain source pixels only. The final artwork contains no title, date, logo, signature, border, watermark, or explanatory text.

## Reference Prompt

Read the appropriate full prompt before producing the image:

- Chinese: [references/starryear-dual-subject-clone-prompt.zh-CN.md](references/starryear-dual-subject-clone-prompt.zh-CN.md)
- English: [references/starryear-dual-subject-clone-prompt.en.md](references/starryear-dual-subject-clone-prompt.en.md)

Keep [assets/examples](assets/examples) empty during drafting and testing. Do not add reference images, test renders, temporary outputs, `.gitkeep`, or placeholders. After Starryear年 explicitly accepts the tested Skill, add only final images supplied or approved by the user; treat them as examples only and never reuse their subject matter, colors, or composition unless the user supplies that exact image.
