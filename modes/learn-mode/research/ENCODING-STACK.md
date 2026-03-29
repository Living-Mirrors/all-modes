# The Encoding Stack: Empirical Evidence for Six Levels of Learning Depth

---

## The Central Claim

Not all learning is equal. The depth at which information is processed at the moment of encoding determines how durably it is stored, how flexibly it can be retrieved, and how effectively it transfers to new contexts. This is not a pedagogical opinion. It is the most replicated finding in 140 years of memory research.

The encoding stack organizes six levels of processing depth, from shallowest (Receive) to deepest (Teach). Each level has empirical evidence for its relative encoding strength. The percentages are calibrated estimates -- directionally accurate, not precise measurements -- drawn from multiple converging research programs.

```
LAYER 6:  TEACH          ██████████  100% encoding depth
LAYER 5:  CONNECT         ████████░░  85%
LAYER 4:  SIMULATE        ███████░░░  75%
LAYER 3:  APPLY           ██████░░░░  65%
LAYER 2:  RETRIEVE        █████░░░░░  55%
LAYER 1:  RECEIVE         ██░░░░░░░░  20%
```

Every interaction should reach Layer 3 (Apply) minimum. Layer 1 alone -- passive reception -- creates an illusion of learning. The specification's job is to push the learner up the stack.

---

## Layer 1: RECEIVE (20%)

**Definition:** The learner reads, watches, or listens to information without being required to process it further.

**What happens cognitively:** Information enters working memory through the sensory register. If the learner engages in shallow processing (registering the physical features of the text, hearing the words without engaging with their meaning), the resulting memory trace is weak. Craik and Lockhart (1972) demonstrated this directly: processing physical features of words (is this word in uppercase?) produces significantly worse retention than processing semantic features (does this word fit in the sentence?).

**The empirical evidence for ~20%:**

- **Lecture retention.** The widely cited "learning pyramid" (often attributed to the NTL Institute) claims 5% retention from lectures. While the specific pyramid lacks a single definitive source and its exact numbers should be treated cautiously, the underlying research consistently shows that passive reception produces the lowest retention of any learning condition. Studies of lecture retention consistently find that students recall 10-25% of lecture content after 24 hours without intervening review (Bligh, 2000).

- **Craik & Lockhart (1972).** Incidental learning experiments: participants who processed words at the physical level (shallow) showed approximately 15-20% recognition accuracy, compared to 65-70% for semantic processing (deep). The ratio is consistent across replications.

- **Roediger & Karpicke (2006).** The "study-study" condition (reading material twice without testing) produced 42% retention after one week -- but this involves two encoding events, not one. A single passive exposure would produce substantially less. The 20% estimate for a single reception event is conservative.

**Why passive reception is so weak:** Reception does not require the learner to do anything with the information. Working memory can process the words without engaging semantic networks, without connecting to existing knowledge, without generating any response. The resulting trace is shallow by definition -- it engages only the input systems, not the elaborative systems that produce durable encoding.

