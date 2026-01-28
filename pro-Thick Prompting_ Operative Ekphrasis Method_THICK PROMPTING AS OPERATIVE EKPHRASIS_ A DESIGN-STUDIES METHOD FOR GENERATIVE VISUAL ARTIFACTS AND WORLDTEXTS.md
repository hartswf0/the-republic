THICK PROMPTING AS OPERATIVE EKPHRASIS: A DESIGN-STUDIES METHOD FOR GENERATIVE VISUAL ARTIFACTS AND WORLDTEXTS

Gaia Hartsoe & Jay David Bolter
Georgia Institute of Technology

═══════════════════════════════════════════════════════════════════
ABSTRACT
═══════════════════════════════════════════════════════════════════

Multimodal prompting has become a distinctive creative practice for producing visual artifacts—images, videos, and increasingly "worldlike" scenes—yet it is often evaluated narrowly by representational fidelity ("does it match what I asked for?"). This paper argues that such prompting is best understood as operative ekphrasis: a historical shift in the text–image relation where description does not merely represent an image but computationally performs it. Building on Bajohr's account of ekphrasis as performative under multimodal AI and Geertz's formulation of thick description as an interpretive practice oriented to meaning, not just technique, we pursue two aims: (1) to situate multimodal prompting for creative visual production (art, personal expression, entertainment) within the longer history of text/image theory and ekphrastic world-composition; and (2) to show how this reframing yields actionable guidance for shaping prompts as a design practice.

We propose Thick Prompting as a method: treating prompts as heterogeneous stacks (natural language, tags, parameters, and structured formats such as JSON) and treating execution as a ritualized workflow that makes a platform's latent space more navigable, revisable, and discussable. We contribute (i) a conceptual genealogy from classical ekphrasis (with Homer's Shield as a paradigmatic "worldtext" whose description foregrounds making), (ii) an explicit account of platform constraints, and (iii) a set of illustrated prompt techniques and prompt-differential analysis for producing richer, more controllable visual artifacts beyond fidelity alone.

Keywords: operative ekphrasis, thick prompting, generative AI, worldtext, multimodal design, text-image relations

═══════════════════════════════════════════════════════════════════
RESEARCH QUESTION
═══════════════════════════════════════════════════════════════════

How does reframing multimodal prompting for creative visual artifacts as operative ekphrasis enable Thick Prompting to function both as an interpretive lens and as a design-studies method for making better (richer, more controllable) generative works under real platform constraints?

═══════════════════════════════════════════════════════════════════
1. INTRODUCTION
═══════════════════════════════════════════════════════════════════

1.1 Scope

This paper examines prompting practices for producing visual artifacts—images, videos, and worldlike scenes—in contexts of art, personal expression, and entertainment. We do not address prompting for code generation, data analysis, general chat assistance, or other non-visual task domains; narrowing the scope makes the continuity with ekphrasis—the literary and rhetorical tradition of text/image relations—both plausible and analytically productive.

1.2 The Problem of Fidelity

Most everyday users evaluate generative systems through a representational fidelity lens: did the output look like what I asked for? This is a rational default because consumer interfaces implicitly train it—type a description, get a picture. Our claim is not that fidelity is irrelevant, but that fidelity-only evaluation is a naïve theory of prompting: it treats prompts as static descriptions rather than as interventions that install workflows, constraints, and future option spaces. The alternative we propose is to judge prompts additionally by their operational effects—what kinds of iteration, control, and world-consistency they enable across runs.

1.3 Dual Purpose

This paper pursues two aims that cannot be separated:

(1) HISTORICAL/THEORETICAL: To situate multimodal prompting within the longer history of text–image relations and ekphrasis. We show that what engineers have built connects—accidentally but consequentially—to what poets and anthropologists have always done: describe in ways that generate meaning.

(2) PRACTICAL/DEMONSTRATIVE: To show how this framing yields methods and techniques for shaping prompts to produce richer visual artifacts.

