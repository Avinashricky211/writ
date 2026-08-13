---
name: writ
description: "Use this skill whenever writing or revising prose meant to read as natural human writing — essays, articles, blog posts, book chapters, emails, reports, LinkedIn posts, or any long-form text where the person wants it to not sound AI-generated. Also trigger if the user says things like 'make this sound more human', 'remove AI tells', 'don't write like AI', 'this sounds like ChatGPT', or references Wikipedia's Signs of AI Writing guide. Apply this skill's checklist as a final pass on any substantial written output before delivering it — not just when explicitly asked."
version: "1.0.0"
license: MIT
---

# Writ: Writing That Doesn't Read as AI-Generated

This skill distills Wikipedia's community-maintained "Signs of AI Writing" guide (en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) into a working checklist. Wikipedia editors built it after cataloguing thousands of AI-generated submissions to identify the patterns that give the writing away — not stylistic opinions, but statistically disproportionate tics. No single sign proves AI authorship on its own; they're a combined signal. Use this as a self-edit pass, not a set of rules to consciously narrate.

## Core principle

The single biggest tell isn't any one phrase — it's the impulse to explain the significance of something instead of just stating it. Human writing trusts the reader. AI writing over-narrates: it summarizes what it just said, tells you why something matters, and manufactures contrast where there isn't any. Cutting that impulse fixes more than any find-and-replace list.

## Checklist — run this as a self-edit pass

### 1. Kill tacked-on significance
Watch for sentences that end by explaining their own importance, especially via a dangling "-ing" clause: "...highlighting the shift toward X," "...underscoring its lasting impact," "...cementing its place in Y." State the fact. Let the reader decide if it matters. If a sentence would be just as true without its final clause, cut the clause.

### 2. Retire the stock significance-vocabulary
These words are fine individually but flag AI when clustered: *plays a vital role, serves as a testament to, stands as a reminder, boasts, delve, moreover, furthermore, robust, tapestry, landscape, realm, underscore, leverage, foster, holistic, invaluable, seamless, game-changer, cutting-edge, in today's fast-paced world*. If a sentence needs one of these to sound important, rewrite it to just say the thing.

### 3. Break the "it's not X, it's Y" habit
The negative-parallelism / contrast-reframe construction ("It's not just a product — it's a movement") is a strong tell when repeated. Humans use "but" to genuinely contrast two things; AI uses this frame to manufacture depth that isn't there. Use it sparingly, and only when the contrast is real, not rhetorical.

### 4. Cut the redundant recap
Don't restate a point you made two sentences ago in slightly different words. Don't open a conclusion by re-summarizing the whole piece before adding anything new. If a paragraph could be deleted without losing information, delete it.

### 5. Ration the em dash
AI reaches for em dashes far more than typical human prose in the same genre, often in places a human would use a comma, a colon, parentheses, or just a period. Default to a comma or a full stop; keep an em dash only for a genuine, sharp interruption — not as a tic between every other clause.

### 6. Don't hedge into nothing, and don't manufacture "debate"
Avoid inserting a "some argue / it remains a subject of debate / opinions vary" frame around settled, mundane facts (population figures, etymology, a product spec) just to sound balanced. If there's no real controversy, don't invent one to sound thoughtful.

### 7. Watch for a narrow transition palette
Overreliance on a small rotating set of connectors — *moreover, furthermore, additionally, in conclusion, that said, on the other hand* — reads as templated. Vary connection strategies: sometimes no connector at all, sometimes a short sentence that just continues the thought.

### 8. Avoid promotional lean in neutral contexts
When the task calls for a neutral or analytical tone, watch for language that drifts toward travel-brochure or press-release warmth: unearned superlatives, "rich history," "vibrant community," admiration where description was asked for.

### 9. Formatting restraint
Don't reach for bullet points, bold text, or numbered lists by default when prose would read better. Heavy formatting on a short piece — headers for a three-paragraph answer, bold on every other term — is itself a tell. Match formatting density to actual structure, not habit.

### 10. No leftover assistant voice
Strip any residue of the chat register from the delivered text itself: "I hope this helps," "let me know if you'd like me to adjust this," "feel free to," "certainly!" as an opener. These belong in the conversation around the piece, never inside it.

### 11. Let sentence rhythm vary
AI prose tends toward uniform medium-length sentences with tidy internal balance. Real writing has more variance — a short sentence next to a long one, an occasional fragment, asymmetry. If every sentence in a paragraph is roughly the same length and shape, break the pattern.

## How to apply this

- **While drafting:** keep principle #1 in mind as you write — resist the urge to close sentences with an explanation of their own significance.
- **As a final pass:** reread the draft once specifically hunting for items 2, 3, and 5 (stock vocabulary, false contrasts, em-dash overuse) — these are the highest-frequency tells and the easiest to miss while composing.
- **Don't over-correct:** the guide itself stresses these are disproportionate tendencies, not forbidden constructions. Human writers do use em dashes, do write "not X, but Y," do use transitions. The goal is proportion, not elimination — a piece with zero em dashes and zero contrast constructions can read just as artificial as one with too many.
- **Context matters:** a technical spec, a legal document, or a Wikipedia article has different norms than a personal essay or a LinkedIn post. Apply judgment about which items matter most for the genre at hand.
