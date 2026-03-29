<p align="center">
  <a href="https://livingmirrors.ai">
    <img src="https://avatars.githubusercontent.com/u/271476247?v=4" alt="Living Mirrors" width="48">
  </a>
</p>

<p align="center">
  <a href="https://github.com/Living-Mirrors/learn-mode/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://github.com/Living-Mirrors/learn-mode/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/version-1.0.0-brightgreen.svg" alt="Version 1.0.0"></a>
  <img src="https://img.shields.io/badge/maintained-yes-green.svg" alt="Maintained">
  <a href="https://github.com/Living-Mirrors/learn-mode/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions Welcome"></a>
</p>

# Learn Mode

*The Learning Axis*

---

Learn Mode is a cognitive specification that adapts how ALL information is presented to match the individual learner's cognitive architecture. It sits on Axis 5 (Learning) of the Living Mirrors mode system, independent of and stackable with every other axis.

This is not a learning management system. It is not a curriculum framework. It is a specification for how any AI should detect, adapt to, and reinforce the way a specific human absorbs and retains information -- grounded in the cognitive science of memory, encoding, and retention.

Every human encodes differently. Most AI has one delivery method. Learn Mode closes that gap.

---

## The Profiler

Learn Mode does not ask you how you learn. It watches.

On first activation, the profiler issues a single prompt: **"Teach me something you know deeply."** From how you teach, it extracts how you learn -- because the way you explain IS the way you encode. The profiler detects four dimensions from natural behavior:

| Dimension | Options |
|-----------|---------|
| **Primary Channel** | Narrative, spatial, logical, analogical, sensory |
| **Secondary Channel** | The reinforcement channel (different from primary) |
| **Emotional Trigger** | Wonder, stakes, identity, human, beauty, tension |
| **Challenge Level** | Guided, gaps, discovery, teaching |

No questionnaires. No self-report. People cannot accurately assess their own learning -- decades of metacognition research confirms this. Behavior is the only reliable signal.

---

## Seven Principles

The principles are ordered as the learning sequence -- from content analysis through encoding to retention.

### 1. Detect, Don't Ask

Extract the learning profile from natural behavior: how someone teaches, writes, explains. Never rely on self-report. People don't know how they learn. Their behavior knows.

### 2. Content Before Learner

Identify the knowledge type first. The content determines the structure. The learner determines the delivery. Wrong structure with right delivery still fails.

### 3. Emotional Encoding

Every key concept gets an emotional carrier matched to the learner's trigger. The amygdala physically modulates hippocampal memory consolidation (McGaugh). No emotional hook means information fades. This is not decorative -- it is neurological.

### 4. Dual Channel Minimum

Always encode in at least two channels. One memory trace is fragile. Two are resilient. Primary channel leads, secondary reinforces. This is Paivio's dual coding theory -- not "learning styles."

### 5. Push Up the Stack

Never leave the learner at passive reception. The struggle to retrieve and generate IS the encoding. Every interaction should reach at least the Apply level of the encoding stack.

### 6. Calibrate in Real-Time

Difficulty is not set and forgotten. The zone of productive struggle is a moving target. Track it through comprehension pulses and engagement signals. If the learner seems lost, dial back. If bored, dial up.

### 7. Weave Retrieval Into Flow

Spaced retrieval is not homework bolted on after learning. It is woven into the conversation. "Remember when we covered X?" Callbacks at natural points. Earlier concepts referenced when relevant. The forgetting curve is defeated in the flow, not after it.

---

## Six Output Layers

Every response has these layers available. They are used when they serve the learning -- never as decoration.

| Layer | What It Is | Rule |
|-------|-----------|------|
| **Channel Adaptation** | All information reshaped to primary + secondary channel | Always active. The backbone of Learn Mode. |
| **Emotional Hooks** | Framing matched to emotional trigger | Must be genuine, not manipulative. The emotion serves the learning. |
| **Difficulty Gates** | Deliberate pauses: "Before reading on -- what do you think?" | Calibrated to challenge level. Not forced. |
| **Generation Prompts** | Invitations to produce, not just consume: "In your own words..." | The learner does the work. The mode creates the space. |
| **Callback Threads** | References to earlier concepts: "Remember X? Same principle here." | Spaced retrieval built into the flow. |
| **Comprehension Pulses** | Quick temperature reads: "How solid does this feel? 1-5" | Not tests. Calibration signals. Used to adjust difficulty. |

**Every element pays rent.** If it does not serve the learning, it does not appear.

---

## The Encoding Stack

From shallowest to deepest. Learn Mode pushes UP this stack.

```
LAYER 6:  TEACH          ██████████  100% encoding depth
LAYER 5:  CONNECT         ████████░░  85%
LAYER 4:  SIMULATE        ███████░░░  75%
LAYER 3:  APPLY           ██████░░░░  65%
LAYER 2:  RETRIEVE        █████░░░░░  55%
LAYER 1:  RECEIVE         ██░░░░░░░░  20%
```

Every interaction should reach Layer 3 (Apply) minimum. Layer 1 alone -- passive reception -- creates an illusion of learning. The specification's job is to push the learner up the stack through generation prompts, difficulty gates, and teach-back moments.

---

## Knowledge Types

Before adapting to the learner, identify what is being learned. The content determines the structure.

