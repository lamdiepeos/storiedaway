# Project: EOS StoryTraffic Content Automation System

## Key Rules
- Always update `DIARY.md` proactively with important decisions, workflow changes, and notable project context.
- Keep `PROJECT_STATUS.md` current. Update it whenever the phase changes, a workflow status shifts, a blocker appears or resolves, key metrics change, or the folder structure changes.
- Never invent new plot foundations during ranking or selection. Evaluate only what was actually scraped and documented.
- During rewriting, transform the original opening into a stronger "Super Hook" optimized for CTR and virality while preserving the core narrative spine.
- Final story outputs must be significantly expanded, end concretely and comprehensively, and finish with the exact closing marker `THE END`. No unresolved or half-story deliverables.
- Build every future episode as approximately 3-5 substantial sequential story parts, with each part between 500 and 1,000 words and normally targeted toward the upper half of that range.
- Push story length through earned scenes, character development, escalating consequences, investigation or revelation, and a complete resolution. Do not inflate word count with repetition, generic reflection, or plot foundations absent from the source.
- Create a new ALL-CAPS title for the full story and a new ALL-CAPS title for every individual part. The applicable title must be the first line of each full-story or part file.
- Change the source character names and apply the replacements consistently across the full story, every part, prompts, trailer materials, metadata, and generation records while preserving character identities, roles, and relationships.
- The 15-second trailer must cover only a compelling portion of finalized Part 1, open from its Super Hook premise, and copy every spoken line exactly from Part 1. Never use later-part events or invent trailer-only dialogue.
- Every candidate story must carry a traceable source record and evaluation notes.
- Apply QA gates before any publish-ready output: hook fidelity and strength, title and renamed-character consistency, ending completeness and exact `THE END` marker, tone consistency, per-part word-count compliance, Part 1/keyframe-prompt/trailer fidelity, prompt completeness, and section completeness.
- Never delete or overwrite collected source material without explicit user approval.
- For JSON captures containing a Facebook storyline and website content, preserve the complete JSON unchanged. Identify and record only the English Facebook storyline and the website's main English storyline; ignore advertisements, unrelated headlines, unrelated links, navigation, and other website noise without deleting them from the source.
- Combine the accepted website main storyline with the Facebook Part 1 storyline for downstream rewriting. Exclude duplicate versions and genuinely unrelated embedded articles; do not mistake surrounding website noise for story content.
- Do not retrofit or regenerate completed episodes when applying new forward-looking workflow requirements unless the user explicitly requests it.
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
- The full-story file must reproduce the finalized sequential parts as one complete narrative, apart from its dedicated first-line full-story title; every part file must begin with its own dedicated first-line title.
- Every episode folder must include `prompt.md` as the dedicated production hub for text-to-image and text-to-video prompts.
- Keep `prompt.md` hyper-minimal with exactly two sections: `Keyframe Image Prompt` and `15-Second Video Prompt`. Do not add episode metadata, explanations, production notes, or separate constraint sections.
- Write the keyframe image prompt as one paragraph under 120 words. Include only subject, clothing, action, visual contrast, lighting, and camera style.
- Treat the keyframe explicitly as the **keyframe image for starting the video**. It must represent the exact frozen state at 0 seconds, immediately before the first trailer action or dialogue begins, and act as the seed image for the opening scene. Every character, prop, position, environment, lighting condition, and camera angle must match the starting state of the `0s-3s` beat. Never depict an action that occurs after playback begins, even if that action belongs to the first scene; never depict a later reveal or climax.
- Write the `0s-3s` beat as the first action or visible change proceeding from the keyframe's exact frozen starting state. Preserve character, prop, environment, lighting, and camera continuity, but do not include the phrase `animate forward from the keyframe's frozen state`.
- Begin every 15-second video prompt with this exact text: `Cinematic trailer, 9:16. Five scenes with explicit hard cuts. 0-3s:` Immediately after the colon, write the first scene description. Continue in the same compact paragraph with `3-6s`, `6-9s`, `9-12s`, and `12-15s` scene beats; one closing `Sound:` sentence; and one closing `Music:` sentence. Do not place any wording before or inside the required opening, and do not use subheadings, bullet breakdowns, production commentary, or long technical specifications inside the prompt.
- Use five distinct, independent scenes connected by explicit cinematic hard cuts. The beats must condense only the selected portion of Part 1 as opening mystery, inciting incident, escalation, emotional consequence, and twist/final sting. End before the story's resolution so the trailer creates curiosity.
- Give each scene one clear visual, one action, one dominant emotion, and one short meaningful dialogue line. Draw dialogue from different moments within finalized Part 1, distribute it across characters when the text supports that choice, and keep total spoken dialogue concise enough to remain intelligible within 15 seconds.
- Make speed come from scene transitions rather than excessive action within a shot. Use concrete visible details and mention camera behavior only when it materially improves the scene.
- Summarize impactful diegetic sound and transition effects in the `Sound:` sentence. Use the `Music:` sentence for an epic cinematic arc that builds tension, ducks beneath dialogue, and ends with silence or one final impact.
- Use `episodes/ep-001-example/prompt.md` as the mandatory format for every new episode and replace all template fields with episode-specific details.
- `video-intro.md` must preserve traceability between the Part 1 Super Hook, all exact Part 1 trailer dialogue, the keyframe image for starting the video, and the five timed scenes.
- Keep `outputs/` available for user-supplied rendered trailer variants and other secondary media deliverables.
- When a website-cover image prompt is requested, treat the cover as an independent **hook image**, not a landscape expansion of the opening keyframe. Select the most dramatic, emotionally compelling, or curiosity-driving truthful moment from the finalized full story and specify 16:9 at 1920x1080 unless another website format is requested. It may come from any part, but must not invent or misrepresent story events.
- For every new episode, write and finalize the required keyframe image prompt and 15-second video prompt after the story, Part 1, and trailer opening are locked. Do not generate, render, or create actual keyframe or website-cover image files unless the user explicitly requests image generation in a later instruction.
- Treat prompt completeness and prompt-to-story fidelity as mandatory QA gates. QA the keyframe prompt against Part 1 and the trailer's exact 0-second state; QA any requested website-cover prompt separately for full-story fidelity, dramatic hook strength, character continuity, and absence of misleading or invented details. Image presence, dimensions, and file placement are no longer publish-ready gates.

## Project Stack / Tools
- Domain: content automation and editorial production workflow.
- Core system goals: competitor story collection, AI-assisted ranking, controlled rewriting and extension, intro-video material generation, and publish-ready episode package preparation.
- Episode package convention: source reference, segmented text story outputs, dedicated prompt hub, intro/video prompt file, publish metadata, generation traceability, and media placeholders.
- Tooling details are TBD and should be documented here as they become concrete.
