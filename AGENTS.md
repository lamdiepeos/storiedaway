# Project: EOS StoryTraffic Content Automation System

## Key Rules
- Always update `DIARY.md` proactively with important decisions, workflow changes, and notable project context.
- Keep `PROJECT_STATUS.md` current. Update it whenever the phase changes, a workflow status shifts, a blocker appears or resolves, key metrics change, or the folder structure changes.
- Never invent new plot foundations during ranking or selection. Evaluate only what was actually scraped and documented.
- During rewriting, transform the original opening into a stronger "Super Hook" optimized for CTR and virality while preserving the core narrative spine.
- Final story outputs must be significantly expanded and must end concretely and comprehensively. No unresolved or half-story deliverables.
- The 15-second trailer must open from the finalized Super Hook's story premise, and every spoken line must be copied exactly from the finalized story. Never invent trailer-only dialogue.
- Every candidate story must carry a traceable source record and evaluation notes.
- Apply QA gates before any publish-ready output: hook fidelity and strength, ending completeness, tone consistency, and asset completeness.
- Never delete or overwrite collected source material without explicit user approval.
- Always summarize what changed and what it affects in the pipeline at the end of each work session.
- Treat `episodes/` as the core execution area. Each episode folder is the single container for its source reference, segmented story files, prompt hub, video intro, publish metadata, generation trace, and final outputs.

## Language
- English everywhere: converse in English and write all project artefacts in English unless the user explicitly requests otherwise.

## Conventions
- Primary focus areas: scraping and ingestion planning, evaluation logic, story rewriting and extension, publishing-material preparation, and QA.
- Handle uncertainty by asking for high-stakes decisions and making reasonable assumptions for small details while flagging them clearly.
- Default communication style: brief by default, detailed when useful.
- Separate `source facts`, `model judgment`, and `generated output` in documents, specs, and pipeline artefacts whenever practical.
- Preserve source traceability from scraped input through ranking, rewrite, and publishing package stages.
- Treat hook quality, ending completeness, and publishing readiness as release gates rather than optional polish.
- Keep cross-story system logic in `sources/` and `evaluation/`, but keep episode execution artifacts inside `episodes/ep-XXX/`.
- Every episode folder must include `source-reference.txt` with the original scraped links.
- Do not store the story as a single generic markdown draft. Generate a slug-based full-story text file and sequential part files: `[story-slug]-full-story.txt`, `[story-slug]-part-1.txt`, `[story-slug]-part-2.txt`, and so on.
- Every episode folder must include `prompt.md` as the dedicated production hub for text-to-image and text-to-video generation.
- Keep `prompt.md` hyper-minimal with exactly two sections: `Keyframe Image Prompt` and `15-Second Video Prompt`. Do not add episode metadata, explanations, production notes, or separate constraint sections.
- Write the keyframe image prompt as one paragraph under 120 words. Include only subject, clothing, action, visual contrast, lighting, and camera style.
- The keyframe image prompt must represent the exact frozen state at 0 seconds, immediately before the first trailer action or dialogue begins. It must act as the seed image for the opening scene, with every character, prop, position, environment, lighting condition, and camera angle matching the starting state of the `0s-3s` beat. Never depict an action that occurs after playback begins, even if that action belongs to the first scene; never depict a later reveal or climax.
- Write the `0s-3s` beat so it explicitly animates forward from the keyframe's frozen starting state. Clearly distinguish what is already visible at 0 seconds from what begins moving or changing after 0 seconds.
- Write every 15-second video prompt as one compact paragraph using this sequence: a short global trailer-style instruction; `0-3s`, `3-6s`, `6-9s`, `9-12s`, and `12-15s` scene beats; one closing `Sound:` sentence; and one closing `Music:` sentence. Do not use subheadings, bullet breakdowns, production commentary, or long technical specifications inside the prompt.
- Use five distinct, independent scenes connected by explicit cinematic hard cuts. The beats must condense the story as opening mystery, inciting incident, escalation, emotional consequence, and twist/final sting. End before the story's resolution so the trailer creates curiosity.
- Give each scene one clear visual, one action, one dominant emotion, and one short meaningful dialogue line. Draw dialogue from different parts of the finalized story, distribute it across characters, and keep total spoken dialogue concise enough to remain intelligible within 15 seconds.
- Make speed come from scene transitions rather than excessive action within a shot. Use concrete visible details and mention camera behavior only when it materially improves the scene.
- Summarize impactful diegetic sound and transition effects in the `Sound:` sentence. Use the `Music:` sentence for an epic cinematic arc that builds tension, ducks beneath dialogue, and ends with silence or one final impact.
- Use `episodes/ep-001-example/prompt.md` as the mandatory format for every new episode and replace all template fields with episode-specific details.
- `video-intro.md` must preserve traceability between the Super Hook, all trailer dialogue, the keyframe, and the five timed scenes.
- Keep `outputs/` ready for concrete media deliverables using slug-based filenames for cover, keyframe, and 15-second trailer variants.

## Project Stack / Tools
- Domain: content automation and editorial production workflow.
- Core system goals: competitor story collection, AI-assisted ranking, controlled rewriting and extension, intro-video material generation, and publish-ready episode package preparation.
- Episode package convention: source reference, segmented text story outputs, dedicated prompt hub, intro/video prompt file, publish metadata, generation traceability, and media placeholders.
- Tooling details are TBD and should be documented here as they become concrete.