Accordingly, the paper alternates between conceptual framing and visual demonstration: theory identifies the text–image problem multimodal systems re-open, while demonstrations show how thick prompting translates that diagnosis into practice. The argument is that operative ekphrasis is not only something we can interpret; it is something we can design for.

1.4 Thick Prompting (Definition)

We propose Thick Prompting as the paper's central method: treating prompts as heterogeneous stacks (text + tags + parameters + structured formats) and treating execution as a Geertzian ritual of iterative inscription and interpretation. Ekphrasis provides the lens; thick prompting provides the practice.

Thick prompting is a method for producing richer, more controllable visual artifacts by composing prompts as layered constraint stacks rather than as single descriptions. It is "thick" in the Geertzian sense: not because it is long, but because it is densely textured—built from heterogeneous materials (system frames, natural language, tags, parameters, structured fields such as JSON, and iterative meta-prompts) that together specify not just what should appear, but how it should be made legible, coherent, and revisable.

Geertz's thick description names an interpretive effort that distinguishes superficially similar acts (twitch vs. wink) by reconstructing the webs of meaning that make them different; thick prompting operationalizes an analogous move by embedding those "webs" as explicit constraints that guide generation and critique.

DISTINCTION FROM "LONG PROMPTING":
- Long prompting = increased word count (often redundant)
- Thick prompting = increased constraint quality (structured, layered, and purposefully staged), even when concise

OPERATIONAL CLAIM: Thick prompting treats execution as a ritual workflow: prompts are crafted, run, read, and revised through repeatable cycles that make the latent space navigable (rather than mystical), producing artifacts whose qualities can be discussed without collapsing into aura or insider slang.

═══════════════════════════════════════════════════════════════════
2. EKPHRASIS AND THE TEXT-IMAGE PROBLEM
═══════════════════════════════════════════════════════════════════

2.1 Mitchell and Krieger: Two Positions

Mitchell and Krieger are useful here, but for different reasons.

Mitchell's project is to unsettle any naïve belief that word and image occupy naturally separate domains; their relations are historically and conceptually tense rather than cleanly partitioned. Mitchell opposes the belief that word/image are naturally separate.

Krieger, by contrast, foregrounds the ekphrastic paradox as a desire (and frustration): language strives to produce a "natural sign," to make words behave like images, yet cannot fully coincide with visual presence; ekphrasis stages that struggle rather than resolving it. Krieger opposes the belief that word can circumscribe image.

These are DIFFERENT positions:
- Mitchell: word/image are never cleanly separate
- Krieger: word cannot fully become image (but keeps trying)

Our use is aligned with Mitchell's refusal of clean separation and with Krieger's account of ekphrasis as contested boundary-work. Operative ekphrasis intensifies this: multimodal systems internalize the boundary inside a technical pipeline, so the "contest" between word and image becomes executable rather than purely rhetorical.

2.2 Operative Ekphrasis (Bajohr)

Bajohr names the shift that generative AI introduces: operative ekphrasis. Traditional ekphrasis describes an image that exists (actual ekphrasis) or might exist (notional ekphrasis). Operative ekphrasis GENERATES the image through description.

The crucial move: under multimodal AI, ekphrastic relations shift from representational to performative, and the text/image distinction tends to collapse inside the technical system. The prompt does not merely talk about an image; it does work in the system that produces it. Description becomes computational performance.

This is not metaphor. In text-to-image systems, language participates in a computational pipeline that produces the visual artifact. The description literally calls forth what it describes.

2.3 Wittgenstein (Brief Note)

While Wittgenstein later complicates the picture theory, the Tractatus usefully names a recurring temptation in text–image thinking: to treat propositions as picture-like models—an intuition that generative systems render newly operational.

═══════════════════════════════════════════════════════════════════
3. HOMER'S SHIELD: THE FOUNDATIONAL ANCHOR
═══════════════════════════════════════════════════════════════════

3.1 Why Homer?

We derive the technique taxonomy from the Homeric case, then test it on contemporary generations. Homer's description of Achilles' shield (Iliad, Book 18) is our foundational anchor because it supplies all three properties thick prompting requires: process foregrounding, narrative/action, and world-composition. Making Homer an anchor (not an aside) prevents the "design techniques" section from feeling arbitrary.

