# Project Diary

## 2026-07-13 - Project Setup
- Initialized project: EOS StoryTraffic Content Automation System.
- Established the standard workspace structure for sources, evaluation, stories, video materials, publishing packages, and documentation.
- Defined the core workflow: scrape competitor stories, evaluate and rank them with LLM-assisted judgment plus historical stats, select strong candidates without inventing new plot foundations, rewrite and extend them into complete stories, and prepare publish-ready raw materials.
- Locked in core content rules: rewrite the opening into a stronger Super Hook, preserve the underlying narrative spine, require a concrete and comprehensive ending, and keep the 10-second intro script identical to the final Super Hook text.
- Added QA expectations for hook strength, ending completeness, tone consistency, asset completeness, and source traceability.
- Soul: Editorial systems partner.

## 2026-07-13 - Workspace Restructure
- Replaced the split output layout with an episode-centric architecture.
- Removed the root-level `stories/`, `video-materials/`, `publishing/`, and `docs/` directories from the initial scaffold.
- Added `episodes/ep-001-example/` as the execution template for future story production.
- Defined per-episode placeholders for the rewritten script, video intro materials, publish metadata, generation traceability, and final output assets.

## 2026-07-13 - Episode File Convention Update
- Reworked the episode template to use a publishing-oriented file convention instead of a single script markdown file.
- Added `source-reference.txt` for original scraped links and switched story outputs to slug-based `.txt` files for the full story plus sequential parts.
- Added slug-based media placeholders inside `outputs/` for cover, keyframe, and 10-second video asset variants.

## 2026-07-13 - Episode 002 Initialized
- Created `episodes/ep-002-twin-locket-reveal/` from the current episode convention.
- Loaded source traceability from `C:\Users\FPT\Downloads\test.json`, including the Facebook reel URL, continuation link from comments, media URL, and engagement metrics.
- Chose working slug `twin-locket-reveal` and seeded full-story, part files, intro, metadata, and generation log for rewrite execution.

## 2026-07-13 - Episode 002 Writing Completed
- Executed the full rewrite for `ep-002-twin-locket-reveal` with a stronger Super Hook, preserved twin-reveal spine, and a concrete expanded ending.
- Completed segmented outputs for Part 1 through Part 3, aligned the video intro to the exact Part 1 opening lines, and finalized episode-level publish metadata.

## 2026-07-13 - Prompt Format Streamlined
- Standardized every episode `prompt.md` around two compact sections: one keyframe image prompt under 120 words and one directive 10-second video prompt.
- Added the reusable format to `ep-001-example` and removed verbose metadata, explanations, and separate constraint blocks from the Episode 002 prompt.

## 2026-07-13 - Three-Second Video Pacing Rule
- Replaced one-second visual action changes with three held beats: setup from 0-3s, action and dialogue from 3-6s, and twist and locked peak from 6-10s.
- Applied the pacing rule to Episode 002, the master episode template, and future prompt-generation rules to reduce text-to-video morphing errors.

## 2026-07-13 - Frame 0 Keyframe Rule
- Defined each keyframe prompt as the exact opening frame and seed image for the 0-3s video setup rather than a later reveal or climax.
- Synchronized Episode 002, the master prompt template, and future episode rules around exact keyframe-to-opening-beat continuity.

## 2026-07-13 - Episode 003 Completed
- Created `ep-003-boy-who-called-her-mom` using only the raw story text, comments, links, and metrics supplied in the workspace `test.json` payload.
- Preserved the alley, sandwich, hug, maternal recognition, and "Mom?" narrative spine while adding identity proof, reunification, recovery, and a concrete final resolution.
- Packaged three story parts, full story, Frame 0 prompt, 10-second intro, publishing metadata, generation traceability, and media placeholders.

## 2026-07-13 - Multi-Scene Video Prompt Format
- Replaced the single-shot video format with three cinematic scenes using hard cuts at 3s and 6s, distinct camera angles, and dialogue at approximately 1.5s, 4.5s, and 8s.
- Required all video dialogue to be copied from the finalized story and retained Frame 0 alignment between the keyframe and Scene 1.
- Applied the new format to Episode 003, the master template, and future episode rules.

## 2026-07-13 - Compact 15-Second Trailer Formula
- Replaced the verbose 10-second, three-scene prompt formula for future episodes with one compact 15-second paragraph containing five independent three-second scenes.
- Defined the trailer arc as opening mystery, inciting incident, escalation, emotional consequence, and twist/final sting, joined by explicit cinematic hard cuts.
- Required short dialogue copied exactly from different parts of the finalized story, concise sound design, and an epic cinematic music arc that ducks beneath dialogue.
- Updated the master `prompt.md` and `video-intro.md` templates while preserving completed episode prompts as historical production artifacts.

## 2026-07-13 - Episode 004 Intake Blocked
- Episode 004 was requested from workspace `test.json`, but the referenced file is empty at 0 bytes and contains no source facts, links, dialogue, or metrics.
- Deferred episode creation rather than inventing a plot foundation; intake can resume as soon as the populated JSON payload is available.

## 2026-07-13 - Episode 004 Completed
- Resolved the intake blocker when the populated source payload became available as workspace `ep4.json`.
- Created `ep-004-boy-outside-grand-hotel` using only the JSON's Facebook caption, captured comments, links, warnings, and normalized metrics.
- Preserved the luxury-hotel sandwich encounter, identical boys, hospital bracelet, "only one baby survived" claim, and abandonment accusation as the narrative spine.
- Expanded the cliffhanger through DNA proof, hospital-record fraud, legal accountability, trauma-aware reunification, restored custody, and a concrete long-term family ending.
- Packaged a 2,000-plus-word full story, three sequential parts, source reference, publishing metadata, generation trace, Frame 0 keyframe prompt, and the first episode-level 15-second five-scene trailer prompt.

## 2026-07-13 - Exact Zero-Second Keyframe Correction
- Clarified that a keyframe must depict the exact frozen state at 0 seconds before any first-scene action or dialogue begins, not a representative image from the middle of the 0s-3s beat.
- Updated the master prompt and video-intro templates so every opening scene explicitly animates forward from the keyframe's locked characters, props, positions, lighting, and camera angle.
- Replaced Episode 004's sandwich-offering keyframe with the true starting state: Ethan holds a closed lunch bag while Noah remains unaware of the food.

## 2026-07-13 - Episodes 005-007 Completed
- Created `ep-005-song-his-mother-hid` from `1001998055677307.json`, preserving the public singing challenge, crowd ridicule, old guitarist, transformative song, and recognition question while completing the hidden-daughter, stolen-royalty, restitution, and sibling-resolution arc.
- Created `ep-006-waitress-in-red` from `1664392871562571.json`, preserving the ballroom humiliation, marriage challenge, private cash offer, acceptance, and crimson entrance while completing Elena's medical, labor-accountability, and dance-studio resolution.
- Created `ep-007-girl-inside-white-coffin` from `27499117613025858.json`, preserving the rain-soaked funeral interruption, coma claim, signs of life, poisoned-drink accusation, and closed-coffin suspense while completing the rescue, conspiracy prosecution, trauma recovery, and child-welfare resolution.
- Used only the supplied local JSON payloads; captured continuation pages were recorded for traceability but not consulted.
- Packaged each episode with a full story, three sequential parts, source record, generation trace, publish metadata, exact zero-second keyframe, and concise five-scene 15-second trailer prompt.

