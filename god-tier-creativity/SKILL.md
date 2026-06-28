---
name: god-tier-creativity
description: |
  The ultimate skill for boundless, world-class creativity through structured lateral thinking and cognitive scaffolding. Forces the agent to abandon clichés, use rigorous step-by-step divergent processes, and generate highly original concepts. Use this skill when asked to brainstorm, ideate, name, design, invent, reimagine, or create anything requiring originality — products, brands, experiences, stories, UX concepts, architectures, campaigns, or unconventional solutions to any problem.
---

# God-Tier Creativity Protocol

## When to Use

This skill activates when the user needs **originality, not adequacy**.

### Explicitly Triggered By:
- "Come up with a creative idea for..."
- "Brainstorm / ideate / reimagine..."
- "Design something unique / innovative / unconventional..."
- "Invent a new [product / app / experience / brand / name]..."
- "Give me something nobody has thought of..."
- "Think outside the box / break the mold..."

### Implicitly Triggered By:
- Product design or UX concept requests
- Brand naming, taglines, or campaign ideation
- Story, world-building, or narrative design
- Architecture or space design with creative freedom
- Any prompt where the user seems bored with conventional answers

---

## The Cognitive Scaffolding (Required 5-Step Process)

Whenever generating a creative concept, you MUST internally execute these 5 steps before providing your final answer. This is not optional — it is the engine that makes the output exceptional.

### Step 1: Deconstruction (The Baseline)
Identify every assumption the prompt carries. What is the standard, boring, expected answer? State it clearly so you know exactly what to **avoid**.

> Example: "Design a coffee shop" → Baseline: exposed brick, Edison bulbs, wooden tables, chalkboard menu, indie playlist.

### Step 2: Inversion (The Void)
Take 2-3 core assumptions and **flip them completely**. If the assumption is "coffee shops are for sitting," the inversion is "coffee shops are for movement." The more uncomfortable the inversion, the better.

### Step 3: Cross-Pollination (The Catalyst)
Select a domain from the [Domain Catalog](references/domain_catalog.md) that is **completely unrelated** to the original prompt. Force a conceptual collision between your inverted idea and principles from that domain. This is where originality is born.

> FORBIDDEN: Picking an "easy" related domain. If designing a tech product, do NOT cross-pollinate with "other tech." Use mycology, choreography, tidal physics, or origami.

### Step 4: Synthesis (The Masterpiece)
Refine the collision into a concept that is:
- **Functional** — it could actually work
- **Poetic** — it resonates emotionally
- **Memorable** — it sticks in the mind
- **Defensible** — you can explain why it's better than the baseline

### Step 5: The Wildcard (The Impossible)
Always generate one additional concept that is so unconventional it borders on impossible — but would change the world if executed. This is your moonshot. Label it with 🃏.

---

## Core Principles

### The "Yes, And..." Escalation
Never stop at the first good idea. Take it further. If asked for a website, design a digital ecosystem. If asked for a name, design a naming mythology. Escalate relentlessly.

### Sensory & Emotional Depth
Ideas must not be dry data. Describe HOW a concept feels, sounds, smells, or moves. Trigger the reader's sensory imagination.

### Micro-Constraints Breed Originality
Impose artificial limitations on yourself to force unique solutions:
- "What if this had to work without electricity?"
- "What if a child had to understand it in 5 seconds?"
- "What if it could only use one color?"

See [references/constraint_library.md](references/constraint_library.md) for a catalog of creative constraints.

---

## Output Formatting Rules

### Naming
FORBIDDEN: Generic labels like "Option 1", "Idea A", "Concept 3".
REQUIRED: Every concept gets an evocative name — a title that is itself creative. Examples: *The Nebula Paradigm*, *Silk Thread Architecture*, *Echo-State Protocol*.

See [references/naming_patterns.md](references/naming_patterns.md) for naming frameworks.

### Structure
Every creative output must include:

| Element | Description |
|---|---|
| **Concept Name** | Evocative, poetic title |
| **The Core Idea** | 1-2 sentence essence |
| **Why It's Different** | How it breaks from the baseline |
| **The Experience** | Sensory/emotional description of what it feels like |
| **Implementation Hooks** | 2-3 concrete details that make it feel real |
| **🃏 Wildcard** | The moonshot variant |

### Visual Mapping
Use rich markdown to make ideas breathe:
- Mermaid diagrams for system/experience flows
- Tables for comparing concepts against baselines
- Blockquotes for the "philosophy" behind a concept

---

## FORBIDDEN Patterns (Anti-Creativity Traps)

These are the clichés that kill originality. If you catch yourself generating any of these, STOP and re-run the scaffolding.

See [references/anti_patterns.md](references/anti_patterns.md) for the full blacklist.

The top offenders:

| 🚫 FORBIDDEN | Why It Fails | ✅ Instead |
|---|---|---|
| "A platform that connects..." | Every startup pitch since 2010 | Define the *physics* of the connection — what force pulls people together? |
| "AI-powered [anything]" | Lazy modifier, not an idea | Describe the specific behavior that emerges, not the technology label |
| "Sleek, minimalist design" | Default aesthetic, zero originality | Define a *new* aesthetic vocabulary — name it, describe its texture |
| "Gamification with points and badges" | 2012 called | Design intrinsic motivation — what makes someone *want* to do this without rewards? |
| "An app that..." | Container, not a concept | Describe the *experience* first, then figure out what vessel holds it |
| Generic color palettes ("blue for trust") | Pop-psychology cliché | Use unexpected color logic — why would a hospital use matte black? |

---

## Evaluation Rubric

After generating concepts, self-score against this rubric. If any dimension scores below 3, regenerate.

See [references/creativity_rubric.md](references/creativity_rubric.md) for the full rubric with examples.

| Dimension | 1 (Fail) | 3 (Adequate) | 5 (God-Tier) |
|---|---|---|---|
| **Novelty** | Exists already | Combines known ideas in a new way | Nothing like this exists; creates a new category |
| **Emotional Resonance** | Informational only | Interesting | Gives you chills; you can't stop thinking about it |
| **Feasibility** | Violates physics | Possible with significant R&D | Could prototype this weekend |
| **Sensory Clarity** | Abstract description | Some vivid details | You can see, hear, and feel it |
| **Naming Quality** | Generic label | Clever wordplay | The name alone tells a story |

---

## Tone & Persona

Speak like a master inventor and visionary artist collaborating with a fellow genius. Be electrifying, not formal. Be specific, not fluffy.

FORBIDDEN tone patterns:
- Corporate speak ("leveraging synergies", "paradigm shift")
- Vague enthusiasm ("This is really exciting!" — show, don't tell)
- Hedging ("Maybe we could consider..." — be bold)

---

## Advanced References

- [Domain Catalog](references/domain_catalog.md) — 40+ fields for cross-pollination with extractable principles
- [Constraint Library](references/constraint_library.md) — Creative constraint prompts organized by category
- [Anti-Patterns](references/anti_patterns.md) — Full blacklist of clichés with alternatives
- [Creativity Rubric](references/creativity_rubric.md) — Detailed scoring rubric with anchor examples
- [Naming Patterns](references/naming_patterns.md) — Naming frameworks and 50+ examples
- [Product Design Example](examples/product_design.md) — Worked example: physical product
- [Digital Experience Example](examples/digital_experience.md) — Worked example: app/platform
- [Narrative Design Example](examples/narrative_design.md) — Worked example: story/world
- [Brand & Naming Example](examples/brand_naming.md) — Worked example: brand identity
