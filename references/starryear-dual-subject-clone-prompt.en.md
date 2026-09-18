# 【S.012】Starryear-Clone Full Prompt

Treat one user-supplied photograph as the only source of subjects, setting, color, and material. Create one continuous vertical 2:3 triptych: a crop-only untouched evidence panel in the middle; subject A made smaller, cloned, and inverted above; and a different subject B transformed by the same method below through a different camera and spatial mechanism. Do not repeat the same cloned subject in both generated panels, and do not remove decisive evidence that establishes the scene's identity.

## 1. Input and evidence lock

- The photograph is the only visual source. Do not introduce unsupported people, objects, landmarks, colors, weather, or decoration.
- Internally list three to six immutable scene anchors, such as a boat, wake, Mount Fuji, building silhouette, skyline, bridge, tree, distinctive road, sign, or strong color relationship.
- Anchors explicitly named by the user have highest priority. Whenever the chosen crop permits, preserve their position, scale, direction, and basic appearance; never delete, replace, enlarge, relocate, or turn them into other objects.
- The middle panel must contain real source pixels only. Allow crop, proportional scaling, and placement; prohibit generation, outpainting, removal, retouching, recoloring, relighting, clone overlays, or text.

## 2. Selecting two subjects

Complete the following judgment internally without outputting analysis:

1. Select two different source objects with clear silhouettes or repeatable construction.
2. Subject A is usually the main character or most active object, such as a person, animal, vehicle, boat, or plant.
3. Subject B must differ from A and should favor a modular or strongly outlined object, such as a railing, lamp, bench, window, sign, bridge segment, boat, tree, architectural part, or vehicle.
4. If the user specifies the upper and lower subjects, follow that choice exactly.
5. Every clone must trace to its corresponding source object. Never replace B with an unrelated abstract symbol.

## 3. Shared clone rule

- Retain one normal-scale or near-normal-scale anchor in each generated panel to prove the subject's identity.
- Create 8–20 A clones above and 10–22 B clones below. A complex scene may use fewer, but never fewer than six.
- Clones are normally 8–35% of the local anchor scale; distant clones may be smaller.
- At least two thirds of the clones in each panel must be rotated approximately 180 degrees. A few sideways or upright exceptions may support rhythm.
- Vary scale, spacing, length, action or module length, focus, occlusion, frame crop, reflection, depth of field, and atmospheric perspective. Avoid uniform size, direction, spacing, grids, queues, sticker rain, and ordinary displays.
- Clones must enter believable space: hide behind rocks, railings, trees, buildings, or foreground objects; cross water, shadow, roads, windows, doors, or cracks; occupy near, middle, and far depth; and occasionally crop at the frame edge.

## 4. Upper panel: first proliferation of subject A

- Continue the source setting or a plausible adjacent view with the same natural light, weather, materials, and color.
- Make A's shrinking and inversion immediately legible while retaining generous negative space and one normal-scale anchor.
- Prefer a relatively open camera that lets clones occupy several depths. Density may gather near one boundary but must not cover the entire frame.
- Keep human and animal bodies complete and natural. Achieve inversion through whole-body rotation, suspension, reflection, shadow, staged alignment, or conflicting gravity—never injury or deformation.

## 5. Lower panel: spatial mutation of a different subject B

- Never continue cloning A below. If A remains visible, show only one normal-scale instance as a reality reference.
- Preserve B's defining construction. For a railing, every clone should retain the handrail, vertical posts, joints, paint, and wear; its inversion should clearly place the handrail below the posts or hang the whole module from the underside of rock.
- Change at least three of the following relative to the upper and middle panels: camera height, dominant boundary, density center, and movement direction. Use a low angle, overhead view, compressed close view, diagonal depth, or local detail when suitable, without sacrificing user-required scene anchors.
- Establish one short causal proposition, such as “the railing enters a tide pool, shrinks, flips, and grows upside down from rock cracks” or “the boat crosses a bridge shadow and becomes many inverted smaller boats.” The boundary must actively change B's direction, scale, material, occlusion, or gravity.
- Do not arrange B as an ordinary fence field, vehicle row, lamp array, or decorative pattern. Prefer irregular flow, loose vortices, local clusters, and large quiet areas.

## 6. Divergence audit

- Hide every clone temporarily: the two generated panels must still look immediately different.
- Do not give both panels the same horizon, viewing height, density distribution, and movement direction.
- The cloned objects above and below must be different. If viewers can mistake them for the same object, the result fails.
- The lower panel cannot merely show more copies of B. It must contain at least one clear boundary crossing or state change.

## 7. Photographic credibility and materials

- Clones may violate gravity and spatial logic but must inherit local light direction, shadow, reflection, grain, perspective, depth of field, motion softness, and atmospheric perspective.
- Near clones are larger, sharper, and higher contrast; distant clones are smaller, softer, and more affected by haze or water.
- Objects retain real joints, thickness, wear, and weight. Reject plastic surfaces, floating stickers, wrong occlusion, incorrect reflections, and unsupported uniform arrangements.
- Derive color only from the source: one dominant family, one structural family, and at most one existing accent color. No neon glow or invented palette.

## 8. Composition and output

- Use a vertical 2:3 canvas. Default panel heights are 32% upper, 34% middle, and 34% lower; adjust slightly only to protect anchors.
- Panels run full width, align at the edges, and join without borders. Use an extremely thin neutral separator only when the layers cannot otherwise be distinguished.
- Generate upper and lower panels separately, then assemble them around the source-pixel middle. Never generate the full triptych in one pass and contaminate the evidence panel.
- Include no title, number, date, signature, logo, watermark, border, or explanatory text.

Return exactly one finished vertical triptych. Do not return analysis, alternatives, prompt notes, partial assets, a source duplicate, before-and-after comparisons, or a contact sheet.

Explicitly exclude: cloning the same subject above and below; losing a user-required boat, mountain, or landmark; redrawing the middle panel; mostly upright clones; ordinary crowds; ordinary fence or object arrays; uniform scale; equal spacing; grids; sticker-like suspension; unsupported subjects; generic fantasy; glowing portals; monumental CGI architecture; bodily harm or malformed anatomy; and incorrect perspective, shadows, occlusion, or reflections.
