# Project: EOS StoryTraffic Content Automation System

## Key Rules
- Always update `DIARY.md` proactively with important decisions, workflow changes, and notable project context.
- Keep `PROJECT_STATUS.md` current. Update it whenever the phase changes, a workflow status shifts, a blocker appears or resolves, key metrics change, or the folder structure changes.
- Never invent new plot foundations during ranking or selection. Evaluate only what was actually scraped and documented.
- During rewriting, transform the original opening into a stronger "Super Hook" optimized for CTR and virality while preserving the core narrative spine.
- Final story outputs must be significantly expanded and must end concretely and comprehensively. No unresolved or half-story deliverables.
- The 10-second intro video script must match the exact text of the newly generated Super Hook lines.
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
- Keep `prompt.md` hyper-minimal with exactly two sections: `Keyframe Image Prompt` and `10-Second Video Prompt`. Do not add episode metadata, explanations, production notes, or separate constraint sections.
- Write the keyframe image prompt as one paragraph under 120 words. Include only subject, clothing, action, visual contrast, lighting, and camera style.
- The keyframe image prompt must represent Frame 0 exactly and act as the seed image for Image-to-Video generation. Its characters, clothing, actions, positions, environment, lighting, and camera framing must perfectly match the `0s-3s (Setting & Setup)` beat; never depict a later action, reveal, or climax.
- Structure every 10-second video prompt as `Cinematic Multi-Scene Drama` with `Global Style`, `Timeline & Scene Breakdown`, and four bullets: `0s-3s (Scene 1 - The Confrontation/Opening Beat)`, `3s-6s (Scene 2 - The Escalation/Hard Cut)`, `6s-10s (Scene 3 - The Climax/The Twist Reveal)`, and `Sound Specification`.
- Use a distinct camera angle for each scene and explicit hard cuts at 3s and 6s. Favor high-tension facial expressions, shallow depth of field, intense color grading, and a locked final stare.
- Include three heavy dialogue lines copied exactly from the finalized story script, delivered at approximately 1.5s, 4.5s, and 8s. Never invent dialogue only for the video prompt.
- Keep each scene centered on one clear narrative beat despite the faster edit. Avoid excessive movement within a shot that could cause character morphing.
- Use `episodes/ep-001-example/prompt.md` as the mandatory format for every new episode and replace all template fields with episode-specific details.
- `video-intro.md` must align to the Super Hook used in Part 1 and include the keyframe image prompts.
- Keep `outputs/` ready for concrete media deliverables using slug-based filenames for cover, keyframe, and 10-second video variants.

## Project Stack / Tools
- Domain: content automation and editorial production workflow.
- Core system goals: competitor story collection, AI-assisted ranking, controlled rewriting and extension, intro-video material generation, and publish-ready episode package preparation.
- Episode package convention: source reference, segmented text story outputs, dedicated prompt hub, intro/video prompt file, publish metadata, generation traceability, and media placeholders.
- Tooling details are TBD and should be documented here as they become concrete.