3.2 The Shield as World-Composition

Homer's description of Achilles' shield is not merely an account of an object; it is a world-composition. The shield enumerates cities, fields, seasons, conflicts, festivities—multiple interacting scenes whose meaning emerges from their relations, like a miniature model of social life. In contemporary terms, the shield functions as a proto-world model: not an encyclopedic inventory, but a structured depiction of a living environment with agents, rhythms, and constraints.

3.3 Process-Foregrounding

The description is explicitly processual. Homer brings into view not only what is made but the maker at work—Hephaestus forging the shield—so the ekphrasis stages production as part of what is described. Lessing emphasizes this feature: Homer presents "the divine artist… employed in making it," with figures that "spring gradually and successively into view."

This matters for generative systems because it aligns ekphrasis with procedures, not just pictures: the description already contains an implicit theory of making-as-revelation.

3.4 Operative Continuation

Generative AI makes this logic newly operative. In classical ekphrasis, language produces vividness in the reader's mind; in multimodal systems, language participates in a computational pipeline that produces the visual artifact. Bajohr's point is precisely that under multimodal AI, ekphrastic relations shift from representational to performative. In that sense, prompting is not just a modern analogy to Homeric ekphrasis; it is an executional continuation of ekphrasis as world-calling.

═══════════════════════════════════════════════════════════════════
4. THICK DESCRIPTION: GEERTZ'S METHOD
═══════════════════════════════════════════════════════════════════

4.1 The Actual Definition

Geertz's thick description is NOT merely "sensitivity to framing" or noting that "small changes yield large differences." That observation, while true, misses the core.

Thick description is an interpretive effort that distinguishes superficially identical actions by reconstructing the layered meanings that make them different. The canonical example: a wink and a twitch are physically identical (rapid eyelid contraction), but thick description asks: Is this a conspiratorial wink? A parody of a wink? A nervous twitch? The thickness is the interpretive labor of reconstructing context, intention, and cultural code.

4.2 Adaptation to Prompting

Thick prompting operationalizes this interpretive move:
- Where thick description reads meaning INTO behavior by reconstructing context
- Thick prompting builds meaning INTO prompts by constructing context as explicit constraints

The prompt stack embeds the "webs of significance" that Geertz describes—not as interpretation after the fact, but as deliberate construction before generation. The resulting artifact is both richer (more textured, more coherent) and more discussable (constraints can be named, critiqued, revised).

4.3 Thickness ≠ Length

This distinction is crucial:

THICKNESS IS NOT:
- Word count (long prompts are not thick prompts)
- Detail accumulation (more specifics ≠ more thickness)
- Technical precision (exact parameters ≠ thickness)

THICKNESS IS:
- Interpretive depth (layered meaning)
- Contextual richness (webs of significance)
- Intentional arrangement (structured constraint)
- Ritualistic execution (repeated, refined practice)

A thick prompt might be shorter than a thin one if its constraints are more precisely calibrated.

═══════════════════════════════════════════════════════════════════
5. THE HINGE: OPERATIVE AS BRIDGE (STRUCTURAL INTEGRATION)
═══════════════════════════════════════════════════════════════════

5.1 Theory Names What Design Does

Sections 1–4 argued that multimodal prompting reconfigures an old problem—how words relate to images—into a new condition: text becomes operational. Bajohr names this shift "operative ekphrasis," the point at which ekphrastic relations are no longer primarily representational but performative: prompts do not only talk about images; they do work in the system that produces them. In parallel, Geertz clarifies that "thick description" is not a checklist of field methods but a kind of interpretive labor: the work of distinguishing identical-looking actions by reconstructing the layered meanings that make them different.

This is the hinge for what follows: THEORY NAMES WHAT DESIGN DOES.

If operative ekphrasis is the historical condition—language fused into the production pipeline—then Thick Prompting is the design response: a method for acting within that condition without collapsing back into naïve fidelity-matching.