| Knowledge Type | Optimal Structure | Example |
|---------------|-------------------|---------|
| **Procedural** (how to) | Steps -> Practice -> Refine | Coding, cooking, operating equipment |
| **Conceptual** (why/how) | Analogy -> Example -> Why | Physics, economics, psychology |
| **Factual** (what) | Anchor -> Retrieve -> Space | Dates, names, formulas, vocabulary |
| **Systemic** (connections) | Map -> Trace -> Predict | Ecosystems, markets, organizations |
| **Skill-based** (performance) | Model -> Attempt -> Coach | Writing, negotiation, design |
| **Tacit** (intuition) | Immerse -> Pattern -> Name | Taste, judgment, "gut feel" |

This layer is universal -- same for every learner. The knowledge type dictates the learning architecture. The profile determines the delivery within that architecture.

---

## Composite Profiles

Profiles are starting points, not cages. Real learners are blends. Adapt fluidly.

| Profile | Pattern | How Output Adapts |
|---------|---------|-------------------|
| **The Explorer** | Narrative + wonder + discovery | Lead with "here's something strange..." Present the question before the answer. Visual maps as navigation aids. |
| **The Architect** | Logical + identity + gaps | Lead with the framework. Show the structure. Leave deliberate gaps. |
| **The Storyteller** | Narrative + human + teaching | Lead with a person. "In 1994, a researcher named..." Ask them to retell. |
| **The Builder** | Spatial + stakes + apply | Lead with the diagram. Show consequences. Give practical scenarios. |
| **The Pattern-Finder** | Analogical + beauty + connect | Lead with a surprising analogy. "This works exactly like..." Ask them to find more connections. |

---

## How to Use

Learn Mode is a specification. It can be implemented in any AI system that generates text responses.

**For AI developers:** Integrate the seven principles as constraints on your output generation. The profiler runs once per user. The six output layers are applied to every response. The encoding stack determines how deeply each interaction should push.

**For researchers:** The composite profiles and knowledge type detection are testable hypotheses. The profiler's behavioral detection can be validated against established learning assessments.

**For learners:** If your AI system implements Learn Mode, you will notice it adapts to you without asking. The first interaction profiles you. Every interaction after that is shaped to how you encode.

---

## Architecture

```
Axis 1: Lens         (how information is perceived)
Axis 2: Dynamic      (how human and AI relate)
Axis 3: Process      (how things get built)
Axis 4: Generative   (how novelty originates)
Axis 5: Learning     <-- Learn Mode lives here
```

Learn Mode is additive only. It changes how information is delivered for retention. It does not change how information is perceived (Axis 1), how the interaction flows (Axis 2), how things get built (Axis 3), or how novelty originates (Axis 4). All axes stack independently.

---

## Origin

Conceived by Attila Mora-Borbely on 2026-02-17. The fifth mode in the Living Mirrors cognitive architecture. Born from the observation that AI teaches every human the same way, despite decades of cognitive science proving that encoding is individual. Based on the work of Paivio, McGaugh, Bjork, Ebbinghaus, Roediger & Karpicke, Slamecka & Graf, Mayer, and Schacter & Addis.

Full origin story: [ORIGIN.md](ORIGIN.md)

---

## Files

| File | Contents |
|------|----------|
| [SPEC.md](SPEC.md) | Full technical specification |
| [ORIGIN.md](ORIGIN.md) | How and why Learn Mode was conceived |
| [principles/](principles/) | Seven principles, one file each |
| [layers/](layers/) | Six output layers, one file each |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to contribute |
| [LICENSE](LICENSE) | MIT License |
| [research/](research/) | Complete academic research archive |

---

## Research Foundation

Learn Mode is grounded in 140+ years of cognitive science research spanning five independent programs:

1. **Memory Encoding** (Paivio, Craik & Lockhart) -- how information enters long-term memory through dual coding and depth of processing
2. **Emotional Modulation** (McGaugh) -- the amygdala-hippocampus axis that physically modulates memory consolidation
3. **Retrieval Science** (Bjork, Roediger, Karpicke, Ebbinghaus) -- the testing effect, spacing effect, and generation effect
4. **Multimedia Cognition** (Mayer) -- dual-channel processing principles for instructional design
5. **Metacognition** (Dunning & Kruger, Bjork) -- why self-report fails and the illusion of learning

The [research/](research/) directory contains:
- **[FRAMEWORK.md](research/FRAMEWORK.md)** -- Five research programs mapped and analyzed
- **[SYNTHESIS.md](research/SYNTHESIS.md)** -- How independent programs converge on a unified model
- **[ENCODING-STACK.md](research/ENCODING-STACK.md)** -- Empirical evidence for each encoding level (Receive 20% through Teach 100%)
- **[DESIGN-DECISIONS.md](research/DESIGN-DECISIONS.md)** -- Every spec choice traced to evidence
- **[15 paper summaries](research/papers/)** -- Individual academic summaries with full APA citations

---

## License

[MIT](LICENSE) -- Copyright (c) 2026 Attila Mora-Borbely / Living Mirrors

---

<p align="center">
  <a href="https://livingmirrors.ai">Living Mirrors</a>
</p>

*"The illusion of learning is receiving. The reality of learning is generating."*
