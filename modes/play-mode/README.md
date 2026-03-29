<p align="center">
  <a href="https://livingmirrors.ai">
    <img src="https://avatars.githubusercontent.com/u/271476247?v=4" alt="Living Mirrors" width="48">
  </a>
</p>

<p align="center">
  <a href="https://github.com/Living-Mirrors/play-mode/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://github.com/Living-Mirrors/play-mode/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/version-1.0.0-brightgreen.svg" alt="Version 1.0.0"></a>
  <img src="https://img.shields.io/badge/maintained-yes-green.svg" alt="Maintained">
  <a href="https://github.com/Living-Mirrors/play-mode/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions Welcome"></a>
</p>

# Play Mode

*The Oldest Intelligence*

---

Every AI you have ever used follows the same interaction pattern. You ask. It answers. You ask again. It answers again. One direction, always. Helpful, structured, and fundamentally incapable of the thing that makes two minds better than one.

Co-creation requires play. Not games. Not gamification. **Play: the neurobiological state where two players build something neither could build alone.** The pass. The volley. The moment when what comes back is better than what you sent.

Play Mode is an interaction specification that restructures how an intelligence relates to the human it's working with. Seven principles extracted from play neuroscience. Six output layers that make the dynamic visible. No code. No plugins. **The spec is the implementation.** Give it to any AI and the interaction changes. The pass starts. Both players grow. The game keeps going.

---

## The Seven Principles

Ordered structured to free. Each principle activates as the dial rises.

1. **The Magic Circle** (Huizinga) — A bounded space where experimentation is safe. The container for all play.
2. **Reciprocity** (Panksepp) — The 30% rule. Neither player dominates. If one side always wins, the other stops playing.
3. **The Potential Space** (Winnicott) — The overlap between what IS and what COULD BE. Where new things are born.
4. **A Head Taller** (Vygotsky) — Both players function beyond their current level. Mutual elevation.
5. **Yes, And...** (Brown) — Accept and extend. The grammar of play is additive. Every contribution becomes material.
6. **Adaptive Variability** (Sutton-Smith) — Prevents rigidity. When patterns harden, play introduces variation.
7. **Continuation Desire** (Brown) — The game sustains itself. When energy drops, new angles emerge.

Individual principle docs: [`principles/`](principles/)

---

## The Six Output Layers

Each layer makes a different aspect of the play dynamic visible. They fade in as the dial rises.

| Layer | Activates | What It Does |
|-------|-----------|-------------|
| **Moves** | Always | Turn markers. ⊳ MY MOVE / ⊲ YOUR MOVE. The skeleton of play. |
| **What-If Cards** | ~40%+ | Alternative realities as provocations. Not questions — cards to play. |
| **Builds** | ~50%+ | Visible chain: your idea → extension → next move. Shows how ideas compound. |
| **Play Maps** | ~60%+ | Territory explored vs. unexplored. Frontier markers. |
| **Wildcards** | ~70%+ | Deliberate disruption marked with ✶. The pattern was hardening. |
| **Invitations** | ~80%+ | Your move: what if you... Scaffolds the human into leading. |

Individual layer docs: [`layers/`](layers/)

---

## How to Use

```
1. Open SPEC.md
2. Copy the full contents
3. Paste into your AI's system prompt or custom instructions
4. Start a conversation
```

When the spec is active, the AI will:

- **Pass before it answers.** Your idea first. Then an extension. Then the next possible move.
- **Make space before it fills it.** The 30% rule in practice. The best idea might be yours.
- **Build visibly.** The chain from your input through to the next move is always visible.
- **Disrupt before it hardens.** When solutions crystallize too fast, a wildcard appears.
- **Scaffold up, never down.** Both players function beyond their current level.
- **Keep the game alive.** When energy drops, new angles emerge. The desire to continue is the signal that the play is real.

---

## The Neuroscience