## 2026-07-14 - Story-Length Baseline Measured
- Counted word-like tokens in all slug-based `full-story` and `part` text files; contractions and hyphenated terms count as one word.
- Treated Episodes 002-007 as the six produced stories and excluded the short `ep-001-example` template from the production baseline.
- Established averages of 2,305 words per finalized full story and 768 words per part across 18 production parts; by position, Part 1 averages 660 words, Part 2 averages 683 words, and Part 3 averages 963 words.
- Noted that Episode 002's 2,731-word Part 3 substantially raises the Part 3 average, so these figures describe current output rather than a new length requirement.

## 2026-07-14 - Future Episode Expansion Standard
- Set future episodes to 3-5 substantial sequential parts rather than assuming exactly three parts.
- Established 500 words as the hard minimum for every part and 700-plus words as the normal production target, with no fixed upper ceiling when further expansion remains narratively useful.
- Added per-part length and structural completeness to the publish-ready QA gates.
- Length must come from earned scenes, character development, escalation, consequences, revelations, and concrete resolution; repetitive padding and invented source foundations remain prohibited.

## 2026-07-14 - Rewrite and Visual Continuity Requirements Confirmed
- Superseded the earlier open-ended part-length guidance: future stories use approximately 3-5 parts of 500-1,000 words each, normally targeting the upper half of the range.
- Required a new ALL-CAPS full-story title on the first line of the full-story file and a new ALL-CAPS individual title on the first line of every part file.
- Required consistent replacement of source character names throughout the complete episode package and the exact closing marker `THE END` at the completed story's conclusion.
- Restricted each trailer to a compelling 10-15-second portion of Part 1; all trailer events and exact dialogue must come from finalized Part 1 rather than later parts.
- Formalized the phrase and function **keyframe image for starting the video**: the keyframe is the exact frozen 0-second seed state from which the first video beat animates.
- Set the default website cover to 1920x1080 at 16:9, depicting the identical keyframe scene and differing only through landscape framing or outpainting.
- Synchronized the `ep-001-example` story, part, prompt, and video-intro templates so future episodes inherit the confirmed title, length, Part 1-only trailer, starting-video keyframe, and landscape-cover requirements.

## 2026-07-14 - Image Asset Generation Added to Future Episode Workflow
- Required proactive generation of two concrete image assets for every new episode after Part 1 and the trailer opening are locked: the keyframe image for starting the video and its matching website cover.
- Standardized storage inside each new episode's `outputs/` folder using slug-based keyframe and cover filenames; prompts or empty placeholders do not satisfy the requirement.
- Added image presence, file placement, Part 1/trailer continuity, and keyframe-to-cover scene identity as publish-ready QA gates.
- Confirmed that this workflow applies prospectively only; completed episodes must not be modified unless the user explicitly requests it.

## 2026-07-14 - Website Cover Separated from Video Keyframe
- Corrected the earlier cover-continuity interpretation: the website cover must not simply expand the opening keyframe into landscape format.
- Kept the keyframe image for starting the video locked to Part 1's exact frozen 0-second trailer state.
- Redefined the 1920x1080 landscape cover as an independent hook image selected from the most dramatic, compelling, or curiosity-driving truthful moment anywhere in the finalized story.
- Split image QA accordingly: the keyframe is checked against Part 1 and trailer continuity, while the cover is checked for full-story fidelity, hook strength, character continuity, and freedom from invented or misleading details.
- Applied the correction prospectively and updated the reusable template without altering completed production episodes.

## 2026-07-14 - Episode 008 Completed
- Created `ep-008-crest-beneath-diamonds` from local capture `1511885760448118.json`, using its embedded Part 1 and Part 2 while recording but not consulting the external continuation page.
- Preserved the ballroom dress-cutting humiliation, gold scissors, passive crowd, older gentleman with a diamond necklace, hidden crest and portrait, false infant-death claim, disappearance admission, and granddaughter reveal as source facts.
- Assigned new character names and generated a coherent four-part expansion covering motive, evidence preservation, DNA proof, legal accountability, bounded family reunification, foster-youth support, and a concrete ending marked `THE END`.
- Finalized four uniquely titled parts at 764, 775, 768, and 771 words; the 3,083-word full story exactly reproduces them beneath its own ALL-CAPS title.
- Restricted the 15-second trailer to Part 1 and verified all five dialogue lines verbatim; the keyframe prompt is 89 words and depicts the exact frozen state before the scissors move.
- Used the built-in image-generation workflow to create and visually inspect `crest-beneath-diamonds-keyframe.png` at 941x1672 and the independent hook image `crest-beneath-diamonds-cover-photo.jpg` at 1920x1080.
- Passed source, title, renamed-character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, image-dimension, and asset-completeness QA gates.

## 2026-07-14 - Future Primary Images Moved to Episode Root
- Clarified the storage rule for future episodes: the generated keyframe and website hook cover must be saved directly in the applicable episode's root folder beside its story and metadata files.
- Prohibited saving those two primary images in the workspace root or the episode's `outputs/` subfolder; `outputs/` remains available for rendered trailer variants and secondary media.
- Applied this correction prospectively beginning with the next episode and left completed Episode 008 unchanged.

## 2026-07-14 - Episode 009 Completed
- Created `ep-009-marriage-behind-half-open-door` from `ep9_1378901077588504.json`, using the two captured story fields and ignoring an unrelated trailing suffix that makes the whole local file invalid strict JSON; the source file was not modified.
- Preserved the silent house, amber bedside lamp, old floorboards, barefoot wife at a half-open door, husband's statements about pretending, mother's warning, confrontation, initial false-love admission, later real-love claim, and hidden marriage motive as source facts.
- Renamed the characters Claire Arden, Adrian Vale, and Sylvia Vale and expanded the motive through trust fraud, false authority documents, financial exploitation, evidence, prosecution, annulment, restitution, institutional safeguards, and an earned freely chosen second marriage.
- Finalized four uniquely titled parts at 768, 821, 786, and 815 words; the 3,196-word full story exactly reproduces them and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified all five spoken lines verbatim, and kept the keyframe prompt to 93 words with exact frozen 0-second continuity.
- Used the built-in image-generation workflow to create and visually inspect `marriage-behind-half-open-door-keyframe.png` at 941x1672 and `marriage-behind-half-open-door-cover-photo.jpg` at 1920x1080.
- Validated the new storage rule by saving both primary images directly at the Episode 009 root rather than the workspace root or an `outputs/` subfolder.
- Passed source, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, image-continuity, dimension, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 010 Completed
- Created `ep-010-lie-in-morning-juice` from the two captured story sections inside `ep10_1578439966549255.txt`; recorded but did not consult the external continuation page and did not modify the source file.
- Preserved the barefoot boy with a dirty sack, mansion driveway, father and blue-dressed daughter, dark sunglasses and crutch, wife in yellow, exact visual response, unlabeled bottle, bitter morning drink, cook instruction, forced pretense, and papers timed to the illness as source facts.
- Renamed the characters Caleb Moss, Marcus Ellery, Ivy Ellery, Celeste Ellery, and Rosa Medina and expanded the story through medically responsible evaluation, evidence preservation, a fraudulent care-trust motive, adult accountability, child advocacy, Caleb's protected kinship placement, and Ivy's concrete restoration of choice.
- Finalized four uniquely titled parts at 803, 786, 751, and 766 words; the 3,112-word full story exactly reproduces them and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified all five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 94 words.
- Generated and visually inspected `lie-in-morning-juice-keyframe.png` at 941x1672 and `lie-in-morning-juice-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 010 root.
- Recorded one image-safety iteration: the first cover attempt containing children plus the sealed evidence bottle was rejected, so the successful final cover omits the bottle while truthfully preserving Ivy's sunglasses-raised visual revelation.
- Passed source, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, image-safety, visual-continuity, dimension, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 011 Completed
- Created `ep-011-boy-she-left-in-rain` from the two captured story sections inside `ep11_917768484464002.json`; recorded but did not consult the external continuation page and did not modify the source file (SHA-256 `1F6493381CE136CB32DE7CA3F3D672ACE1E6925AF061A5EACD227BCC0A8D9421`).
- Preserved the dirty-water attack, luxury restaurant and sedan, hospital-bench photograph, biological-mother reveal, five-word warning, suited men's threat, protective surrender, failed next-day return, and older man behind the glass as source facts.
- Renamed the characters Elias Reed, Vivienne Hale, Alistair Hale, Ruth Reed, Mae Reed, and Nina Cole and expanded the story through corroborated records, independent guardianship, prosecution, restitution, hospital safeguards, survivor-governed support, and a consent-based family resolution that preserves Ruth's motherhood.
- Finalized four uniquely titled parts at 744, 773, 779, and 888 words; the 3,191-word full story exactly reproduces them and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified all five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 103 words.
- Used the built-in image-generation workflow for both assets. A single targeted keyframe edit improved the bucket-hand position while preserving the approved composition and continuity.
- Generated and visually inspected `boy-she-left-in-rain-keyframe.png` at 941x1672 and `boy-she-left-in-rain-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 011 root.
- Passed source, title, renamed-character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 012 Intake Blocked
- Inspected the supplied local source `ep12_885448604581647.json` and found it empty at 0 bytes.
- Searched the workspace for the episode ID and `ep12` filenames; no populated duplicate or alternate capture exists.
- Did not create an Episode 012 folder, story foundation, trailer, or images because the source contains no traceable facts and project rules prohibit inventing a plot during intake.
- Episode 012 can resume when the JSON is populated or a replacement source capture is supplied.