**Why most AI stops here:** The default mode of AI interaction is: user asks, AI answers, user reads. This is Layer 1. The user receives information. Nothing in the default interaction pushes them to retrieve, apply, simulate, connect, or teach. The information feels understood in the moment (Bjork's illusion of learning) and fades within hours. AI has accidentally created the world's most sophisticated passive reception system.

---

## Layer 2: RETRIEVE (55%)

**Definition:** The learner attempts to recall information from memory before receiving it again. The act of retrieval, successful or not, strengthens the memory trace.

**What happens cognitively:** When the brain attempts to retrieve a memory, it must reactivate the neural pathways that encoded it. This reactivation is itself an encoding event -- the trace is strengthened by the act of being accessed. Failed retrieval attempts (the tip-of-the-tongue experience) still produce encoding benefits because the search process activates related networks. Schacter and Addis (2007) showed that memory retrieval is reconstructive -- the hippocampus reassembles the memory from stored elements, and this reassembly constitutes a new encoding event.

**The empirical evidence for ~55%:**

- **Roediger & Karpicke (2006).** The definitive testing effect experiment. After one week: the group that studied once and was tested three times retained 56%. The group that studied four times retained 42%. More study time, less retention. More retrieval practice, more retention. The tested group's 56% vs. the study group's 42% represents a 33% improvement from a single procedural change -- replacing re-reading with retrieval.

- **Karpicke & Blunt (2011).** Retrieval practice produced better performance than elaborative concept mapping on both verbatim questions (recall of specific information) and inference questions (application of information to new situations). The retrieval advantage held even when the concept mapping group spent more time actively processing the material.

- **Slamecka & Graf (1978).** The generation effect: across five experiments, words generated by the participant (from a cue) were remembered approximately 15-20% better than words simply read. Generation IS retrieval -- the learner must search memory to produce the response.

**Why retrieval works:** The retrieval effort paradox: the harder a successful retrieval, the greater the encoding benefit. Easy retrieval (the answer comes immediately) produces less strengthening than effortful retrieval (the answer requires a search). This is because effortful retrieval activates more of the surrounding associative network, creating more connections to the retrieved information. The difficulty IS the mechanism.

---

## Layer 3: APPLY (65%)

**Definition:** The learner uses retrieved knowledge to solve a problem, complete a task, or address a situation that was not part of the original learning.

**What happens cognitively:** Application requires retrieval PLUS deployment. The learner must not only recall the relevant information but map it onto a new context, determine which elements are relevant, and execute. This engages executive function and contextual binding in addition to the retrieval mechanisms of Layer 2. The resulting memory trace includes both the original information and the application context, creating a richer, more cross-linked representation.

**The empirical evidence for ~65%:**

- **Transfer studies.** Research on transfer of learning consistently shows that applied knowledge is more robustly retained and more flexibly deployable than merely recalled knowledge. Bransford, Brown, and Cocking (2000), in the National Research Council's synthesis *How People Learn*, concluded that "learning with understanding" (applying concepts to novel situations) produces qualitatively different retention than "learning for recall."

- **The generation effect extended.** Slamecka and Graf (1978) demonstrated generation superiority for individual words. Subsequent research showed the same effect for problem solutions, explanations, and procedural steps: when the learner generates the application rather than reading a worked example, retention and transfer both improve.

- **Problem-based learning research.** While PBL as an educational method has mixed outcomes (Kirschner, Sweller & Clark, 2006), the specific mechanism -- applying knowledge to authentic problems -- consistently produces better long-term retention than passive instruction of the same content. The issue with PBL is not that application fails; it is that unguided application can fail because the learner lacks the knowledge to apply. This is why Learn Mode requires Content Before Learner (Principle 2) -- the structure must support the application.

**Why Apply is the minimum acceptable level:** Retrieval alone proves the learner can recall. Application proves they can use. The specification targets usable knowledge -- information that can be deployed when needed, not just recognized when encountered. Any interaction that reaches Apply has produced encoding that includes retrieval, deployment, and contextual binding. This is the threshold for functional learning.

---

## Layer 4: SIMULATE (75%)

**Definition:** The learner constructs a mental simulation -- imagining how knowledge would apply in a scenario they haven't encountered, predicting outcomes, running "what if" experiments in their mind.

**What happens cognitively:** Schacter and Addis (2007) demonstrated that the same hippocampal system that reconstructs past memories constructs imagined future scenarios. Simulation engages this constructive episodic system: the learner must decompose their knowledge into elements, recombine those elements into a novel scenario, and evaluate the coherence of the result. This is cognitively more demanding than applying to a given problem (Layer 3) because the learner must also generate the context, not just operate within one.

**The empirical evidence for ~75%:**

- **Schacter & Addis (2007).** Amnesic patients with hippocampal damage cannot imagine novel future scenarios -- they produce fragmented, spatially incoherent descriptions. This double dissociation (memory loss = simulation loss) confirms that simulation uses the same neural machinery as memory encoding. Engaging this machinery through simulation creates rich, cross-linked traces.

- **Elaborative interrogation research.** Asking "why?" and "what if?" questions during learning (elaborative interrogation) produces significantly better retention than reading alone. Meta-analyses of elaborative interrogation (Dunlosky et al., 2013) rate it as a moderately effective learning strategy -- more effective than highlighting or re-reading, comparable to practice testing.

- **Mental practice literature.** The mental simulation of motor skills (mental practice) produces measurable improvement in subsequent physical performance (Driskell, Copper & Moran, 1994). The mechanism is the same: simulation engages the same neural pathways as actual performance, creating encoding without physical execution.

**Why simulation exceeds application:** Application operates within a given context. Simulation requires the learner to generate the context. This additional generative step engages the constructive memory system more deeply, creating traces that include not just "how to use X" but "where X could be used, what would happen, what could go wrong." The resulting knowledge structure is more flexible and more richly connected.

---

## Layer 5: CONNECT (85%)

**Definition:** The learner identifies relationships between the current material and other knowledge domains, building cross-domain bridges that integrate new information into their existing schema.

**What happens cognitively:** Connection is elaborative encoding at its deepest. The learner must access knowledge from domain A, access knowledge from domain B, identify structural similarities or productive tensions between them, and construct a representation that links them. This engages semantic processing across multiple knowledge networks simultaneously, creating the richest possible web of associative connections around the new information.

**The empirical evidence for ~85%:**

- **Craik & Lockhart (1972).** The deepest level of processing in their original framework was semantic elaboration -- connecting new information to existing meaning structures. Their experiments showed semantic processing produced approximately 65-70% recognition accuracy vs. 15-20% for shallow processing. But their paradigm tested single-domain elaboration. Cross-domain connection goes further.

- **Schema theory (Bartlett, 1932; Anderson, 1977).** Information that is integrated into an existing schema is dramatically more durable and more flexibly retrievable than information stored as an isolated fact. Schema integration means the new information has multiple retrieval paths -- it can be accessed from any node in the connected schema, not just from the original encoding context.

- **Analogical reasoning research (Gentner, 1983).** Cross-domain analogies produce deeper understanding and better transfer than within-domain examples. When a learner maps the structure of one domain onto another (e.g., "the atom is like the solar system"), they encode both the target information and the structural mapping, creating a representation that is richer than either domain alone.

- **Interleaving effect (Bjork & Bjork, 2011).** Interleaving different categories of problems during practice -- rather than blocking by category -- forces the learner to discriminate between categories and connect each problem to its appropriate solution strategy. This produces better long-term retention and transfer, precisely because it requires the cross-referencing that connection demands.

**Why connection exceeds simulation:** Simulation operates within a single knowledge domain, imagining future applications of current knowledge. Connection bridges domains, integrating current knowledge with knowledge from other areas. The resulting trace is embedded in a richer associative network with more retrieval paths. Information that is connected to three domains has three times as many routes back to it as information connected to one.

---

## Layer 6: TEACH (100%)

**Definition:** The learner explains the material to someone else (or prepares to), organizing it for comprehension, anticipating questions, identifying gaps in their own understanding.

**What happens cognitively:** Teaching requires every preceding level simultaneously. The learner must retrieve the information (Layer 2), determine how to apply it in the listener's context (Layer 3), simulate the listener's likely confusion points (Layer 4), and connect it to frameworks the listener already understands (Layer 5). Additionally, teaching requires metacognitive monitoring -- the teacher must assess their own understanding in real-time, identify gaps, and fill them. This combination of retrieval, application, simulation, connection, and metacognitive evaluation produces the deepest encoding measured in the research literature.

**The empirical evidence for ~100%:**

- **The protege effect (Fiorella & Mayer, 2013).** Across multiple experiments, students who prepared to teach material to a peer learned it more deeply and retained it longer than students who studied for a test on the same material. The effect persisted even when the teaching never actually occurred -- merely preparing to teach was sufficient to produce enhanced encoding. The mechanism: anticipating a teaching role changes how information is processed, from "what do I need to remember?" to "how would I explain this?" The latter requires deeper, more organized processing.

- **Learning by teaching studies (Roscoe & Chi, 2007).** Tutors who provided explanations (not just answers) showed learning gains comparable to or exceeding their tutees. The act of constructing an explanation required the tutor to identify the essential structure of the material, organize it coherently, and fill gaps in their own understanding. These are the same operations that produce deep encoding.

- **Self-explanation effect (Chi, 2000).** Students who explained material to themselves during learning showed significantly better comprehension and transfer than students who merely read. Self-explanation requires the learner to identify what they do and don't understand, generate inferences, and repair comprehension failures -- the same metacognitive operations that teaching demands.

- **Why 100% and not just "high":** Teaching is the ceiling of the encoding stack because it necessarily encompasses all lower levels. You cannot teach what you cannot retrieve. You cannot explain application without simulating the learner's context. You cannot answer unexpected questions without cross-domain connection. Teaching is the only activity that simultaneously engages every encoding mechanism in the stack. There is no empirically documented learning activity that produces deeper encoding than teaching.

---

## The Generation Effect: The Mechanism Across All Levels

The thread that runs through every level above Receive is the generation effect (Slamecka & Graf, 1978). At each level, the learner is generating something:

| Level | What the Learner Generates |
|-------|---------------------------|
| Receive | Nothing. Information flows in. |
| Retrieve | The answer (from memory). |
| Apply | A solution (in a given context). |
| Simulate | A scenario (in an imagined context). |
| Connect | A relationship (between domains). |
| Teach | An explanation (for another person). |

Each higher level requires generating something more complex, more deeply processed, and more richly connected. The generation effect is not a single phenomenon -- it is a gradient. The more the learner generates, the deeper the encoding. The encoding stack is a map of this gradient.

---

## Why Most AI Leaves Users at Layer 1

The default interaction pattern of AI -- user asks, AI answers, user reads -- is structurally identical to passive reception. The information is well-organized, clearly explained, and immediately comprehensible. This feels like learning (Bjork's illusion of learning). It is not.

Consider what a typical AI interaction lacks:

- **No retrieval demand.** The user does not need to recall anything -- the answer is presented. Layer 1.
- **No application prompt.** The user is not asked to do anything with the information. Still Layer 1.
- **No generation requirement.** The user does not produce anything. Still Layer 1.
- **No difficulty calibration.** The information arrives at whatever level is requested, without productive struggle. Still Layer 1.
- **No spaced retrieval.** The conversation ends. The information is never revisited. Still Layer 1.

The result: the user walks away feeling informed (the information was clear and comprehensive) but forgetting rapidly (the information was processed at the shallowest possible level). The AI has answered the question perfectly while failing the user's learning completely.

Learn Mode exists to solve this structural problem. Every principle, every output layer, and every design decision is aimed at moving the learner up the encoding stack -- from passive reception toward active production. The specification does not change what information is delivered. It changes how deeply that information is encoded.

---

## The Encoding Stack in Practice

At minimum (every interaction), the specification targets Layer 3 (Apply):

1. **Channel Adaptation** encodes the information in primary + secondary channels (dual coding, cross-stack).
2. **Emotional Hook** tags the key concept with the learner's emotional trigger (consolidation amplification, cross-stack).
3. **Generation Prompt** asks the learner to DO something with the information: "Try applying this to..." or "In your own words, what does this mean for...?" (pushing to Layer 3 minimum).

At full activation (100% dial), the specification pushes toward Layers 4-6:

4. **Difficulty Gate** pauses before key information: "Before reading on -- what do you think happens?" (generation before reception = deeper encoding of the subsequent information).
5. **Callback Thread** references earlier material: "Remember when we discussed X? Same principle here." (spaced retrieval + cross-domain connection = Layers 2 + 5).
6. **Comprehension Pulse** calibrates: "How solid does this feel? 1-5" (metacognitive monitoring = teaching yourself what you know and don't know).

The goal is not to reach Layer 6 (Teach) in every interaction. The goal is to never stay at Layer 1 (Receive). The specification ensures that every piece of information delivered is processed at a depth that gives it a meaningful chance of surviving in long-term memory.

---

*Part of [Learn Mode](https://github.com/Living-Mirrors/learn-mode) by [Living Mirrors](https://livingmirrors.ai)*
