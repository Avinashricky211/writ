# writ

A Claude skill that catches AI writing tells before you hit send.

`writ` turns Wikipedia's community-maintained [Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) guide into a self-edit checklist. Wikipedia editors built the original guide after reviewing thousands of AI-generated submissions and cataloguing what gave them away. No single item on the list proves AI authorship. It's a combined signal, and applying it well means reading the genre, not just running the list mechanically.

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

Copy the `writ/` folder into your Claude skills directory:

```bash
cp -r writ/ /mnt/skills/user/writ/
```

Claude picks it up automatically on long-form writing tasks, and whenever someone asks to "make this sound more human" or "remove AI tells."

## Usage

Write or paste a draft and ask Claude to revise it. Or just say:

> "Rewrite this so it doesn't sound AI-generated."

The checklist runs as a silent self-edit pass. Claude won't narrate it back to you.

## Notes

Built for English prose. Several checks, em dash frequency especially, don't map onto other languages.

The stock-vocabulary list is a snapshot, not a fixed blocklist. Writing patterns shift, and the list should shift with them.

Proportion is the goal here, not elimination. A piece with zero em dashes and zero contrast constructions can read just as artificial as one stuffed with them.

## License

MIT. See [LICENSE](./LICENSE).