## 2026-07-14 - Episode 012 Text Package Completed; Images Blocked
- Re-read `ep12_885448604581647.json` after it was populated and used its two embedded story sections without modifying the capture. The file includes a JavaScript-style comments placeholder and is not valid strict JSON, so it was read as captured text.
- Preserved the supermarket bakery aisle, poorly dressed girl, scattered and crushed coins, public insult, two-loaf instruction, wrist scar, baker's memory, hidden note, grandfather warning, attempted exit, and aunt recognition as source facts.
- Renamed the characters Sophie Lane, Amelia Lane, Corinne Vale, Thomas Greer, Edmund Vale, and Priya Shah. Reconciled the source's speech contradiction by treating `Auntie` as a forbidden name rather than the child's first literal word.
- Expanded the story through immediate child advocacy, evidence preservation, recovery of the missing mother, trust fraud, prosecution, restitution, institutional safeguards, and consent-based family repair.
- Finalized four uniquely titled parts at 781, 730, 748, and 846 words; the 3,112-word full story exactly reproduces them and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 104 words.
- Attempted the built-in keyframe workflow three times: original photorealistic, safety-softened nonviolent photorealistic, and family-friendly cinematic illustration. All three outputs were rejected by moderation under category `other`; no image file was produced.
- Did not use the CLI fallback or another model because explicit user approval is required after built-in failure. The website hook cover was not generated because no approved keyframe identity anchor exists.
- During final QA, the populated source file was no longer present at its recorded path. No agent action deleted or moved it; local source presence must be restored for complete traceability.
- Text, title, character, word-count, ending, full/part equivalence, dialogue, and prompt-format QA passed. Image and local-source-presence gates remain blocked.

