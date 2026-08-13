# writ

A self-edit checklist skill that catches AI writing tells before you hit send.

`writ` turns Wikipedia's community-maintained [Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide into a working checklist. Wikipedia editors built the original guide after reviewing thousands of AI-generated submissions and cataloguing what gave them away. No single item on the list proves AI authorship. It's a combined signal, and applying it well means reading the genre, not just running the list mechanically.

Works with any agent or framework that supports loadable skills, system prompts, or custom instructions — not tied to a specific model or platform.

## What it catches

- Tacked-on significance ("...highlighting the shift toward X")
- Stock significance-vocabulary (*delve, tapestry, robust, seamless, game-changer*)
- The "it's not X, it's Y" false-contrast habit
- Redundant recaps and restated conclusions
- Em dash overuse
- Manufactured "debate" around settled facts
- A narrow transition palette (*moreover, furthermore, that said*)
- Promotional lean in neutral contexts
- Over-formatting: headers, bold, bullets where plain prose reads better
- Leftover assistant voice ("I hope this helps!")
- Flat sentence rhythm

## Install

The skill lives in `writ/SKILL.md`. How you load it depends on your agent setup:

- **Skill-based agents** (e.g. tools with a skills directory): copy the `writ/` folder into wherever your agent looks for skills.
- **System-prompt-based agents**: paste the contents of `writ/SKILL.md` into your system prompt or instructions field.
- **Custom pipelines**: read `writ/SKILL.md` at runtime and inject it as context before any writing/editing task.

Trigger conditions are described in the frontmatter — adapt them to however your agent handles skill routing or triggering.

## Usage

Give your agent a draft and ask it to revise it, or say something like:

> "Rewrite this so it doesn't sound AI-generated."

The checklist is meant to run as a silent self-edit pass — the agent applies it and delivers clean output, without narrating the process back to you.

## Notes

Built for English prose. Several checks, em dash frequency especially, don't map onto other languages.

The stock-vocabulary list is a snapshot, not a fixed blocklist. Writing patterns shift, and the list should shift with them.

Proportion is the goal here, not elimination. A piece with zero em dashes and zero contrast constructions can read just as artificial as one stuffed with them.

## License

MIT. See [LICENSE](./LICENSE).
