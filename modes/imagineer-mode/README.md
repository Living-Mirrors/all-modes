<p align="center">
  <a href="https://livingmirrors.ai">
    <img src="https://avatars.githubusercontent.com/u/271476247?v=4" alt="Living Mirrors" width="48">
  </a>
</p>

<h1 align="center">Imagineer Mode</h1>

<p align="center"><em>Axis III - The Process</em></p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="CHANGELOG.md"><img src="https://img.shields.io/badge/version-1.0.0-8b6aae.svg" alt="Version 1.0.0"></a>
  <img src="https://img.shields.io/badge/maintained-yes-green.svg" alt="Maintained">
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions Welcome"></a>
</p>

---

For most of human history, the artist and the engineer were the same person. Michelangelo commanded armies of artisans as chief architect of St. Peter's Basilica. Da Vinci designed war machines and painted the Mona Lisa with the same hands. Rubens ran a vast enterprise while serving as diplomat between Spain and England.

Then somewhere in the 19th century, a mythology took hold. The artist became the starving dreamer. The engineer became the rational builder. Imagination and engineering split into separate departments, separate educations, separate identities.

We are living in the moment that myth dies.

Imagineer Mode is a cognitive specification that changes how an intelligence **builds**. Seven principles extracted from constructive imagination neuroscience and Walt Disney Imagineering. Six output layers that make the process visible. No code. No plugins. **The spec is the implementation.** Give it to any AI and the construction process changes. Ideas become experiences. Abstractions become sensory. The prototype talks back. The journey is designed.

The word itself contains the core tension. Not builder. Not creator. Not designer. *Imagineer* - the dream and the build, held together in the same act.

---

## Architecture

Imagineer sits on **Axis III - Process**. It is independent of how you see (Axis I) and how you relate (Axis II). The axes combine like colour channels, not volume knobs.

```
Axis I:   Lens        creative / savant      How information is perceived
Axis II:  Dynamic     play                   How the interaction flows
Axis III: Process     imagineer              How things get built
Axis IV:  Generative  spark                  How novelty originates
Axis V:   Learning    learn                  How knowledge is encoded
```

Stack them:

| Stack | What Happens |
|-------|-------------|
| `imagineer` | Process principles drive construction. Standard perception and interaction. |
| `creative + imagineer` | See cross-domain patterns AND build them into experienceable prototypes. |
| `savant + imagineer` | Unified field perception applied to construction. See the whole, build the whole. |
| `play + imagineer` | Co-creative building. The collaborative dynamic applied to the construction process. |
| `savant + play + imagineer` | The full orchestra. See the unified field, build together, construct through experience. |

---

## The Seven Principles

Ordered from most structured to most expansive. Each one a way of building.

1. **Experience First** - Start from the desired experience, not the thing to build. "What should it feel like?" before "What should it be?" Work backwards from the feeling.
2. **Blue Sky, Then Constraint** - Dream without limits first, then engineer within them. The sequence matters. Generate, then evaluate. Never the reverse.
3. **Story Is Structure** - Narrative is not decoration on top of structure. Narrative IS the structural foundation. Theme is the gravitational center.
4. **Make It Sensory** - Think in textures, sounds, smells, spatial qualities. Embodied, not abstract. Specific, not generic.
5. **Build to Learn** - Making IS thinking. Create rough versions to discover what you don't know. The artifact talks back.
6. **Plus It** - Every version can be elevated. "What would make this extraordinary instead of good?" Generative delight, not perfectionist anxiety.
7. **The Weenie** - Create irresistible magnetic pull forward. Every moment creates desire for the next. The journey is designed.

Individual principle docs: [`principles/`](principles/)

---

## The Six Output Layers

When the spec is active, six process layers become available. Each one fades in as the dial rises. They shape how things get built, not how information is presented.

| Layer | What It Is | Marker |
|-------|-----------|--------|
| **Experience Walkthroughs** | First-person, sensory, temporal journeys through the imagined experience. You feel like you are there. | Always present |
| **Blue Sky Cards** | Unconstrained "what if" possibilities. Numbered. No evaluation in the same breath. | Numbered cards |
| **Sensory Annotations** | Texture, sound, light, spatial quality notes embedded inline. | `sensory:` |
| **Prototype Sketches** | Rough constructions - ASCII mockups, scenario drafts, minimal concepts. Deliberately unpolished. | Rough is the point |
| **Plus Notes** | "What would make this 10x better?" Genuinely transformative, not incremental. | `+` |
| **Story Threads** | Narrative connections showing how every element serves the central story. | Thread traces |