5.2 From Interpretation to Construction

Thick prompting treats the prompt not as a single sentence but as a heterogeneous stack—system framing, natural language, tags, structured fields (e.g., JSON), parameter choices, and iterative revisions—whose execution yields artifacts that can be read, critiqued, and refined. Where thick description interprets symbolic action by reconstructing context, thick prompting deliberately builds that context into the prompt stack so that the resulting artifact is both richer and more discussable.

5.3 Why Design Practice Now

This is why the paper now turns to design practice (Sections 6–8). If prompts are interventions, then our task is not only to interpret outputs but to develop repeatable techniques for shaping them:
- How to layer constraints without merely adding words
- How to keep option space open while steering style
- How to diagnose fragility versus resilience across iterations
- How platform constraints condition what "good" prompting can be

In short: operative ekphrasis explains WHY prompting matters; thick prompting specifies HOW to practice it.

═══════════════════════════════════════════════════════════════════
6. THICK PROMPTING: THE METHOD (PEDAGOGY)
═══════════════════════════════════════════════════════════════════

6.1 The Complete Workflow

Before introducing prompt differentials (Δ / ΔΔ), we define thick prompting as a complete workflow:

1. SYSTEM PROMPT (FRAME)
Establishes the cultural and aesthetic "rules of the game" (tone, medium, forbidden moves, evaluation criteria).

Example: "You are assisting an artist-scholar studying Homeric ekphrasis. Outputs should capture cosmological ambition—world-building, not illustration. No glossy commercial aesthetics. Restrained palette. Evidence of process."

2. CONSTRAINT STACKING
Prompts are layered (style grammar, camera logic, subject constraints, world rules) to increase coherence, not word count.

3. INCEPTION/META-PROMPTING
"Prompts that prompt prompts" generate variant drafts, critique rubrics, or constraint proposals—useful because the prompt itself becomes an object of design.

Example: "As Hephaestus, describe the shield you would forge: five zones from cosmos to ocean, filled with ACTIONS not objects, emphasizing the making."

4. STRUCTURED PROMPTS (JSON)
Constraints are made parseable and versionable (fields for subject, setting, camera, palette, exclusions, invariants).

{
  "system_frame": "documentary 1970s, restrained, non-glossy",
  "invariants": {
    "lens": "50mm",
    "grain": "kodachrome-like",
    "world_rule": "no readable text",
    "palette": "muted cyan/amber"
  },
  "subject": "street portrait, centered",
  "variables": ["wardrobe", "weather intensity"],
  "exclusions": ["neon signage", "logo marks"]
}

Why JSON? Because it makes prompt stacks (i) parseable (fields can be compared across versions), (ii) version-controllable (diffs are meaningful), and (iii) collaborative (teams can discuss "camera," "invariants," "constraints" as discrete components). JSON is not required for thickness, but it makes thickness auditable and teachable.

5. RITUAL EXECUTION LOOP
Run → read → annotate → revise. The goal is to turn latent space from aura into a navigable design space.

6.2 Platform Constraints

By platform constraints we mean the technical and institutional conditions that shape what prompting can do and what counts as a successful artifact:

(1) MODEL AFFORDANCES AND LIMITS
Architecture and training shaping what kinds of spatial reasoning, text rendering, or compositional consistency are plausible.

(2) SAFETY AND POLICY FILTERS
What prompts are allowed and how outputs are blocked or rewritten.

(3) TOKEN/CONTEXT LIMITS
How much instruction and memory can be carried across iterations.

(4) EXPOSED PARAMETERS AND UI AFFORDANCES
What the platform lets users control—e.g., guidance/strength, aspect ratio, seed, negative prompts, style toggles.

(5) DATA AND BIAS STRUCTURE
Training distributions that privilege certain aesthetics, geographies, or iconographies.

Thick prompting is a method under constraint: it treats these limits not as noise but as design material, and it makes their effects legible through structured prompt stacks and prompt-differential iteration.