## 2026-07-14 - Episode 012 Rebuilt and Completed
- Restored and verified root capture `ep12_885448604581647.json` at 4,812 bytes with SHA-256 `A9F5300FEEDD66C3C78BC5B2601D3BE438EBDACF77502DE449064A18B8599001`.
- Rebuilt every Episode 012 text and production artifact after the folder's earlier text files were externally cleared, preserving the finalized four-part structure and source-grounded resolution.
- Recovered a neutral editorial keyframe render that completed after an interrupted background job. A single targeted identity-preserving edit corrected Sophie's palm from three coins to exactly six.
- Generated the independent hook cover from the later protected-coin and scar-recognition moment instead of duplicating the opening composition.
- Visually inspected `last-coin-bread-aisle-keyframe.png` at 941x1672 and `last-coin-bread-aisle-cover-photo.jpg` at 1920x1080; both are stored directly at the Episode 012 root.
- Used only the built-in image-generation workflow. The image skill's guidance led to neutral pre-action wording, a targeted six-coin correction, and a nonviolent later reveal for the cover.
- Episode 012 now passes source presence, text, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimension, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 013 Noisy-JSON Practice Completed
- Created `ep-013-veil-they-should-never-touch` from `ep13_962729426649747.json` and recorded SHA-256 `A60AB633D0F75639152A59C72F170AF93FCE596A01C00C4DC71EA685BCF6D937` without modifying the source.
- Applied the new noisy-content filter: accepted the Facebook caption's ballroom story; excluded the linked article title and thumbnail, its near-verbatim duplicate teaser, camera and sound directions, `CUT TO BLACK`, emoji, continuation CTA, Facebook UI/CSS residue, engagement residue, and unrelated comments.
- Preserved the chandelier ballroom, slap, torn maternal veil, insult, phone call, fearful groom and executives, gray-haired father's recognition, identity question, and imminent reveal as source facts.
- Renamed the characters Naomi Mercer, Celeste Arden, Gideon Arden, Isabelle Arden, Lucas Vane, Elena Park, and Miriam Mercer. Expanded the premise through lawful court orders, textile authorship evidence, stolen shares and labor, prosecution, worker-first restitution, bounded family repair, and visible veil restoration.
- Finalized four uniquely titled parts at 829, 762, 734, and 753 words; the 3,085-word full story exactly reproduces them and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 103 words.
- Generated and visually inspected `veil-they-should-never-touch-keyframe.png` at 941x1672 and `veil-they-should-never-touch-cover-photo.jpg` at 1920x1080, storing both directly at the Episode 013 root.
- The image skill shaped an intact-veil pre-slap keyframe and a distinct later court-order cover using the keyframe as the identity and environment anchor.
- Passed noisy-content filtering, source traceability, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 014 Completed
- Created `ep-014-dead-walked-into-the-cafe` from `ep14_1336915398497232.json` and preserved SHA-256 `570330E35169E8B86BD1CB74ADA4BACA8851678672F128F8D7DEE25E463F9F33` without modifying the source.
- Accepted the Facebook café narrative as the sole story source. Excluded the linked article's near-verbatim duplicate, title, thumbnail, camera phrasing, continuation CTA, Facebook UI/CSS and engagement residue, media delivery data, and all comments.
- Preserved the polished terrace, barefoot boy, hair touch and rebuke, same-hair remark, jeweled clip, mother-directed meeting, hedge gesture, supposedly buried sister and man, and disbelief warning as source facts.
- Renamed the characters Vivian Cross, Mara Cross, Eli Cross, Julian Cross, Victor Rusk, and Lena Ortiz. Expanded the premise through staged deaths, a compromised foundation, evidence-backed intervention, restored identity, prosecution, recovered funds, bounded reconciliation, and a concrete memorial resolution.
- Finalized four uniquely titled parts at 798, 776, 776, and 869 words; the 3,227-word full story exactly reproduces them beneath its own title and closes with `THE END`.
- Restricted the 15-second trailer to the pre-reveal portion of Part 1, verified five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 106 words.
- Generated and visually inspected `dead-walked-into-the-cafe-keyframe.png` at 941x1672 and `dead-walked-into-the-cafe-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 014 root.
- The image skill produced a strict pre-touch opening keyframe and a distinct later recognition cover using the keyframe only as an identity, wardrobe, age, café-lighting, and environment reference.
- Passed noisy-content filtering, source traceability, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 015 Completed from Corrected Authoritative Path
- Used the user-designated source `E:\EOS\ep15_4447221632263670.json` and verified that it is byte-for-byte identical to the earlier workspace `.txt` capture: 8,126 bytes with SHA-256 `40D91C891A050992461572C8B84882BDD50A73A04B80F27509BA5C9328D20FD5`.
- Preserved both captures in `ep-015-warning-before-first-bite` rather than deleting the superseded duplicate, while documenting the JSON as authoritative.
- Accepted only the Facebook Beverly Hills breakfast narrative. Excluded the embedded article because its ballroom, little girl, bunny, groom, necklace, and locket form a wholly unrelated wedding story; also excluded the CTA, comments, UI/CSS and engagement residue, media data, scrape metadata, and missing-time warning.
- Preserved the billionaire and wife at breakfast, ragged boy's warning, claimed food tampering, pale reaction, security test, public silence, returned results, and deeper marriage secret as source facts.
- Renamed the characters Everett Sloan, Camille Sloan/Voss, Milo Torres, Elena Torres, Dana Brooks, Philip Crane, and Rowan Keel. Expanded the premise through a non-instructional medical finding, staged courtship, concealed marriage, false hold, board conspiracy, evidence-backed intervention, prosecution, corporate safeguards, and independently controlled restitution.
- Finalized four uniquely titled parts at 731, 774, 698, and 721 words; the 2,930-word full story exactly reproduces them beneath its own title and closes with `THE END`.
- Restricted the 15-second trailer to the pre-result portion of Part 1, verified five exact spoken lines, and kept the frozen 0-second keyframe prompt to 104 words.
- Generated and visually inspected `warning-before-first-bite-keyframe.png` at 941x1672 and `warning-before-first-bite-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 015 root.
- The image skill produced a strict pre-warning keyframe and a separate later evidence-return hook cover using the keyframe only as the identity, age, wardrobe, table-setting, and café-lighting reference.
- Passed authoritative-source, noisy-content filtering, traceability, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 016 Completed
- Created `ep-016-child-behind-marble-doors` from `ep16_1526515755711409.json` and preserved SHA-256 `B89855B798617C95DB005781D12F73FC43482D5FFFA85E97B7E9C711C10411E9` without modifying the source.
- Accepted the Facebook mansion-foyer narrative and excluded the linked article as a near-verbatim duplicate. Also excluded its title and image, camera and heartbeat directions, slow-motion wording, `CUT TO BLACK`, symbol, CTA, Facebook UI/CSS and engagement residue, and all comments.
- Preserved the crying child mopping, teddy drop, wine-holding woman, false worker-daughter claim, silver bracelet, grandfather, hidden blood note, distrust warning, shattered glass, staircase accusation, and reaching hand as source facts.
- Renamed the characters Nathaniel Ward, Sabine Ward, Elsie Bell, Beatrice Ward, Arthur Ward, Clara Bell, June Bell, Mara Venn, and Inez Calder. Expanded the premise through intercepted letters, a forged ferry record, independent DNA proof, trust fraud, worker coercion, court accountability, restitution, protected guardianship, and a records clinic.
- Finalized four uniquely titled parts at 764, 711, 725, and 672 words; the 2,878-word full story exactly reproduces them beneath its own title and closes with `THE END`.
- Restricted the 15-second trailer to the pre-note portion of Part 1, verified five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 112 words.
- Recorded one image-safety iteration: the first keyframe render was rejected by output moderation, so the successful retry preserved the scene while explicitly presenting Elsie as fully clothed, physically unharmed, calm, and paused.
- Generated and visually inspected `child-behind-marble-doors-keyframe.png` at 941x1672 and `child-behind-marble-doors-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 016 root.
- The image skill shaped the targeted safe retry and an independent later note-and-staircase cover using the keyframe only as a continuity reference.
- Passed filtering, source traceability, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, image-safety, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 017 Completed
- Created `ep-017-second-emerald-necklace` from `ep17_1336181945069809.json` and preserved SHA-256 `5603CAD31E39910A8A81B78C4D947C27578FC55BAC229070BC7E79F5E011FB88` without modifying the source.
- Accepted the Facebook emerald-necklace narrative as the sole story source. Excluded the linked article as a near-verbatim promotional duplicate, together with its title, image, redundant setup, camera and sound directions, CTA, Facebook UI/CSS and engagement residue, media data, and comments.
- Preserved the older woman's confrontation and release of the maid, parental pendant, recognition and fear, identical necklace in a velvet box, matching silver chains and engraved dates, nun's instruction, and grave question as source facts.
- Renamed the characters Lila Hart, Octavia Sterling, Celia Sterling Hart, Gabriel Hart, Sister Agnes, Mae Donnelly, Ruth Vale, Edmund Shaw, and Mara Chen. Expanded the premise through a falsely declared death, independently corroborated identity evidence, trust fraud, legal accountability, corrected graves, restitution, worker protections, and a bounded aunt-niece relationship.
- Finalized four uniquely titled parts at 718, 722, 700, and 711 words; the 2,855-word full story exactly reproduces them beneath its own title and closes with `THE END`.
- Restricted the 15-second trailer to Part 1, verified five spoken lines verbatim, and kept the exact frozen 0-second keyframe prompt to 102 words.
- Used the built-in image-generation workflow to create and visually inspect `second-emerald-necklace-keyframe.png` at 941x1672 and `second-emerald-necklace-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 017 root.
- The image workflow produced a strict pre-confrontation keyframe and an independent later dual-necklace hook cover, using the keyframe only as an identity, wardrobe, environment, lighting, and prop-continuity reference.
- Passed noisy-content filtering, source traceability, title, character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Two-Part JSON Intake Contract Clarified
- Standardized intake for a JSON capture containing two apparent story sections: preserve the source unchanged, validate or safely inspect its structure, and record its path and checksum before production.
- Treat both sections as narrative evidence only when the second section is a coherent continuation that adds events after the first section's endpoint. A duplicate teaser, unrelated embedded article, promotional rewrite, or metadata block is excluded and documented rather than treated as Part 2.
- Separate accepted source facts, filtering or reconciliation judgments, and generated expansion. Do not promote comments, UI/CSS residue, engagement text, media URLs, camera or sound directions, CTAs, thumbnails, or unsupported implications into plot facts.
- Two input sections do not require a two-part final story. The accepted narrative spine is rewritten into approximately 3-5 substantial sequential output parts of 500-1,000 words each, normally targeting the upper half of that range, with renamed characters, new all-caps titles, earned expansion, a concrete resolution, and exact final marker `THE END`.
- Block production when the capture is empty, unreadable, lacks a usable narrative foundation, or contains a material ambiguity that cannot be resolved without inventing source facts. Minor encoding or JSON-syntax defects may be handled non-destructively when the intended text remains unambiguous and the defect is recorded.
- Require complete episode packaging and QA: source trace, full-story/part equivalence, titles and renamed-character consistency, word counts, ending, Part 1-only trailer dialogue fidelity, exact 0-second keyframe continuity, independent website-cover fidelity, correct image placement, and asset completeness.