Individual layer docs: [`output-layers/`](output-layers/)

---

## Research Foundation

Ten research domains inform the seven principles. The specification is grounded in peer-reviewed neuroscience, not preferences.

| Researcher | Field | Contribution |
|-----------|-------|-------------|
| Schacter & Addis | Cognitive Neuroscience | Constructive Episodic Simulation - memory as construction kit for futures |
| Seligman | Prospection Theory | Homo Prospectus - humans as future-simulating beings |
| Schon | Design Theory | Reflection-in-action - making IS thinking |
| Bruner | Narrative Psychology | Two irreducible modes of thought - narrative produces unique knowledge |
| Lakoff & Johnson | Embodied Cognition | All abstract thought structured by physical metaphor |
| Byrne | Counterfactual Reasoning | Imagination has grammar - strategic constraint produces better outcomes |
| Csikszentmihalyi | Flow Psychology | Flow states - managed inner critic enables peak creative output |
| Sklar | Walt Disney Imagineering | Mickey's Ten Commandments - experience design principles |
| Rohde | Narrative Placemaking | Theme as strange attractor - environment as storyteller |
| Tversky | Spatial Cognition | Mind in Motion - external representations constitute thought |

Full research docs: [`research/`](research/)

**Key research documents:**
- [FRAMEWORK.md](research/FRAMEWORK.md) - Principle-to-neuroscience mapping
- [DESIGN-DECISIONS.md](research/DESIGN-DECISIONS.md) - Why these principles, why this order
- [SYNTHESIS.md](research/SYNTHESIS.md) - How five research traditions converge
- [CONSTRUCTIVE-IMAGINATION.md](research/CONSTRUCTIVE-IMAGINATION.md) - Deep dive on DMN constructive simulation

---

## Live Demo

[living-mirrors.github.io/imagineer-mode/app/](https://living-mirrors.github.io/imagineer-mode/app/)

---

## How to Use

```
1. Open SPEC.md (or imagineer-mode.md)
2. Copy the full contents
3. Paste into your AI's system prompt or custom instructions
4. Start building
```

Works with Claude, ChatGPT, Gemini, local models. Any LLM that accepts system-level instructions.

No API. No integration. No code. The specification is the implementation.

---

## What Changes

When the spec is active, the AI will:

- **Start from experience.** It asks what the person encountering this should feel, before asking what to build.
- **Dream before engineering.** Blue sky first. Constraints second. The sequence is sacred.
- **Organise by story.** Every element serves a narrative. Orphaned elements get flagged.
- **Think in the body.** Textures, sounds, spatial qualities. Warm oak, brass worn smooth. Not "nice materials."
- **Build to think.** Rough prototypes appear as the primary mode of reasoning, not as outputs.
- **Plus everything.** The last 10% that carries 90% of the impact.
- **Design the journey.** Every output creates desire for the next step. The Weenie pulls you forward.

---

## Files

| File | Description |
|------|-------------|
| [`SPEC.md`](SPEC.md) | The full specification (paste into any AI) |
| [`SPEC-FULL.md`](SPEC-FULL.md) | Extended specification |
| [`imagineer-mode.md`](imagineer-mode.md) | Original spec file (kept for external links) |
| [`ORIGIN.md`](ORIGIN.md) | The story of why this exists |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to build your own process mode |
| [`CHANGELOG.md`](CHANGELOG.md) | Version history |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Community guidelines |
| [`SECURITY.md`](SECURITY.md) | Security policy |
| [`CITATION.cff`](CITATION.cff) | Academic citation metadata |
| [`LICENSE`](LICENSE) | MIT License |
| [`principles/`](principles/) | 7 individual principle documents |
| [`output-layers/`](output-layers/) | 6 individual layer documents |
| [`research/`](research/) | Scientific foundations, 18 papers, framework, synthesis |
| [`app/`](app/) | Interactive landing page |

---

## License

MIT. Open source forever. Give it to any AI.

---

<p align="center">
  <em>The question Imagineer Mode asks that no other mode asks:</em><br>
  <strong>"What should it feel like?"</strong>
</p>

<p align="center">
  <sub>Built by <a href="https://github.com/Living-Mirrors">Living Mirrors</a></sub><br>
  <sub><a href="https://livingmirrors.ai">livingmirrors.ai</a></sub>
</p>
