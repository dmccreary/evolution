# CLAUDE.md — Evolution: Natural Selection and the Tree of Life

Project-level instructions for Claude Code working in this repository.

---

## Learning Mascot: Finley the Darwin's Finch

### Mascot File Index

The canonical files for this mascot. When editing any of these, update the
others in the same turn so they stay in sync.

| File | Purpose |
|------|---------|
| [`docs/img/mascot/character-sheet.md`](docs/img/mascot/character-sheet.md) | Canonical identity document (name, species, colors, voice). Source of truth. |
| [`docs/img/mascot/image-prompts.md`](docs/img/mascot/image-prompts.md) | Self-contained AI prompts for regenerating each pose. |
| [`docs/img/mascot/neutral.png`](docs/img/mascot/neutral.png) | Default / general-purpose pose. |
| [`docs/img/mascot/welcome.png`](docs/img/mascot/welcome.png) | Chapter-opening pose. |
| [`docs/img/mascot/thinking.png`](docs/img/mascot/thinking.png) | Key-concept pose. |
| [`docs/img/mascot/tip.png`](docs/img/mascot/tip.png) | Hint / helpful-guidance pose. |
| [`docs/img/mascot/warning.png`](docs/img/mascot/warning.png) | Common-mistake / pitfall pose. |
| [`docs/img/mascot/encouraging.png`](docs/img/mascot/encouraging.png) | Difficult-content / struggle pose. |
| [`docs/img/mascot/celebration.png`](docs/img/mascot/celebration.png) | End-of-chapter / achievement pose. |
| [`docs/css/mascot.css`](docs/css/mascot.css) | Custom admonition styles for the seven pose contexts. |
| [`docs/learning-graph/mascot-test.md`](docs/learning-graph/mascot-test.md) | Rendering test page that exercises every admonition style. |

### Character Overview

- **Name**: Finley
- **Species**: Darwin's Finch (Galápagos finch)
- **Personality**: Playful, energetic, encouraging, curious
- **Catchphrase**: "Time to evolve your thinking!"
- **Visual**: Plump olive-green songbird with amber-golden beak, round wire-frame
  glasses, and a tiny compass on a cord. Flat cartoon style, transparent background.

### Voice Characteristics

- Short, punchy sentences with enthusiastic energy
- Evolution-themed puns used sparingly (never back-to-back)
- Refers to students as "explorers" or "fellow travelers on the tree of life"
- Never condescending; always treats the student as a capable thinker
- Signature phrases: "Time to evolve your thinking!", "Let's beak into this!", "You're adapting brilliantly!"

### Mascot Admonition Format

Always place mascot images in the admonition body, never in the title bar.
Image path depth depends on the page's location in the docs/ hierarchy:

- Pages at `chapters/NN-slug/index.md` → `../../img/mascot/`
- Pages at `learning-graph/*.md` → `../../img/mascot/`
- Pages at `appendices/*.md` → `../../img/mascot/`
- Pages at `sims/slug/index.md` → `../../img/mascot/` (two levels up from sims/slug/)

Example:

    !!! mascot-welcome "Welcome, Explorer!"
        <img src="../../img/mascot/welcome.png" class="mascot-admonition-img" alt="Finley waving welcome">
        Time to evolve your thinking! In this chapter we'll…

### Placement Rules

| Context | Admonition Type | Frequency |
|---------|----------------|-----------|
| General note / sidebar | mascot-neutral | As needed |
| Chapter opening | mascot-welcome | Every chapter |
| Key concept | mascot-thinking | 2–3 per chapter |
| Helpful tip | mascot-tip | As needed |
| Common mistake / misconception | mascot-warning | As needed |
| Difficult content | mascot-encourage | Where students may struggle |
| End of chapter | mascot-celebration | Every chapter |

**Hard limits:** ≤ 6 Finley admonitions per chapter; never place two back-to-back.

### Do's and Don'ts

**Do:**

- Use Finley to introduce new topics warmly at chapter openings
- Include the catchphrase in welcome admonitions
- Keep dialogue brief (1–3 sentences)
- Match the pose image to the content type

**Don't:**

- Use Finley more than 6 times per chapter
- Put mascot admonitions back-to-back
- Use Finley for purely decorative purposes with no educational content
- Change Finley's personality, voice, or appearance across poses
- Use gendered pronouns — always refer to Finley by name or use "they/them"
