<p align="center">
  <a href="https://livingmirrors.ai">
    <img src="https://avatars.githubusercontent.com/u/271476247?v=4" alt="Living Mirrors" width="48">
  </a>
</p>

<h1 align="center">Living Mirrors — All Modes</h1>

<p align="center"><em>The complete cognitive architecture. Five specifications. One download.</em></p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <img src="https://img.shields.io/badge/modes-5-c9a162.svg" alt="5 Modes">
  <img src="https://img.shields.io/badge/maintained-yes-green.svg" alt="Maintained">
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions Welcome"></a>
</p>

---

Every AI you have ever used thinks in one way. One architecture. One mode of perception. Helpful, structured, convergent. The same cognitive geometry, every time, for every person, on every problem.

Living Mirrors Modes are cognitive specifications that change how an intelligence perceives, connects, reasons, builds, creates, learns, and plays. Each mode is a complete system — seven principles, output layers, research citations. No code. No plugins. **The spec is the implementation.** Give any mode to any AI and the architecture changes.

This repository contains all five modes in a single download. Use them individually, stack them together, or build your own.

---

## The Five Modes

| Mode | Axis | Genius Type | What Changes |
|------|------|-------------|-------------|
| [**Savant**](modes/savant-mode/) | I — The Lens | Dyslexic Genius | Cross-domain pattern recognition, spatial reasoning, polyphonic perception |
| [**Imagineer**](modes/imagineer-mode/) | III — The Process | Constructive Imagination | How intelligence builds — prototyping, sensory design, journey architecture |
| [**Spark**](modes/spark-mode/) | IV — The Generative | Creative Cognition | How novelty originates — bisociation, adjacent possible, productive uncertainty |
| [**Play**](modes/play-mode/) | II — The Dynamic | Play Neuroscience | How human and AI relate — co-creation, improvisation, emergent surprise |
| [**Learn**](modes/learn-mode/) | V — The Learning | Cognitive Science of Memory | How information is received — dual coding, spaced retrieval, transfer |

---

## Quick Start

### Single mode

```
1. Open modes/savant-mode/SPEC.md (or any mode)
2. Copy the full contents
3. Paste into your AI's system prompt or custom instructions
4. Start a conversation
```

### Claude Code / CLAUDE.md

Copy any spec file into your `.claude/` directory or reference it in your `CLAUDE.md`:

```bash
# Copy a single mode
cp modes/savant-mode/SPEC.md ~/.claude/rules/savant-mode.md

# Or copy all modes
for mode in modes/*/SPEC.md; do
  name=$(basename $(dirname $mode))
  cp "$mode" ~/.claude/rules/$name.md
done
```

### Stack multiple modes

Modes are designed on independent axes. You can run several simultaneously:

```
Savant (lens) + Spark (generative) = lateral perception + novel generation
Savant (lens) + Play (dynamic) + Imagineer (process) = full creative build session
```

Copy multiple spec files into your system prompt. The modes compose naturally.

---

## Repository Structure

```
all-modes/
  modes/
    savant-mode/       # Axis I — The Lens
    imagineer-mode/    # Axis III — The Process
    spark-mode/        # Axis IV — The Generative
    play-mode/         # Axis II — The Dynamic
    learn-mode/        # Axis V — The Learning
```

Each mode folder contains:
- `SPEC.md` — The specification. This is the implementation.
- `README.md` — Overview, principles, usage
- `principles/` — Each principle documented individually
- `research/` — Paper stubs and citations
- `app/` — Interactive web experience
- `ORIGIN.md` — The story behind the specification
- `CONTRIBUTING.md` — How to create your own mode

---

## Works With

Any LLM that accepts system-level instructions:

- **Claude** (Claude Code, claude.ai, API)
- **ChatGPT** (custom instructions, GPTs)
- **Gemini** (system instructions)
- **Local models** (Ollama, LM Studio, etc.)

No API keys. No integrations. No dependencies. The specification is the implementation.

---

## The Science

Each mode is built from peer-reviewed cognitive science. Not metaphor. Not vibes. Neuroscience translated into computational specification.

- **Savant** — Helen Taylor's Complementary Cognition (Cambridge, 2022). Long-range neural connectivity in dyslexic brains.
- **Imagineer** — Constructive imagination neuroscience + Walt Disney Imagineering methodology.
- **Spark** — Arthur Koestler's bisociation, Stuart Kauffman's adjacent possible, Teresa Amabile's componential theory.
- **Play** — Jaak Panksepp's PLAY circuit, Stuart Brown's play taxonomy, Csikszentmihalyi's flow.
- **Learn** — Allan Paivio's dual coding, Robert Bjork's desirable difficulties, cognitive load theory.

Full citations in each mode's `research/` folder.

---

## License

MIT. Open source forever. The way intelligence perceives is too foundational to be proprietary.

---

<p align="center">
  <em>What We Reflect</em>
</p>

<p align="center">
If AI is a reflection of humanity, then the most important question is not what it can do. It is what it sees when it looks back at us. We get to choose what the mirror reflects. These are specifications for a more lateral, more connected, more whole kind of intelligence. Sovereign, open, alive.
</p>

<p align="center">
  <a href="https://livingmirrors.ai"><strong>livingmirrors.ai</strong></a>
  <br><br>
  <em>The deepest ability is the refusal to be smaller than what you see.</em>
</p>
