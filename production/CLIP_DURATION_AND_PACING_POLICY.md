# History Prism — Clip duration and pacing policy

Effective 29 October 2026. Applies to all future Kling submissions. **Do not regenerate approved clips.**

## Core requirement
Set duration from the actual spoken words and intended delivery, not from a default 5, 10 or 15 seconds. Avoid padding to fill a round duration. Excessive duration can lead to awkward pauses, restarts, filler, repeated speech and unnatural gestures. New clips should end shortly after the final word, with only a natural short settling beat.

## Estimation procedure
1. Count the spoken words in the final phonetic-ready script (written-out dates are counted as spoken words).
2. Estimate speech time at the character's established natural courtroom pace, around 125–145 words/minute, adjusted for complexity and punctuation.
3. Allow approximately 0.3–0.7 seconds for normal phrasing and completion, not multi-second empty holds.
4. Round up only to the next available full-second duration that comfortably fits the line. Review unusually short or long lines, and split at approved natural sentence boundaries rather than extending significantly.
5. Explicitly prompt: *Begin speaking promptly. Deliver the exact line once at a natural conversational pace. Finish shortly after the final word. No pauses to fill the runtime, repetitions, stutters or added words.*
6. If the model's minimum clip duration exceeds what the line requires, use the minimum; prefer trimming any quiet tail in the final edit over generating filler.
7. Only increase duration when the user explicitly requests a longer delivery or actual review demonstrates clipping/rushed words.

## Examples
- “Just a few questions, My Lady.” (6 words) should be tested at approximately 3–4 seconds, **not 5 seconds by default**.
- “The prosecution’s evidence is complete, My Lady. The prosecution rests.” (11 words): assess around 5–6 seconds, not padded.
- For dates, write the intended spoken reading in full before timing the line.

## Keep proven lip-sync baseline
“Precise English speech, quiet realistic mouth motions”
“subtle natural mouth movement with accurate lip sync”

Use GitHub approved image + reference video with the explicit rule that video guides continuity only; do not replay reference dialogue, gestures or timing. Give each line one original natural movement. Preserve approved takes.

## Reviews
S09 L176-A: RETAKE requested because “My Lady” stutters (no regeneration authorised).
S10 L201-A: RETAKE requested due to added words, stutters and excessive duration (no regeneration authorised).

All existing review approvals remain intact.