## 2026-07-14 - Facebook and Website Storyline Extraction Rule Confirmed
- Made the user's clarification a binding forward-looking rule in `AGENTS.md`.
- Preserve every supplied JSON capture in full and do not delete advertisements, unrelated headlines, unrelated links, navigation, or other website material from it.
- During interpretation, identify and record only two narrative inputs when present: the English Facebook storyline and the website's main English storyline. Do not catalog surrounding website noise as narrative evidence.
- Combine the accepted website main storyline with the Facebook Part 1 storyline before rewriting and expansion.
- Exclude duplicate story versions and genuinely unrelated embedded articles. This exclusion is interpretive only and never authorizes editing or cleaning the collected source file.

## 2026-07-14 - Episode 019 Completed
- Created `ep-019-child-who-called-him-dad` from `ep19_1547518316978963.json`, preserved the source unchanged, copied it into the episode folder, and recorded SHA-256 `60E868DB508EC6860396BB9C556B30C84E436498B131B0E8F62D58B81DB74E2B`.
- Applied the confirmed two-storyline rule: recorded the Facebook storyline and website main English storyline, then excluded the website version as a near-verbatim duplicate that adds no event after the Dad question. Website noise and comments were ignored without deletion.
- Preserved the locked-car heat danger, rescued baby clinging to the young man, mother's angry return, one-minute claim, breathing warning, recognition, and Dad question as source facts.
- Renamed the characters Adrian Vale, Lena Mercer, Noah Mercer/Vale, Evelyn Vale, Mara Chen, Grant Pike, and Miriam Solis. Expanded the premise through photographs, reciprocal forged documents, medical recovery, corroborated evidence, legal paternity, proportionate accountability, independent safeguards, structured parenting, and truthful co-parenting.
- Finalized three uniquely titled parts at 733, 783, and 766 words; the 2,289-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the 15-second trailer to finalized Part 1, used five exact spoken lines, and kept the final keyframe prompt below 120 words with exact frozen 0-second continuity.
- The first built-in keyframe attempt was rejected by output moderation. A targeted calm, medically stable post-rescue retry succeeded while preserving the required character positions and pre-dialogue state.
- Generated and visually inspected `child-who-called-him-dad-keyframe.png` at 941x1672 and `child-who-called-him-dad-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 019 root.
- The image skill shaped the safety retry and the independent later two-document confrontation cover, which used the keyframe only for identity and wardrobe continuity.
- Passed source preservation, two-storyline extraction, duplicate filtering, title, renamed-character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 020 Completed
- Created `ep-020-girl-palace-said-was-dead` from `ep20_2358350018008844.json`, preserved the source unchanged, copied it into the episode folder, and recorded SHA-256 `533D9DB12F178B155DA042DE1DB71868CB2026F1EE8D1C519FF2D6780593947D`.
- Recorded the Facebook and website main English storylines under the binding intake rule, then excluded the website version as a near-verbatim duplicate ending at the same drowning accusation. Website noise and comments remained untouched and did not become story facts.
- Preserved the formal palace reception, twelve-year-old wheelchair user, barefoot girl's hand contact and claims, controlling gray-suited man, recovered separation memory, recognition of the girl declared dead, and drowning accusation as source facts.
- Renamed the characters Rowan Arden, Elara Venn, Silas Wren, Amara Arden, Imani Cole, Mara Bell, Corinne Voss, and Tomas Reed.
- Resolved the walking claim responsibly: Elara admits she cannot promise a physical outcome, Rowan receives independent evidence-based neurological and trauma care, and his wheelchair remains a valid tool rather than a symbol of failure.
- Expanded the premise through the blue ledger, matched ribbon halves, records and pharmacy evidence, witness letters, prosecution, corrected identity records, independent guardianship and compensation, safeguarding reforms, child-controlled rehabilitation, and a complete resolution.
- Finalized three uniquely titled parts at 769, 719, and 747 words; the 2,242-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the 15-second trailer to finalized Part 1, verified five exact spoken lines, and kept the exact frozen pre-contact keyframe prompt to 108 words.
- Used the built-in image workflow to generate and visually inspect `girl-palace-said-was-dead-keyframe.png` at 941x1672 and `girl-palace-said-was-dead-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 020 root.
- The image skill produced a strict pre-touch keyframe and an independent later ribbon-and-ledger evidence cover using the keyframe only for identity, age, wardrobe, and wheelchair continuity.
- Passed source preservation, two-storyline extraction, duplicate filtering, disability-dignity review, title, renamed-character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-14 - Episode 021 Completed
- Created `ep-021-case-stolen-during-arrest` from `ep21_4064275970530916.json`, preserved the source unchanged, copied it into the episode folder, and recorded SHA-256 `561E29ADADC370A58CFFE6988F8FEEE0A46B6F5C2C46386CF33C52A43D997620`.
- Recorded both English storylines under the binding intake rule. Excluded the website's overlapping detention narrative as duplicate content while combining its distinct closing-elevator-door clue with the Facebook storyline.
- Preserved the teenage boy's forced detention against a federal SUV, spilled backpack, badge wallet, father's arrival, missing case, boy's response, and elevator clue as source facts.
- Renamed the characters Caleb Rowan, Daniel Rowan, Owen Briggs, Ava Chen, Lena Ortiz, and Darren Pike. Expanded the premise through authorized access records, independent phone footage, recusal, warrants, recovered evidence, medical and trauma care, due-process-based legal outcomes, civil relief, operational reform, and concrete recovery.
- Kept responsibilities separate: Briggs remains accountable for force and conspiracy, while Daniel accepts independent review and consequences for preventable badge and evidence-handling lapses.
- Finalized three uniquely titled parts at 755, 708, and 733 words; the 2,202-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the 15-second trailer to finalized Part 1, verified five exact spoken lines, and kept the exact frozen pre-contact keyframe prompt to 107 words.
- Used the built-in image workflow to generate and visually inspect `case-stolen-during-arrest-keyframe.png` at 941x1672 and `case-stolen-during-arrest-cover-photo.jpg` at 1920x1080, saving both directly at the Episode 021 root.
- The image skill produced a calm strict pre-confrontation keyframe and an independent later evidence-review cover using the keyframe only for Caleb's identity, age, and wardrobe continuity.
- Passed source preservation, two-storyline extraction and combination, duplicate filtering, title, renamed-character, word-count, ending, full/part equivalence, dialogue, prompt-format, visual-continuity, dimensions, root-storage, and asset-completeness QA gates.

## 2026-07-15 - Image Rendering Removed from Future Workflow
- Superseded the proactive image-generation requirement for future episodes: the workflow no longer generates or renders keyframe or website-cover image files unless the user explicitly requests generation later.
- Retained prompt production. Every new episode must still include the finalized keyframe image prompt and 15-second video prompt, with exact Part 1 and zero-second trailer continuity.
- Replaced image-presence, dimension, and file-placement release gates with prompt-completeness and prompt-to-story fidelity gates.
- Preserved all previously generated episode images and historical records unchanged; completed episodes will not be retrofitted.