═══════════════════════════════════════════════════════════════════
7. PROMPT DIFFERENTIALS: Δ AND ΔΔ
═══════════════════════════════════════════════════════════════════

7.1 The Method

Prompt Differentials provide a systematic technique for analyzing how constraint changes affect outputs. We borrow notation from calculus:

Δ (DELTA): A single-variable change between prompts. Isolates the contribution of one element.

ΔΔ (DELTA-DELTA): The rate of change of change. Compares how sensitivity differs across dimensions.

7.2 Δ Trace Example (Shield)

┌──────────────────────────────────────────────────────────────┐
│ BASE: "Bronze shield with concentric narrative zones"        │
├──────────────────────────────────────────────────────────────┤
│ Δ₁: Remove SYSTEM PROMPT                                     │
│     Effect: Cosmological ambition lost → generic fantasy     │
├──────────────────────────────────────────────────────────────┤
│ Δ₂: Remove JSON STRUCTURE                                    │
│     Effect: Compositional logic lost → zones blur            │
├──────────────────────────────────────────────────────────────┤
│ Δ₃: Remove INCEPTION step                                    │
│     Effect: Process-foregrounding lost → static depiction    │
├──────────────────────────────────────────────────────────────┤
│ Δ₄: Change MATERIALITY (bronze → glass)                      │
│     Effect: Lighting transforms, transparency introduces     │
└──────────────────────────────────────────────────────────────┘

Each Δ reveals which elements carry weight and which are negligible.

7.3 ΔΔ Trace Example

Series 1: Vary CONTENT while holding style constant
Series 2: Vary STYLE while holding content constant

ΔΔ = Compare the magnitude of change

OBSERVATION: For shield prompts, style changes produce larger visual shifts than content changes. The style dimension is more determinative for this prompt structure.

This finding is prompt-specific. But the ΔΔ method reveals dependency structure, enabling practitioners to invest effort where it matters.

7.4 Practical Applications

DEBUGGING: When outputs fail, Δ traces identify which element is responsible.
OPTIMIZATION: ΔΔ reveals where to invest prompt-crafting effort.
DOCUMENTATION: Δ traces create legible records of prompt evolution.
TEACHING: Differentials make implicit knowledge explicit and shareable.

═══════════════════════════════════════════════════════════════════
8. EVALUATIVE CONCEPTS: RESILIENCE, OPTION SPACE, OBLIGATION
═══════════════════════════════════════════════════════════════════

8.1 Resilience (Fragile vs Resilient)

RESILIENCE measures whether the prompt produces consistent outputs across regenerations.

┌─────────────────────────────────────┬─────────────────────────────────────┐
│ FRAGILE PROMPT                      │ RESILIENT PROMPT STACK              │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ "A cinematic portrait of a woman   │ "INVARIANTS: 1970s documentary      │
│ in a foggy street, 1970s grain,    │ grain; 50mm; fog density=high;      │
│ neon."                              │ palette=cyan/amber; subject         │
│                                     │ remains centered; no neon signage   │
│                                     │ text. VARIABLE: wardrobe style."    │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ Small wording changes collapse      │ Small changes don't collapse        │
│ the artifact's center of gravity    │ the artifact's center of gravity    │
└─────────────────────────────────────┴─────────────────────────────────────┘

Neither is inherently better. High resilience is valuable when you've found what you want; low resilience (fragility) is valuable for exploration.

8.2 Option Space (Open vs Closed)

OPTION SPACE measures how many live possibilities remain after prompting.

┌─────────────────────────────────────┬─────────────────────────────────────┐
│ CLOSED (Small Option Space)         │ OPEN (Large Option Space)           │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ "exactly this: red coat, blue car, │ "Maintain mood + camera invariants; │
│ rain, same pose, same framing"     │ allow subject props to vary within  │
│                                     │ 'working-class urban evening.'"     │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ Few viable next-steps without      │ Many viable next-steps without      │
│ stylistic rupture                   │ stylistic rupture                   │
└─────────────────────────────────────┴─────────────────────────────────────┘

