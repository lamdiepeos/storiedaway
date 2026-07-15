# Generation Process

## Episode ID
- `ep-012-last-coin-bread-aisle`

## Input and Source Handling
- Read restored root capture `ep12_885448604581647.json` without modifying it.
- Used its embedded Part 1 and Part 2 story fields.
- Read the JSON-like file as captured text because its comments array contains a JavaScript-style comment invalid under strict JSON.
- Did not treat the comments placeholder as source content.
- Verified source size at 4,812 bytes and SHA-256 `A9F5300FEEDD66C3C78BC5B2601D3BE438EBDACF77502DE449064A18B8599001`.

## Source Facts Preserved
- Poorly dressed child beside supermarket bread, scattered and crushed coins, wealthy woman's insult, two-loaf instruction, wrist scar, baker's memory of the baby and fleeing mother, note on the protected coin, grandfather warning, woman's attempted exit, and aunt recognition.

## Editorial Decisions and Generated Expansion
- Renamed and defined the characters as Sophie Lane, Amelia Lane, Corinne Vale, Thomas Greer, Edmund Vale, and Priya Shah.
- Reconciled the source contradiction in which the child speaks several sentences before `Auntie` is described as her first word in years; the rewritten reveal makes it a forbidden name she has not spoken, not her first literal speech.
- Added an immediate child-advocacy response and evidence preservation rather than allowing the crowd to control the case.
- Built the disappearance and financial motive through corroborated motel, clinic, trust, and phone records.
- Made Edmund accountable for the coercive family structure without granting him automatic access to Sophie or Amelia.
- Ended through restored identity, independent safeguards, bounded family repair, and Sophie's choice to help another child without judging his poverty.

## Structure and Length Intent
- Four sequential parts with unique ALL-CAPS first-line titles.
- Each part targets 500-1,000 words and uses earned escalation rather than filler.
- Full story has a distinct ALL-CAPS title and reproduces all finalized parts in order.
- Final part closes with exact `THE END`.

## Trailer and Image Logic
- Trailer restricted to a 15-second portion of finalized Part 1.
- Five spoken lines copied verbatim from Part 1.
- Keyframe freezes all six coins in Sophie's palm before Corinne takes her first step or speaks.
- A neutral editorial-photography render completed after earlier output-moderation failures and an interrupted background job.
- The recovered keyframe initially showed three coins; one targeted identity-preserving edit corrected the palm to exactly six visible coins while keeping every other approved detail unchanged.
- Keyframe final: `last-coin-bread-aisle-keyframe.png`, 941x1672 portrait, stored directly at the episode root.
- Independent cover uses the later protected-coin and scar-recognition moment, with the keyframe as a strict identity, wardrobe, bakery, and lighting reference.
- Website hook cover final: `last-coin-bread-aisle-cover-photo.jpg`, 1920x1080 landscape, stored directly at the episode root.
- Used only the built-in image-generation workflow; no CLI fallback or alternate model was used.

## QA Record
- Source traceability and hash: Passed
- ALL-CAPS titles and renamed-character consistency: Passed
- Per-part word counts: Passed at 781, 730, 748, and 846 words
- Full/part equivalence: Passed; 3,112-word full story matches all four parts
- Exact `THE END`: Passed
- Part 1 trailer dialogue: Passed; five exact lines occur once in Part 1 and once in the prompt
- Prompt format: Passed; exactly two required sections and a 103-word keyframe prompt
- Keyframe continuity, six-coin correction, visual inspection, and episode-root file presence: Passed
- Cover hook fidelity, identity continuity, 1920x1080 dimensions, visual inspection, and episode-root file presence: Passed
- Asset completeness: Passed