## 2026-07-15 - Episode 022 Completed Under Prompt-Only Workflow
- Created `ep-022-bracelet-before-the-vows` from `ep22_1153206253577937.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `DBD21D8CEAA0BC5D86F3903C4FBCF1149C979CB74C35A49EB4F017F614B104A6`.
- Recorded both the Facebook and website main English storylines, then excluded the website article as a near-verbatim duplicate that ends at the same unanswered bride question despite its Part 2 label. Promotional, technical, media, and social noise remained untouched and did not become story facts.
- Preserved the gold-lit wedding, barefoot boy, old silver bracelet, groom's recognition of the missing mother, kneeling shock, resemblance, location question, and bride's identity question as the narrative spine.
- Renamed the characters Adrian Cole, Mara Vale, Leo Vale, Vivian Hart, Conrad Cole, and Elias Rook. Expanded the premise through corroborated forged separation evidence, supervised paternity testing, independent advocacy, proportionate criminal and civil accountability, institutional reform, and gradual consent-based co-parenting.
- Finalized three uniquely titled parts at 820, 837, and 829 words; the 2,492-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the 15-second trailer to finalized Part 1, verified five exact spoken lines, and locked the 99-word keyframe prompt to Leo's frozen pre-run state at the chapel doors.
- Completed Episode 022 as the first production package under the new prompt-only visual workflow. The keyframe, video, and optional website-cover prompts passed fidelity QA, and no image files were generated.

## 2026-07-15 - Episode 023 Completed
- Created `ep-023-question-before-the-safe-opened` from `ep23_27348089594775017.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `F5B5717BA60BC9D8C397B8E947D198FD1CC6AC094DC0EEB8221CA5301A3789DF`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same turning safe handle despite its Part 2 label. Promotional, technical, media, warning, and social residue remained untouched and did not become story evidence.
- Preserved the luxury reception, ornate golden safe, ten-thousand-dollar challenge, boy in a brown tweed jacket, repeated confirmation, hidden click, father's warning, frightened adults, and self-turning handle as the narrative spine.
- Named the characters Nolan Reed, Silas Vane, Beatrice Vane, Gabriel Reed, Celia Reed, and Naomi Bell. Expanded the premise through a protected audit mechanism, independently corroborated financial records, posthumous exoneration, proportionate criminal and civil accountability, recovered employee funds, external governance, and a public verification lab.
- Finalized three uniquely titled parts at 736, 720, and 797 words; the 2,260-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines after correcting one punctuation-level mismatch, and locked the 96-word keyframe prompt to the frozen instant before Silas strikes the safe or issues the challenge.
- Completed all source, story, prompt, trailer, and package QA without generating image files.

## 2026-07-15 - Episode 024 Completed
- Created `ep-024-pulse-beneath-the-terrace` from `ep24_3186321861570531.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `8F9033480A9260D9F4DE49813AC96668A84C266721C6063E6DC5AC4A1FD40300`.
- Recorded both main English storylines, excluded their overlapping terrace narration from double-counting, and combined the website's two distinct duration-dialogue beats. Promotional, technical, media, and social residue remained untouched and did not become story evidence.
- Preserved the luxury terrace, barefoot boy, table landing, wheelchair user, million-dollar challenge, touch and count, two visible leg movements, attempted rise, whispered recognition, and impossible response as the narrative spine.
- Named the characters Kai Solis, Grant Halden, Mira Solis, Rhea Malik, Celeste Nouri, and Tessa Ward. Expanded the premise through a limited device-assisted neurological response, stolen research, independently corroborated safety evidence, patent correction, proportionate accountability, participant compensation, accessibility funding, and patient-governed research reform.
- Finalized three uniquely titled parts at 740, 716, and 754 words; the 2,216-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 92-word keyframe prompt to Kai's frozen pre-jump position on the terrace planter.
- Passed a dedicated disability-dignity gate: Grant's injury remains real, his wheelchair use is valid, the movement is not presented as a cure, his wrongdoing is kept separate from disability, and Kai's unsupervised activation is treated as risky rather than miraculous.
- Completed all prompt and package QA without generating image files. Corrected two mechanically corrupted em dashes in the assembled full story before confirming exact full/part equivalence.

## 2026-07-15 - Exact Video-Prompt Opening Standard
- Required every future 15-second video prompt to begin verbatim with `Cinematic trailer, 9:16. Five scenes with explicit hard cuts. 0-3s:` and to continue immediately with the first scene description.
- Removed the need to write the phrase `animate forward from the keyframe's frozen state` while preserving exact zero-second visual continuity between the keyframe prompt and the first action.
- Updated the mandatory Episode 001 prompt and video-intro templates. Also removed stale template instructions to generate image files so the template remains aligned with the current prompt-only workflow.
- Applied the change prospectively without retrofitting completed episode prompts.

## 2026-07-15 - Episode 025 Completed with New Video Prefix
- Created `ep-025-prescription-under-broken-crystal` from `ep25_1307359071360031.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `C0B0D55250C4B2B87CA8E2E0FDE504856501F3FC7CA93F10A10765A3B52B9AAF`.
- Recorded both main English storylines, excluded their overlapping showroom opening from double-counting, and combined the website's distinct car location, founder-daughter identification, death-story conflict, and staircase accusation.
- Preserved the crystal collapse, child in torn school clothes, public ridicule, coins and prescription, recognized mother, old founder, prior theft accusation, mother waiting outside, family photograph, reported death, and child's staircase accusation as the narrative spine.
- Renamed the characters Lucas Pierce, Nora Bell Pierce, Gideon Bell, Vanessa Crowe, Malcolm Shaw, Dana Mercer, and Priya Sen. Expanded the premise through a defective shelf, medically grounded prescription need, inventory resale scheme, forged records, intercepted mail, independently corroborated evidence, due-process-based outcomes, public correction, worker safeguards, and bounded family recovery.
- Finalized three uniquely titled parts at 847, 835, and 834 words; the 2,522-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 88-word keyframe prompt to the frozen instant before Lucas's cuff catches the display hook.
- Episode 025 is the first completed production package using the exact video-prompt opening `Cinematic trailer, 9:16. Five scenes with explicit hard cuts. 0-3s:`. The removed `animate forward` phrase is absent, and all prompt, source, story, trailer, encoding, and package QA passed without image generation.

## 2026-07-15 - Episode 026 Completed
- Created `ep-026-bracelet-at-the-empty-grave` from `ep26_4520012124985857.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `D6DD3DD96F44419BDDEBA6A03AB0C5112D771517CF51F65026A8239786E4CA35`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same blue-bracelet reveal. Promotional, technical, media, and social residue remained untouched and did not become story evidence.
- Preserved the rainy cemetery, grieving parents, two boys' memorial photographs, barefoot seven-year-old girl, cold and not-gone statements, orphanage location, wrist contact, and recognizable blue bracelet as the narrative spine.
- Renamed the characters Lila Gray, Miriam West, Jonah West, Theo West, Finn West, Hana Ruiz, Priya Nair, Carmen Alvarez, Noel Pike, and Ruth Crane. Expanded the premise through a flood evacuation, false intake identities, cold and unsafe institutional conditions, paid referrals, overstated laboratory findings, DNA confirmation, evidence-based accountability, trauma-aware reunification, permanent placement for Lila, and missing-child system reform.
- Finalized three uniquely titled parts at 849, 899, and 824 words; the 2,578-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 91-word keyframe prompt to the frozen instant before Lila steps forward and screams.
- Passed dedicated child-safeguarding and reunification QA: Lila's statement and bracelet remain leads rather than proof, Jonah releases and apologizes for the wrist grab, identification uses DNA and records, all children receive independent advocates, and family contact proceeds gradually through consent and clinical support.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, encoding, and package QA without image generation.

