# Write and Edit Images the Lira Way (Lite)

Distilled for Muse from the user-supplied Lira image prompt system (~/workspace/user/files/LIRA_SKILL.md). Lira binds its routing to Higgsfield and Nano Banana Pro, so this version keeps the method and templates, routes by job instead of brand, and adapts the parameter rules to the image tools in this workspace. For character assets, this skill's own spec governs: the three-panel photoreal character sheet in the templates below.

## Governance rule (owner-set, 2026-10-23)

- Follow this skill strictly as written. Never add, remove, or alter any part of this file on your own initiative, and never blend in outside experience or other workflows while working under it. Any change to this file requires the owner's explicit confirmation three separate times before it is applied. Until the third confirmation, the file stays exactly as it is.

## Prompt-only delivery rule (user-set, 2026-10-23)

- This skill produces image prompts and edit orders only. When working under this skill, never proactively generate or edit images yourself, and never dispatch generation to another model or pipeline on your own initiative. The user generates the media themselves or explicitly orders a generation in a separate instruction. Deliver the finished prompt or edit order plus the acceptance checklist, then stop and wait for the user to bring back the generated media for review.

## Route the image job first

- Classify the request before writing: character generation, cinematic location or keyframe, prop or product sheet, surgical edit of an existing image, texture pass on a finished frame, or narrow local surgery.

- Generate a character from identity anchors and a reference image, never from prose alone. Prose reinforces consistency with wardrobe and marks, while the reference carries the face. A reference image contributes identity only: face, hairstyle, wardrobe, and style. It never contributes pose. Every panel's pose comes from the template text alone, stated positively and in full, especially when the reference itself holds an artistic or dynamic pose.

- Treat an edit as post-processing of the original image. An edit changes the minimum on top of the original, and rebuilding the whole frame belongs to a fresh generation, never to the edit lane.

- Reserve the texture pass for one job only: reviving sloppy generated textures such as skin pores, fabric weave, or ground dirt on a finished frame. Never hand it a point edit.

- Use the strongest local editor only as a last resort for the finest micro-edit, because broad editors dirty the whole frame while working well locally. Keep its change as narrow as possible.

- When the user is actually working on Higgsfield, the original Lira routing applies: Soul 2.0 for characters, Soul Cinema for locations and cinematic stills, AI Cast for automatic character sheets, Nano Banana Pro first for every edit and for props, Seedream 4.5 for texture only, and GPT Image 2 as the last-resort local editor.

## Write the prompt as natural prose

- Write flowing natural prose instead of stacked keywords. One clear description of subject, light, material, and framing beats a comma list of adjectives.

- Keep the prompt lean, targeting roughly 1500 to 2000 characters at most. Cut filler before adding detail, and spend the budget on identity anchors, light, materials, and composition.

- Phrase everything positively. No tool in this workflow takes a negative prompt slot, and written NOT-stacks inject the very concepts they ban. Want clean skin, write clean dry skin. Want an empty street, write empty deserted street with bare walls and still air. Want no logo, write plain unbranded wrapper with a blank matte surface, and never name the brand.

- Put aspect ratio in the prompt text when using the image tools in this workspace, because they expose no ratio parameter. Lira keeps ratio as a platform parameter on Higgsfield, so move it back to the platform settings only when generating there.

- Describe lighting and materials technically instead of naming a mood. Give the key light direction, the light ratio, the falloff, and each important material with its finish, such as brushed steel with a matte finish or worn leather with cracked grain.

- Control the palette with a 60/30/10 split named in real hues, with 60 percent dominant tone, 30 percent supporting tone, and 10 percent accent. Derive the split from the user instructions, the scene, or the uploaded references, and never invent a palette over them.

- Add one compact technical register line when a photographic look matters, choosing either a film register with camera, lens, and film stock grain, or a clean modern digital register. One register line anchors the look, and stacking grain and film words on top fights the model.

- Guard photoreal work against illustration drift. Words such as painterly or character reference sheet pull a photoreal prompt toward illustration, so anchor with studio photographs, film still, real materials, and a named film stock instead.

- Handle text inside an image deliberately. Quote the exact copy and name its font weight, color, and placement, and prefer generating clean artwork with a label area and adding final text with a layout tool when the text is long or must be exact.

- Describe real people by features, never by name, and keep brands and protected characters out of the prompt entirely.

## Edit surgically with CHANGE and PRESERVE

- Structure every edit prompt in three parts: one line stating the goal, a CHANGE block naming only the single thing that changes described precisely, and a PRESERVE EXACTLY block listing everything that must stay identical.

- List in PRESERVE every element at risk: face, clothing, props, positions, walls and floor, camera angle, existing shadows, color grade, palette, contrast, and grain.

- Close the edit prompt by restating that only the named change happens and the image stays 100 percent identical otherwise.

- Make one change per pass. When the user says an edit overdid it or drifted, the diagnosis is fixed: lock more, change less, and narrow the CHANGE block on the next pass.

- Pair every removal with its fill. Removing an object leaves a hole the model invents into, so state what continues behind it, such as continuous brick wall or unbroken pavement.

- Spell out the new arrangement explicitly when changing a location viewpoint. State where each major object lands in the new view, for example the sofa that stood on the right now stands on the left, because an editor left to infer the mirrored geometry scrambles it.

- Run a texture pass with the same template: the goal names reviving textures, CHANGE lists the surfaces, and PRESERVE locks composition, identity, light, and grade.

## Use the per-type starting templates

- Character sheet, photoreal: arrange studio photographs of the same real person side by side on a flat neutral mid-grey backdrop, describe each panel in flowing prose with its pose and framing, repeat the same person in all panels as the consistency anchor, and repeat the wardrobe as consistent in every panel. Use directional side light rather than flat light, and skip composition rules such as rule of thirds because sheets are exempt. Different character states (clean, damaged, bloodied) are separate assets with separate sheets, never mixed on one board. The close-up panel is an identification portrait: head straight and level, front-facing, camera at eye level, hair resting still and symmetrical, neutral expression. State this pose explicitly every time; a tilted, turned, or dynamic head makes the sheet fail its purpose.

- Location or environment: open with a plain camera sentence that a person could act on, such as high angle three-quarter wide shot with the camera above the room looking diagonally down at 45 degrees, because concrete camera wording beats abstract jargon. Add era, materials, light direction, and the palette split, and use a 21:9 frame when the plate is a cinemascope backdrop for video.

- Prop or product sheet: isolate the object on a neutral background, name shape, scale cues, material and finish, surface state, and the light that reveals its form. Keep branding surfaces blank unless the user supplies exact copy for them.

- Cinematic keyframe for later video work: compose it as the first frame of the intended shot, with the subject already in position, the spatial layout readable, and the lighting direction the video prompt will later lock to.

## Check before sending

- Confirm the job was routed correctly and the lane matches it, generation for new images, surgical edit for changes, texture pass only for surface revival.

- Confirm the prose is natural and lean, the constraints are positive, the lighting and materials are technical, and the palette follows the 60/30/10 split from the user material.

- Confirm identity rests on a reference plus repeated anchors, and the ratio sits in the prompt text for this workspace tools or in the platform settings on Higgsfield.

- For an edit, confirm CHANGE names exactly one thing, PRESERVE lists every element at risk, every removal carries its fill, and the closing line restates that nothing else changes.

- Confirm every panel states its pose explicitly, and the portrait panel states upright, level, and front-facing.