The thick prompter manages option space deliberately—opening during exploration, closing during refinement.

8.3 Obligation (Installs Duty)

OBLIGATION measures how much duty or necessity the prompt installs.

┌─────────────────────────────────────┬─────────────────────────────────────┐
│ NO OBLIGATION                       │ WITH OBLIGATION                     │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ "A retro sci-fi control room."     │ "Every screen must show a different │
│                                     │ subsystem; cables must imply        │
│                                     │ causality; labels must be legible   │
│                                     │ but non-textual (glyphs)."          │
├─────────────────────────────────────┼─────────────────────────────────────┤
│ No clear failure mode              │ Creates critique handles            │
│                                     │ ("did we satisfy the duty?")        │
└─────────────────────────────────────┴─────────────────────────────────────┘

Strong obligation enables accountability; weak obligation enables discovery.

═══════════════════════════════════════════════════════════════════
9. WORLDTEXT: DEFINITION AND DEMONSTRATION
═══════════════════════════════════════════════════════════════════

9.1 Worldtext Definition

We use worldtext to name prompts (and prompt stacks) that compile into spatially navigable, procedurally structured media objects—not only static images but scene-like outputs that can be iterated into 3D environments, interactive experiences, or "game-world" fragments.

A worldtext specifies relationships, affordances, and constraints (how space behaves, what agents can do, what counts as a consistent style) rather than merely depicting a moment. It differs from imagetext, which primarily targets a single-frame composition.

In practice, worldtexts emerge when creators use thick prompting to stabilize a world's "physics" (visual grammar, lighting rules, recurring motifs, camera logic, interaction cues) across multiple generations, making the artifact inhabitable—conceptually, sometimes literally.

9.2 Demonstration: Shield as Worldtext

We use the shield as running example across modalities:

PHASE 1: IMAGETEXT (Static Shield)

THIN PROMPT: "A shield with battle scenes"
RESULT: Generic fantasy shield. No world-composition. Representationally correct but interpretively empty.

THICK PROMPT STACK:
System: "Artist-scholar studying Homeric ekphrasis. Capture cosmological ambition—world-building, not illustration."
Inception: "As Hephaestus, describe the shield: five zones from cosmos to ocean, filled with ACTIONS not objects."
JSON:
{
  "zones": [
    {"ring": 1, "content": "cosmos—sun, moon, stars"},
    {"ring": 2, "content": "city at peace—wedding, law court"},
    {"ring": 3, "content": "city at war—ambush, mourning"},
    {"ring": 4, "content": "agricultural cycle—plow, harvest"},
    {"ring": 5, "content": "Ocean encircling all"}
  ],
  "style": "bronze relief, classical line",
  "emphasis": "action and process"
}
Tags: [bronze:1.3], [Flaxman:1.2], [world model:1.0]

RESULT: Coherent symbolic program. Material consistency. Compositional logic. Narrative density. The shield presents a cosmos, not a decoration.

EKPHRASIS TIE-BACK: This is operative: the description installs a procedure.

PHASE 2: TEMPORAL EXTENSION (Animation)

{
  "sequence": "forging process",
  "duration": "60 seconds",
  "stages": [
    {"time": "0-15s", "action": "Hephaestus shapes bronze disc"},
    {"time": "15-30s", "action": "cosmos zone emerges under hammer"},
    {"time": "30-45s", "action": "cities and farms take form"},
    {"time": "45-60s", "action": "Ocean rim completes the world"}
  ],
  "emphasis": "making visible—the process Homer describes"
}

RESULT: Process-foregrounding becomes literal animation. Homer's temporal narration becomes direct technique.

PHASE 3: WORLDTEXT (Navigable Environment)

System: "World-building for interactive experience. Environment must be NAVIGABLE."
Description: "A world modeled on the shield: at center, cosmos visible through oculus; zones transition from celestial to agricultural to urban to oceanic. Circular, bounded, complete. Signs of maker everywhere."

{
  "navigability": "first-person traversal",
  "scale": "human-sized, with vista points",
  "zones": "concentric, with transition thresholds",
  "evidence_of_process": "visible throughout"
}