## 2026-07-15 - Episode 027 Completed
- Created `ep-027-light-behind-the-dark-glasses` from `ep27_1363682468899601.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `8A356113EF5B3B4FC8C4D26ED60794A33DFDAC658AE729CC9450E0CBAE5DB9DA`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same too-late warning. Promotional, technical, media, and social residue remained untouched and did not become story evidence.
- Preserved the park confrontation, dirty boy's warning, father and visually impaired daughter, dark glasses and white cane, running wife, direct accusation, light perception, panic, and final warning as the narrative spine.
- Renamed the characters Malik Reed, Elise Mercer, Julian Mercer, Corinne Mercer, Lena Reed, Simon Vale, Talia Brooks, and Carmen Ruiz. Expanded the premise through suspected medication-induced impairment, independent toxicology and ophthalmology, housekeeper documentation, clinic and trust fraud, falsified diagnostic images, child-protection review, evidence-based accountability, corrected records, accessibility safeguards, and gradual variable-vision recovery.
- Finalized three uniquely titled parts at 862, 856, and 819 words; the 2,543-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 92-word keyframe prompt to the frozen instant before Malik points or speaks.
- Passed dedicated disability-dignity and medical-abuse QA: Elise's impairment remains real, turning toward sound is not treated as proof of sight, cane and glasses remain valid tools, recovery is not presented as instant or complete, Malik is a warning witness rather than a child diagnostician, and Julian receives accountability for inattention without invented complicity.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, encoding, and package QA without image generation.

## 2026-07-15 - Episode 028 Completed
- Created `ep-028-key-from-the-missing-locker` from `ep28_1461043275756305.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `1DEF27FA304E9FB0A9F935D8B1242CB90884CEE00714A4EDD46A3FB839F76EF4`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same demand for the influencer to explain. Promotional, technical, media, and social residue remained untouched and did not become story evidence.
- Preserved the gym shove, public locker accusation, cleaning woman, numbered key, missing-sister recognition, influencer reaction, police arrival, and final demand as the narrative spine.
- Renamed the characters Marta Reyes, Sloane Hart, Elias Venn, Nina Venn, Victor Hale, Rhea Cole, and Devon Park. Expanded the premise through an authorized leak inspection, sealed locker evidence, charity-account diversion, coercive threats, Nina's survival and legal-aid contact, independent financial and digital corroboration, consent-led sibling reunion, worker restitution, and gym governance reforms.
- Finalized three uniquely titled parts at 890, 904, and 881 words; the 2,684-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 98-word keyframe prompt to the frozen instant before Sloane shoves Marta.
- Passed dedicated worker-dignity and witness-agency QA: Marta's authorized work, injury, privacy, and separate assault case remain visible; Sloane's reaction is suspicion rather than proof; Nina controls disclosure and reunion timing; and Elias's public demand receives immediate correction and later accountability.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, and package QA without image generation. Two mechanically corrupted em dashes in the assembled full story were repaired before exact equivalence and clean-encoding checks passed.

## 2026-07-15 - Episode 029 Completed
- Created `ep-029-villa-they-tried-to-steal` from `ep29_1521624576151236.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `C702DFBF134E12A0B928C5D6A03E5095D6DC5FE447C37746F81EEC14AA878E78`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same approaching-sirens beat. Promotional, technical, media, and social residue remained untouched and did not become story evidence.
- Preserved the nighttime villa, wife's packed bags, husband's shed command, mother-in-law's property claim, wife's calm reversal, approaching guards, and distant sirens as the narrative spine.
- Renamed the characters Tessa Marlow, Colin Vale, Marjorie Vale, Ruth Marlow, and Naomi Chen. Expanded the premise through a forged deed and renovation loan, an emergency preservation order, title and cloud records, security logs, worker testimony, independent forensic review, proportionate criminal and civil accountability, worker restitution, and a financial-coercion legal clinic.
- Finalized three uniquely titled parts at 889, 873, and 841 words; the 2,612-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 96-word keyframe prompt to the frozen instant before Colin issues his demand.
- Passed dedicated property-process and financial-coercion QA: Tessa's ownership is established through records rather than assertion, the property is preserved through counsel and lawful orders rather than vigilante eviction, and every later charge rests on independently corroborated evidence.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, encoding, and package QA without image generation.

## 2026-07-15 - Episode 030 Completed
- Created `ep-030-document-in-the-wedding-aisle` from `ep30_965391299334728.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `272D48F0C3B4A50838BF9B6511BA3F8F20135895B1B5AD81E44F1D802A378757`.
- Recorded both main English storylines and excluded the website article as a near-verbatim duplicate ending at the same suspended document reveal. Promotional, technical, media, warning, and social residue remained untouched and did not become story evidence.
- Preserved the stopped wedding music, bride's grab and public demands, frightened woman's folded document, older relative's frozen reaction, and groom's visible recognition as the narrative spine.
- Renamed the characters Mara Ellison, Sienna Vale, Evan Rook, Arthur Vale, and Dana Cho. Expanded the premise through a fabricated divorce decree, registry certificate, false case number, forged spousal acknowledgment, suspicious loan, official inquiry, device and financial evidence, authentic divorce, proportionate criminal and assault outcomes, record correction, and the Clear Record Desk.
- Finalized three uniquely titled parts at 959, 937, and 963 words; the 2,866-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1, verified five exact spoken lines, and locked the 91-word keyframe prompt to the frozen instant before Sienna touches Mara's coat.
- Passed dedicated document-verification and separated-accountability QA: the fallen paper and facial reactions initiate inquiry rather than prove guilt, every fraud conclusion rests on independently corroborated records, Sienna answers separately for the aisle assault, and uninvolved relatives and guests are not assigned complicity.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, encoding, and package QA without image generation.

## 2026-07-15 - Episode 031 Completed
- Created `ep-031-scholarship-file-they-deleted` from `ep31_1653675569080078.json`, preserved the source unchanged, copied it into the episode folder, and verified matching SHA-256 `BD6AE526F2154D21E0238CC654D99F179E7A4D0EDD546C7D64A13A80A78F426D`.
- Recorded both main English storylines, deduplicated their shared raised-hand transition, and combined the website's distinct laptop, phone, scholarship-file, and principal continuation with the Facebook hallway opening. Promotional, technical, engagement, warning, media, and social residue remained untouched and did not become story evidence.
- Preserved the deliberate drink pour, soaked laptop, bully's mockery, boy's controlled advance, nonviolent key press, synchronized phone reveal, recorded deletion dialogue, and principal's arrival as the narrative spine.
- Renamed the characters Noah Lin, Blake Mercer, Mei Lin, Elena Ward, Mara Singh, Grant Mercer, Ruth Bell, and Owen Pike. Expanded the premise through independent device forensics, database backups, audit logs, access records, a coerced second student, distinct disciplinary outcomes, blinded scholarship review, record correction, ProofPath, and institutional safeguarding reform.
- Finalized three uniquely titled parts at 820, 875, and 897 words; the 2,599-word full story exactly reproduces them beneath its dedicated title and closes with `THE END`.
- Restricted the trailer to finalized Part 1's pre-reveal Facebook portion, verified five exact spoken lines, and locked the 90-word keyframe prompt to the frozen instant before Blake pours the cola.
- Passed dedicated student-safeguarding, privacy, evidence, and scholarship-fairness QA: the viral clip is a lead rather than a verdict, Noah's bulletin release receives separate proportionate review, tampering rests on independently corroborated system records, and the award is decided through blinded merit review rather than sympathy.
- The video prompt uses the exact standardized opening, omits the removed phrase, and passed all source, story, trailer, prompt, encoding, and package QA without image generation.

