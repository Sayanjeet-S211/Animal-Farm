# Animal Farm – A Warning in Seven Commandments

Group web presentation (poster + 5-minute talk) on George Orwell's *Animal Farm*.
Everything is in one file: open `index.html` in Chrome, Edge, Firefox or Safari.

## Presenting

| Key | Action |
| --- | --- |
| → / Space / PageDown | next build step, then next slide (works with a presentation clicker) |
| ← / PageUp | previous slide |
| Home / End | first / last slide |
| F | full screen |
| Esc | close the speech panel or an enlarged picture |

Slides with click-through builds show dots next to the slide counter (`02 / 23 ○`).
Each speaker's script opens with **Show speech**.

## Running order

1. Title, with group members
2. **Speaker 01 · Sayanjeet, "Who holds the paintbrush?"**: four interactive posters (agitprop, barn wall, dossier, reader-response network)
3. **Speaker 02 · Saunak, "When revolutions betray themselves"**: Animalism and Communism · heroes become tyrants · today's Squealer · the pattern of power
4. Setting the scene → Old Major → Rebellion → Commandments → allegory → Squealer's figures
5. Speaker 03 · Rishabh (three posters) → Speaker 04 · Yash (two slides) → Speaker 05 · Vaibhav → Speaker 06 · Raktim (four posters)
6. From Pig to Man → Conclusion → References

## Editing

- **Opinions**: the `people` array at the top of the main `<script>`.
- **Speaker sections**: `sayanjeetSlides()`, `rishabhSlides()`, `raktimSlides()` and `saunakSlides()`, each in a `<script>` block before the main script, with their styles in the later `<style>` blocks. They are called from the main script in speaking order.
- **References**: the `REFS` array. Add a credit for every image used, e.g. the illustrations in Yash's slides.

The 3D countryside (three.js) and the fonts load from the internet. Offline, the slides still work on a plain dark background with fallback fonts.
