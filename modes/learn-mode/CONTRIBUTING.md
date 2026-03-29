# Contributing to Learn Mode

Learn Mode is an open cognitive specification. Contributions that deepen its scientific grounding, expand its applicability, or validate its claims are welcome.

---

## Areas of Focus

### Testing the Profiler

The profiler detects learning profile from behavior rather than self-report. This is the most testable and most important claim in the specification.

- Run the profiler prompt ("Teach me something you know deeply") with different learner types
- Compare detected profiles against established learning assessments (not self-report -- validated instruments)
- Document cases where the profiler misreads the learner and what signals were misleading
- Propose refinements to the four detection dimensions (primary channel, secondary channel, emotional trigger, challenge level)

### Validating Emotional Encoding

Principle 3 claims that emotional carriers improve retention of key concepts. This is well-established in laboratory settings (McGaugh) but less tested in AI-mediated learning.

- Design controlled comparisons: same content with and without emotional framing
- Measure retention at 1 day, 1 week, 1 month intervals
- Identify emotional triggers that work across learner types vs. those that are profile-specific

### New Composite Profiles

The current specification includes five composite profiles (Explorer, Architect, Storyteller, Builder, Pattern-Finder). Real learners are blends, and the profile space is larger than five archetypes.

- Propose new profiles grounded in observed behavior patterns
- Include the three dimensions (channel + trigger + challenge level)
- Describe how output adapts for the profile
- Test against real learners to validate the pattern

### Cross-Model Testing

Learn Mode is model-agnostic. It should work with any AI that generates text.

- Implement the specification in different AI systems
- Document where different models struggle with specific principles
- Identify principles that require capabilities not all models have
- Propose graceful degradation strategies for less capable models

---

## How to Submit

1. Fork the repository
2. Create a branch for your contribution
3. Include evidence or reasoning for changes to principles or layers
4. Submit a pull request with a clear description of what was tested, changed, or added

---

## Standards

- Ground claims in published research. Cite sources.
- Prefer behavioral evidence over self-report data.
- Test with real learners, not hypothetical ones.
- Keep the specification tight. Every element pays rent.

---

*Part of [Learn Mode](https://github.com/Living-Mirrors/learn-mode) by [Living Mirrors](https://livingmirrors.ai)*