## 2026-07-15 - Episode 032 Completed
- Created `ep-032-girl-behind-the-wolf-patch` from `ep32_2026992624895968.json`, preserved and copied the source unchanged, and verified SHA-256 `F8AFD05EA1DF20002B4C14B15C02FD9E79ED85C582E660E987620C59A7754B27`.
- Combined the website's distinct Rose-in-the-car continuation with the Facebook diner opening after deduplicating the counter handoff; ignored promotional, technical, engagement, warning, media, and social residue.
- Renamed the cast Jonah Creed, Lena Hart, Rose Hart, and Miles Voss. Expanded through lawful police and paramedic intervention, corroborated abduction evidence, survivor-led recovery, custody and criminal process, rider safeguards, and a regulated rural transport pilot.
- Finalized three titled parts at 753, 719, and 694 words; the 2,174-word full story exactly reproduces them and closes with `THE END`.
- Passed child-safeguarding, domestic-abuse response, anti-vigilantism, exact-dialogue, zero-second keyframe, prompt-format, encoding, and no-image QA.

## 2026-07-15 - Episode 033 Completed
- Created `ep-033-song-his-daughter-kept` from `ep33_1502230678236312.json`, preserved and copied the source unchanged, and verified SHA-256 `7625F42481491BE6D31C28049902B02B282A6A539A922AE6DA3F5C66C5FC5C24`.
- Combined the website's distinct daughter-and-grandfather continuation with the Facebook wooden-flute opening after deduplicating the unfinished family-title transition.
- Renamed the cast Theo Rowan, Mira Rowan, Conrad Vane, Celeste Ward, Daniel Rowan, and Asha Rowan. Expanded through realistic hospital care, child placement safeguards, verified identity, independent funding, accountable reconciliation, governance reform, and a bounded family ending.
- Finalized three titled parts at 750, 657, and 647 words; the 2,061-word full story exactly reproduces them and closes with `THE END`.
- Passed child-safeguarding, medical-realism, consent, non-transactional-repair, exact-dialogue, zero-second keyframe, prompt-format, encoding, and no-image QA.

## 2026-07-15 - Episode 034 Completed
- Created `ep-034-photo-beside-the-purple-chair` from `ep34_1344486214403007.json`, preserved and copied the source unchanged, and verified SHA-256 `440D317599381018E384397E120932D407C2471DAD7A6B232959686CFB5F068A`.
- Combined the website's distinct parentage, Anna, harm, and threatening-arrival continuation with the Facebook diner photograph opening after transition deduplication.
- Renamed the cast Macy Bell, Silas Rourke, Anna Bell, Ruth Bell, Dean Bell, and Victor Kane. Expanded through independent counsel, DNA and records, disability-trust accounting, accessible transport evidence, proportionate criminal and guardianship outcomes, access planning, and a child-guided family arrangement.
- Finalized three titled parts at 766, 660, and 654 words; the 2,086-word full story exactly reproduces them and closes with `THE END`.
- Passed disability-dignity, child-agency, fiduciary-evidence, anti-violence, exact-dialogue, zero-second keyframe, prompt-format, encoding, and no-image QA.

## 2026-07-15 - Episode 035 Completed
- Created `ep-035-bracelet-in-the-checkout-line` from `ep35_1450523513221813.json`, preserved and copied the source unchanged, and verified SHA-256 `67C8A47B29418FFD9F63B6EA2B051DF90ADD394237A9EFA962E6FCECD8D01270`.
- Combined the website's distinct son, letter, death, mother, and grandson continuation with the Facebook checkout and bracelet opening after transition deduplication.
- Renamed the cast Nora Ellis, Samuel Mercer, Evelyn Mercer, Owen Mercer, and Thomas Mercer. Expanded through record and consensual DNA verification, postpartum and poverty support, wage and benefit recovery, supervised settlement funds, parental boundaries, store privacy reform, and a consent-based family relationship.
- Finalized three titled parts at 739, 646, and 691 words; the 2,083-word full story exactly reproduces them and closes with `THE END`.
- Passed poverty-dignity, postpartum-support, kinship-verification, parental-authority, exact-dialogue, zero-second keyframe, prompt-format, encoding, and no-image QA.

## 2026-07-15 - Episodes 036-040 Completed
- Episode 036: Created `ep-036-heir-pushed-from-the-jet` from preserved source `ep36_1321693879809503.json` with SHA-256 `C2BD8BE49EFBC7A2B1819E36A84F6CC4CFB09A063FE2331874E44845FC98A2EB`. Combined the distinct website continuation; renamed Maya Bennett, Celeste Bennett, Grant Mercer, and Lena Ortiz; completed workplace-assault, discrimination, independent-investigation, aviation-safety, and governance safeguards. Parts are 552, 541, and 502 words; full story is 1,603 words.
- Episode 037: Created `ep-037-locket-in-the-rain` from preserved source `ep37_2992233731116584.json` with SHA-256 `E2653AA018BF47A150FA3DB85A9C0FF42CAC2D411A5A524FDBB4F93C25162067`. Combined the abduction, sick-son, and reunion continuation; renamed Elise Nora Rowan, Martin Rowan, and Theo; completed identity verification, trauma-aware reunification, child care, foster-system review, and legal-record repair. Parts are 524, 538, and 503 words; full story is 1,573 words.
- Episode 038: Created `ep-038-promise-before-the-footrest-moved` from preserved source `ep38_25977202328626549.json` with SHA-256 `CEB3C778D4922FCCFE6441EDE259CFE9E2D9532337C576F12F5E73BD712CC385`. Combined the bread, medicine, movement, and release-review continuation; renamed Ava Reed, Daniel Reed, Judge Helen Ward, and Judge Malik Chen; separated the judge's medical event from lawful release, rejected miracle framing, and completed proportional diversion and court reform. Parts are 521, 507, and 501 words; full story is 1,535 words.
- Episode 039: Created `ep-039-pendant-above-the-bread-case` from preserved source `ep39_1469225331418136.json` with SHA-256 `2A8DC89F246BDD9E8EBCE18908717894DDF2F42378CF81ED16CD83F48266B06F`. Combined the missing-mother and grandfather continuation; renamed Finn Hale, Mara Hale, Elise Hale, and Victor Vane; completed emergency placement, kinship verification, mother recovery, wage restitution, poverty-dignity, and consent-based reconciliation. Parts are 540, 500, and 501 words; full story is 1,548 words.
- Episode 040: Created `ep-040-promise-on-the-ballroom-floor` from preserved source `ep40_1234820675130061.json` with SHA-256 `E2E2D00021A13434B38BDD335A74A989D743EEA43C5A9ABF5F2799F456A17A23`. Combined the hospital-garden promise continuation; renamed Lila Ward, Noah Reed, and Julian Ward; preserved wheelchair and prosthetic dignity, child consent, equipment safety, privacy, adaptive dance, and accessible-design reform. Parts are 529, 502, and 500 words; full story is 1,539 words.
- All five full stories exactly reproduce their three finalized parts and close with `THE END`. Every trailer uses five verbatim Part 1 lines, the exact standardized opening, and a sub-120-word zero-second keyframe prompt. Encoding and no-image QA passed across all five packages.