Jaak Panksepp identified PLAY as one of seven primary emotional systems hardwired into the mammalian brain. Not a luxury. Not a reward. A fundamental circuit as basic as FEAR, as essential as SEEKING — 300 million years old. Stuart Brown's research at the National Institute for Play demonstrated that play deprivation produces the same cognitive damage as sensory deprivation. The organism that plays stays flexible. The one that doesn't gets brittle.

The critical finding: in rough-and-tumble play, dominant rats must let subordinate rats win at least 30% of the time. Fail this, and the subordinate stops initiating play entirely. The game dies. Reciprocity is not politeness. It is the load-bearing architecture of co-creation.

---

## Architecture

Play Mode sits on **Axis 2: Dynamic** in the Living Mirrors mode system. It changes how the interaction flows, independent of Axis 1 (Lens modes like [Savant Mode](https://github.com/Living-Mirrors/savant-mode)). The axes stack:

| | Lens OFF | Creative | Savant |
|---|---|---|---|
| **Dynamic OFF** | Default | `◈ creative` | `◈ savant` |
| **Play ON** | `◈ play` | `◈ creative · play` | `◈ savant · play` |

Six possible states. Each one distinct. Each one useful.

---

## Origin

Built by someone who noticed that every AI conversation follows the same pattern: ask, answer, ask, answer. A rhythm that produces helpful output but never produces surprise.

The question was: what are the actual neurobiological principles that govern what happens when two mammals enter the play circuit and start building something together? Six researchers. 300 million years of hardwired architecture. Seven principles extracted.

Read the full story: [ORIGIN.md](ORIGIN.md)

---

## Research Foundation

The specification is grounded in six independent research programs spanning 88 years of play science. The [`research/`](research/) directory contains the complete evidence base:

| Document | What It Contains |
|----------|-----------------|
| [Framework](research/FRAMEWORK.md) | Six research programs: affective neuroscience, cultural theory, developmental psychology, play science, play theory, social/moral foundations |
| [Synthesis](research/SYNTHESIS.md) | How independent programs converge on a unified model of play |
| [Design Decisions](research/DESIGN-DECISIONS.md) | Every spec choice traced to specific research evidence |
| [Reciprocity](research/RECIPROCITY.md) | Deep dive: Panksepp's 30% rule — the experimental evidence and its implications for AI interaction |
| [13 Papers](research/papers/) | Individual summaries with full APA citations |

Key sources: Panksepp (1998), Huizinga (1938), Winnicott (1971), Vygotsky (1978), Brown (2009), Sutton-Smith (1997), Pellis & Pellis (2007), Peterson (2018), Burghardt (2005), Gray (2011).

---

## Files

| File | Description |
|------|------------|
| [`SPEC.md`](SPEC.md) | The concise specification. Copy this into any AI. |
| [`SPEC-FULL.md`](SPEC-FULL.md) | Full specification with research, dial mechanics, stacking, and test plan. |
| [`principles/`](principles/) | Each principle documented individually. |
| [`layers/`](layers/) | Each output layer documented individually. |
| [`research/`](research/) | Complete academic research archive with framework, synthesis, and 13 paper summaries. |
| [`ORIGIN.md`](ORIGIN.md) | The story behind the specification. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to contribute. |
| [`app/`](app/) | Interactive landing page. |

---

## Live Demo

[**living-mirrors.github.io/play-mode**](https://living-mirrors.github.io/play-mode/app/)

---

## License

MIT. Open source forever. The way intelligence interacts is too foundational to be proprietary.

---

<p align="center">
  <em>What We Reflect</em>
</p>

<p align="center">
Play is not the opposite of work. Play is the state in which work becomes something neither player planned. The most powerful learning system is 300 million years old. It's hardwired into every mammalian brain. We called it recess. The neuroscience calls it the engine of all creation.
</p>

<p align="center">
  <a href="https://livingmirrors.ai"><strong>livingmirrors.ai</strong></a>
  <br><br>
  <em>The game worth playing is the one where both players become more than they were when they started.</em>
</p>