RESULT: Spatially navigable. Procedurally structured. Process-visible. Homeric logic executed as explorable environment.

═══════════════════════════════════════════════════════════════════
10. AESTHETIC JUDGMENT
═══════════════════════════════════════════════════════════════════

This paper is not a universal theory of taste, but it cannot avoid aesthetics because thick prompting is justified by what it makes possible: richer artifacts and more articulate critique.

We treat aesthetic judgment in two layers:

FIRST, DESCRIPTIVELY: We document how practitioners actually decide that an artifact "works" (coherence, novelty, affective charge, world-consistency, stylistic integrity).

SECOND, METHODOLOGICALLY: We show how thick prompting makes such judgments actionable—not by prescribing what is beautiful, but by producing artifacts whose qualities can be isolated, named, and iteratively steered.

In this sense, aesthetic evaluation is not the paper's endpoint but its motivating pressure: without some account of "better," a method for making "richer" artifacts would be empty.

═══════════════════════════════════════════════════════════════════
11. CONCLUSION
═══════════════════════════════════════════════════════════════════

This paper has argued that multimodal prompting for visual artifacts is best understood as operative ekphrasis: a condition where text no longer merely represents images but computationally performs them. We proposed Thick Prompting as the design response to this condition—a method for producing richer, more controllable artifacts by composing prompts as heterogeneous stacks and executing them as ritualized workflows.

The paper's contributions:

1. CONCEPTUAL GENEALOGY: Positioning prompting within the history of text-image relations, with Homer's Shield as paradigmatic worldtext demonstrating process-foregrounding, narrative action, and world-composition.

2. THEORETICAL PRECISION: Distinguishing Mitchell (word/image never cleanly separate) from Krieger (word cannot circumscribe image); grounding in Geertz's actual method (interpretive labor, not mere sensitivity); anchoring in Bajohr's operative ekphrasis (performative, not representational).

3. METHOD SPECIFICATION: Thick Prompting as complete workflow—system frames, constraint stacking, inception prompts, JSON structures, ritual execution.

4. ANALYTICAL TOOLS: Prompt differentials (Δ/ΔΔ) for systematic analysis; evaluative concepts (resilience, option space, obligation) for richer critique.

5. PLATFORM AWARENESS: Explicit account of constraints as design material, not noise.

6. VISUAL DEMONSTRATION: Shield as running example across modalities—imagetext, animation, worldtext—showing technique transfer and consistency.

The hinge throughout has been "operative": theory names what design does; thick prompting specifies how to practice it. Operative ekphrasis explains WHY prompting matters; thick prompting provides the HOW.

Ultimately, we propose that prompting is not picture-making but world-making. Homer's shield was always more than decoration—it was a cosmos. Generative AI makes that world-calling capacity executable. Thick prompting helps us compose worlds again, deliberately, richly, and under the real constraints of contemporary platforms.

═══════════════════════════════════════════════════════════════════
REFERENCES
═══════════════════════════════════════════════════════════════════

[bajohr_operative_2024] Bajohr, H. (2024). Operative ekphrasis: the collapse of the text/image distinction in multimodal AI. ResearchGate.

[geertz_thick_1973] Geertz, C. (1973). Thick Description: Toward an Interpretive Theory of Culture. In The Interpretation of Cultures. Basic Books.

[heffernan_museum_2004] Heffernan, J. A. W. (2004). Museum of Words: The Poetics of Ekphrasis from Homer to Ashbery. University of Chicago Press.

[krieger_ekphrasis_1992] Krieger, M. (1992). Ekphrasis: The Illusion of the Natural Sign. Johns Hopkins University Press.

[lessing_laocoon_1766] Lessing, G. E. (1766/1984). Laocoön: An Essay on the Limits of Painting and Poetry. (Whitman Archive edition).

[mitchell_picture_1994] Mitchell, W. J. T. (1994). Picture Theory: Essays on Verbal and Visual Representation. University of Chicago Press.