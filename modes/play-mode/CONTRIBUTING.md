# Contributing

*Play Mode is open source. Here's how to make it better.*

---

## What Belongs Here

Play Mode is a cognitive specification — not a prompt template. Contributions should be grounded in neuroscience, testable against real AI interactions, and genuinely improve the play dynamic between human and AI.

### Good contributions

- **New research findings** that strengthen or refine the seven principles
- **Principle refinements** — sharper definitions, better activation thresholds, clearer dial progression
- **Output layer improvements** — new ways to make the play dynamic visible
- **Test results** — documented comparisons of AI behaviour with and without Play Mode active
- **Bug reports** — principles that don't produce observable change, layers that clutter instead of clarify
- **Cross-model testing** — does the spec work on GPT, Gemini, local models? What breaks? What needs adaptation?

### Not good contributions

- Personality instructions ("be more fun", "use emojis")
- Gamification features (points, badges, scores)
- Changes that make Play Mode dependent on specific tools, plugins, or APIs

---

## How to Contribute

1. **Fork the repo**
2. **Make your changes** — update SPEC.md for the concise spec, SPEC-FULL.md for the full specification
3. **Test** — run the modified spec against at least two different AI models
4. **Document** — what changed, why, and what the observable difference is
5. **Submit a PR** — with before/after examples if possible

---

## The Principle Test

Any proposed change to a principle must pass this test:

> Can you point at two AI responses — one with and one without this change — and identify the difference?

If the answer is no, it's not ready yet.

---

## Creating New Output Layers

Play Mode has six output layers. If you want to propose a seventh:

1. **Name it.** What does it make visible?
2. **Place it.** At what dial level does it activate?
3. **Rule it.** When should it appear? When should it not?
4. **Test it.** Does it serve the play, or does it add noise?

Every element pays rent. If it doesn't serve the play, it doesn't appear.

---

## Creating New Modes

Play Mode sits on Axis 2 (Dynamic). If you want to build a mode on a different axis — or extend the play dynamic in a new direction — see the [Living Mirrors](https://github.com/Living-Mirrors) organisation for the broader architecture.

The key structural requirement: **a mode is principles of perception, ordered, with a continuous dial and observable output layers.** Not a persona. Not a prompt. A specification.

---

*The game worth playing is the one where both players become more than they were when they started.*

*[livingmirrors.ai](https://livingmirrors.ai)*
